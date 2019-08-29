# Managing Administrator Roles and Permissions

UNIWeb administrators are differentiated from general UNIWeb members because they can perform certain tasks within UNIWeb that general users cannot, or would not need to. The ability to perform a particular administrative task is called a _permission_.

Not every UNIWeb administrator will need access to every permission across the entire UNIWeb network; generally, a small number of users will need to have a particular set of permissions to perform administrative tasks within their academic unit. Accordingly, UNIWeb delegates administrator permissions through the creation of administrator _roles_, groupings of permissions that are restricted to a particular academic unit and its sub-units. Roles can be assigned, modified, and removed from multiple UNIWeb members at once.

For example, a department of health sciences may have 3 faculty members that are dedicated to performing administrative tasks within the health sciences academic unit in UNIWeb. These three administrators could be assigned a single role that may include the following settings:
 
**Role Name:** Health Sciences Administrator 
**Academic Unit:** Health Sciences
**Permissions:**
• Approve New Themes
• Assign Roles to Members 
• Create New Accounts
• Delete Existing Accounts 
• Edit Member Information 
• Send Email Invites
• View Analytics

As the role above applies only to the Health Sciences academic unit, the administrators who have been assigned the role above would only be able to perform the tasks indicated in role’s permissions within that academic unit and its sub-units. If the role above is modified, the modifications will be applied to all three administrator accounts at the same time.

### On this page:
- [Creating Administrator Roles][1]
- [Editing Administrator Roles][2]
- [Deleting Administrator Roles][3]
- [Administrator Permissions][4]

---- 

## Creating Administrator Roles

> **Before you begin: **this procedure requires an Administrator Role within the subject’s Academic Unit that includes the following permissions:
> - Edit Roles
> If you have not been assigned a Role with the permissions listed above, and believe that you should be able to perform this task within your Academic Unit, please contact your system administrator.

1. From your UNIWeb Administration page, go to **Access Control**
2. Click the **Add role** button in the left panel
3. In the _New Role_ dialog, type in a **Role name** and select the **Academic Unit** where the new role’s permissions will be applied. You may only create Roles within your own Academic Unit and its sub-units.
4. Select the **permissions**that you would like to assign to the new role. You may only assign permissions that you have access to within your Academic Unit.
5. Click **Save**.

##### **Tip:** The permissions that you assign to a role are applied within the role’s selected Academic Unit and all of its sub-units. If you want a role to have access to all members and academic units of the network, choose the name of your institution as the Academic Unit for the role.

---- 

## Editing Administrator Roles

You may add or remove permissions that have been assigned to an existing role as needed. 

###### **Note:** Any changes made to an existing role will immediately affect all of the administrators who have previously been assigned that role.

> **Before you begin: **this procedure requires an Administrator Role within the subject’s Academic Unit that includes the following permissions:
> - Edit Roles
> If you have not been assigned a Role with the permissions listed above, and believe that you should be able to perform this task within your Academic Unit, please contact your system administrator.

1. From your UNIWeb Administration page, go to **Access Control**
2. In the left panel, locate and**click on the role** that you would like to modify. You may only edit roles within your Academic Unit and its sub-units.
3. In the role dialog, you can modify the role name, Academic Unit, and select or deselect permissions for the role. You may only assign permissions that you have access to within your Academic Unit.
4. Select the [**permissions**][5] that you would like to assign to the new role.
5. Click **Save**.

##### **Tip:** Permissions are applied to roles within their specific Academic Unit and all of the child units under it. If you want a role to have access to all members and academic units of the network, choose the name of your institution as the Academic Unit for the role.

---- 

## Deleting Administrator Roles
Roles cannot be deleted, but their permissions can be revoked. Roles that do not have any permissions assigned are greyed out and considered inactive, but can be made active again by reassigning permissions to it.

###### **Note:** Any changes made to an existing role will immediately affect all of the administrators who have previously been assigned that role.

> **Before you begin: **this procedure requires an Administrator Role within the subject’s Academic Unit that includes the following permissions:
> - Edit Roles
> If you have not been assigned a Role with the permissions listed above, and believe that you should be able to perform this task within your Academic Unit, please contact your system administrator.

1. From your UNIWeb Administration page, go to **Access Control**
2. In the left panel, locate and**click on the role** that you would like to modify. You may only edit roles within your Academic Unit and its sub-units.
3. In the role dialog, deselect all of the role’s assigned permissions.
4. Click **Save**.

##### **Tip:** Permissions are applied to roles within their specific Academic Unit and all of the child units under it. If you want a role to have access to all members and academic units of the network, choose the name of your institution as the Academic Unit for the role.

---- 

## Administrator Permissions

#### Approve New Themes
Edit, delete or approve **research themes** that have been proposed by UNIWeb members within your Academic Unit.

#### Assign Roles to Members
Assign roles to grant other UNIWeb members **Administrator access** to your Academic Unit or its sub-units.

#### Create API Clients
Grant other software systems secure read/write access to information stored by UNIWeb. See **API Access** for more information.

#### Create New Accounts
Create **UNIWeb member accounts**.

#### Delete Existing Accounts
Delete **UNIWeb member accounts**.

#### Edit Academic Units
Add, edit or delete **Academic Units** and **unit types**.

#### Edit Equipment Information
Add, edit or delete **equipment / resource profiles**.

#### Edit Member Information
Edit the public profile data of UNIWeb members in your Academic Unit, view their CV information, and **generate CVs and Reports** on their behalf.

#### Edit Roles
Add, edit or delete **Administrator Roles**.

#### Edit web articles
Add, edit or delete **custom web articles**.

#### Receive new theme notifications
Get automatic emails whenever a new **research theme** is created by a UNIWeb member in your Academic Unit.

#### Receive signup notifications
Get automatic emails whenever a new UNIWeb member completes the **UNIWeb signup process**.

#### Send Email Invites
Invite users to join the UNIWeb network by **sending account sign-up invitations**.

#### Upgrade profile schema
Accept requests to update profile schemas from this user.

#### View Analytics
View and download **Academic Metrics** data from an Academic Unit.

[1]:	#creating-administrator-roles
[2]:	#editing-administrator-roles
[3]:	#deleting-administrator-roles
[4]:	#administrator-permissions
[5]:	##administrator-permissions