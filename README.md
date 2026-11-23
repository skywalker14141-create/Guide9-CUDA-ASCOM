# Guide9-CUDA-ASCOM

**[Télécharger le ZIP / Download the ZIP](Guide9-CUDA-ASCOM.zip)**

Français:

Ce pack complète une installation de Guide 9.1 du 1er janvier 2019 sur Windows 64 bits. Les deux éditions accélèrent l’indexation des astéroïdes MPCORB et prennent en charge ASCOM et la passerelle vers l’Assistant de cadrage de N.I.N.A.

Ferme Guide et les outils du pack. Sauvegarde les fichiers à remplacer, puis copie le contenu du ZIP dans le dossier qui contient guide9.exe. Choisis l’exécutable adapté à ton GPU.

Guide9-CUDA.exe pour une carte NVIDIA compatible avec le noyau sm_86.
Guide9-OpenCL.exe pour un GPU qui prend en charge OpenCL 1.2 et la double précision (FP64). Édition vérifiée sur un GPU AMD Radeon intégré (gfx90c) et une NVIDIA RTX 2050.
Active Utiliser MPCORB dans Guide. Si le GPU est indisponible ou que le calcul échoue, Guide calcule l’index sur le processeur. Notice française

Pour importer une cible, lance aussi Guide9-NINA.exe. Dans les options Planétarium de N.I.N.A., choisis Cartes du Ciel, hôte localhost, port 3293. Centre la cible dans Guide puis, dans N.I.N.A. → Cadrage, clique sur l’épingle à droite de Coordonnées.

English (US):

This package requires the January 1, 2019 build of Guide 9.1 and 64-bit Windows. Both editions accelerate MPCORB asteroid indexing and support ASCOM mount control and the N.I.N.A. Framing Assistant bridge.

Close Guide and any package tools. Back up the files you will replace, then extract the ZIP alongside guide9.exe. Choose the executable for your GPU.

Guide9-CUDA.exe for an NVIDIA GPU compatible with the sm_86 kernel.
Guide9-OpenCL.exe for a GPU that supports OpenCL 1.2 and double precision (FP64). Verified on an integrated AMD Radeon GPU (gfx90c) and an NVIDIA RTX 2050.
Enable Use MPCORB in Guide. If the GPU is unavailable or the calculation fails, Guide builds the index on the CPU. English instructions

To import a target, also launch Guide9-NINA.exe. Set the N.I.N.A. planetarium to Cartes du Ciel, host localhost, port 3293. Center the target in Guide, then click the pin next to Coordinates in the N.I.N.A. Framing Assistant.
