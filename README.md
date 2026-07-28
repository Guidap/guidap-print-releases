# guidap-print-releases
Binaires de l'application Guidap Print (Android)

# Installer Guidap Print sur votre tablette

Guidap Print est l'application qui imprime vos tickets de caisse sur votre
imprimante Bluetooth. L'installation prend environ 5 minutes.

> **Important : faites toutes ces étapes sur la tablette de caisse** (pas sur
> un ordinateur).

## Étape 1 — Télécharger l'application

1. Sur la tablette, ouvrez **Chrome**.
2. Ouvrez ce lien (la dernière version se télécharge automatiquement) :

   **https://github.com/Guidap/guidap-print-releases/releases/latest/download/guidap-print.apk**
3. Si un message « Ce type de fichier peut endommager votre appareil »
   apparaît : appuyez sur **Télécharger quand même** (ou **OK**). C'est un
   message standard d'Android pour toute application hors Play Store.

## Étape 2 — Installer

1. Quand le téléchargement est terminé, appuyez sur **Ouvrir** dans la
   notification (ou ouvrez l'application **Fichiers** → **Téléchargements** →
   appuyez sur le fichier `guidap-print.apk`).
2. Si un message « Pour votre sécurité, votre tablette n'est pas autorisée à
   installer des applications inconnues provenant de cette source » apparaît :
   - Appuyez sur **Paramètres** ;
   - Activez **Autoriser les applications de cette source** ;
   - Revenez en arrière avec la flèche ← .
3. Appuyez sur **Installer**.
4. Si un message de **Play Protect** apparaît (« Analyser l'application ? » ou
   « Application non vérifiée ») : appuyez sur **Installer quand même**
   (parfois caché derrière « Plus de détails »).
5. Appuyez sur **Ouvrir** une fois l'installation terminée.

## Étape 3 — Connecter l'imprimante (une seule fois)

1. Allumez votre imprimante de tickets.
2. Sur la tablette, ouvrez **Paramètres → Bluetooth**, puis associez
   l'imprimante (elle s'appelle par exemple « TM-m30_012345 »). Si un code est
   demandé, essayez `0000` ou `1234`.
3. Ouvrez l'application **Guidap Print** (icône verte avec une imprimante).
4. Si l'application demande l'autorisation d'utiliser le Bluetooth :
   appuyez sur **Autoriser**.
5. Dans la liste « Imprimantes appairées », appuyez sur votre imprimante :
   le statut passe à **Connectée** ✅.
6. Appuyez sur **Page de test** : un ticket de test doit sortir.

## Étape 4 — Configurer la caisse Guidap (une seule fois)

> Ce réglage se fait aussi sur la tablette de caisse : il est propre à chaque
> appareil.

1. Sur la tablette, ouvrez votre **caisse Guidap** dans Chrome et
   connectez-vous.
2. Ouvrez la page de **configuration des tickets de caisse** de votre
   administration Guidap.
3. Dans **« Point de vente utilisé sur... »**, choisissez
   **Tablette ou smartphone Android**.
4. Dans **« Taille du papier »**, choisissez la taille correspondant à votre
   imprimante (par exemple **imprimante 80mm** pour une Epson TM-m30).
5. Appuyez sur **Paramètres avancés** (juste en dessous).
6. Dans **« Application d'impression »**, sélectionnez
   **Guidap Print (HTTP, sans changement d'app)**.
7. Laissez le champ **Port** à `9631` (ne le changez que si Guidap vous le
   demande).
8. Appuyez sur **Imprimer un test** : un ticket doit sortir, **sans quitter la
   page de la caisse**.

## Étape 5 — C'est prêt !

Vous pouvez utiliser votre caisse Guidap et imprimer normalement.
L'application Guidap Print travaille en arrière-plan (une petite notification
« Guidap Print actif » reste affichée : c'est normal, ne la fermez pas).

## En cas de problème

- **Le ticket ne sort pas** : vérifiez que l'imprimante est allumée, avec du
  papier, et que l'application Guidap Print affiche « Connectée ».
- **Rien ne se passe quand vous imprimez depuis la caisse** : vérifiez dans les
  **Paramètres avancés** de la configuration des tickets (étape 4) que
  l'application d'impression sélectionnée est bien
  **Guidap Print (HTTP, sans changement d'app)**.
- **Message d'erreur lors de l'impression** : ouvrez Guidap Print →
  **Journal** — l'erreur y est affichée. Envoyez une capture d'écran au
  support Guidap.
- Pour toute question : contactez le support Guidap.

