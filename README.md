# code-blocks-config

This repo contains my personal theme's configurations for Code::Blocks IDE and options for adding Allegro 5.2's libraries on it's compiler. It works on variable operational systems.

1) **Backup original "default.conf" file by just renaming it:**

       mv /home/$USER/.config/codeblocks/default.conf /home/$USER/.config/codeblocks/BKP_default.conf

2) **Rename and move .conf file to Code::Blocks IDE config folder:**

* *Replace "<file_name.conf>" with the file's name you've chosen.*

       mv <file_name.conf> /home/$USER/.config/codeblocks/default.conf

#
* Allegro's integration options on these files does not work for flatpak or snap versions of CodeBlocks, I use it only on .deb version.

* Allegro's integration options on these files requires installing Allegro 5.2's libraries in your system. If you haven't done it yet, you should get information about it on Allegro's website: https://liballeg.org/
