1°) Mupen64plus-core : LE COEUR DU PROGRAMME
--------------------------------------------

Dézipper l'archive puis les commandes suivantes :

cd mupen64plus-core-master/projects/unix
make all
sudo make install


2°) Mupen64plus-ui-console : POUR LANCER L'INTERFACE
----------------------------------------------------

Dézipper l'archive puis les commandes suivantes :

cd mupen64plus-ui-console-master/projects/unix
make all
sudo make install


3°) Mupen64plus-audio-sdl : POUR LE SON
---------------------------------------

Dézipper l'archive puis les commandes suivantes :

cd mupen64plus-audio-sdl-master/projects/unix
make all
sudo make install


4°) Mupen64plus-input-sdl : POUR LES MANETTES
---------------------------------------------

Dézipper l'archive puis les commandes suivantes :

cd mupen64plus-input-sdl-master/projects/unix
make all
sudo make install


5°) Mupen64plus-rsp-hle : PLUGIN RSP
------------------------------------

Dézipper l'archive puis les commandes suivantes :

cd mupen64plus-rsp-hle-master/projects/unix
make all
sudo make install


6°) Mupen64plus-video-rice : LE PLUGIN VIDEO CLASSIQUE
------------------------------------------------------

Dézipper l'archive puis les commandes suivantes :

cd mupen64plus-video-rice-master/projects/unix
make all
sudo make install


7°) GLideN64 : LE PLUGIN VIDEO AVANCE DE gonetz
-----------------------------------------------

Dézipper l'archive puis les commandes suivantes :

cd GLideN64-master/projects/cmake
cmake -DMUPENPLUSAPI=On ../../src
../../src/getRevision.sh
make
sudo cp -R ./plugin/release/mupen64plus-video-GLideN64.so /usr/local/lib/mupen64plus/mupen64plus-video-GLideN64.so
sudo cp -R ../../ini/GLideN64.custom.ini /usr/local/share/mupen64plus/GLideN64.custom.ini
sudo cp -R ../../ini/GLideN64.ini /usr/local/share/mupen64plus/GLideN64.ini


Exemple ligne de commande en mode fenetre avec GLideN64 :

MESA_GL_VERSION_OVERRIDE=3.3COMPAT /usr/local/bin/mupen64plus --gfx /usr/local/lib/mupen64plus/mupen64plus-video-GLideN64.so --rsp /usr/local/lib/mupen64plus/mupen64plus-rsp-hle.so --audio /usr/local/lib/mupen64plus/mupen64plus-audio-sdl.so --input /usr/local/lib/mupen64plus/mupen64plus-input-sdl.so --datadir /usr/local/share/mupen64plus --corelib /usr/local/lib/libmupen64plus.so.2.0.0 --windowed /var/www/html/data/N64/Mario_Tennis.n64




