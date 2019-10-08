echo "# deb-maker" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/baibc/deb-maker.git
git push -u origin master


dpkg-deb -b xxx xxx.deb
dpkg -i xxx.deb
