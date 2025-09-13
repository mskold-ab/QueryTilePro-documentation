
## DateDiff(dateFrom: {Date|string}, dateTo: {Date|string}, [d2NullValue]:Date|string): number 

### Description:

Returns the time in miliseconds between the two dates
Input is either javascript Dates or a date string 
if dateTo is null, the value is replaced with d2NullValue (making it possible to calculate running times up till today)

### Example 

DateDiff("@System.CreatedDate",'@Microsoft.VSTS.Common.ResolvedDate', new Date())
Returning the time between CreateDate and ResolvedDate - if no resolved date is set it returns the time between CreatedDate and Now (Today) 
