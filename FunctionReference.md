
DateDiff(dateFrom:Date|string, dateTo:Date|string, [d2NullValue]:Date|string): number 

Description:
Returns the time in miliseconds between the two dates, 
if dateTo is null, the value is replaced with d2NullValue (making it possible to calculate running times up till today)

Example 
DateDiff("@System.CreatedDate","@System.ActivatedDate")
