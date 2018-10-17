# MC2Bank
Simple collection of warpscript macros that i use.

## DISPLAY
 - pretty : Limit number of point of the serie keeping the shape of it for lighter display.

## GT
 - compactTime : Remove duplicate values over time.

## FETCH
 - counter : Fetch data and bucketize a counter, replacing gap by previous value or next one.
 - gauge : Fetch data and bucketize a gauge, replacing gab by 0.

## MAP
 - delta : Compute delta between n and n-1 removing first point of the series as it's now meaningless. 
 - rate : Compute rate between n and n-1 removing first point of the series as it's now meaningless.

## REDUCE
 - sum : Reduce list of GTS by sum.

## UTILS
 - blame : Retrieve cardinality of each class matching the selector.
 - list : List all available class for the matching selector.
