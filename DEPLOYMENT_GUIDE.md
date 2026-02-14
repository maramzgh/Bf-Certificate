# 🚀 GUIDE DE DÉPLOIEMENT - Streamlit Cloud

## 📦 FICHIERS DU PROJET

Voici les 3 fichiers essentiels à uploader sur GitHub:

1. **streamlit_app.py** - L'application principale (contient le certificat intégré)
2. **requirements.txt** - Les dépendances Python
3. **README.md** - Documentation (optionnel mais recommandé)

---

## 🎯 ÉTAPES DE DÉPLOIEMENT

### ÉTAPE 1: Créer un repository GitHub

1. Va sur **https://github.com**
2. Connecte-toi (ou crée un compte)
3. Clique sur le **+** en haut à droite → **New repository**
4. Nom du repository: `kouki-award` (ou ce que tu veux)
5. Choisis **Public**
6. ✅ Coche "Add a README file"
7. Clique sur **Create repository**

---

### ÉTAPE 2: Uploader les fichiers

**Option A: Via l'interface web (PLUS FACILE)**

1. Dans ton repository, clique sur **Add file** → **Upload files**
2. **Drag & drop** ou sélectionne ces fichiers:
   - `streamlit_app.py`
   - `requirements.txt`
   - `README.md` (optionnel)
3. Scroll en bas et clique sur **Commit changes**

**Option B: Via Git (si tu connais Git)**

```bash
git clone https://github.com/TON-USERNAME/kouki-award.git
cd kouki-award
# Copie les 3 fichiers dans ce dossier
git add .
git commit -m "Add Kouki award app"
git push
```

---

### ÉTAPE 3: Déployer sur Streamlit Cloud

1. Va sur **https://share.streamlit.io**
2. Clique sur **Sign up** ou **Continue with GitHub**
3. Autorise Streamlit à accéder à ton GitHub
4. Clique sur **New app**
5. Remplis les champs:
   - **Repository**: `ton-username/kouki-award`
   - **Branch**: `main`
   - **Main file path**: `streamlit_app.py`
6. Clique sur **Deploy!**
7. ⏳ Attends 2-3 minutes...

---

### ÉTAPE 4: Récupère ton lien! 🎉

Une fois le déploiement terminé, ton app sera accessible à une URL comme:

```
https://kouki-award-xxxxx.streamlit.app
```

**OU**

```
https://ton-username-kouki-award-xxxxx.streamlit.app
```

**Copie ce lien et envoie-le à Kouki!** 💕

---

## 📧 MESSAGE À ENVOYER

```
Hey Kouki! 💝

J'ai quelque chose de spécial pour toi...
Clique sur ce lien:

[TON LIEN STREAMLIT ICI]

Je t'aime! 💕
Ta Marrouma la plus mignonne
```

---

## 🆘 PROBLÈMES COURANTS

**❌ "Module not found" error**
- Vérifie que `requirements.txt` est bien présent et contient: `streamlit>=1.31.0`

**❌ "File not found" error**
- Vérifie que le "Main file path" est exactement: `streamlit_app.py`

**❌ L'app ne se déploie pas**
- Attends quelques minutes, ça peut prendre du temps
- Vérifie les logs pour voir les erreurs
- Assure-toi que le repository est **Public**

**❌ Le certificat n'apparaît pas**
- C'est normal, le certificat est déjà intégré dans `streamlit_app.py`!

---

## ✨ TIPS

- L'app sera **GRATUITE et permanente**
- Tu peux modifier l'app plus tard en modifiant les fichiers sur GitHub
- L'app redémarre automatiquement quand tu modifies les fichiers
- Ça marche sur **mobile, tablette, et PC**!

---

## 🎀 BESOIN D'AIDE?

Si tu es bloquée à une étape, n'hésite pas à:
1. Vérifier que tous les fichiers sont bien uploadés
2. Relire les instructions étape par étape
3. Vérifier que ton repository est Public

**Bonne chance! Tu vas y arriver! 💪💕**
