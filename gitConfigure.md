git config --global user.email welzyalzy@gmail.com
git config --global init.defaultBranch main
git config --global color.ui auto
git config --global pull.rebase false
ls ~/.ssh/id_ed25519.pub
ssh-keygen -t ed25519 -C welzyalzy@gmail.com
cat ~/.ssh/id_ed25519.pub
ssh -T git@github.com
