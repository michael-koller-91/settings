# How I installed it

## Install Emacs
```bash
# clone the Emacs repo
# cd into the repo
# checkout an emacs version
git checkout emacs-29.1
./autogen.sh
./configure --with-pgtk
make
make check
make bootstrap
make check
sudo make install
```

## Install Spacemacs
```bash
# get the command from https://www.spacemacs.org
# something like
git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d
# checkout the develop branch of spacemacs
cd ~/.emacs.d
git checkout develop
```

# How to uninstall it

```bash
# uninstall Emacs
# cd into the Eamcs repo
sudo make uninstall
make clean
make distclean

# remove the Spacemacs stuff
rm ~/.spacemacs*
rm .rf ~/.emacs.d
```
