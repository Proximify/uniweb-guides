# Account Creation

### On this page:

- [Creating your UNIWeb account from an institution’s UNIWeb website][1]
- [Creating your UNIWeb account from an invitation email][2]
- [Creating UNIWeb member accounts manually][3]
- [Creating UNIWeb member accounts in bulk using a spreadsheet][4]
- [Sending account activation emails][5]
- [Sending account activation reminder emails][6]

---- 

## Creating your UNIWeb account from an institution’s UNIWeb website

##### Before you begin: If your institution has integrated UNIWeb with an existing single-sign-on system, then an account will be created for you automatically when you follow the steps to [log in to your UNIWeb account](). There will be no option to sign up from your institution’s UNIWeb Network page.

1.  From your institution’s UNIWeb Network page, click the **Sign up** button on the right side of the navigation bar.
2. On the account creation screen, select your **role** within your institution. This will correspond to your [account type][8]. Click **Next**.
3. Fill out the details of your [membership information][9]. Fields marked with an asterisk are mandatory. Click **Next**.
4. Select the name of your primary supervisor and co-supervisor (if application) at your institution, and provide the expected end date of your supervision at the institution. The selected supervisor(s) will be asked to validate this information in order to activate your account.
5. A confirmation email will be sent to your chosen email address. **Click the “Verify my email” link** within the confirmation email message. 

Once you have verified your email address, UNIWeb will indicate whether your supervisors have validated your account. If your supervisors verify that your account information is correct, you will receive an [invitation email][10] to complete your account creation. 

---- 

## Creating your UNIWeb account from an invitation email

##### Before you begin: you will receive an invitation email from UNIWeb either when you create your own account through your institution’s UNIWeb Network page, or if a UNIWeb administrator creates an account for you. If you believe that you should have received an invitation email and have not, please reach out to a system administrator for your institution’s UNIWeb instance.

1. Click the **Activate my UNIWeb account** link in the body of the email.
2. Review the Software License terms, and if you agree, **click the “I agree” button** to proceed.
3. **Create a password** for your new UNIWeb account, and **click the “Submit” button**.
---- 

## Creating UNIWeb member accounts manually

##### **Before you begin: **this procedure requires an Administrator Role within the subject’s Academic Unit that includes the following permissions:
##### - Create new accounts
##### If you have not been assigned a Role with the permissions listed above, and believe that you should be able to perform this task within your Academic Unit, please contact your system administrator.

1. From your UNIWeb Administration page, go to **Members**.
2. In the right panel, click the **Add a new member** button.
3. In the _Add new members_ dialog, fill in the [member information fields][11] for the new UNIWeb member. Fields that are marked with an asterisk are mandatory:
	- First Name
	- Last Name
	- Account Type
	- Position Title
	- Academic Unit
4. Click **Save**.

###### **Note** After following the above procedure, you must [send an account activation email][12] in order for the new UNIWeb member to complete the account activation process. 

---- 

## Creating UNIWeb member accounts in bulk using a spreadsheet

##### **Before you begin: **this procedure requires an Administrator Role within the subject’s Academic Unit that includes the following permissions:
##### - Create new accounts
##### If you have not been assigned a Role with the permissions listed above, and believe that you should be able to perform this task within your Academic Unit, please contact your system administrator.

From time to time, you may need to add many new member accounts at once. You can create member accounts in bulk by uploading a spreadsheet into UNIWeb that includes information for all of the accounts that you would like to add. UNIWeb will scan the spreadsheet for accounts that already exist in the network, and so you can maintain and upload a single spreadsheet numerous times without creating duplicates.

To get your member account spreadsheet started, you can download a template spreadsheet that’s already formatted properly for UNIWeb to read and understand.

### To download a template spreadsheet:

1. From your UNIWeb Administration page, go to Members
2. In the right panel, click **Add members from a file**
3. In the _Add new members_ dialog, click **Download template file**

This will download an example spreadsheet that follows the necessary format for creating new UNIWeb accounts in bulk. You can start building your account spreadsheet directly from this template.

The sample spreadsheet includes all of the accepted [member information fields]() that can be used when creating a UNIWeb account spreadsheet. Entries marked with an asterisk are mandatory.
- First Name* - Middle Name
- Last Name* - Account Type* - Position Title* - Academic Unit* - Email* - Username 
- Telephone 
- Homepage 
- Office
Acceptable entries for account type, position title and [academic unit]() are dictated by your institution. 

### Spreadsheet tips:

- The order of the columns does not matter
- Each row corresponds to one member account
- Empty rows are ignored
- If a row provides the same email address of an existing user in the system, the row is ignored (this is how UNIWeb screens for duplicate entries)
- Columns that UNIWeb does not recognize will cause an error.

### Uploading your spreadsheet to UNIWeb

1. From your UNIWeb Administration page, go to **Members**.
2. In the right panel, click **Add members from a file**
3. In the _Add new members_ dialog, click **Choose File**, and locate your UNIWeb members spreadsheet on your computer.
4. Click **Submit**.

> **Tip:** If you enter an Account Type, Position Title, or Academic Unit that does not exist in the network, you will receive an error message. This will describe the error, indicate where it is located in your spreadsheet and provide you with a list of suitable replacements. If your spreadsheet contains any blank fields that are mandatory or columns that UNIWeb does not recognize, you will receive a similar error.

---- 

## Sending account activation emails

Once you have added new members to UNIWeb, you need to invite them to activate their accounts. This will send them a welcome email with text and information approved by your institution.

##### **Before you begin: **this procedure requires an Administrator Role within the subject’s Academic Unit that includes the following permissions:
##### - Create new accounts
##### If you have not been assigned a Role with the permissions listed above, and believe that you should be able to perform this task within your Academic Unit, please contact your system administrator.

1. From your UNIWeb Administration page, go to **Members**.
2. Locate the UNIWeb member(s) to whom you would like to send an account activation email, and **click the checkbox** on the side side of their row.
3. In the right panel, click **Account activation**.
4. In the _Invite selected members_ dialog, verify the UNIWeb members that you have selected.
5. Click **Invite**.

---- _ 
## Sending account activation reminder emails

If you have invited members previously, but they have yet to activate their accounts, you can send them a reminder email. If you’re unsure which members have already been sent invitation emails, UNIWeb can filter members for you to automatically select members who have been sent invitation and reminder emails in the past.

##### **Before you begin: **this procedure requires an Administrator Role within the subject’s Academic Unit that includes the following permissions:
##### - Create new accounts
##### If you have not been assigned a Role with the permissions listed above, and believe that you should be able to perform this task within your Academic Unit, please contact your system administrator.

1. From your UNIWeb Administration page, go to **Members**.
2. In the right panel, click **Unactivated accounts**. 
3. In the _Unactivated accounts_ dialog, select the maximum number of sent activation emails to filter the UNIWeb accounts that will be selected. This will ensure that you don’t send too many emails to users who are not interested in activating their accounts. 
4. Click **Unactivated accounts**. UNIWeb will automatically select the members who have received the specified number of account activation emails.
5. In the right panel, click **Account activation**.
6. In the _Invite seleted members_ dialog, verify the UNIWeb members that you have selected.
7. Click **Invite**.

[1]:	#Creating-your-UNIWeb-account-from-an-institutions-UNIWeb-website
[2]:	#creating-your-UNIWeb-account-from-an-invitation-email
[3]:	#creating-UNIWeb-member-accounts-manually
[4]:	#creating-UNIWeb-member-accounts-in-bulk-using-a-spreadsheet
[5]:	#sending-account-activation-emails
[6]:	#sending-account-activation-reminder-emails
[8]:	####account-type
[9]:	##member-information-fields
[10]:	##creating-your-UNIWeb-account-from-an-invitation-email
[11]:	##member-information-fields
[12]:	##sending-account-activation-emails
