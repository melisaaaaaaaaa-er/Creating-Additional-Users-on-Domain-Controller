# Creating Additional Users on Domain Controller

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/41.png"/>

Logon to DC-1 as jane-admin.

Open up PowerShell ISE as an administrator.

Create a new file and run the script from the following link to create new user accounts on the directory - https://github.com/joshmadakor1/AD_PS/blob/master/Generate-Names-Create-Users.ps1

You can change the password and number of users created  as defined at the beginning of the script. Observe the user accounts as they are generated.

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/42.png"/>

Open ADUC and navigate to the _EMPLOYEES OU to see all the accounts that have been created.

#
<h3>Testing the new accounts</h3>

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/43.png"/>

Choose one of the newly made accounts to login to Client-1 with. Remember the username and password.

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/44.png"/>

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/45.png"/>

Use these credentials to login to Client-1 to test the account.
