# Creation de comptes

#### Sur cette page :

* [Créer votre compte UNIWeb à partir du site UNIWeb de l'institution](account-creation.md#creating-your-uniweb-account-from-an-institutions-uniweb-website)
* [Créer votre compte UNIWeb à partir d'un courriel d'invitation](account-creation.md#creating-your-uniweb-account-from-an-invitation-email)
* [Créer des comptes pour des membres d'UNIWeb manuellement ](account-creation.md#creating-uniweb-member-accounts-manually)
* [Créer des comptes pour des membres d'UNIWeb en gros avec une feuille de calcul](account-creation.md#creating-uniweb-member-accounts-in-bulk-using-a-spreadsheet)
* [Envoyer des courriels pour activer des comptes ](account-creation.md#sending-account-activation-emails)
* [Envoyer des rappels pour l'activation du compte](account-creation.md#sending-account-activation-reminder-emails)

## Créer votre compte UNIWeb à partir du site UNIWeb de l'institution

{% hint style="warning" %}
**Avant de commencer :** Si votre institution a intégré UNIWeb avec un système d'authentification unique existant, il n'y aura pas d'option pour s'inscrire à partir de la page Réseau UNIWeb de votre établissement. Au lieu de cela, un compte sera créé automatiquement pour vous lorsque vous suivez les étapes pour [se connecter avec votre compte UNIWeb](account-login.md#logging-in-to-your-uniweb-account) pour la première fois.
{% endhint %}

1. Sur la page du [réseau UNIWeb](../../navigating-uniweb/the-network-page.md) de votre établissement, cliquez sur le bouton **«**Connexion**»** sur le côté droit de la barre de navigation.
2. Sur l'écran de création de compte, sélectionnez votre rôle au sein de votre institution. Cela correspondra à votre [type de compte](member-account-information.md#membership-information-fields). Cliquez sur **Suivant**.
3. Remplissez les détails de votre [information de compte](member-account-information.md#account-information-fields). Les champs marqués d'un astérisque sont obligatoires. Remplissez les détails de vos informations de compte de membre. Les champs marqués d'un astérisque sont obligatoires. Cliquez sur **Suivant**.
4. Sélectionnez le nom de votre superviseur principal et co-superviseur \(le cas échéant\) dans votre établissement et indiquez la date de fin prévue de votre contrôle dans l'établissement. Le ou les superviseurs sélectionnés seront invités à valider ces informations afin d'activer votre compte.
5. Un courriel de confirmation sera envoyé à l'adresse que vous avez choisie. **Cliquez sur le lien «Vérifier mon e-mail»** dans l'e-mail de confirmation

Une fois que vous aurez vérifié votre adresse courriel, UNIWeb vous indiquera si vos superviseurs ont validé votre compte. Si vos superviseurs vérifient que les informations de votre compte sont correctes, vous recevrez un  [courriel d'invitation](account-creation.md#creating-your-uniweb-account-from-an-invitation-email) pour terminer la création de votre compte.

## Créer votre compte UNIWeb à partir d'un courriel d'invitationl

{% hint style="warning" %}
**Avant de commencer :** vous recevrez un e-mail d'invitation d'UNIWeb soit lorsque vous créez votre propre compte via la page Réseau UNIWeb de votre institution, soit si un administrateur UNIWeb crée un compte pour vous. Si vous pensez que vous auriez dû recevoir un courriel d'invitation et que vous ne l'avez pas fait, veuillez contacter un administrateur système pour l'instance UNIWeb de votre institution.
{% endhint %}

1. Cliquez sur le lien **Activer mon compte UNIWeb** dans le corps de l'e-mail.
2. Lisez les termes de la licence du logiciel et, si vous êtes d'accord, **cliquez sur le bouton «J'accepte»** pour continuer
3. **Créez un mot de passe** pour votre nouveau compte UNIWeb et **cliquez sur le bouton «Soumettre».**

## ![](../../.gitbook/assets/key%20%281%29.svg) Créer des comptes pour des membres d'UNIWeb manuellement

{% hint style="warning" %}
**Avant de commencer :** Si votre institution a intégré UNIWeb avec un système d'authentification unique existant, **il n'y aura pas de besoin pour créer un compte UNIWeb manuellement.** Les comptes sont créés automatiquement pour les utilisateurs lorsqu'ils suivent les étapes pour [se connecter à leur compte UNIWeb](account-login.md#logging-in-to-your-uniweb-account) pour la première fois.

**Cette procédure nécessite un**[ **role administrateur**](../access-control/managing-administrator-roles-and-permissions.md) au sein de l'unité scolaire du sujet qui inclut les [autorisations](../access-control/managing-administrator-roles-and-permissions.md#administrator-permissions) suivantes :

* Créer des nouveaux comptes
* Modifier l'information des membres 

Si aucun rôle ne vous a été attribué avec les autorisations répertoriées ci-dessus et que vous pensez pouvoir effectuer cette tâche au sein de votre unité scolaire, veuillez contacter votre administrateur système.
{% endhint %}

1. From your [UNIWeb Administration ](../../navigating-uniweb/the-administration-page.md)page, go to **Members**.
2. In the right panel, click the **Add a new member** button.
3. In the _Add new members_ dialog, fill in the [member information fields](member-account-information.md#membership-information-fields) for the new UNIWeb member. Fields that are marked with an asterisk are mandatory.
4. Click **Save**.

{% hint style="danger" %}
**Note:** After following the above procedure, you must [send an account activation email ](account-creation.md#sending-account-activation-emails)in order for the new UNIWeb member to complete the account activation process.
{% endhint %}

## ![](../../.gitbook/assets/key%20%281%29.svg) Créer des comptes pour des membres d'UNIWeb en gros avec une feuille de calcul

From time to time, you may need to add many new member accounts at once. You can create member accounts in bulk by uploading a spreadsheet into UNIWeb that includes information for all of the accounts that you would like to add. UNIWeb will scan the spreadsheet for accounts that already exist in the network, and so you can maintain and upload a single spreadsheet numerous times without creating duplicates.

{% hint style="warning" %}
**Avant de commencer :** If your institution has integrated UNIWeb with an existing single-sign-on system, **there is no need to create UNIWed accounts manually**. Accounts are created for users automatically when they follow the steps to [log in to their UNIWeb account](account-login.md#logging-in-to-your-uniweb-account) for the first time.
{% endhint %}

{% hint style="warning" %}
**This procedure requires an** [**administrator role**](../access-control/managing-administrator-roles-and-permissions.md) within the subject’s academic unit that includes the following [permissions](../access-control/managing-administrator-roles-and-permissions.md#administrator-permissions):

* Create new accounts
* Edit member information

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

### Creating a UNIWeb member account spreadsheet:

To get your member account spreadsheet started, you can download a template spreadsheet that’s already formatted properly for UNIWeb's requirements.

{% file src="../../.gitbook/assets/accounts\_creation\_templates.zip" caption="Download a member account template spreadsheet" %}

The sample spreadsheet includes all of the accepted [member information fields](member-account-information.md#membership-information-fields) that can be used when creating a UNIWeb account spreadsheet. An example record is listed below; **entries marked with an asterisk are mandatory:**

| First Name\* | Middle Name | Last Name\* | Account Type\* | Position Title\* | Academic Unit\* | Email\* | Username | Telephone | Homepage | Office |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |


<table>
  <thead>
    <tr>
      <th style="text-align:left">Alexander</th>
      <th style="text-align:left">Graham</th>
      <th style="text-align:left">Bell</th>
      <th style="text-align:left">Professor</th>
      <th style="text-align:left">Associate Professor</th>
      <th style="text-align:left">Electrical Engineering</th>
      <th style="text-align:left">agbell@proximify.ca</th>
      <th style="text-align:left">bell024</th>
      <th style="text-align:left">613-555-5555</th>
      <th style="text-align:left"><a href="https://en.wikipedia.org/wiki/Alexander_Graham_Bell">https://en.wikipedia.org/wiki/Alexander_Graham_Bell</a>
      </th>
      <th style="text-align:left">
        <p>1105 Beinn Bhreagh Rd, Baddeck, NS</p>
        <p>B0E 1B0</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>{% hint style="success" %}
#### Best practices for your spreadsheet:

* The order of the columns does not matter
* Each row corresponds to one member account
* Empty rows are ignored
* If a row provides the same email address of an existing user in the system, the row is ignored \(this is how UNIWeb screens for duplicate entries\)
* Columns that UNIWeb does not recognize will cause an error.
* Acceptable entries for **account type, position title** and **academic unit** are dictated by your institution. 
{% endhint %}

### Uploading your spreadsheet to UNIWeb

1. From your [UNIWeb Administration ](../../navigating-uniweb/the-administration-page.md)page, go to **Members**.
2. In the right panel, click **Add members from a file**
3. In the _Add new members_ dialog, click **Choose File**, and locate your UNIWeb members spreadsheet on your computer.
4. Click **Submit**.

{% hint style="info" %}
**Tip:** If you enter an **Account Type, Position Title, or Academic Unit** that does not exist in the network, you will receive an error message. This will describe the error, indicate where it is located in your spreadsheet and provide you with a list of suitable replacements. If your spreadsheet contains any **blank fields that are mandatory or columns that UNIWeb does not recognize**, you will receive a similar error.
{% endhint %}

## ![](../../.gitbook/assets/key%20%281%29.svg) Envoyer des courriels pour activer des comptes

Once you have added new members to UNIWeb, you need to invite them to activate their accounts. This will send them a welcome email with text and information approved by your institution.

{% hint style="warning" %}
**Avant de commencer :** this procedure requires an [administrator role](../access-control/managing-administrator-roles-and-permissions.md) within the subject’s academic unit that includes the following [permissions](../access-control/managing-administrator-roles-and-permissions.md#administrator-permissions):
{% endhint %}

{% hint style="warning" %}
* Create new accounts
* Edit member information
* Send email invites

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your [UNIWeb Administration ](../../navigating-uniweb/the-administration-page.md)page, go to **Members**.
2. Locate the UNIWeb member\(s\) to whom you would like to send an account activation email, and **click the checkbox** on the right side of their row.
3. In the right panel, click **Account activation**.
4. In the _Invite selected members_ dialog, verify that you have selected the correct UNIWeb member\(s\).
5. Click **Invite**.

## ![](../../.gitbook/assets/key%20%281%29.svg) Envoyer des rappels pour l'activation du compte

If you have invited members previously, but they have yet to activate their accounts, you can send them a reminder email. If you’re unsure which members have already been sent invitation emails, UNIWeb can filter members for you to automatically select members who have been sent invitation and reminder emails in the past.

{% hint style="warning" %}
**Avant de commencer :** this procedure requires an [administrator role](../access-control/managing-administrator-roles-and-permissions.md) within the subject’s academic unit that includes the following [permissions](../access-control/managing-administrator-roles-and-permissions.md#administrator-permissions):
{% endhint %}

{% hint style="warning" %}
* Create new accounts
* Edit member information
* Send email invites

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your [UNIWeb Administration ](../../navigating-uniweb/the-administration-page.md)page, go to **Members**.
2. In the right panel, click **Unactivated accounts**. 
3. In the _Unactivated accounts_ dialog, select the maximum number of sent activation emails to filter the UNIWeb accounts that will be selected. This will ensure that you don’t send too many emails to users who are not interested in activating their accounts. 
4. Click **Unactivated accounts**. UNIWeb will automatically select the members who have received the specified number of account activation emails.
5. In the right panel, click **Account activation**.
6. In the _Invite seleted members_ dialog, verify the UNIWeb members that you have selected.
7. Click **Invite**.

