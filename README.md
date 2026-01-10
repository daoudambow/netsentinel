# NetSentinel

**NetSentinel** est une plateforme de cybersécurité qui permet
d’évaluer en quelques secondes le niveau de confiance d’un réseau Wi-Fi
(café, hôtel, campus, salle de réunion).

L’objectif : **rendre la sécurité Wi-Fi visible et compréhensible pour tous**.

---

## 🚀 Fonctionnalités clés

- 📡 Scan Wi-Fi en moins de 5 secondes
- ⚠️ Détection de réseaux suspects (Evil Twin, Rogue AP)
- 🔢 Score de confiance du réseau (0–100)
- 🛡️ Recommandations automatiques pour se protéger
- 🤖 IA embarquée (TensorFlow Lite – en local)
- 📦 Sonde matérielle Raspberry Pi (optionnelle)

---

## 🧠 Comment ça marche

NetSentinel combine :
- une **application Android** pour le scan Wi-Fi et l’interface utilisateur,
- une **logique de détection heuristique** (et IA à terme),
- une **sonde Raspberry Pi** pour l’analyse réseau avancée.

Les données sensibles ne quittent pas l’appareil :
l’analyse est réalisée **localement** (edge computing).

---

## 🏗️ Architecture du projet

netsentinel/
├── android-app/ # Application Android (Kotlin) [en cours]
├── ml/ # Modèle IA TensorFlow Lite
├── materiel/ # Boîtier Raspberry Pi imprimable en 3D
├── docs/ # Documentation technique (à venir)
├── LICENSE
└── README.md

---

## 📍 État du projet

- [x] Vision et concept définis
- [x] Dépôt GitHub public
- [x] Modèle IA initial (TFLite v0.1)
- [x] Boîtier Raspberry Pi imprimable
- [ ] Application Android (MVP en cours)
- [ ] Démo vidéo
- [ ] Version bêta

---

## 🛠️ Technologies utilisées

- **Android** : Kotlin, Android Studio
- **IA** : TensorFlow Lite
- **Sonde réseau** : Raspberry Pi, Kismet, Suricata
- **CI/CD** : GitHub Actions (prévu)

---

## 🎓 Contexte

Projet open-source initié par **Daouda Mbow**  
dans un contexte académique et entrepreneurial
(cybersécurité, réseaux, edge AI).

---

## 🤝 Contribution

Les contributions sont bienvenues :
- idées
- tests
- documentation
- code

👉 Forkez le projet et ouvrez une Pull Request.

---

## 📄 Licence

Ce projet est distribué sous licence **GPL-3.0**.
