Perso=`whoami`

cd /sgoinfre/goinfre/Perso
mkdir VOTRE_LOGIN
chmod 700 VOTRE_LOGIN
cd $Perso
curl -o anaconda3.sh https://repo.continuum.io/archive/Anaconda3-5.0.1-MacOSX-x86_64.sh
sh anaconda3.sh
echo export PATH="/sgoinfre/goinfre/Perso/$Perso/anaconda3/bin:$PATH" >> ~/.zshrc
source ~/.zshrc
echo devrait afficher
echo /sgoinfre/goinfre/Perso/$Perso/anaconda3/bin/python
which python
