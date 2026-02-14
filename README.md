#  HARDBEAT PRO STUDIO

![Version](https://img.shields.io/badge/Version-1.0_Stable-00f3ff?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Web_Audio_API-b026ff?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Production_Ready-ccff00?style=for-the-badge)

<p align="center">
  <img src="URL_DE_TA_CAPTURE_D_ECRAN_ICI.png" alt="Interface Hardbeat Pro Studio" width="800">
</p>

> *"L'usine à Hardgroove : 4 canaux, séquenceur matriciel, drones infinis et mixage live, réunis au sein d'une seule interface Dark Neon."*

---

##  Présentation du Projet
**HARDBEAT PRO STUDIO** est une Groovebox numérique de calibre professionnel. Pensée pour les producteurs de musique électronique, de Techno Industrielle et de Hardgroove, cette Single Page Application (SPA) transforme le navigateur en un véritable cockpit de studio matériel.

Conçu avec une approche Orientée Objet (OOP), le studio permet de contrôler de manière parfaitement synchronisée **3 Synthétiseurs de modélisation analogique** et **1 Percussion Module (Beatbox V2)**, le tout piloté par une Horloge Maître (Master Clock) chirurgicale.

##  Détails Techniques & Fonctionnalités

###  Cœur du Système (Master Clock)
* **Contrôle de Transport Centralisé :** Un seul bouton "PLAY GLOBAL" synchronise instantanément les 4 machines à la milliseconde près.
* **BPM Maître :** Le tempo dicte sa loi à tous les séquenceurs de l'application.
* **Architecture SPA :** Changement de canal instantané via le routeur visuel (Zéro défilement, Zéro latence).

###  3x Synthétiseurs Indépendants
Chaque synthétiseur possède sa propre chaîne audio isolée :
* **Générateur (OSC) :** Sine, Saw, Square, Triangle avec contrôles d'Octave et de Detune spatial.
* **Filtre (VCF) :** Low-pass, High-pass, Band-pass avec résonance auto-oscillante.
* **Modulation (ADSR & LFO) :** Enveloppes punchy (Anti-clic 5ms intégré) et LFO routable (Cutoff/Pitch).
* **Modes de Jeu :**
  * **Séquenceur (SEQ) :** Séquenceur pas-à-pas (jusqu'à 64 steps) avec réglage du Gate.
  * **Arpégiateur (ARP) :** Matrice intelligente avec modes Up, Down, Up/Down, Random et Converge.
  * **Drone Infini (SNAP) :** Bouton de maintien (Latch) permettant de superposer des accords continus en temps réel tout en libérant les mains pour le "Live Tweaking".

###  Beatbox V2 (Percussion Module)
* 3 pistes dédiées : **Kick, Snare, et Hi-Hat**.
* **Moteur Dynamique :** Implémentation de 3 niveaux de vélocité par pas, permettant la création de *Ghost Notes* organiques et d'accents surpuissants pour un groove implacable.
* **Randomizer Intelligent :** Génération algorithmique de polyrythmies musicales et cohérentes.

###  Table de Mixage Globale (Mixer Live)
* Contrôle permanent des 4 canaux en bas de l'écran.
* "Headroom" audio optimisé pour éviter l'écrasement dynamique (Clipping).
* Boutons **MUTE** instantanés pour chaque piste, idéaux pour les performances live.

---

##  Crédits & Liens
**Un projet imaginé et développé par BINOKUB.**

* 🌐 **Site Web / Jeux & Projets :** [binokub.com](https://binokub.com)
* 🎧 **Design & Audio Engine :** Conçu pour la performance, la stabilité et le groove.
