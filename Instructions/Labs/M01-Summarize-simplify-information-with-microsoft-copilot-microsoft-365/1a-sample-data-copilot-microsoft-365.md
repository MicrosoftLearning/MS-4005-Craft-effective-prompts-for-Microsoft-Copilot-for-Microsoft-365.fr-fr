# Exercice : suivre avec des exemples de données avec Microsoft 365 Copilot

Tout au long de ce module, nous allons créer des prompts Microsoft 365 Copilot qui référencent les fichiers suivants :

- [Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [Contoso Chai Tea market trends 2023.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)
- [Contoso Chai Tea market trends 2023.docx](https://go.microsoft.com/fwlink/?linkid=2269122)
- [Market Trend Report- Protein shake.docx](https://go.microsoft.com/fwlink/?linkid=2268827)
- [Mystic Spice Premium Chai Market Analysis Presentation.pptx](https://go.microsoft.com/fwlink/?linkid=2268768)

**Remarque** : ce sont les fichiers que nous référencerons tout au long du module. Pour ce labo, toutefois, nous allons commencer par charger tous les fichiers sur **OneDrive** afin que les prompts Copilot puissent y accéder plus tard.

## Chargement des fichiers dans OneDrive

Suivez les étapes ci-dessous pour charger tous les fichiers requis dans **OneDrive** :

1. Connectez-vous à la machine virtuelle fournie par votre fournisseur de locataire en tant que compte **Administrateur** local avec le mot de passe `Pa55w.rd`.
2. Dans la barre des tâches Windows, sélectionnez **Microsoft Edge**.
3. Dans la barre d’adresse, entrez `https://www.office.com` .
4. Sous **Bienvenue dans Microsoft 365**, sélectionnez **Se connecter**.
5. À l’**invite de connexion**, entrez `userx@yourtenant.onmicrosoft.com` (nom d’utilisateur et locataire fournis par votre fournisseur de locataire), puis sélectionnez **Suivant**.

    [![Capture d’écran du volet de ressources](../media/lab_resources_password.png)](../media/lab_resources_password.png#lightbox)

6. Dans l’écran **Entrez le mot de passe**, entrez le mot de passe (fourni par le fournisseur de locataire) pour le compte d’utilisateur, puis sélectionnez **Se connecter**.
7. Si vous êtes invité à **rester connecté**, sélectionnez **Ne plus afficher**, puis **Oui**.

    **Note :** si la page web apparaît floue après la connexion, actualisez la page.

8. Dans **Microsoft 365**, sélectionnez **Applications**.
9. Dans **Applications**, sélectionnez **OneDrive**.
10. Dans **OneDrive**, dans le coin supérieur gauche, sélectionnez **+** (ajouter) > **Chargement de fichiers**.
11. Dans l’**Explorateur de fichiers**, sélectionnez **Ce PC** > **Disque local (C:)** et ouvrez le dossier **ResourceFiles**.
12. Sélectionnez tous les fichiers du dossier **ResourceFiles**, puis sélectionnez **Ouvrir** pour les charger dans **OneDrive**.
13. Une fois le chargement terminé, vous devriez voir **29 éléments chargés dans Mes fichiers** en bas au centre de l’écran.
14. Laissez **Edge** ouvert et passez à la tâche suivante.

### Référencement de fichiers

Lorsque vous référencez des fichiers à partir de Copilot, vous pouvez constater que vous ne pouvez pas trouver certains fichiers à partir des suggestions fournies. En effet, certaines expériences avec Copilot référencent uniquement les fichiers figurant dans la liste des éléments utilisés récemment, tandis que d’autres vous permettent de parcourir OneDrive pour trouver votre fichier. Il est aussi facile de les ajouter à cette liste que de les ouvrir dans l’application Microsoft 365 appropriée.  Une fois qu’ils ont été ouverts, ils doivent apparaître dans la liste des éléments utilisés récemment.

> [!IMPORTANT]
> Microsoft 365 Copilot fonctionne uniquement avec les fichiers enregistrés dans OneDrive. Si les fichiers sont stockés localement sur votre PC, vous devrez les déplacer vers OneDrive pour activer Copilot.

À mesure que vous progressez dans le module, vous aurez la possibilité d’essayer d’autres invites sur ces fichiers et vous êtes encouragés à le faire pour explorer et améliorer vos compétences d’invite.
