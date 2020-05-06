# La gestion de votre Curriculum Vitae \(CV\) UNIWeb

Votre curriculum vitae \(CV\) est la pierre angulaire de votre compte UNIWeb. Vous pouvez utiliser votre CV UNIWeb pour [vous préparer pour des applications de financement](applying-for-funding-with-the-canadian-common-cv.md), ****remplir des [rapports annuels](downloading-cvs-and-reports.md#downloading-your-own-cv-and-report-files), et ****créer un [profile publique](../networking-on-uniweb/filling-out-your-public-profile.md#filling-out-your-public-profile-automatically-using-your-cv) pour vous-même. Votre institution peut utiliser les données de votre CV pour gérer des sites Web institutionnels, calculer des mesures et produire des rapports annuels sur les performances de votre faculté.

Par défaut, vous êtes la seule personne à pouvoir modifier les informations de votre CV UNIWeb. Bien que certains administrateurs puissent être autorisés à afficher les données de votre CV, il n'y a pas de privilèges d'administrateur pour modifier les informations du CV de l'utilisateur. Vous pouvez autoriser d'autres utilisateurs à modifier les informations de votre CV en leur accordant [accès délégué](../uniweb-accounts/access-control/delegate-access.md#granting-delegate-access) à votre compte.

Lorsque vous remplissez votre CV UNIWeb, vous pouvez soit ajouter de nouvelles entrées à partir de zéro, soit importer des données dans UNIWeb à partir de votre compte CV commun canadien \(CCV\).

#### Sur cette page:

* [Importer à partir du CV commun canadien](your-uniweb-curriculum-vitae-cv.md#importing-from-the-canadian-common-cv)
* [Remplir manuellement votre curriculum vitae](your-uniweb-curriculum-vitae-cv.md#populating-your-curriculum-vitae-manually)
* [Supprimer un enregistrement de votre curriculum vitae](your-uniweb-curriculum-vitae-cv.md#deleting-a-record-from-your-curriculum-vitae)
* [Création et restauration de sauvegardes de CV](your-uniweb-curriculum-vitae-cv.md#creating-and-restoring-cv-backups)
* [Sections du curriculum vitae](your-uniweb-curriculum-vitae-cv.md#curriculum-vitae-sections)

## Importer à partir du CV commun canadien 

Pour importer vos informations de CV à partir du site Web Canadian Common CV \(CCV\), vous devez d'abord télécharger ces informations depuis votre compte CCV dans un fichier XML, que vous téléchargerez ensuite dans UNIWeb.

![](../.gitbook/assets/screencast-2019-10-20-13-05-31.gif)

1. À partir de votre [Page d'accueil du CVC](https://ccv-cvc.ca), cliquez sur **Utilitaires** dans la barre de navigation.
2. Dans le menu déroulant Utilitaires, cliquez sur **Exporter CV XML.**
3. Dans la boîte de dialogue _Captcha_, cochez la case **Je ne suis pas un robot**.
4. Cliquez sur **Exporter**. Le fichier CV XML apparaîtra dans votre dossier de téléchargements.
5. À partir de votre [page d'accueil UNIWeb](../navigating-uniweb/the-home-page.md), allez sur Curriculum Vitae.
6. Cliquez sur **Importer à partir du CCV** dans le panneau de droite.
7. Cliquez sur **Choisir un fichier** et sélectionnez le fichier XML que vous avez téléchargé à partir du site Web CVC.
8. Cliquez sur **Importer** et une fois le téléchargement du fichier terminé, cliquez sur **Terminé.** 

### **Comment UNIWeb gère les importations et les doublons futurs**

Vous pouvez réimporter des informations dans votre CV UNIWeb à partir du site Web du CCV après avoir déjà créé des entrées dans UNIWeb. UNIWeb vérifie chaque enregistrement lors de l'importation pour s'assurer qu'il ne crée pas d'entrées en double et, lorsque vous cliquez sur Importer, vous indiquera les modifications qui se produiront, selon les exemples ci-dessous:

| CV UNIWeb actuel | XML importé | Résultat |
| :--- | :--- | :--- |
| Enregistrement A | Enregistrement A  ****\(identique\) | UNIWeb **ignore** les enregistrements identiques et ne crée pas de doublons |
| Enregistrement B | \[Pas de correspondance\] | UNIWeb **supprime** sa copie de l'enregistrement B |
| Enregistrement C | Enregistrement C \(modifié\) | UNIWeb **remplace** l'enregistrement C par l'entrée modifiée dans l'importation XML. |
| \[Pas de correspondance\] | Enregistrement D | UNIWeb **importe** le record D |

{% hint style="danger" %}
**Remarque:** comme UNIWeb remplacera les enregistrements dont les copies importées ont été modifiées, il est important de noter que le CCV ne capture pas toujours autant d'informations que UNIWeb dans chaque enregistrement. Notamment, **le CCV ne capture pas les informations de mois et de date, et le CCV ne capture pas les champs personnalisés que votre institution a demandés dans les sections,** et ainsi toutes les informations saisies dans ces champs **peuvent être perdues** si elles sont remplacées par des copies qui ont été modifiées le le site Web du CCV.
{% endhint %}

## **Remplir manuellement votre curriculum vitae**

1. À partir de votre [Page d'accueil du CVC](https://ccv-cvc.ca), cliquez sur **Curriculum Vitae**.
2. Localisez la section CV où vous souhaitez créer un nouvel enregistrement. Vous pouvez **cliquer sur une section répertoriée dans le panneau de gauche** pour accéder directement à cette section.
3. Dans le panneau central, cliquez sur le bouton **Ajouter** à droite du titre de la section pour ajouter un nouvel enregistrement, ou cliquez sur le bouton **Modifier** à droite d'un enregistrement existant pour le modifier.
4. Ajoutez ou modifiez des informations dans le formulaire de saisie de données selon vos besoins.
5. Cliquez sur **Enregistrer.**

{% hint style="info" %}
**Tip: Conseil:** si vous essayez de trouver une entrée particulière à modifier, vous pouvez la rechercher en appuyant sur **Commande + F \(Mac\)** ou **CTRL + F \(Windows\)** dans votre navigateur Web sur la page Curriculum Vitae. Votre CV UNIWeb est affiché sur une seule page, et donc tous vos enregistrements de CV sont consultables à la fois.
{% endhint %}

## **Supprimer un enregistrement de votre curriculum vitae**

1. À partir de votre [page d'accueil UNIWeb](../navigating-uniweb/the-home-page.md), allez sur Curriculum Vitae.
2. Recherchez l'enregistrement CV que vous souhaitez **supprimer**, puis cliquez sur le bouton Modifier à droite de l'enregistrement.
3. En bas à droite du formulaire de saisie de données, cliquez sur **Supprimer.**

{% hint style="info" %}
**Conseil:** si vous essayez de trouver une entrée particulière à modifier, vous pouvez la rechercher en appuyant sur **Commande + F \(Mac\)** ou **CTRL + F \(Windows\)** dans votre navigateur Web sur la page Curriculum Vitae. Votre CV UNIWeb est affiché sur une seule page, et donc tous vos enregistrements de CV sont consultables à la fois.
{% endhint %}

## **Création et restauration de sauvegardes de CV**

Votre curriculum vitae est un document vivant qui évolue avec vous tout au long de votre carrière. Étant donné que vous mettrez régulièrement à jour votre CV, il est important d'effectuer des sauvegardes régulières afin de pouvoir restaurer vos informations en cas de suppression ou de modification incorrecte accidentelle.

Les fichiers de sauvegarde sont différents des fichiers XML CCV car ils contiennent toutes vos informations CCV, ainsi que des enregistrements personnalisés qui sont uniques à votre institution.

### **Création d'une sauvegarde de votre CV**

1. À partir de votre [page d'accueil UNIWeb](../navigating-uniweb/the-home-page.md), allez sur Curriculum Vitae.
2. Dans le panneau de droite, cliquez sur **Créer / restaurer des sauvegardes.**
3. Dans le panneau de droite, cliquez sur **Télécharger une sauvegarde de CV UNIWeb.**

Une sauvegarde des informations de votre CV sera téléchargée sous forme de fichier JSON.

{% hint style="success" %}
**Meilleure pratique:** il est toujours préférable de conserver plus d'une copie d'une sauvegarde, à plusieurs endroits en lesquels vous avez confiance pour conserver vos informations en toute sécurité - un ordinateur personnel ou professionnel, un service cloud, etc.
{% endhint %}

### **Restaurer une sauvegarde de votre CV**

1. À partir de votre [page d'accueil UNIWeb](../navigating-uniweb/the-home-page.md), allez sur Curriculum Vitae.
2. Dans le panneau de droite, cliquez sur **Créer / restaurer des sauvegardes.**
3. Dans le panneau de droite, cliquez sur **Restaurer à partir d'un fichier.**
4. Dans le panneau central, cliquez sur **Choisir un fichier** et recherchez sur votre ordinateur votre fichier JSON de sauvegarde.
5. Click **Restore**, and after the restore process is complete, click **Done**.

Cliquez sur **Terminé** pour revenir à l'écran principal des sauvegardes, où vous verrez une liste des fichiers de sauvegarde que vous avez précédemment restaurés. Une fois qu'un fichier de sauvegarde a été téléchargé, il est conservé par UNIWeb afin que vous puissiez revenir à cette sauvegarde à l'avenir si nécessaire.

## **Sections du curriculum vitae**

Le Curriculum Vitae d'UNIWeb comprend toutes les sections standard du CV commun canadien \(CVC\). Si votre établissement a demandé des champs de saisie d'informations personnalisés ou des sections qui ne font pas partie du CVC, ils seront délimités par le logo de votre établissement à droite du champ ou du titre de la section.

| Section du CV | Objectif |
| :--- | :--- |
| **Information personelle** | Informations sur la personne qui facilitent l'identification, y compris le nom, la date de naissance et le sexe. |
| **Education** | Collecte de dossiers d'information qui, combinés, représentent l'historique complet et à jour de l'éducation de la personne. |
| **Reconnaissances** | Tous les prix et citations que vous avez reçus au cours de votre carrière universitaire |
| **Profil d'utilisateur** | Vos informations biographiques et vos intérêts de recherche. |
| **Travail** | Collecte de dossiers d'information qui, combinés, représentent l'historique complet et à jour de l'emploi de la personne. |
| **Financement de recherche** | Une chronologie de vos sources de financement tout au long de votre carrière |
| **Activités** | Services, y compris l'enseignement, la supervision et les activités communautaires et bénévoles, auxquels vous avez contribué. |
| **Adhésion** | Les services ont contribué au sein d'un groupe élu ou nommé pour fournir ces services, mais qui n'étaient pas directement liés aux activités de recherche de la personne. |
| **Contributions les plus importantes** | Focalisation sur les réalisations les plus significatives de votre carrière académique et leur impact. |
| **Contributions** | Les choses, y compris les présentations, [publications](publications-1.md), entrevues, brevets, etc., que vous avez réalisées dans le cadre de votre carrière. |



