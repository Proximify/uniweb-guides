# La gestion de rôles d'administrateur et des permissions

Les administrateurs d'UNIWeb sont différenciés des membres d'UNIWeb en général parce qu'ils peuvent effectuer certaines tâches au sein d'UNIWeb que les utilisateurs en général ne peuvent pas ou n'auraient pas besoin de faire. La possibilité d'effectuer une tâche administrative particulière est appelée une [_**permission**_](managing-administrator-roles-and-permissions.md#administrator-permissions).

Tous les administrateurs UNIWeb n'auront pas besoin d'accéder à toutes les autorisations sur l'ensemble du réseau UNIWeb. En règle générale, un petit nombre d'utilisateurs devront disposer d'un ensemble particulier d'autorisations pour effectuer des tâches administratives au sein de leur unité académique. En conséquence, UNIWeb délègue les autorisations d'administrateur par la création de **rôles** d'administrateur, de regroupements d'autorisations qui sont limités à une [unité académique](../academic-units/) and its sub-units. Les rôles peuvent être attribués, modifiés et supprimés de plusieurs membres UNIWeb à la fois.

Par exemple, un département des sciences de la santé peut avoir 3 professeurs qui se consacrent à l'exécution de tâches administratives au sein de l'unité scolaire des sciences de la santé. Ces trois administrateurs pourraient se voir attribuer un rôle unique qui ressemble à ceci:

<table>
  <thead>
    <tr>
      <th style="text-align:left">Nom de r&#xF4;le</th>
      <th style="text-align:left">Unit&#xE9; acad&#xE9;mique</th>
      <th style="text-align:left">Permissions</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Administrateur des sciences de la sant&#xE9;</b>
      </td>
      <td style="text-align:left">Sciences de la sant&#xE9;</td>
      <td style="text-align:left">
        <ul>
          <li>Approuver de nouveaux th&#xE8;mes</li>
          <li>Attribuer des r&#xF4;les aux membres</li>
          <li>Cr&#xE9;er de nouveaux comptes</li>
          <li>Supprimer les comptes existants</li>
          <li>Modifier les informations sur les membres</li>
          <li>Envoyer des invitations par e-mail</li>
          <li>Afficher les analyses</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>Étant donné que le rôle dans l'exemple ci-dessus ne s'applique qu'à l'unité scolaire des sciences de la santé, les administrateurs qui ont reçu le rôle ci-dessus ne pourraient effectuer ces tâches **qu'au sein de l'unité scolaire des sciences de la santé et de ses sous-unités**. Si le rôle ci-dessus est modifié - si des autorisations sont ajoutées ou supprimées - ces modifications seront appliquées aux trois comptes d'administrateur en même temps.

Lorsque votre institution met en place son réseau, l'équipe Proximify créera vos premiers comptes administrateur. En tant qu'administrateur, il est de votre responsabilité de créer et d'attribuer des rôles aux futurs utilisateurs.

**Sur cette page:**

* [Création de rôles d'administrateur](managing-administrator-roles-and-permissions.md#creating-administrator-roles)
* [Modification de rôles d'administrateur](managing-administrator-roles-and-permissions.md#editing-administrator-roles)
* [Suppression de rôles d'administrateur](managing-administrator-roles-and-permissions.md#deleting-administrator-roles)
* [Autorisations d'administrateur](managing-administrator-roles-and-permissions.md#administrator-permissions)

## ![](../../.gitbook/assets/key%20%281%29.svg) **Création de rôles d'administrateur**

{% hint style="warning" %}
**Before you begin:** this procedure requires an administrator role within the subject’s academic unit that includes the following [permissions](managing-administrator-roles-and-permissions.md#administrator-permissions):

* Edit Roles

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your [UNIWeb Administration ](../../navigating-uniweb/the-administration-page.md)page, go to **Access Control**
2. Click the **Add role** button in the left panel
3. In the _New Role_ dialog, type in a **Role name** and select the **Academic Unit** where the new role’s permissions will be applied. You may only create Roles within your own Academic Unit and its sub-units.
4. Select the [**permissions**](managing-administrator-roles-and-permissions.md#administrator-permissions) ****that you would like to assign to the new role. You may only assign permissions that you have access to within your Academic Unit.
5. Click **Save**.

{% hint style="info" %}
**Tip:** The permissions that you assign to a role are applied within the role’s selected academic unit and all of its sub-units. If you want a role to have access to all members and academic units of the network, choose the name of your institution as the academic unit for the role.
{% endhint %}

## ![](../../.gitbook/assets/key%20%281%29.svg) **Modification des rôles d'administrateur** 

{% hint style="warning" %}
**Before you begin:** this procedure requires an administrator role within the subject’s Academic Unit that includes the following [permissions](managing-administrator-roles-and-permissions.md#administrator-permissions):

* Edit Roles

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your [UNIWeb Administration ](../../navigating-uniweb/the-administration-page.md)page, go to **Access Control**
2. In the left panel, locate and **click on the role** that you would like to modify. You may only edit roles within your Academic Unit and its sub-units.
3. In the role dialog, you can modify the role name, Academic Unit, and select or deselect permissions for the role. You may only assign permissions that you have access to within your Academic Unit.
4. Select the [**permissions**](managing-administrator-roles-and-permissions.md#administrator-permissions) ****that you would like to assign to the new role
5. Click **Save.**

{% hint style="danger" %}
**Note:** Any changes made to an existing role will immediately affect all of the administrators who have previously been assigned that role.
{% endhint %}

## ![](../../.gitbook/assets/key%20%281%29.svg) **Suppression de rôles d'administrateur**

Roles cannot be deleted, but their [permissions](managing-administrator-roles-and-permissions.md#administrator-permissions) can be revoked. Roles that do not have any permissions assigned are greyed out and considered inactive, but can be made active again by reassigning permissions to it.

{% hint style="warning" %}
**Before you begin:** this procedure requires an administrator role within the subject’s academic unit that includes the following [permissions](managing-administrator-roles-and-permissions.md#administrator-permissions):

* Edit Roles

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your [UNIWeb Administration ](../../navigating-uniweb/the-administration-page.md)page, go to **Access Control**
2. In the left panel, locate and **click on the role** that you would like to modify. **You may only edit roles within your academic unit and its sub-units.**
3. In the role dialog, deselect all of the role’s assigned permissions.
4. Click **Save**.

{% hint style="danger" %}
**Note:** Any changes made to an existing role will immediately affect all of the administrators who have previously been assigned that role.
{% endhint %}

## **Autorisations d'administrateur**

| Permission Name | Permission Function |
| :--- | :--- |
| **Approve new themes** | Edit, delete or approve [**research themes**](../../networking-on-uniweb/research-themes/managing-research-themes.md) that have been proposed by UNIWeb members within your Academic Unit. |
| **Assign roles to members** | \*\*\*\*[**Assign roles**](managing-administrators.md) to grant other UNIWeb members **administrator access** to your Academic Unit or its sub-units. |
| **Create API clients** | Grant other software systems secure read/write access to information stored by UNIWeb. See **API Access** for more information. |
| **Create new accounts** | \*\*\*\*[**Create**](../account-management/account-creation.md#creating-uniweb-member-accounts-manually) ****UNIWeb member accounts. |
| **Delete existing accounts** | \*\*\*\*[**Delete**](../account-management/account-deletion.md#deleting-a-uniweb-members-account) ****UNIWeb member accounts. |
| **Edit academic units** | Create, edit or delete [**academic units**](../academic-units/managing-academic-units.md#create-an-academic-unit-manually) and [**unit types**](../academic-units/managing-academic-units.md#add-a-unit-type). |
| **Edit equipment information** | Create, edit or delete **equipment / resource profiles**. |
| **Edit member information** | \*\*\*\*[**Edit the public profile data of UNIWeb members**](../../networking-on-uniweb/filling-out-your-public-profile.md#filling-out-another-uniweb-members-public-profile) in your academic unit, **view their CV information**, and [**generate CVs and Reports**](../../your-academic-information/downloading-cvs-and-reports.md#downloading-member-cvs-and-reports) on their behalf. |
| **Edit roles** | Add, edit or delete [**administrator roles**](managing-administrator-roles-and-permissions.md). |
| **Edit web articles** | Add, edit or delete **web articles**. |
| **Receive new theme notifications** | Get automatic emails whenever a new [**research theme**](../../networking-on-uniweb/research-themes/managing-research-themes.md#approving-research-themes) is created by a UNIWeb member in your Academic Unit. |
| **Receive signup notifications** | Get automatic emails whenever a new UNIWeb member completes the [**UNIWeb signup process**](../account-management/account-creation.md). |
| **Send email invites** | Invite users to join the UNIWeb network by [**sending account sign-up invitations**](../account-management/account-creation.md#sending-account-activation-emails) ****and **reminder emails**. |
| **Upgrade profile schema** | Accept requests to update profile schemas. |
| **View analytics** | View and download **Academic Metrics** data from an Academic Unit. |

#### 

