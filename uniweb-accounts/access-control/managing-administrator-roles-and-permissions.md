# Managing Administrator Roles and Permissions

UNIWeb administrators are differentiated from general UNIWeb members because they can perform certain tasks within UNIWeb that general users cannot, or would not need to. The ability to perform a particular administrative task is called a [_**permission**_](managing-administrator-roles-and-permissions.md#administrator-permissions).

Not every UNIWeb administrator will need access to every permission across the entire UNIWeb network. Generally, a small number of users will need to have a particular set of permissions to perform administrative tasks within their academic unit. Accordingly, UNIWeb delegates administrator permissions through the creation of administrator _**roles**_, groupings of permissions that are restricted to a particular [academic unit](../academic-units/) and its sub-units. Roles can be assigned, modified, and removed from multiple UNIWeb members at once.

For example, a department of health sciences may have 3 faculty members that are dedicated to performing administrative tasks within the health sciences academic unit. These three administrators could be assigned a single role that looks like this:

<table>
  <thead>
    <tr>
      <th style="text-align:left">Role Name</th>
      <th style="text-align:left">Academic Unit</th>
      <th style="text-align:left">Permissions</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Health Sciences Administrator</b>
      </td>
      <td style="text-align:left">Health Sciences</td>
      <td style="text-align:left">
        <ul>
          <li>Approve new themes</li>
          <li>Assign roles to members</li>
          <li>Create new accounts</li>
          <li>Delete existing accounts</li>
          <li>Edit member information</li>
          <li>Send email invites</li>
          <li>View analytics</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>As the role in the example above applies only to the Health Sciences academic unit, the administrators who have been assigned the role above would _only be able to perform those tasks within the Health Sciences academic unit and its sub-units_. If the role above is modified - if permissions are added or removed - those modifications would be applied to all three administrator accounts at the same time.

#### On this page:

* [Creating Administrator Roles](managing-administrator-roles-and-permissions.md#creating-administrator-roles)
* [Editing Administrator Roles](managing-administrator-roles-and-permissions.md#editing-administrator-roles)
* [Deleting Administrator Roles](managing-administrator-roles-and-permissions.md#deleting-administrator-roles)
* [Administrator Permissions](managing-administrator-roles-and-permissions.md#administrator-permissions)

## Creating Administrator Roles

{% hint style="warning" %}
**Before you begin:** this procedure requires an administrator role within the subject’s academic unit that includes the following permissions:

* Edit Roles

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your [UNIWeb Administration page](../../introduction/feature-overview/navigating-uniweb.md#the-administration-page), go to **Access Control**
2. Click the **Add role** button in the left panel
3. In the _New Role_ dialog, type in a **Role name** and select the **Academic Unit** where the new role’s permissions will be applied. You may only create Roles within your own Academic Unit and its sub-units.
4. Select the [**permissions**](managing-administrator-roles-and-permissions.md#administrator-permissions) ****that you would like to assign to the new role. You may only assign permissions that you have access to within your Academic Unit.
5. Click **Save**.

{% hint style="info" %}
**Tip:** The permissions that you assign to a role are applied within the role’s selected academic unit and all of its sub-units. If you want a role to have access to all members and academic units of the network, choose the name of your institution as the academic unit for the role.
{% endhint %}

## Editing Administrator Roles

{% hint style="warning" %}
**Before you begin:** this procedure requires an administrator role within the subject’s Academic Unit that includes the following permissions:

* Edit Roles

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your [UNIWeb Administration page](../../introduction/feature-overview/navigating-uniweb.md#the-administration-page), go to **Access Control**
2. In the left panel, locate and **click on the role** that you would like to modify. You may only edit roles within your Academic Unit and its sub-units.
3. In the role dialog, you can modify the role name, Academic Unit, and select or deselect permissions for the role. You may only assign permissions that you have access to within your Academic Unit.
4. Select the [**permissions**](managing-administrator-roles-and-permissions.md#administrator-permissions) ****that you would like to assign to the new role
5. Click **Save.**

{% hint style="danger" %}
**Note:** Any changes made to an existing role will immediately affect all of the administrators who have previously been assigned that role.
{% endhint %}

## Deleting Administrator Roles

Roles cannot be deleted, but their [permissions](managing-administrator-roles-and-permissions.md#administrator-permissions) can be revoked. Roles that do not have any permissions assigned are greyed out and considered inactive, but can be made active again by reassigning permissions to it.

{% hint style="warning" %}
**Before you begin:** this procedure requires an administrator role within the subject’s academic unit that includes the following permissions:

* Edit Roles

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your UNIWeb Administration page, go to **Access Control**
2. In the left panel, locate and **click on the role** that you would like to modify. **You may only edit roles within your academic unit and its sub-units.**
3. In the role dialog, deselect all of the role’s assigned permissions.
4. Click **Save**.

{% hint style="danger" %}
**Note:** Any changes made to an existing role will immediately affect all of the administrators who have previously been assigned that role.
{% endhint %}

## Administrator Permissions

| Permission Name | Permission Function |
| :--- | :--- |
| **Approve new themes** | Edit, delete or approve [**research themes**](../../networking-on-uniweb/research-themes/managing-research-themes.md) that have been proposed by UNIWeb members within your Academic Unit. |
| **Assign roles to members** | \*\*\*\*[**Assign roles**](managing-administrators.md) to grant other UNIWeb members **administrator access** to your Academic Unit or its sub-units. |
| **Create API clients** | Grant other software systems secure read/write access to information stored by UNIWeb. See [**API Access**](../../uniweb-support-docs/api-access/) for more information. |
| **Create new accounts** | \*\*\*\*[**Create**](../account-management/account-creation.md#creating-uniweb-member-accounts-manually) ****UNIWeb member accounts. |
| **Delete existing accounts** | \*\*\*\*[**Delete**](../account-management/account-deletion.md#deleting-a-uniweb-members-account) ****UNIWeb member accounts. |
| **Edit academic units** | Create, edit or delete [**academic units**](../academic-units/managing-academic-units.md#create-an-academic-unit-manually) and [**unit types**](../academic-units/managing-academic-units.md#add-a-unit-type). |
| **Edit equipment information** | Create, edit or delete **equipment / resource profiles**. |
| **Edit member information** | \*\*\*\*[**Edit the public profile data of UNIWeb members**](../../networking-on-uniweb/your-public-profile/filling-out-your-public-profile.md#filling-out-another-uniweb-members-public-profile) in your academic unit, **view their CV information**, and [**generate CVs and Reports**](../../your-academic-information/exporting-academic-information/downloading-cvs-and-reports.md#downloading-member-cvs-and-reports) on their behalf. |
| **Edit roles** | Add, edit or delete [**administrator roles**](managing-administrator-roles-and-permissions.md). |
| **Edit web articles** | Add, edit or delete **web articles**. |
| **Receive new theme notifications** | Get automatic emails whenever a new [**research theme**](../../networking-on-uniweb/research-themes/managing-research-themes.md#approving-research-themes) is created by a UNIWeb member in your Academic Unit. |
| **Receive signup notifications** | Get automatic emails whenever a new UNIWeb member completes the [**UNIWeb signup process**](../account-management/account-creation.md). |
| **Send email invites** | Invite users to join the UNIWeb network by [**sending account sign-up invitations**](../account-management/account-creation.md#sending-account-activation-emails) ****and **reminder emails**. |
| **Upgrade profile schema** | Accept requests to update profile schemas. |
| **View analytics** | View and download **Academic Metrics** data from an Academic Unit. |

#### 

