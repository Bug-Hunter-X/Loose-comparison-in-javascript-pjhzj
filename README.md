# Loose comparison in javascript
This repository contains a bug report about the loose comparison in javascript. The loose comparison (==) does not check the datatype of the variables. It converts the datatype of the variables to the same datatype before comparing them. This can lead to unexpected results. 
The bug is fixed by using the strict comparison (===) which checks the datatype of the variables before comparing them. 