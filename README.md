# MC2Bank
Simple collection of warpscript macros that i use.

## Quick description
Please check macro header for more informations.

### ALERT
 - ack : Acknowledge an alert notification.
 - cleanup : Remove all duplicate informations from 'level' gts.
 - fetch : Fetch 'level, description and ack' gts.
 - glue : Assemble all alert macro into a script that should be scheduled.
 - hash : Compute a unique alert hash from a gts.
 - notify : Notify an alert manager.
 - set : Set an alert level and description.

### DISPLAY
 - pretty : Limit number of point of the serie keeping the shape of it for lighter display.
 - keep_labels : Use to keep only the specified labels of the gts.

### GT
 - compactTime : Remove duplicate values over time.
 - last : Return the gts with only it's las point.

### FETCH
 - counter : Fetch data and bucketize a counter, replacing gap by previous value or next one.
 - gauge : Fetch data and bucketize a gauge, replacing gab by 0.

### MAP
 - delta : Compute delta between n and n-1 removing first point of the series as it's now meaningless. 
 - rate : Compute rate between n and n-1 removing first point of the series as it's now meaningless.

### REDUCE
 - sum : Reduce list of GTS by sum.
 - percentile : Compute the specified percentile of a gts values.

## TRACE
 - mark : Add a trace marker.
 - report : Display trace report.

### UTILS
 - blame : Retrieve cardinality of each class matching the selector.
 - list : List all available class for the matching selector.
