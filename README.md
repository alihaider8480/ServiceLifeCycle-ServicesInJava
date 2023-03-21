# ServiceLifeCycle-ServicesInJava
                          Services in Java Method 1) postUpdateRequest 2) updateRecord 3) inputRecord

 
 service jab bhi banti hai to uska load file ka lia hum getIds() ka method use karta hai java ka throw
dono method ma major ya faraq ha ka dono ofs ka throw data post karta hai aik post karak queue ma dalata hai or aik ofs ka karta hai direct post karta hai without queue maor inputRecord jo hai wo ofs ka or InputRecord deprecated to updateRecord

1)
postUpdateRequest : 
is mehtod ma hum record ko post kar sakta hai matlab insert kar sakta hai asynchronus mode ma  and postUpdateRequest  write karta hai OFS.MESSAGE.REQUEST ma or post karna ka lia user ko cheya ka wo OFS.MESSAGE.SERVICE ko run kare or is mehtod ko batch call karta hai matlab batch>JOB.CONTROL. or iski EB.API call karti hai batch file ka name ko or version should not be comma mode or OFS.SOURCE (OFSSOURCEID) dana zarori hai agar ofs name hi mojoood ni hoga to request process ni hogi and The related hooks for initialise and getTableName can be created by appending .LOAD and .SELECT to the EB.API id. (matlba load or select ki jaga initialise and getTableName use honga.



2)
updateRecord 
: is mehthod ma hum record ko update kar sakta hai kisi bhi table ma . or is mehtod ko batch call karta hai matlab batch>JOB.CONTROL. or iski EB.API call karti hai batch file ka name ko or version should not be comma mode or is ma hum source id ni data jabka postUpdateRequest wala mehtod ma huma dana lazmi hai nad ya method updateRecord forefully update kardaga db ma.


3) inputRecord is absolute hogaya hai updateRecord pa

