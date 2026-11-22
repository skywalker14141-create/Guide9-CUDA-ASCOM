# Guide9-CUDA-ASCOM

This package requires an existing Guide 9.1 installation (January 1, 2019
build). Close Guide and the ASCOM diagnostic tool. Back up guide.dat and
any files in your Guide folder that will be replaced. Copy the six program
and configuration files from this ZIP into that folder, alongside guide9.exe.
Launch Guide9-CUDA.exe.

For ASCOM, install the ASCOM Platform and a telescope driver that supports
32-bit clients. In guide.dat, add SCOPE_EPOCH=2000 or update the existing
value. If your existing asc_link.ini specifies CoordinateMode, set it to J2000.
In Guide9-CUDA, open Settings > Scope Control, select ASCOM Scope, and
confirm. Select your driver and configure its connection. Guide9-ASCOM.exe
is an optional diagnostic tool for testing the connection and reading the
telescope position without issuing a slew command. ASCOM was tested with
a simulator.

To accelerate asteroid indexing, enable Use MPCORB in Guide. The bundled
CUDA engine targets NVIDIA GPUs compatible with sm_86 and was tested on a
GeForce RTX 2050. Guide automatically falls back to the CPU if CUDA is
unavailable.

SHA-256 of the original guide9.exe for checking the required build:
32893608e82b014c84f9a3487263ec345f3611b75d5b0f786f7a878fbb047c9d

Ce ZIP complète une installation existante de Guide 9.1 (édition Jan 1 2019).
Fermez Guide et le diagnostic ASCOM. Sauvegardez les fichiers du ZIP déjà
présents dans votre dossier Guide ainsi que guide.dat. Copiez les six fichiers
du ZIP dans ce dossier, à côté de guide9.exe. Lancez Guide9-CUDA.exe.
__________________________________________________________________________________

Pour ASCOM, installez la plateforme ASCOM et le pilote de votre monture,
accessible aux applications 32 bits. Dans guide.dat, ajoutez SCOPE_EPOCH=2000
ou remplacez la valeur existante. Si une ancienne configuration asc_link.ini
contient CoordinateMode, réglez-le sur J2000. Dans Guide9-CUDA, ouvrez
Paramétrages > Contrôle monture, choisissez ASCOM Scope et validez. Sélectionnez
et configurez votre pilote. Guide9-ASCOM.exe sert à tester la connexion et lire
la position sans commande de pointage. ASCOM a été testé avec le simulateur.

Pour accélérer l'index des astéroïdes, activez Utiliser MPCORB dans Guide.
Le moteur embarqué cible les GPU NVIDIA compatibles sm_86 et a été testé sur
RTX 2050. Guide utilise automatiquement le CPU si CUDA est indisponible.

SHA-256 de guide9.exe d'origine pour vérifier l'édition :
32893608e82b014c84f9a3487263ec345f3611b75d5b0f786f7a878fbb047c9d
