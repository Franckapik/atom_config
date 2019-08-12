# atom_config
Ma configuration du logiciel IDE Atom

# Mettre a jour les deux fichiers de configuration
Git add config.cson package.list

#To track installed packages as well, you will need to run:

apm list --installed --bare > ~/.atom/package.list

#And add that file to Git also. To restore, use:

apm install --packages-file ~/.atom/package.list

