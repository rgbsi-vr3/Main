mkdir ~/bin
curl https://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
chmod a+x ~/bin/repo

export PATH=~/bin:$PATH

mkdir RITS_V1.1
cd RITS_V1.1
repo init -u https://github.com/vigneshrgbsi/Main.git -b main
repo sync
