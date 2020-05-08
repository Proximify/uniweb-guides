# Gestion des unités académiques

Dans UNIWeb, la hiérarchie des unités académiques définit la structure globale du réseau. Cette hiérarchie commence avec l'institution elle-même - l'unité académique de haut niveau - qui se décompose en unités académiques plus petites, et ces unités académiques peuvent elles-mêmes se décomposer en unités académiques plus petites. Pour aider à illustrer cette hiérarchie, UNIWeb fait référence aux unités académiques différemment selon leur relation avec les autres unités:

Les petites unités académiques sont imbriquées dans une _**unité parente**_.

Les unités parentes sont composées de _**sous-unités**_ plus petites.

Quelle que soit leur position dans la hiérarchie de l'établissement, les unités académiques sont en outre classées en fonction de leur _**type d'unité**_: facultés, départements, programmes, bureaux ou toute autre classification requise par l'établissement.

En conséquence, chaque unité scolaire a un **nom**, un **type d'unité** et une **unité parente**. Voir l'exemple suivant:

|  | **Nom de l'unité** | **Type d'unité** | Unité parente |
| :--- | :--- | :--- | :--- |
| 1 | Théâtre | Programme | Département des beaux-arts |
| 2 | Département des beaux-arts | Département | Faculté d'arts et de sciences |
| 3 | Faculté d'arts et de sciences | Faculté | Université UNIWeb |
| 4 | Université UNIWeb | Université | \[aucune unité parente\] |

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

* Modifier les unités académiques

Avec cet ensemble d'autorisations, un utilisateur ne peut créer de nouvelles unités académiques que dans l'unité académique associée à son rôle d'administrateur.

Si aucun rôle ne vous a été attribué avec les autorisations répertoriées ci-dessus et que vous pensez que vous devriez pouvoir effectuer cette tâche au sein de votre unité scolaire, veuillez contacter votre administrateur système.
{% endhint %}

### **Création d'une feuille de calcul d'unité académique**

Pour démarrer la feuille de calcul de votre unité académique, vous pouvez télécharger une feuille de calcul modèle qui est déjà correctement formatée pour les exigences d'UNIWeb.

{% file src="../../.gitbook/assets/units\_creation\_templates.zip" caption="Download an academic unit spreadsheet template" %}

Le modèle de feuille de calcul comprend tous les champs d'[**information sur des unités académiques**](managing-academic-units.md#academic-unit-information-fields) acceptés qui peuvent être utilisés lors de la création d'une feuille de calcul d'unité universitaire. Un exemple d'enregistrement est répertorié ci-dessous; **les entrées marquées d'un astérisque sont obligatoires:**

| Type\* | Nom de l'unité\* | Unité parente \* | Nom en français | Nom d'URL | Page d'accueil | Publique | Couleur |
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

1. À partir de votre page [UNIWeb administrateur](../../navigating-uniweb/the-administration-page.md), allez sur **unités académiques**. 
2. Dans le panneau de droite, cliquez sur **Ajouter des unités à partir d'un fichier**
3. Dans la boîte de dialogue _Ajouter de nouvelles unités_, cliquez sur **Choisir un fichier** et recherchez la feuille de calcul de vos unités académiques sur votre ordinateur.
4. Cliquez sur **Soumettre.**

{% hint style="info" %}
**Conseil**: Si vous entrez un type ou une unité parent qui n'existe pas sur le réseau, vous recevrez un message d'erreur. Cela décrira l'erreur, indiquera où elle se trouve dans votre feuille de calcul et vous fournira une liste de remplacements appropriés. Si votre feuille de calcul contient des champs vides obligatoires ou des colonnes que UNIWeb ne reconnaît pas, vous recevrez une erreur similaire.
{% endhint %}

## ![](../../.gitbook/assets/key%20%281%29.svg) **Modifier une unité académique**

{% hint style="warning" %}
**Avant de commencer:** cette procédure nécessite un[ rôle d'administrateur](../access-control/managing-administrator-roles-and-permissions.md) qui inclut les autorisations suivantes:

* **Modifier les unités académiques**

Si aucun rôle ne vous a été attribué avec les autorisations répertoriées ci-dessus et que vous pensez que vous devriez pouvoir effectuer cette tâche au sein de votre unité scolaire, veuillez contacter votre administrateur système.
{% endhint %}

1. À partir de votre page [UNIWeb administrateur](../../navigating-uniweb/the-administration-page.md), allez sur **unités académiques**. 
2. Dans le panneau central, localisez et cliquez sur l'unité scolaire que vous souhaitez modifier.
3. Cliquez sur **Modifier** à droite de l'en-tête Informations sur l'unité.
4. Ajoutez ou modifiez les [informations sur l'unité académique ](managing-academic-units.md#academic-unit-information-fields)dans le formulaire de saisie des informations sur l'unité selon vos besoins.
5. **Facultatif:** si nécessaire, cliquez sur la bascule multilingue à côté des champs de saisie de données, le cas échéant, pour ajouter des informations sur l'unité dans une deuxième langue.
6. Cliquez sur **Sauvegarder**

.

## ![](../../.gitbook/assets/key%20%281%29.svg) **Supprimer une unité académique**

{% hint style="warning" %}
**Avant de commencer:** cette procédure nécessite un[ rôle d'administrateur](../access-control/managing-administrator-roles-and-permissions.md) qui inclut les autorisations suivantes:

* **Modifier les unités académiques**

Si aucun rôle ne vous a été attribué avec les autorisations répertoriées ci-dessus et que vous pensez que vous devriez pouvoir effectuer cette tâche au sein de votre unité scolaire, veuillez contacter votre administrateur système.
{% endhint %}

1. À partir de votre page [UNIWeb administrateur](../../navigating-uniweb/the-administration-page.md), allez sur **unités académiques**. 
2. Dans le panneau central, localisez et cliquez sur la case à cocher à droite des unités universitaires que vous souhaitez supprimer.
3. Dans le panneau de droite, cliquez sur **Supprimer la sélection**.
4. Dans la boîte de dialogue _Supprimer les unités sélectionnées_, confirmez que vous avez sélectionné les unités académiques appropriées.
5. Cliquez sur **Supprimer**.

{% hint style="danger" %}
**À noter:** S'il y a des membres d'UNIWeb qui ont l'unité académique que vous essayez de supprimer répertoriée comme unité académique principale, vous devrez d'abord affecter ces membres à d'autres unités académiques, sinon UNIWeb ne vous permettra pas de supprimer cette unité académique.
{% endhint %}

## ![](../../.gitbook/assets/key%20%281%29.svg) **Ajouter un type d'unité**

Les _**types d'unités**_ catégorisent les unités académiques et servent à faciliter la recherche et le filtrage pour des unités académiques particulières. Les types d'unités courants sont les **facultés**, les **départements** ou les **bureaux**, mais vous pouvez ajouter de nouveaux types d'unités selon les besoins pour refléter correctement la structure de votre établissement.

{% hint style="warning" %}
**Avant de commencer:** cette procédure nécessite un[ rôle d'administrateur](../access-control/managing-administrator-roles-and-permissions.md) qui inclut les autorisations suivantes:

* **Modifier les unités académiques**

Si aucun rôle ne vous a été attribué avec les autorisations répertoriées ci-dessus et que vous pensez que vous devriez pouvoir effectuer cette tâche au sein de votre unité scolaire, veuillez contacter votre administrateur système.
{% endhint %}

1. À partir de votre page [UNIWeb administrateur](../../navigating-uniweb/the-administration-page.md), allez sur **unités académiques**. 
2. Dans le panneau de droite, cliquez sur **Ajouter un type d'unité.**
3. Dans la boîte de dialogue _Créer et type d'unité académique_, entrez un nom pour votre nouveau type d'unité académique.
4. **Facultatif:** si nécessaire, cliquez sur la bascule **multilingue** à côté du champ de saisie de données pour ajouter le nom du type d'unité dans une seconde langue.
5. Cliquez sur **Sauvegarder.**

## **Champs d'informations sur l'unité scolaire**

| Champ de saisie des données | Objectif |
| :--- | :--- |
| **Nom** | Le nom de l'unité scolaire. |
| **Type** | Type d'unité de l'unité scolaire. |
| **Unité parente** | L' unité de niveau supérieur qui contient cette unité. Par exemple, si une unité académique de la **Faculté de génie** contient l'unité universitaire du **Département de génie électrique**, la Faculté de génie est considérée comme l'unité parente. |
| **Nom d'URL** | Vous pouvez définir la manière dont vous souhaitez que la fin de l'URL apparaisse pour la page dédiée de l'unité universitaire dans la section Membres d'UNIWeb. Il doit être en minuscules et ne contenir aucun espace. Par exemple, pour la **Faculté de génie**, vous pouvez définir le nom d'URL comme **faculté de génie**, et il apparaîtra dans UNIWeb sous la forme https://www.uniweb.network/members?unit=faculty-of-engineering. |
| **Page d'accueil** | Un lien vers le site Web principal de cette unité universitaire - il peut s'agir d'un site Web externe à UNIWeb. Cette page Web sera liée par le nom de l'unité universitaire sur sa page dédiée dans la section Membres d'UNIWeb. |
| **Visibilité publique** | Si vous souhaitez que cette unité universitaire apparaisse dans la version publique de votre réseau UNIWeb. Si cette case n'est pas cochée, l'unité académique ne sera visible que par les membres connectés au réseau UNIWeb. |
| **Couleur** | La valeur de couleur hexadécimale qui représentera cette unité académique dans les cartes de connexion de recherche. Si vous ne définissez pas de valeur de couleur pour une unité scolaire, elle héritera de la couleur de son unité parent. |
| **Modèle de CV par défaut** | Vous pouvez sélectionner un modèle de saisie qui sera présélectionné pour les membres d'UNIWeb affiliés à cette unité académique lorsqu'ils accèdent à leur [Curriculum Vitae UNIWeb](../../your-academic-information/your-uniweb-curriculum-vitae-cv.md). Ils peuvent toujours choisir parmi d'autres options**.** |

