# Creating Additional Users on Domain Controller

![41](https://github.com/melisa-er/Creating-Additional-Users-on-Domain-Controller/assets/157723219/f5535d5c-3dbc-4c6d-b8a1-f8b2a9b914f6)

Logon to DC-1 as jane-admin.

Open up PowerShell ISE as an administrator.

Create a new file and run the script from the following link to create new user accounts on the directory - https://github.com/joshmadakor1/AD_PS/blob/master/Generate-Names-Create-Users.ps1

You can change the password and number of users created  as defined at the beginning of the script. Observe the user accounts as they are generated.

#
![42](https://github.com/melisa-er/Creating-Additional-Users-on-Domain-Controller/assets/157723219/90f02a03-ad04-4d27-89df-57f001a6774b)

Open ADUC and navigate to the _EMPLOYEES OU to see all the accounts that have been created.

#
<h3>Testing the new accounts</h3>

![43](https://github.com/melisa-er/Creating-Additional-Users-on-Domain-Controller/assets/157723219/e8afb103-2c53-4dfc-b47d-3a7316b5940b)

Choose one of the newly made accounts to login to Client-1 with. Remember the username and password.

#
![44](https://github.com/melisa-er/Creating-Additional-Users-on-Domain-Controller/assets/157723219/31ee7eb7-eb23-482c-b7ec-32ea9ef70182)

![45](https://github.com/melisa-er/Creating-Additional-Users-on-Domain-Controller/assets/157723219/f01f25b2-6977-4fcf-b35a-d8b8224b0071)

Use these credentials to login to Client-1 to test the account.
