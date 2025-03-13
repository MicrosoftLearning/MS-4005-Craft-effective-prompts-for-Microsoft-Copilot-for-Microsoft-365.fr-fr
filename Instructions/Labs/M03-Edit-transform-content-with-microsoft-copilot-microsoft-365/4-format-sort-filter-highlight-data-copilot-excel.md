# Mettre en forme, trier, filtrer et surligner des données à l’aide de Microsoft 365 Copilot dans Excel

Avec Microsoft 365 Copilot dans Excel, il est facile de mettre en surbrillance, trier et filtrer vos tableaux pour attirer rapidement l’attention sur ce qui vous importe. Dans un seul tableau dans Excel, vous pouvez facilement demander à Copilot de :

- Trier et filtrer vos données

- Appliquer une mise en forme conditionnelle simple

Pour commencer, mettez en forme vos données dans un [format pris en charge](https://support.microsoft.com/topic/format-data-for-copilot-in-excel-1604c8eb-57f1-4db1-8363-d53336228c65) et sélectionnez le bouton **Copilot** dans le ruban. Ensuite, indiquez à Copilot comment vous souhaitez manipuler le tableau pour mieux afficher certaines parties de vos données.

Dans l’exemple suivant, nous commençons par un prompt simple et nous ajoutons des éléments au fur et à mesure. Suivez la procédure avec l’exemple en utilisant vos propres données.

## Commençons

Tout d’abord, téléchargez **_[Fabrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)_** et enregistrez le fichier dans votre **dossier OneDrive** si vous ne l’avez pas encore fait.

Ouvrez la feuille de calcul dans Excel, puis ouvrez le volet **Copilot** en sélectionnant l’icône Copilot dans l’onglet **Accueil** du ruban. Entrez les prompts ci-dessous et suivez les instructions.

> [!NOTE]
> Prompt de départ :
>
> _Trie ce tableau._

Dans ce prompt simple, vous commencez par l’**objectif** de base : _trier et filtrer un tableau Excel_. Toutefois, il n’existe aucune indication sur la façon dont vous souhaitez trier les données et le champ que vous souhaitez filtrer.

| Élément | Exemple |
| :------ | :------- |
| **Invite de base :** commencez par un **objectif** | **_Trie ce tableau..._** |
| **Bon prompt :** ajouter un **contexte** | L’ajout de **contexte** peut aider Copilot à comprendre la finalité des diapositives et le thème sur lequel se concentrer. _« …pour rechercher le vendeur le plus performant. »_ |
| **Meilleur prompt :** spécifier la ou les **sources** | La **source** de ce prompt est supposée être le tableau avec lequel nous travaillons dans Excel. _« … ce tableau [Table1]… »_ |
| **Meilleur prompt :** définir des **attentes** claires | Enfin, ajouter des **attentes** peut aider Copilot à comprendre comment vous souhaitez que le tableau soit trié, filtré et présenté. _« et mets en évidence les meilleurs et les pires propriétaires de campagne selon leur revenu net. »_ |

> [!NOTE]
> **Prompt créé **:
>
> _Trie le tableau [Tableau1] pour rechercher le vendeur le plus performant et mets en évidence les meilleurs et les pires propriétaires de campagnes selon leur revenu net._

Ce prompt nécessite plusieurs étapes pour exécuter une technique de prompt appelée **chaînage** qui consiste à demander à Copilot d’effectuer des commandes séquentielles et back-to-back pour atteindre un seul objectif.

**Premier prompt** :

```text
Sort this table [Table1] to look for the most impactful salesperson.
```

**Deuxième prompt** :

```text
highlight the top and bottom campaign owners based off of net revenue
```

Copilot dispose de toutes les informations dont il a besoin pour vous donner une réponse efficace, grâce à l’**objectif**, au **contexte**, à la **source** et aux **attentes** que contient cette invite.

## Explorer davantage

Essayez ces invites simples pour mettre en surbrillance, trier et filtrer vos données et ajouter d’autres éléments pour améliorer vos résultats :

- Mettre en gras les 10 premières valeurs de la colonne Ventes.

- Surligner les valeurs les plus élevées en termes d’unités vendues.

- Trier le taux d’engagement du plus petit au plus grand.  

- Appliquer un filtre sur les éléments dus la semaine prochaine.

> [!IMPORTANT]
> Copilot utilise uniquement les fichiers stockés sur OneDrive ou SharePoint. Si vous ne pouvez pas sélectionner le bouton Copilot dans le ruban, essayez d’abord d’enregistrer le fichier dans le cloud. Pour plus d’informations, consultez [Mettre en surbrillance, trier et filtrer vos données avec Copilot dans Excel](https://support.microsoft.com/office/highlight-sort-and-filter-your-data-with-copilot-in-excel-05302e3f-de42-4475-b235-be9cb3d4e936).
