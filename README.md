# Suite Cinema 35mm

Ce logiciel en Python doté d'une interface graphique (Tkinter) permet de fusionner des bobines audio de films 35mm. Il intègre des algorithmes de détection et suppression automatique des bips d'amorce et de fin (Goertzel + Énergie).

## 🚀 Fonctionnalités
- **Détection ultra-précise** et suppression des bips d'amorce et de fin.
- **Pipeline multicanal** (Gestion du 5.1 cinéma, traitement LFE).
- **Auto-installation** des outils nécessaires (FFmpeg, FFprobe).
- **Normalisation optionnelle** du volume via SoX.
- **Muxing final** au format Matroska (.mka) avec chapitrage automatique des bobines.

## 📋 Prérequis
Le script télécharge automatiquement FFmpeg si nécessaire. Pour les options avancées, vous pouvez installer séparément :
