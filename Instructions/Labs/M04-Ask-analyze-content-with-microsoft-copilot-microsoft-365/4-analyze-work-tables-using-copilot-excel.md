# Analyser et utiliser des tableaux à l’aide de Microsoft 365 Copilot dans Excel

Si vous ne savez pas comment écrire une formule pour une nouvelle colonne, Microsoft 365 Copilot peut rapidement ajouter de nouvelles colonnes comportant des formules basées sur vos données.

1. Avec vos données sont formatées en tableau, sélectionnez le bouton **Copilot** du ruban.

1. Sélectionnez **Ajouter des colonnes de formules** ou **Afficher des suggestions pour les colonnes de formules**. Vous pouvez également décrire les colonnes que vous souhaitez ajouter en les tapant selon vos propres mots.

1. Copilot fournit des suggestions de formules comportant une explication sur le fonctionnement de chaque formule. Affichez l’explication en sélectionnant **Expliquer la formule**.

1. Sélectionnez Insérer une colonne pour ajouter la colonne de formules dans votre tableau.

> [!IMPORTANT]
> Comme pour tout contenu généré par l’IA, il est important de passer en revue, modifier et vérifier tout ce que Copilot crée pour vous.

## Commençons

Tout d’abord, téléchargez **_[Fabrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)_** et enregistrez le fichier dans votre **dossier OneDrive** si vous ne l’avez pas encore fait.

Ouvrez la feuille de calcul dans Excel, puis ouvrez le volet **Copilot** en sélectionnant l’icône Copilot dans l’onglet **Accueil** du ruban. Entrez les prompts ci-dessous et suivez les instructions.

> [!NOTE]
> Prompt de départ :
>
> _Suggérer une colonne de formule._

Dans cette invite simple, vous commencez par l’**objectif** de base : _créer une colonne avec une formule_. Toutefois, il n’y a pas suffisamment de détails pour déterminer ce que la formule doit calculer.  

| Élément | Exemple |
| :------ | :------- |
| **Invite de base :** commencez par un **objectif** | **_Suggérer une colonne de formule._** |
| **Bon prompt :** ajouter un **contexte** | L’ajout de **contexte** aide Copilot à comprendre ce que la formule doit calculer. _« ... pour la colonne J pour déterminer le taux d’engagement de chaque campagne. »_ |
| **Meilleur prompt :** spécifier la ou les **sources** | La **source** de ce prompt est les colonnes spécifiques nécessaires au calcul. _« ... en utilisant les valeurs de "Utilisateurs engagés" et "Nombre total d’utilisateurs ciblés". »_ |
| **Meilleur prompt :** définir des **attentes** claires | L’ajout d’**attentes** aide Copilot à structurer correctement la formule. _« Veille à ce que la formule divise "Utilisateurs engagés" par "Nombre total d’utilisateurs ciblés" et présente le résultat sous la forme d’un pourcentage. »_ |

> [!NOTE]  
> **Prompt créé **:  
>
> _Suggère une formule pour la colonne J pour calculer le taux d’engagement de chaque campagne. Utilise les valeurs de « Utilisateurs engagés » et « Nombre total d’utilisateurs ciblés ». Veille à ce que la formule divise « Utilisateurs engagés » par « Nombre total d’utilisateurs ciblés » et présente le résultat sous la forme d’un pourcentage._  

![Capture d’écran des résultats du prompt créé à l’aide de Copilot dans Excel.](../media/ask_copilot-explain-formula-results-excel.png)

Copilot dispose de toutes les informations dont il a besoin pour vous donner une réponse efficace, grâce à l’**objectif**, au **contexte**, à la **source** et aux **attentes** que contient cette invite.

## Explorer davantage

Utilisez ces invites comme point de départ. Copiez et modifiez-les selon vos besoins.

- Calculez le coût total par produit dans une nouvelle colonne.

- Ajoutez une colonne calculant le bénéfice total de chaque campagne de marketing en 2022.

- Ajoutez une colonne calculant le nombre de jours après l’événement de lancement de produit.

Pour plus d’informations, consultez [Générer des colonnes de formule avec Copilot dans Excel](https://support.microsoft.com/office/generate-formula-columns-with-copilot-in-excel-d866d926-9791-4e5f-be2a-c6dd9e587a47).
