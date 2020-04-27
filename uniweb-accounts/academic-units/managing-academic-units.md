# Gestion des unités académiques

Dans UNIWeb, la hiérarchie des unités académiques définit la structure globale du réseau. Cette hiérarchie commence avec l'institution elle-même - l'unité académique de haut niveau - qui se décompose en unités académiques plus petites, et ces unités académiques peuvent elles-mêmes se décomposer en unités académiques plus petites. Pour aider à illustrer cette hiérarchie, UNIWeb fait référence aux unités académiques différemment selon leur relation avec les autres unités:

Les petites unités académiques sont imbriquées dans une _**unité parentale**_.

Les unités parentales sont composées de _**sous-unités**_ plus petites.

Quelle que soit leur position dans la hiérarchie de l'établissement, les unités académiques sont en outre classées en fonction de leur _**type d'unité**_: facultés, départements, programmes, bureaux ou toute autre classification requise par l'établissement.

En conséquence, chaque unité scolaire a un **nom**, un **type d'unité** et une **unité parentale**. Voir l'exemple suivant:

|  | **Nom de l'unité** | **Type d'unité** | Unité parentale |
| :--- | :--- | :--- | :--- |
| 1 | Théâtre | Programme | Département des beaux-arts |
| 2 | Département des beaux-arts | Département | Faculté d'arts et de sciences |
| 3 | Faculté d'arts et de sciences | Faculté | Université UNIWeb |
| 4 | Université UNIWeb | Université | \[aucune unité parentale\] |

La hiérarchie des unités académiques de chaque établissement est unique, de sorte que les unités académiques et les types d'unités peuvent être créés, modifiés et supprimés dans UNIWeb si nécessaire pour refléter la structure de votre établissement au fur et à mesure de sa croissance.

#### Sur cette page:

* [Créer une unité académique manuellement](managing-academic-units.md#create-an-academic-unit-manually)
* [Créer plusieurs unités académiques à partis d'une feuille de calcul](managing-academic-units.md#create-multiple-academic-units-using-a-spreadsheet)\*\*\*\*
* [Modifier une unité académique](managing-academic-units.md#edit-an-academic-unit)\*\*\*\*
* [Supprimer une unité académique](managing-academic-units.md#delete-an-academic-unit)
* [Ajouter un type d'unité](managing-academic-units.md#add-a-unit-type)
* [Champs d'informations sur l'unité scolaire](managing-academic-units.md#academic-unit-information-fields)

## ![](../../.gitbook/assets/key%20%281%29.svg) **Créer une unité académique manuellement**

{% hint style="warning" %}
**Avant de commencer:** cette procédure nécessite un[ rôle d'administrateur](../access-control/managing-administrator-roles-and-permissions.md) qui inclut les autorisations suivantes[: ](../access-control/managing-administrator-roles-and-permissions.md) 

* Modifier les unités académiques

Avec cet ensemble d'autorisations, un utilisateur ne peut créer de nouvelles unités académiques que dans l'unité académique associée à son rôle d'administrateur.  
  
Si aucun rôle ne vous a été attribué avec les autorisations répertoriées ci-dessus et que vous pensez que vous devriez pouvoir effectuer cette tâche au sein de votre unité scolaire, veuillez contacter votre administrateur système.
{% endhint %}

1. À partir de votre page [UNIWeb administrateur](../../navigating-uniweb/the-administration-page.md), allez sur **unités académiques**. 
2. Dans le panneau de droite, cliquez sur le bouton **Ajouter une nouvelle unité**.
3. Dans la boîte de dialogue _Ajouter une nouvelle unité_, **remplissez le formulaire de saisie des données**[ **information sur des unités académiques**](managing-academic-units.md#academic-unit-information-fields). Les champs marqués d'un astérisque sont obligatoires.
4. **Facultatif:** si nécessaire, cliquez sur la bascule **multilingue** à côté des champs de saisie de données, le cas échéant, pour ajouter des informations sur l'unité dans une deuxième langue.
5. Cliquez sur **Enregistrer.**

## ![](../../.gitbook/assets/key%20%281%29.svg) **Créer plusieurs unités académiques à l'aide d'une feuille de calcul**

Lorsque vous configurez votre réseau UNIWeb pour la première fois, vous devrez peut-être ajouter plusieurs nouvelles unités académiques à la fois. Vous pouvez créer des unités académiques en masse en téléchargeant une feuille de calcul dans UNIWeb qui comprend des informations pour toutes les unités académiques que vous souhaitez ajouter. UNIWeb analysera la feuille de calcul pour rechercher les unités académiques qui existent déjà dans le réseau, et ainsi vous pouvez maintenir et télécharger une seule feuille de calcul plusieurs fois sans créer de doublons.

{% hint style="warning" %}
**Avant de commencer:** cette procédure nécessite un[ rôle d'administrateur](../access-control/managing-administrator-roles-and-permissions.md) qui inclut les autorisations suivantes:

* **Modifier les unités académiques**

**Avec cet ensemble d'autorisations, un utilisateur ne peut créer de nouvelles unités académiques que dans l'unité académique associée à son rôle d'administrateur.**

Si aucun rôle ne vous a été attribué avec les autorisations répertoriées ci-dessus et que vous pensez que vous devriez pouvoir effectuer cette tâche au sein de votre unité scolaire, veuillez contacter votre administrateur système.
{% endhint %}

### **Création d'une feuille de calcul d'unité académique**

Pour démarrer la feuille de calcul de votre unité académique, vous pouvez télécharger une feuille de calcul modèle qui est déjà correctement formatée pour les exigences d'UNIWeb.

{% file src="../../.gitbook/assets/units\_creation\_templates.zip" caption="Download an academic unit spreadsheet template" %}

Le modèle de feuille de calcul comprend tous les champs d'[**information sur des unités académiques**](managing-academic-units.md#academic-unit-information-fields) acceptés qui peuvent être utilisés lors de la création d'une feuille de calcul d'unité universitaire. Un exemple d'enregistrement est répertorié ci-dessous; **les entrées marquées d'un astérisque sont obligatoires:**

| Type\* | Nom de l'unité\* | Unité parentale \* | Nom en français | Nom d'URL | Page d'accueil | Publique | Couleur |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Département | Ingénierie électrique | Faculté des sciences | Ingénierie Électrique | electrical-engineering | www.uniweb.io/eleng | Oui | F4D5E2 |

{% hint style="success" %}
**Meilleures pratiques pour créer votre feuille de calcul:**

* L'ordre des colonnes n'a pas d'importance.
* Chaque ligne correspond à une unité académique.
* Les lignes vides sont ignorées
* Si une ligne fournit le même nom d'unité d'une unité académique existante dans le système, la ligne sera ignorée \(c'est ainsi qu'UNIWeb filtre les entrées en double\).
* Les colonnes que UNIWeb ne reconnaît pas ne généraient pas une erreur.
{% endhint %}

### Uploading your spreadsheet to UNIWeb

1. From your [UNIWeb Administration](../../navigating-uniweb/the-administration-page.md) page, go to **Academic Units**.
2. In the right panel, click **Add units from a file**
3. In the _Add new units_ dialog, click **Choose File**, and locate your academic units spreadsheet on your computer.
4. Click **Submit**.

{% hint style="info" %}
**Tip:** If you enter a type or parent unit that does not exist in the network, you will receive an error message. This will describe the error, indicate where it is located in your spreadsheet and provide you with a list of suitable replacements. If your spreadsheet contains any blank fields that are mandatory or columns that UNIWeb does not recognize, you will receive a similar error.
{% endhint %}

## ![](../../.gitbook/assets/key%20%281%29.svg) **Modifier une unité académique**

{% hint style="warning" %}
**Before you begin:** this procedure requires an [administrator role](../access-control/managing-administrator-roles-and-permissions.md) within the subject’s academic unit that includes the following permissions:

* Edit academic units

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your [UNIWeb Administration](../../navigating-uniweb/the-administration-page.md) page, go to **Academic Units**.
2. In the centre panel, locate and click on the academic unit that you would like to edit.
3. Click **Edit** to the right of the _Unit Information_ heading.
4. Add to or edit the [academic unit information ](managing-academic-units.md#academic-unit-information-fields)in the _Unit Information_ data entry form as needed.
5. **Optional:** if necessary, click the **multilingual** toggle next to the data entry fields where applicable to add unit information in a second language. 
6. Click **Save**.

## ![](../../.gitbook/assets/key%20%281%29.svg) **Supprimer une unité académique**

{% hint style="warning" %}
**Before you begin:** this procedure requires an [administrator role](../access-control/managing-administrator-roles-and-permissions.md) within the subject’s academic unit that includes the following permissions:

* Edit academic units

If you have not been assigned a role with the permissions listed above, and believe that you should be able to perform this task within your academic unit, please contact your system administrator.
{% endhint %}

1. From your [UNIWeb Administration](../../navigating-uniweb/the-administration-page.md) page, go to **Academic Units**.
2. In the centre panel, locate and click on the checkbox to the right of the academic unit\(s\) that you would like to delete.
3. In the right panel, click **Delete selected**.
4. In the _Delete selected units_ dialog, confirm that you have selected the correct academic units.
5. Click **Delete**.

{% hint style="danger" %}
**Note:** If there are any UNIWeb members who have the academic unit that you are trying to delete listed as their primary academic unit, you will first need to assign those members to other academic units, otherwise UNIWeb will not allow you to delete that academic unit.
{% endhint %}

## ![](../../.gitbook/assets/key%20%281%29.svg) **Ajouter un type d'unité**

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

## **Champs d'informations sur l'unité scolaire**

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

