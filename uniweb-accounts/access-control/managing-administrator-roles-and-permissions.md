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
**Avant de commencer:** cette procédure nécessite un rôle d'administrateur au sein de l'unité académique du sujet qui inclut les [permissions](managing-administrator-roles-and-permissions.md#administrator-permissions) suivantes:

* Modifier les rôles

Si aucun rôle ne vous a été attribué avec les autorisations répertoriées ci-dessus et que vous pensez que vous devriez pouvoir effectuer cette tâche au sein de votre unité scolaire, veuillez contacter votre administrateur système.
{% endhint %}

1. À partir de votre page d'[Administrateur UNIWeb ](../../navigating-uniweb/the-administration-page.md)allez sur **Contrôle d'accès**. 
2. Cliquez sur le bouton **Ajouter un rôle** dans le panneau de gauche.
3. Dans la boîte de dialogue _Nouveau rôle_, saisissez un nom de rôle et sélectionnez **l'unité académique** où les autorisations du nouveau rôle seront appliquées. Vous ne pouvez créer des rôles que dans votre propre unité académique et ses sous-unités.
4. Sélectionnez les [**permissions**](managing-administrator-roles-and-permissions.md#administrator-permissions) ****que vous souhaitez attribuer au nouveau rôle. Vous ne pouvez attribuer que les autorisations auxquelles vous avez accès au sein de votre unité académique.
5. Cliquez sur **Enregistrer.**

{% hint style="info" %}
**Conseil:** les autorisations que vous attribuez à un rôle sont appliquées au sein de l'unité scolaire sélectionnée du rôle et de toutes ses sous-unités. Si vous souhaitez qu'un rôle ait accès à tous les membres et unités académiques du réseau, choisissez le nom de votre établissement comme unité académique pour le rôle.
{% endhint %}

## ![](../../.gitbook/assets/key%20%281%29.svg) **Modification des rôles d'administrateur**

{% hint style="warning" %}
**Avant de commencer:** cette procédure nécessite un rôle d'administrateur au sein de l'unité académique du sujet qui inclut les [permissions](managing-administrator-roles-and-permissions.md#administrator-permissions) suivantes:

* Modifier les rôles

Si aucun rôle ne vous a été attribué avec les autorisations répertoriées ci-dessus et que vous pensez que vous devriez pouvoir effectuer cette tâche au sein de votre unité scolaire, veuillez contacter votre administrateur système.
{% endhint %}

1. À partir de votre page d'[Administrateur UNIWeb ](../../navigating-uniweb/the-administration-page.md)allez sur **Contrôle d'accès**. 
2. Dans le panneau de gauche, recherchez et cliquez sur **le rôle** que vous souhaitez modifier. Vous ne pouvez modifier que les rôles au sein de votre unité académique et de ses sous-unités.
3. Dans la boîte de dialogue du rôle, vous pouvez modifier le nom du rôle, Unité académique, et sélectionner ou désélectionner les autorisations pour le rôle. Vous ne pouvez attribuer que les autorisations auxquelles vous avez accès au sein de votre unité académique.
4. Sélectionnez les [**permissions**](managing-administrator-roles-and-permissions.md#administrator-permissions) que vous souhaitez attribuer au nouveau rôle.
5. Cliquez sur **Enregistrer.**

{% hint style="danger" %}
**À noter:** Toute modification apportée à un rôle existant affectera immédiatement tous les administrateurs auxquels ce rôle a déjà été attribué.
{% endhint %}

## ![](../../.gitbook/assets/key%20%281%29.svg) **Suppression de rôles d'administrateur**

Les rôles ne peuvent pas être supprimés, mais leurs [permissions](managing-administrator-roles-and-permissions.md#administrator-permissions) peuvent être révoquées. Les rôles auxquels aucune autorisation n'est attribuée sont grisés et considérés comme inactifs, mais peuvent être réactivés en lui réaffectant des autorisations.

{% hint style="warning" %}
**Avant de commencer:** cette procédure nécessite un rôle d'administrateur au sein de l'unité académique du sujet qui inclut les [permissions](managing-administrator-roles-and-permissions.md#administrator-permissions) suivantes:

* Modifier les rôles

Si aucun rôle ne vous a été attribué avec les autorisations répertoriées ci-dessus et que vous pensez que vous devriez pouvoir effectuer cette tâche au sein de votre unité scolaire, veuillez contacter votre administrateur système.
{% endhint %}

1. À partir de votre page d'[Administrateur UNIWeb](../../navigating-uniweb/the-administration-page.md), allez sur **Contrôle d'accès.**
2. Dans le panneau de gauche, recherchez et **cliquez sur le rôle** que vous souhaitez modifier. **Vous ne pouvez modifier que les rôles au sein de votre unité académique et de ses sous-unités.**
3. Dans la boîte de dialogue de rôle, désélectionnez toutes les autorisations attribuées au rôle.
4. Cliquez sur **Enregistrer.**

{% hint style="danger" %}
**À noter:** Toute modification apportée à un rôle existant affectera immédiatement tous les administrateurs auxquels ce rôle a déjà été attribué.
{% endhint %}

## **Autorisations d'administrateur**

| Nom de la permission | Fonction de la permission  |
| :--- | :--- |
| **Approuver de nouveaux thèmes** | Modifiez, supprimez ou approuvez les [**thèmes de recherche**](../../networking-on-uniweb/research-themes/managing-research-themes.md) proposés par les membres d'UNIWeb au sein de votre unité scolaire. |
| **Attribuer des rôles aux membres** | \*\*\*\*[**Attribuez des rôles**](managing-administrators.md) pour accorder aux autres membres d'UNIWeb un accès administrateur à votre **unité académique** ou à ses sous-unités. |
| **Créer des clients API** | Accordez à d'autres systèmes logiciels un accès sécurisé en lecture / écriture aux informations stockées par UNIWeb. Voir **Accès API** pour plus d'informations. |
| **Créer de nouveaux comptes** | \*\*\*\*[**Créez**](../account-management/account-creation.md#creating-uniweb-member-accounts-manually) ****des comptes de membre UNIWeb. |
| **Supprimer les comptes existants** | \*\*\*\*[**Suprimer**](../account-management/account-deletion.md#deleting-a-uniweb-members-account) les comptes des membres UNIWeb. |
| **Modifier les unités académiques** | Créez, modifiez ou supprimez [**unités académiques**](../academic-units/managing-academic-units.md#create-an-academic-unit-manually) ****et des ****[**types d'unités**](../academic-units/managing-academic-units.md#add-a-unit-type). |
| **Modifier les informations sur l'équipement** | Créez, modifiez ou supprimez des **profils d'équipement / des ressources.** |
| **Modifier les informations sur les membres** | \*\*\*\*[**Modifier les données du profil public des membres d'UNIWeb**](../../networking-on-uniweb/filling-out-your-public-profile.md#filling-out-another-uniweb-members-public-profile) dans votre unité académique, **affichez les informations de leur CV** et [**genérer des CVs et des rapports**](../../your-academic-information/downloading-cvs-and-reports.md#downloading-member-cvs-and-reports) en leur nom. |
| **Modifier les rôles** | Ajoutez, modifiez ou supprimez des [**roles d'administrateur**](managing-administrator-roles-and-permissions.md). |
| **Modifier des articles Web** | Ajoutez, modifiez ou supprimez des **articles Web.** |
| **Recevez de nouvelles notifications de thème** | Recevez des e-mails automatiques chaque fois qu'un nouveau [**thème de recherche**](../../networking-on-uniweb/research-themes/managing-research-themes.md#approving-research-themes) est créé par un membre d'UNIWeb dans votre unité scolaire. |
| **Recevoir des notifications d'inscription** | Recevez des e-mails automatiques chaque fois qu'un nouveau membre UNIWeb termine le [**processus d'inscription UNIWeb**](../account-management/account-creation.md). |
| **Envoyer des invitations par e-mail** | Invitez les utilisateurs à rejoindre le réseau UNIWeb en [**envoyant des invitations à créer un compte**](../account-management/account-creation.md#sending-account-activation-emails) ****et des **courriels de rappel** |
| **Mettre à jour le schéma de profil** | Acceptez les demandes de mise à jour des schémas de profil. |
| **Afficher les analytiques** | Affichez et téléchargez les données de rapports académiques à partir d'une **unité académique**. |

#### 

