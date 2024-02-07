# How I installed it

## Install Emacs
```bash
# clone the Emacs repo
# cd into the repo
./autogen.sh
./configure --with=pgtk
make -j16
make check
sudo make install
```

## Install Spacemacs
```bash
# get the command from https://www.spacemacs.org
# something like
git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d
```

# How to uninstall it

```bash
# remove the Spacemacs stuff
rm ~/.spacemacs*

# uninstall Emacs
# cd into the Eamcs repo
sudo make uninstall
make clean
make distclean
```
