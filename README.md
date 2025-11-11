# ⚽ Organiseur d’équipe – Rematch

Un outil **autonome** pour visualiser, organiser et partager les compositions de ton équipe **Rematch**, en **3v3** ou **5v5**.

Créé pour les matchs de **football en jeu vidéo** (Rematch, Rocket League, etc.), cet organiseur offre une vue du terrain du dessus avec des joueurs déplaçables, renommables, et une balle ⚽️ manipulable librement.

---

## 🧭 Fonctionnalités principales

### ⚙️ Gestion d’équipe
- Choix du **format** : `3v3` ou `5v5`
- **Joueurs bleus** et **rouges**, déplaçables librement
- **Renommage** rapide :
  - Double-clic (PC)
  - Appui long 600 ms (mobile)
- Sauvegarde automatique dans le navigateur

### 🪄 Menu contextuel sur chaque joueur
> (clic droit ou appui long)

- ✏️ **Renommer**
- ➕ **Dupliquer** (ajoute un joueur du même camp)
- 🗑️ **Supprimer**

### ⚽ Balle interactive
- Nouvelle entité indépendante **⚽️**, déplaçable comme un joueur  
- Position sauvegardée et incluse dans export/import/lien de partage  
- Idéale pour simuler des actions ou stratégies

### 💾 Sauvegarde et partage
- **Export JSON** / **Import JSON**
- **Lien de partage encodé** directement dans l’URL (`#state=...`)
- Les liens fonctionnent **même hors-ligne**, parfait pour GitHub Pages

### 🎯 Zones et repères
- Terrain complet vu du dessus
- Zones repérées : GK, DEF, MID, ATT
- Bande centrale, but, corners et cercle central visibles

---

## 🌍 Mise en ligne (GitHub Pages)

### Étape 1 — dépôt GitHub
Crée un dépôt (ou utilise l’existant) :
```bash
git init
git remote add origin https://github.com/<ton_pseudo>/rematch-organizer.git
```

### Étape 2 — ajout du fichier
Ajoute le fichier :
```
index.html
```
(téléchargé ici : `organiseur-equipe-rematch-TOUT-EN-UN-MENU-BALLE.html`)

Sur GitHub :
1. Clique **Add file → Upload files**
2. Glisse ton fichier `index.html`
3. Clique **Commit changes**

### Étape 3 — activer GitHub Pages
1. Va dans **Settings → Pages**
2. Dans **Branch**, choisis `main` (ou `master`) puis `/ (root)`
3. Clique **Save**
4. Ton site sera accessible à :
   ```
   https://<ton_pseudo>.github.io/rematch-organizer/
   ```

---

## 🧩 Export / Import JSON

- **Exporter JSON** → sauvegarde une compo (`composition-rematch.json`)
- **Importer JSON** → recharge ta disposition
- Tu peux avoir plusieurs fichiers :
  - `attaque.json`
  - `defense.json`
  - `contre.json`

---

## 🔗 Partager une compo

Chaque composition est encodée directement dans l’URL :
```
https://<ton_pseudo>.github.io/rematch-organizer/#state=...
```
Copie simplement ce lien (bouton **Copier lien de partage**) et envoie-le à ton équipe.  
En ouvrant le lien, la disposition se charge instantanément.

---

## 💡 Astuces
- Double-clic ou clic droit = **actions rapides**  
- Le menu s’adapte sur mobile (appui long)
- Le terrain est **responsive** : fonctionne sur PC, tablette, ou smartphone
- La **balle ⚽️** est enregistrée comme les joueurs dans chaque composition

---

## 🧱 Fichiers inclus
| Nom du fichier | Description |
|----------------|--------------|
| `index.html` | Version tout-en-un (joueurs, menu, balle, export/import, partage) |
| `README.md` | Ce guide explicatif |
| `composition-rematch.json` *(exemple)* | Fichier de composition exporté (optionnel) |

---

🛠️ Créé par **Jim (Rematch)**  
✨ Avec l’aide de *Alden – GPT-5 Designer*
