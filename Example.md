### Example
A business company has decided to encourage early payment on its invoices binary introducing the following payment procedure for its regular customer. 10% discount if the invoice is settled within 10 days. 7% discount if the invoice is settled within 20 days. 5% discount if the invoice is settled within 30 days. Other cases for discount must be referred to the manager. Construct a decision table for the above procedure.

|Conditions Stubs:|Action Stubs:|
|:-|:-|
|1. within 10 days|1. 10% discount|
|2. within 20 days|2. 7% discount|
|3. within 30 days|3. 5% discount|
||4. referred to the manager|

Numbers of Rules: $2^N = 2^3 = 8$

||Discount of invoice|-|1|2|3|4|5|6|7|8|
|-|-|-|-|-|-|-|-|-|-|-|
|1|within 10 days|-|Y|Y|Y|Y|N|N|N|N|
|2|within 20 days|-|Y|Y|N|N|Y|Y|N|N|
|3|within 30 days|-|Y|N|Y|N|Y|N|Y|N|
|-|-|-|-|-|-|-|-|-|-|-|
|1|10 % discount|
|2|7% discount|
|3|5% discount|
|4|referred to manager|

>rule no 1,2,3 and 5 are doesn't exist at the same time, Therefore the decision table reduces to the simplified decision table.

||Discount of invoice|-|4|6|7|8|
|-|-|-|-|-|-|-|
|1|within 10 days|-|Y|N|N|N|
|2|within 20 days|-|N|Y|N|N|
|3|within 30 days|-|N|N|Y|N|
|-|-|-|-|-|-|-|
|1|10 % discount|-|X|
|2|7% discount|-||X|
|3|5% discount|-|||X|
|4|referred to manager|-||||X|
