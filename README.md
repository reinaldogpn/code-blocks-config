# code-blocks-config
My personal config options for CodeBlocks on variable operational systems.

1) Rename .conf file as:

       default.conf
        
2) Copy and paste "default.conf" file to CodeBlocks config folder:

       cp default.conf /home/$USER/.config/codeblocks/
       
** It must replace the existing "default.conf" existing file.

This file contains theme's configurations for CodeBlocks and options for adding Allegro 5.2's libraries in it's compiler.

** Allegro's integration options on these files does not work for flatpak or snap versions of CodeBlocks, I use it only on .deb version.
