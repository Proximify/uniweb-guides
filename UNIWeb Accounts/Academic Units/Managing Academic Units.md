# Managing Academic Units

### On this page:
- [Add an academic unit manually][1]
- [Add multiple academic units using a spreadsheet][2]
- [Edit an academic unit][3]
- [Delete an academic unit][4]
- [Add a unit type][5]
- [Academic unit information fields][6]

## Add an academic unit Manually
> **Before you begin: **this procedure requires an Administrator Role within the subject’s academic unit that includes the following permissions:
> - Edit academic units
> If you have not been assigned a Role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.

1. From your UNIWeb Administrator page, go to **Academic Units**.
2. In the right panel, click the **Add a new unit** button.
3. In the _Add a new unit_ dialog, fill in the academic unit information form. Fields that are marked with an asterisk are mandatory:
	- Name
	- Type
	- URL Name
4. **Optional:** if necessary, click the **multilingual** toggle next to the text entry fields where applicable to add unit information in a second language. 
5. Click **Save**.

## Add multiple academic units using a spreadsheet
> **Before you begin: **this procedure requires an Administrator Role within the subject’s academic unit that includes the following permissions:
> - Edit academic units
> If you have not been assigned a Role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.  
> 
When setting up your UNIWeb network for the first time, you may need to add many new academic units at once. You can create academic units in bulk by uploading a spreadsheet into UNIWeb that includes information for all of the academic units that you would like to add. UNIWeb will scan the spreadsheet for academic units that already exist in the network, and so you can maintain and upload a single spreadsheet numerous times without creating duplicates.

To get your academic unit spreadsheet started, you can download a template spreadsheet that’s already formatted properly for UNIWeb to read and understand.

### To download a template spreadsheet:
1. From your UNIWeb Administration page, go to **Academic Units**.
2. In the right panel, click **Add units from a file**
3. In the _Add new units_ dialog, click **Download template file**

The template spreadsheet includes all of the accepted [academic unit information fields]() that can be used when creating an academic unit spreadsheet. Entries marked with an asterisk are mandatory:
 
- Type* - Unit Name * - Parent Unit * - French Name
- URL Name
- Homepage
- Public
- Colour

### Spreadsheet tips:
• The order of the columns does not matter
• Each row corresponds to one academic unit
• Empty rows are ignored
• If a row provides the same unit name of an existing academic unit in the system, the row will be ignored (this is how UNIWeb screens for duplicate entries)
• Columns that UNIWeb does not recognize will cause an error.

### Uploading your spreadsheet to UNIWeb
1. From your UNIWeb Administration page, go to **Academic Units**.
2. In the right panel, click **Add units from a file**
3. In the _Add new units_ dialog, click **Choose File**, and locate your academic units spreadsheet on your computer.
4. Click **Submit**.

##### **Tip:** If you enter a type or parent unit that does not exist in the network, you will receive an error message. This will describe the error, indicate where it is located in your spreadsheet and provide you with a list of suitable replacements. If your spreadsheet contains any blank fields that are mandatory or columns that UNIWeb does not recognize, you will receive a similar error.

## Edit an academic unit
> **Before you begin: **this procedure requires an Administrator Role within the subject’s academic unit that includes the following permissions:
> - Edit academic units
> If you have not been assigned a Role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.

1. From your UNIWeb Administration page, go to **Academic Units**.
2. In the centre panel, locate and click on the academic unit that you would like to edit.
3. Click **Edit** to the right of the _Unit Information_ heading.
4. Add or edit information in the _Unit Information_ entry form as needed.
5. **Optional:** if necessary, click the **multilingual** toggle next to the text entry fields where applicable to add unit information in a second language. 
6. Click **Save**.

## Delete an academic unit
> **Before you begin: **this procedure requires an Administrator Role within the subject’s academic unit that includes the following permissions:
> - Edit academic units
> If you have not been assigned a Role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.

1. From your UNIWeb Administration page, go to **Academic Units**.
2. In the centre panel, locate and click on the checkbox to the right of the academic unit(s) that you would like to delete.
3. In the right panel, click **Delete selected**.
4. In the _Delete selected units_ dialog, confirm that you have selected the correct academic units.
5. Click **Delete**.

###### **Note:** If there are any UNIWeb members who have the academic unit that you are trying to delete listed as their primary academic unit, you will first need to assign those members to other academic units, otherwise UNIWeb will not allow you to delete that academic unit.

## Add a unit type
> **Before you begin: **this procedure requires an Administrator Role within the subject’s academic unit that includes the following permissions:
> - Edit academic units
> If you have not been assigned a Role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.

_Unit types_ categorize academic units, and serve to make searching and filtering for particular academic units easier.

A unit type is the category of an academic unit. Common unit types are faculty, department or office, but you also have the option to add new types.
To add a unit type, select the Add Unit Type option from the right-hand menu. Here you can enter your new unit type and it will become an available option across the network.

## Academic unit information fields

#### Name
The name of the academic unit.

#### Type
The academic unit’s unit type.

#### Parent Unit
The higher level unit that contains this unit. For example, the Faculty of Engineering would contain the Department of Electrical Engineering. The Faculty of Engineering is considered the parent unit.

#### URL Name
You can define how you would like the end of the URL to appear for the academic unit’s dedicated page in the Members section of UNIWeb. It must be lowercase and contain no spaces. For example, for the Faculty of Engineering, you could define the URL Name as faculty-of-engineering, and it would appear in UNIWeb as [https://www.uniweb.network/members?unit=faculty-of-engineering][8].

#### Homepage
A link to the main website for this academic unit - it can be a website that is external from UNIWeb. This webpage will be linked through the academic unit’s name on its dedicated page in the Members section of UNIWeb. 

#### Public Visibility
Whether you would like this academic unit to appear in the public version of your UNIWeb network. If this checkbox is deselected, the academic unit will only be visible to members who are logged in to the UNIWeb network.

#### Colour
The hexadecimal colour value that will represent this academic unit in research connection maps. If you do not define a colour value for an academic unit, it will inherit the colour of its parent unit.

#### Default CV Template
You can select an input template that will be preselected for UNIWeb members affiliated with this academic unit when they access their UNIWeb Curriculum Vitae. They can still select from other options.

[1]:	#add-an-academic-unit-manually
[2]:	#add-multiple-academic-units-using-a-spreadsheet
[3]:	#edit-an-academic-unit
[4]:	#delete-an-academic-unit
[5]:	#add-a-unit-type
[6]:	#academic-unit-information-fields
[8]:	https://demo.uniweb.network/members?unit=facofeng