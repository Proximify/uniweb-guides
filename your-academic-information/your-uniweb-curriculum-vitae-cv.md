# Managing Your UNIWeb Curriculum Vitae \(CV\)

Your curriculum vitae \(CV\) is the cornerstone of your UNIWeb account. You can use your UNIWeb CV to [prepare for funding competitions](applying-for-funding-with-the-canadian-common-cv.md), complete [annual reports](downloading-cvs-and-reports.md#downloading-your-own-cv-and-report-files), and create a [public profile](../networking-on-uniweb/filling-out-your-public-profile.md#filling-out-your-public-profile-automatically-using-your-cv) for yourself. Your institution can use your CV data to maintain institutional websites, calculate metrics, and produce annual reports on your faculty’s performance.

By default, you are the only person who can edit your UNIWeb CV information. While certain administrators may have permission to view your CV data, there are no administrator privileges to modify user CV information. You may allow other users to edit your CV information by granting them [delegate access](../uniweb-accounts/access-control/delegate-access.md#granting-delegate-access) to your account.

As you populate your UNIWeb CV, you can either add new entries from scratch, or you can import data into UNIWeb from your Canadian Common CV \(CCV\) account.

#### On this page:

* [Importing from the Canadian Common CV](your-uniweb-curriculum-vitae-cv.md#importing-from-the-canadian-common-cv)
* [Populating your curriculum vitae manually](your-uniweb-curriculum-vitae-cv.md#populating-your-curriculum-vitae-manually)
* [Deleting curriculum vitae entries](your-uniweb-curriculum-vitae-cv.md#deleting-curriculum-vitae-entries)
* [Creating and restoring CV backups](your-uniweb-curriculum-vitae-cv.md#creating-and-restoring-cv-backups)
* [Curriculum vitae sections](your-uniweb-curriculum-vitae-cv.md#curriculum-vitae-sections)

## Importing from the Canadian Common CV

To import your CV information from the Canadian Common CV \(CCV\) website, you must first download that information from your CCV account into an XML file, which you will then upload into UNIWeb.

![](../.gitbook/assets/screencast-2019-10-20-13-05-31.gif)

1. From your [CCV account homepage](https://ccv-cvc.ca), click **Utilities** in the navigation bar.
2. In the Utilities dropdown menu, click **Export CV XML**.
3. In the _Captcha_ dialog, click the **“I’m not a robot”** checkbox.
4. Click **Export**. The CV XML file will appear in your downloads folder.
5. From your [UNIWeb Home page](../navigating-uniweb.md#the-home-page), go to Curriculum Vitae.
6. Click **Import from CCV** in the right panel.
7. Click **Choose file**, and select the XML file that you downloaded from the CCV website.
8. Click **Import**, and when the file is finished uploading, click **Done**. 

### How UNIWeb handles future imports and duplicates

You can reimport information to your UNIWeb CV from the CCV website after you have already created entries in UNIWeb. UNIWeb checks each record on import to ensure that it does not create duplicate entries, and when you click Import, will tell you what changes will occur, as per the examples below:

| Existing UNIWeb CV | Imported XML | Result |
| :--- | :--- | :--- |
| Record A | Record A \(identical\) | UNIWeb **ignores** identical records and will not create duplicates |
| Record B | \[No Match\] | UNIWeb **deletes** its copy of Record B |
| Record C | Record C \(modified\) | UNIWeb **replaces** Record C with the modified entry in the XML import. |
| \[No Match\] | Record D | UNIWeb **imports** Record D |

{% hint style="danger" %}
**Note:** because UNIWeb will replace records where the imported copies have been modified, it is important to note that the CCV does not always capture as much information as UNIWeb in each record. Notably, **the CCV does not capture month and date information**, and **the CCV does not capture any custom fields that your institution has requested** within sections, and so any information entered into these fields **may be lost** if they are replaced by copies that were modified on the CCV website.
{% endhint %}

## Populating your curriculum vitae manually

1. From your [UNIWeb Home page](../navigating-uniweb.md#the-home-page), go to **Curriculum Vitae**.
2. Locate the CV section where you would like to create a new record. You can **click on a section listed in the left panel** to navigate directly to that section.
3. In the centre panel, click the **Add** button to the right of the section title to add a new record, or click the **Edit** button to the right of an existing record to modify it.
4. Add or edit information in the data entry form as needed.
5. Click **Save**.

{% hint style="info" %}
**Tip:** if you’re trying to find a particular entry to edit, you can search for it by pressing **Command+F \(Mac\)** or **CTRL+F \(Windows\)** in your web browser while on the Curriculum Vitae page. Your UNIWeb CV is displayed on a single page, and so all of your CV records are searchable at once.
{% endhint %}

## Deleting a record from your curriculum vitae

1. From your [UNIWeb Home page](../navigating-uniweb.md#the-home-page), go to **Curriculum Vitae**.
2. Locate the CV record that you would like to delete, and click the **Edit** button to the right of the record.
3. At the bottom right of the data entry form, click **Delete**.

{% hint style="info" %}
**Tip:** if you’re trying to find a particular entry to edit, you can search for it by pressing **Command+F \(Mac\)** or **CTRL+F \(Windows\)** in your web browser while on the Curriculum Vitae page. Your UNIWeb CV is displayed on a single page, and so all of your CV records are searchable at once.
{% endhint %}

## Creating and restoring CV backups

Your curriculum vitae is a living document that grows with you through the course of your career. Because you will be regularly updating your CV, it's important to take regular backups so that you can restore your information in the event that something is accidentally deleted or modified incorrectly.

Backup files are different from CCV XML files because they contain all of your CCV information, as well as custom records that are unique to your institution.

### Creating a backup of your CV

1. From your [UNIWeb Home page](../navigating-uniweb.md#the-home-page), go to **Curriculum Vitae**.
2. In the right panel, click **Create/restore backups**.
3. In the right panel, click **Download a UNIWeb CV backup**.

A backup of your CV information will be downloaded as a JSON file. 

{% hint style="success" %}
**Best practice:** it's always best to keep more than one copy of a backup, in multiple places that you trust to hold your information securely - a personal or work computer, cloud service, etc.
{% endhint %}

### Restoring a backup of your CV

1. From your [UNIWeb Home page](../navigating-uniweb.md#the-home-page), go to **Curriculum Vitae**.
2. In the right panel, click **Create/restore backups**.
3. In the right panel, click **Restore from a file**.
4. In the centre panel, click **Choose file**, and browse your computer for your backup JSON file.
5. Click **Restore**, and after the restore process is complete, click **Done**.

Clicking **Done** will return you to the main backups screen, where you will see a list of backup files that you have previously restored. Once a backup file has been uploaded, it is retained by UNIWeb so that you can revert to that backup in the future if necessary.

## Curriculum Vitae Sections

UNIWeb’s Curriculum Vitae include all of the standard sections of the Canadian Common CV \(CCV\). If your institution has requested any custom information input fields or sections that are not part of the CCV, they will be demarcated by your institution’s logo to the right of the field or section title.

| CV Section | Purpose |
| :--- | :--- |
| **Personal Information** | Information about the person that facilitates identification, including name, date of birth, and sex. |
| **Education** | Collection of information records that, in combination, represent the full and up-to-date history of the person's education. |
| **Recognitions** | Any awards and citations that you have received over the course of oyur academic career |
| **User Profile** | Your biographical information and research interests. |
| **Employment** | Collection of information records that, in combination, represent the full and up-to-date history of the person's employment. |
| **Research Funding History** | A timeline of your funding sources throughout your career |
| **Activities** | Services, including teaching, supervisory, and community and volunteer activities, that you have contributed to. |
| **Memberships** | Services contributed as part of a group elected or appointed to perform such services but not directly related to the person's research activities. |
| **Most Significant Contributions** | A spotlight on the most significant achievements of your academic career and their impact. |
| **Contributions** | Things, including presentations, [publications](publications-1.md), interviews, patents, etc, that you have carried out as part of your career.  |



