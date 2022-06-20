# code-blocks-config
My personal config options for Code::Blocks IDE on variable operational systems.

1) Rename .conf file (replacing <file_name.conf> with the file version you've chosen):

       mv <file_name.conf> default.conf
        
2) Copy and paste "default.conf" file to Code::Blocks IDE config folder:

       cp default.conf /home/$USER/.config/codeblocks/
       
** It must replace the existing "default.conf" existing file.

This file contains theme's configurations for Code::Blocks IDE and options for adding Allegro 5.2's libraries on it's compiler.

** Allegro's integration options on these files does not work for flatpak or snap versions of CodeBlocks, I use it only on .deb version.
