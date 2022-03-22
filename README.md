# Introduction-to-Scala---Independent-Project

## Background Information<br />
Clean up user-entered phone numbers so that we can send them SMS
messages.<br />
The National Numbering Plan of Kenya is a telephone numbering system used
by many African countries like Tanzania, Uganda, and Rwanda. The only
difference is the international country code.<br />

The numbers are 12-digit numbers consisting of the country code 254 followed
by a nine-digit numbering plan.

We represent this format as (NNN)-YXX-XXXXXX, where NNN is the country
code, Y represents the digit 7, and X is any digit from 0 through 9.<br />

Using Scala, your task is to clean up differently formatted telephone numbers
stored in a collection by removing punctuation, the prefix +, if present, and any
hyphens, so that the outcome is in the format: NNNYXXXXXXXX. You also need
to validate digits that comprise the country code, Y and XXXXXXXX.<br />
For example, the inputs:<br />
+ (254)-111-111111<br />
+254111111111<br />
254-111-111111<br />
0111111111<br />
0111-111111<br />
should all produce the output:<br />
254111111111<br />
