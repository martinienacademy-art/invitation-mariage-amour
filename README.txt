INVITATION DE MARIAGE — GUIDE RAPIDE

1. Ouvrez index.html dans VS Code.
2. Tout en bas, dans CONFIG, remplacez les prénoms, initiales, date, lieu,
   adresse, lien du formulaire RSVP, date limite et hashtag.
3. Remplacez les photos du dossier photos en gardant les noms exacts :
   couple.jpg et photo-1.jpg à photo-6.jpg.
4. Ouvrez index.html dans votre navigateur pour tester.

MISE EN LIGNE AVEC GITHUB + VERCEL
A. GitHub
   - Connectez-vous à https://github.com et cliquez sur New repository.
   - Donnez un nom (ex. invitation-mariage), choisissez Public ou Private,
     puis Create repository.
   - Cliquez sur Add file > Upload files.
   - Déposez index.html, README.txt et le dossier photos (avec les images).
   - Cliquez sur Commit changes.

B. Vercel
   - Allez sur https://vercel.com et connectez-vous avec GitHub.
   - Cliquez sur Add New > Project.
   - Importez le dépôt invitation-mariage.
   - Framework Preset : Other ; Build Command et Output Directory : laissez vides
     (ou utilisez ./ si Vercel exige un dossier de sortie).
   - Cliquez sur Deploy.
   - Vercel vous donne une adresse du type https://nom-du-projet.vercel.app.
     Copiez-la et partagez-la avec vos invités.

C. Modifier plus tard
   - Modifiez les fichiers dans GitHub, puis Commit changes.
   - Vercel redéploie automatiquement le site.

IMPORTANT
- La dateISO doit être au format AAAA-MM-JJTHH:MM:SS et correspond à l'heure locale
  du lieu du mariage.
- Le lien RSVP doit pointer vers un formulaire réel (Google Forms, par exemple).
- Google Maps utilise l'adresse écrite dans rechercheMaps.
- Les images sont chargées depuis le dossier photos ; respectez les noms.
- Ce site est statique : aucun serveur, base de données ou abonnement n'est nécessaire.
