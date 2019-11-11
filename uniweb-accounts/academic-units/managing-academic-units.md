# Managing Academic Units

In UNIWeb, the hierarchy of academic units defines the overall structure of the network. This hierarchy begins with the institution itself - the top-level academic unit - which breaks down into smaller academic units, and these academic units may themselves break down into smaller academic units. To help illustrate this hierarchy, UNIWeb refers to academic units differently depending on their relationship to other units:

Smaller academic units are nested into a _**parent unit**_. 

Parent units are composed of smaller _**sub-units**_.

Regardless of their position in the institution's hierarchy, academic units are further categorized by their _**unit type:**_ faculties, departments, programs, offices, or any other classification as required by the institution.

Accordingly, every academic unit has a **name**, a **unit type** and a **parent unit**. See the following example:

|  | Unit Name | Unit Type | Parent Unit |
| :--- | :--- | :--- | :--- |
| 1 | Theatre | Program | Department of Fine Arts |
| 2 | Department of Fine Arts | Department | Faculty of Arts |
| 3 | Faculty of Arts | Faculty | UNIWeb University |
| 4 | UNIWeb University | University | \[no parent\] |

Every institution's hierarchy of academic units is unique, and so academic units and unit types can be created, edited, and deleted in UNIWeb as necessary to reflect the structure of your institution as it grows.

#### On this page:

* [Create an academic unit manually](managing-academic-units.md#add-an-academic-unit-manually)
* [Create multiple academic units using a spreadsheet](managing-academic-units.md#add-multiple-academic-units-using-a-spreadsheet)
* [Edit an academic unit](managing-academic-units.md#edit-an-academic-unit)
* [Delete an academic unit](managing-academic-units.md#delete-an-academic-unit)
* [Add a unit type](managing-academic-units.md#add-a-unit-type)
* [Academic unit information fields](managing-academic-units.md#academic-unit-information-fields)

## Create an academic unit Manually

{% hint style="warning" %}
**Before you begin:** this procedure requires an [administrator role](../access-control/managing-administrator-roles-and-permissions.md) that includes the following permissions:

* Edit academic units

**With this set of permissions, a user may create new academic units only within the academic unit associated with their administrator role.**

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.  
{% endhint %}

1. From your [UNIWeb Administrator](../../navigating-uniweb/#the-administration-page) page, go to **Academic Units**. 
2. In the right panel, click the **Add a new unit** button.
3. In the _Add a new unit_ dialog, **fill in the** [**academic unit information**](managing-academic-units.md#academic-unit-information-fields) **data entry form**. Fields that are marked with an asterisk are mandatory.
4. **Optional:** if necessary, click the **multilingual** toggle next to the data entry fields where applicable to add unit information in a second language. 
5. Click **Save**.

## Create multiple academic units using a spreadsheet

When setting up your UNIWeb network for the first time, you may need to add many new academic units at once. You can create academic units in bulk by uploading a spreadsheet into UNIWeb that includes information for all of the academic units that you would like to add. UNIWeb will scan the spreadsheet for academic units that already exist in the network, and so you can maintain and upload a single spreadsheet numerous times without creating duplicates.

{% hint style="warning" %}
**Before you begin:** this procedure requires an [administrator role](../access-control/managing-administrator-roles-and-permissions.md) that includes the following permissions:

* Edit academic units

**With this set of permissions, a user may create new academic units only within the academic unit associated with their administrator role.**

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.  
{% endhint %}

### Creating an academic unit spreadsheet

To get your academic unit spreadsheet started, you can download a template spreadsheet that’s already formatted properly for UNIWeb's requirements.

{% file src="../../.gitbook/assets/units\_creation\_templates.zip" caption="Download an academic unit spreadsheet template" %}

The template spreadsheet includes all of the accepted [academic unit information fields](managing-academic-units.md) that can be used when creating an academic unit spreadsheet. An example record is listed below; **entries marked with an asterisk are mandatory:**

| Type\* | Unit Name\* | Parent Unit\* | French Name | URL Name | Homepage | Public | Colour |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Department | Electrical Engineering | Faculty of Science | Ingénierie Électrique | electrical-engineering | www.uniweb.io/eleng | Yes | F4D5E2 |

{% hint style="success" %}
**Best practices for building your spreadsheet:**

* The order of the columns does not matter.
* Each row corresponds to one academic unit. 
* Empty rows are ignored 
* If a row provides the same unit name of an existing academic unit in the system, the row will be ignored \(this is how UNIWeb screens for duplicate entries\).
* Columns that UNIWeb does not recognize will cause an error.
{% endhint %}

### Uploading your spreadsheet to UNIWeb

1. From your [UNIWeb Administration](../access-control/managing-administrator-roles-and-permissions.md) page, go to **Academic Units**.
2. In the right panel, click **Add units from a file**
3. In the _Add new units_ dialog, click **Choose File**, and locate your academic units spreadsheet on your computer.
4. Click **Submit**.

{% hint style="info" %}
**Tip:** If you enter a type or parent unit that does not exist in the network, you will receive an error message. This will describe the error, indicate where it is located in your spreadsheet and provide you with a list of suitable replacements. If your spreadsheet contains any blank fields that are mandatory or columns that UNIWeb does not recognize, you will receive a similar error.
{% endhint %}

## Edit an academic unit

{% hint style="warning" %}
**Before you begin:** this procedure requires an [administrator role](../access-control/managing-administrator-roles-and-permissions.md) within the subject’s academic unit that includes the following permissions:

* Edit academic units

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your [UNIWeb Administration](../../navigating-uniweb/#the-administration-page) page, go to **Academic Units**.
2. In the centre panel, locate and click on the academic unit that you would like to edit.
3. Click **Edit** to the right of the _Unit Information_ heading.
4. Add to or edit the [academic unit information ](https://app.gitbook.com/@proximify/s/uniweb-docs/~/drafts/-LnYEzOBp5J6ui_Qtfpl/primary/uniweb-accounts/academic-units/managing-academic-units#academic-unit-information-fields)in the _Unit Information_ data entry form as needed.
5. **Optional:** if necessary, click the **multilingual** toggle next to the data entry fields where applicable to add unit information in a second language. 
6. Click **Save**.

## Delete an academic unit

{% hint style="warning" %}
**Before you begin:** this procedure requires an [administrator role](../access-control/managing-administrator-roles-and-permissions.md) within the subject’s academic unit that includes the following permissions:

* Edit academic units

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your [UNIWeb Administration](../../navigating-uniweb/#the-administration-page) page, go to **Academic Units**.
2. In the centre panel, locate and click on the checkbox to the right of the academic unit\(s\) that you would like to delete.
3. In the right panel, click **Delete selected**.
4. In the _Delete selected units_ dialog, confirm that you have selected the correct academic units.
5. Click **Delete**.

{% hint style="danger" %}
**Note:** If there are any UNIWeb members who have the academic unit that you are trying to delete listed as their primary academic unit, you will first need to assign those members to other academic units, otherwise UNIWeb will not allow you to delete that academic unit.
{% endhint %}

## Add a unit type

_**Unit types**_ categorize academic units, and serve to make searching and filtering for particular academic units easier. Common unit types are **faculty**, **department**, ****or **office**, but you can add new unit types as needed to properly reflect the structure of your institution.

{% hint style="warning" %}
**Before you begin:** this procedure requires an [administrator role](../access-control/managing-administrator-roles-and-permissions.md) within the subject’s academic unit that includes the following permissions:

* Edit academic units

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your [UNIWeb Administration](../../navigating-uniweb/#the-administration-page) page, go to **Academic Units**.
2. In the right panel, click **Add a unit type**.
3. In the _Create and academic unit type_ dialog, enter a name for your new academic unit type.
4. **Optional:** if necessary, click the **multilingual** toggle next to the data entry field to add the unit type name in a second language. 
5. Click **Save**.

## Academic unit information fields

| Data entry field | Purpose |
| :--- | :--- |
| **Name** | The name of the academic unit. |
| **Type** | The academic unit’s unit type. |
| **Parent Unit** | The higher level unit that contains this unit. For example, if a **Faculty of Engineering** academic unit contains the **Department of Electrical Engineering** academic unit, the Faculty of Engineering is considered the parent unit. |
| **URL Name** | You can define how you would like the end of the URL to appear for the academic unit’s dedicated page in the Members section of UNIWeb. It must be lowercase and contain no spaces. For example, for the Faculty of Engineering, you could define the URL Name as **faculty-of-engineering**, and it would appear in UNIWeb as https://www.uniweb.network/members?unit=**faculty-of-engineering** . |
| **Homepage** | A link to the main website for this academic unit - it can be a website that is external from UNIWeb. This webpage will be linked through the academic unit’s name on its dedicated page in the Members section of UNIWeb. |
| **Public Visibility** | Whether you would like this academic unit to appear in the public version of your UNIWeb network. If this checkbox is deselected, the academic unit will only be visible to members who are logged in to the UNIWeb network. |
| **Colour** | The hexadecimal colour value that will represent this academic unit in research connection maps. If you do not define a colour value for an academic unit, it will inherit the colour of its parent unit. |
| **Default CV Template** | You can select an input template that will be preselected for UNIWeb members affiliated with this academic unit when they access their [UNIWeb Curriculum Vitae](../../your-academic-information/your-uniweb-curriculum-vitae-cv.md). They can still select from other options. |

