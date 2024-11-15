
Avec Microsoft 365 Copilot dans Excel, il est facile de mettre en surbrillance, trier et filtrer vos tableaux pour attirer rapidement l’attention sur ce qui vous importe. Dans un seul tableau dans Excel, vous pouvez facilement demander à Copilot de : 

- Trier et filtrer vos données

- Appliquer une mise en forme conditionnelle simple

Pour commencer, mettez en forme vos données sous forme de tableau et sélectionnez l’icône **Copilot** dans le ruban. Ensuite, indiquez à Copilot comment vous souhaitez manipuler le tableau pour mieux afficher certaines parties de vos données. 

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
| Prompt de base : <br>Commencer par un **objectif** | **_Trie ce tableau..._** |
| Prompt correct : <br>Ajouter un **contexte** | L’ajout de **contexte** peut aider Copilot à comprendre la finalité des diapositives et le thème sur lequel se concentrer.<br><br>«  _… pour rechercher le vendeur le plus performant._  » |
| Prompt amélioré : <br>Spécifier la ou les **source(s)** | La **source** de ce prompt est supposée être le tableau avec lequel nous travaillons dans Excel.<br><br>«  _… ce tableau [Table1]…_  » |
| Prompt le plus efficace : <br>Définir des **attentes** claires | Enfin, ajouter des **attentes** peut aider Copilot à comprendre comment vous souhaitez que le tableau soit trié, filtré et présenté.<br><br>« _Ajoute une troisième colonne qui calcule le revenu net par utilisateur engagé, en tenant compte de leurs coûts budgétaires. Trie ce tableau dans l’ordre décroissant par revenu net par utilisateur engagé et surligne les propriétaires du haut et du bas de l’échelle._  » |

> [!NOTE]
> **Prompt créé **:
>
> _Trie ce tableau [Table1] pour rechercher le vendeur le plus performant. Ajoute une troisième colonne qui calcule le revenu net par utilisateur engagé, en tenant compte de leurs coûts budgétaires. Trie ce tableau dans l’ordre décroissant par revenu net par utilisateur engagé et surligner les propriétaires du haut et du bas de l’échelle._

Ce prompt nécessite plusieurs étapes pour exécuter une technique de prompt appelée **chaînage** qui consiste à demander à Copilot d’effectuer des commandes séquentielles et back-to-back pour atteindre un seul objectif. 

Dans l’invite conçue, Copilot comprend qu’il doit d’abord trouver une formule pour la nouvelle colonne pour calculer le revenu net par utilisateur engagé et l’insérer dans le tableau.

![Capture d’écran de Copilot dans Excel générant une formule à insérer dans le tableau.](../media/copilot-add-formula-excel.png)

Maintenant que la nouvelle colonne a été insérée dans le tableau, vous pouvez demander à Copilot de trier le tableau en fonction du revenu net le plus élevé par utilisateur engagé, ainsi que de mettre en évidence les meilleurs et les moins bons vendeurs.

[![Capture d’écran des résultats du prompt créé sur l’exemple de feuille de calcul à l’aide de Copilot dans Excel.](../media/copilot-sort-highlight-table-excel.png)](../media/copilot-sort-highlight-table-excel.png#lightbox)

Copilot dispose de toutes les informations dont il a besoin pour vous donner une réponse efficace, grâce à l’**objectif**, au **contexte**, à la **source** et aux **attentes** que contient cette invite.

## Explorer davantage

Essayez ces invites simples pour mettre en surbrillance, trier et filtrer vos données et ajouter d’autres éléments pour améliorer vos résultats :

- Mettre en gras les 10 premières valeurs de la colonne Ventes.

- Surligner les valeurs les plus élevées en termes d’unités vendues.

- Trier le taux d’engagement du plus petit au plus grand.  

- Appliquer un filtre sur les éléments dus la semaine prochaine.

> [!IMPORTANT]
> Copilot utilise uniquement les fichiers stockés sur OneDrive ou SharePoint. Si vous ne pouvez pas sélectionner le bouton Copilot dans le ruban, essayez d’abord d’enregistrer le fichier dans le cloud. Pour plus d’informations, consultez **[Mettre en surbrillance, trier et filtrer vos données avec Copilot dans Excel](https://support.microsoft.com/office/highlight-sort-and-filter-your-data-with-copilot-in-excel-05302e3f-de42-4475-b235-be9cb3d4e936)**.