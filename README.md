# Duplicate-check-using-script

Sometimes we usually get some duplicate records from source system in boomi. Boomi needs to handle the duplicate records by rejecting or ignoring the duplicate records and sending only the unique recirds.

We need to use a set properties and a data process after the source connector

example:
![image](https://user-images.githubusercontent.com/97012694/147904107-764e85ec-74da-40cb-b41f-060fce3cd2fd.png)

1st step: Set property image

![image](https://user-images.githubusercontent.com/97012694/147904120-7381b514-0d6f-4aef-9249-2e20d7c28201.png)

We need to set the filter by value field with the unique field of that record(ie. Primary key)

2nd step: custom scripting 

Find the code in Duplicate check file
