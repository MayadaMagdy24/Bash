# Bash

● Process a text file which has users and their properties in each line.

● Determine one by one if the ID number of the user (last column) is odd or even number if it's
specified.

● Check whether that user has a routable, FQDN email address.

● If so, write a message to stdout like:

The $ID of $EMAIL is (even|odd) number.

● If the user has no valid email address OR user ID, the script should silently continue the next user

showing a warning for the invalid parameters

The content of the source text file:

name, email, id

John, john_j123@domain.com, 325
Susan, ,510
Jane, jane_j121@domain.com, 131
Karl, karl_ka234@domain.com
Bert, bert_bb23@localhost, 150

-------------------------------------------------

- using awk
  
![image](https://github.com/MayadaMagdy24/Bash/assets/93229250/81b35187-df55-4bf2-ae25-b0fb4c2f0d47)
-------------------------------------

OR

------------------------------------------

- using while
  
  ![image](https://github.com/MayadaMagdy24/Bash/assets/93229250/425fb8da-ef35-41e1-9506-cfd2fd41e0c3)
----------------------------------------

- file of data

![image](https://github.com/MayadaMagdy24/Bash/assets/93229250/e5270004-12e2-47a1-9cbf-9a65804b81d8)

------------------------------------------------

- Validation (both give the same result)

  ![image](https://github.com/MayadaMagdy24/Bash/assets/93229250/5067c49a-fd02-491a-9f59-7451bf8527ca)
