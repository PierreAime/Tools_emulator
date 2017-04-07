Dossier F-Zero-Tracks-Editor :
------------------------------

Cet outil est un freeware permettant de modifier les courses F-Zero X.
Testé avec F-Zero X version USA !

Son nom est F-Zero Execution Project.
Je n'en suis pas l'auteur.

Testé et fourni avec les DLLs manquantes ;) (Sous wine avec Ubuntu 16.04)


Installer les emulateurs et les outils Linux :
----------------------------------------------

A faire via le script 'Emulateurs_linux' et à exécuter dans le dossier même !
Testé sous Ubuntu 16.04 en 64 bits.


Script d'installation à lancer dans ce dossier (A EXECUTER EN TANT QUE ROOT !) :
--------------------------------------------------------------------------------

./Emulateurs_linux "opt"


Liste pour les differents 'opt' possibles (mettre seulement 1 option) :
-----------------------------------------------------------------------

-h => Aide

-intel => installation des firmwares INTEL manquants si vous possedez une carte graphique INTEL

-jstest-gtk => installation du viewer de manette Jstest-gtk

-mupen64plus => installation de l'emulateur Mupen64plus et ses extensions pour N64

-mednafen => installation de l'emulateur Mednafen pour NES, SNES et Virtual Boy

-retroarch 'votre dossier utilisateur' => installation de l'emulateur Retroarch avec son extension pour la GameBoy et GameBoy Color

Ex : -retroarch /home/linux

