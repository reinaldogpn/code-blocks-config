# code-blocks-config
My personal config options for Code::Blocks IDE on variable operational systems.

1) (Optional) Backup original "default.conf" file by just renaming it:

       mv /home/$USER/.config/codeblocks/default.conf /home/$USER/.config/codeblocks/'(bkp)default.conf'

2) Rename .conf file (replace "<file_name.conf>" with the file's name you've chosen):

       mv <file_name.conf> default.conf
        
3) Copy and paste "default.conf" file to Code::Blocks IDE config folder:

       cp default.conf /home/$USER/.config/codeblocks/
       
* It must replace the "default.conf" original file.

* This file contains theme's configurations for Code::Blocks IDE and options for adding Allegro 5.2's libraries on it's compiler.

** Allegro's integration options on these files does not work for flatpak or snap versions of CodeBlocks, I use it only on .deb version.
