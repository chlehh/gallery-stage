# Ma galerie de stage — La Poste

Petit site pour montrer des images avec un titre. Léger, propre, pensé pour le téléphone.

---

## 1. Ajouter mes images

1. Glissez vos photos dans le dossier **`images/`**.
2. Ouvrez **`index.html`** et trouvez la liste `GALLERY` (vers le milieu du fichier).
3. Remplacez les 3 exemples par vos images, une ligne par image :

   ```js
   const GALLERY = [
     { src: "images/photo1.jpg", title: "Tableau de bord supervision" },
     { src: "images/photo2.jpg", title: "Migration des postes" },
     { src: "images/photo3.jpg", title: "Schéma réseau" },
   ];
   ```

   - `src` = le chemin vers le fichier (respectez bien le nom, majuscules comprises).
   - `title` = le petit titre affiché sous l'image.
   - L'ordre d'affichage = l'ordre de la liste.

4. Pour changer le titre du site, le sous-titre, etc. → la section `CONFIG` juste au-dessus.

> Astuce : des images autour de **1500 px de large** suffisent largement et gardent le site rapide.

---

## 2. Mettre en ligne avec GitHub Pages (gratuit, sans ligne de commande)

1. Créez un compte sur **github.com** (si ce n'est pas déjà fait).
2. Cliquez sur **New** (nouveau dépôt). Nom au choix, par ex. `stage-laposte`. Laissez en **Public**. Créez.
3. Sur la page du dépôt : **Add file → Upload files**. Glissez **`index.html`** **et** le dossier **`images/`** (avec vos photos dedans). Cliquez **Commit changes**.
4. Allez dans **Settings → Pages**.
5. Sous *Build and deployment*, **Source** = `Deploy from a branch`. **Branch** = `main`, dossier `/ (root)`. **Save**.
6. Patientez ~1 minute, rechargez la page : l'adresse de votre site apparaît, du type :

   ```
   https://VOTRE-PSEUDO.github.io/stage-laposte/
   ```

7. Ouvrez ce lien sur votre téléphone pour vérifier l'affichage.

Pour modifier plus tard : re-uploadez le fichier ou l'image modifiée (même nom), le site se met à jour tout seul.

---

## 3. Le QR code

Deux façons :

- **Dans le site** : bouton **« Partager »** en haut à droite → un QR code de l'adresse s'affiche, prêt à scanner. Vous pouvez aussi copier le lien.
- **À imprimer / mettre sur une diapo** : une fois l'adresse en ligne connue, je peux vous générer un QR code en image (PNG haute définition). Envoyez-moi simplement le lien `https://...github.io/...`.

---

## Bon à savoir

Un site GitHub Pages est **public** : vérifiez que vos captures ne contiennent pas d'informations internes ou confidentielles avant de publier.
