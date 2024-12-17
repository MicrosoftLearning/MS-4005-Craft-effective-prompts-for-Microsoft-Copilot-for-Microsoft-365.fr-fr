Tout au long de ce module, nous allons créer des prompts Microsoft 365 Copilot qui référencent les fichiers suivants :

- [Contoso CipherGuard Product Specification.docx](https://go.microsoft.com/fwlink/?linkid=2269123)
- [Contoso CipherGuard project plan.docx](https://go.microsoft.com/fwlink/?linkid=2268924)
- [Market Trend Report- Protein shake.docx](https://go.microsoft.com/fwlink/?linkid=2268827)

**Remarque** : ce sont les fichiers que nous référencerons tout au long du module. Pour ce labo, toutefois, nous allons commencer par charger tous les fichiers sur **OneDrive** afin que les prompts Copilot puissent y accéder plus tard.

### Chargement des fichiers dans OneDrive

Suivez les étapes ci-dessous pour charger tous les fichiers requis dans **OneDrive** :

1. Connectez-vous à la machine virtuelle fournie par votre fournisseur de locataire en tant que compte **Administrateur** local avec le mot de passe `Pa55w.rd`.
2. Dans la barre des tâches Windows, sélectionnez **Microsoft Edge**.
3. Dans la barre d’adresse, entrez `https://www.office.com` .
4. Sous **Bienvenue dans Microsoft 365**, sélectionnez **Se connecter**.
5. À l’**invite de connexion**, entrez `userx@yourtenant.onmicrosoft.com` (nom d’utilisateur et locataire fournis par votre fournisseur de locataire), puis sélectionnez **Suivant**.
6. Dans l’écran **Entrez le mot de passe**, entrez le mot de passe (fourni par le fournisseur de locataire) pour le compte d’utilisateur, puis sélectionnez **Se connecter**.
7. Si vous êtes invité à **rester connecté**, sélectionnez **Ne plus afficher**, puis **Oui**.
8. Dans **Microsoft 365**, sélectionnez **Applications**.
9. Dans **Applications**, sélectionnez **OneDrive**.
10. Dans **OneDrive**, dans le coin supérieur gauche, sélectionnez **+** (ajouter) > **Chargement de fichiers**.
11. Dans l’**Explorateur de fichiers**, sélectionnez **Ce PC** > **Disque local (C:)** et ouvrez le dossier **ResourceFiles**.
12. Sélectionnez tous les fichiers du dossier **ResourceFiles**, puis sélectionnez **Ouvrir** pour les charger dans **OneDrive**.
13. Une fois le chargement terminé, vous devriez voir **29 éléments chargés dans Mes fichiers** en bas au centre de l’écran.
14. Laissez **Edge** ouvert et passez à la tâche suivante.

### Référencement de fichiers dans Copilot

Lorsque vous utilisez Copilot, vous pouvez constater que certains fichiers ne sont pas immédiatement disponibles dans les suggestions. En effet, certaines expériences Copilot référencent uniquement les fichiers figurant dans la **liste des éléments utilisés récemment**, tandis que d’autres vous permettent de parcourir **OneDrive** directement. Pour vous assurer qu’un fichier apparaît dans la **liste des éléments utilisés récemment**, il vous suffit de l’ouvrir dans l’application Microsoft 365 appropriée, et il sera ajouté automatiquement.

> [!IMPORTANT]
> Microsoft 365 Copilot fonctionne uniquement avec les fichiers enregistrés dans **OneDrive**. Les fichiers stockés localement sur votre PC doivent être déplacés vers **OneDrive** pour que Copilot puisse y accéder.

À mesure que vous progressez dans le module, vous aurez la possibilité d’essayer différents prompts sur ces fichiers. N’hésitez pas à expérimenter différentes approches pour améliorer vos compétences avec Copilot.