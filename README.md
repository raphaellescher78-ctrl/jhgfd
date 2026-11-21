# Spatial 3D — plugin AU pour Logic Pro

## Compilation (macOS)
1. Installe Xcode + CMake.
2. `git clone https://github.com/juce-framework/JUCE` dans ce dossier.
3. `cmake -B build -G Xcode && cmake --build build --config Release`
   (le .component est copié dans ~/Library/Audio/Plug-Ins/Components)
4. `auval -v aufx Sp3d Tnom` pour valider, puis relance Logic (Réglages > Plug-ins > Réinitialiser/Analyser).

## Utilisation
Insère « Spatial 3D » en insert sur CHAQUE piste. Chaque instance apparaît comme une sphère
dans la scène 3D visible depuis n'importe quelle instance. Les sphères se déplacent à la souris.
