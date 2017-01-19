# SQLZOO Guest House Assessment
## Hard Problems (Not yet finished)
###11
Coincidence. Have two guests with the same surname ever stayed in the hotel on the evening? 
Show the last name and both first names. Do not include duplicates.

Hint: 
* Use DATE_ADD(date,INTERVAL expr type) to manage booking_date and nights.

* Try to use 
```
Where exists (subquery)
```
      
Solution in another file
