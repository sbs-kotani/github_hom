git clone https://github.com/sbs-kotani/blogprj.git
  VS codeでソース修正
  
cd blogprj

git init
git add .
git status
git commit -m "2022.3.7"

git remote rm origin
git remote add origin https://sbs-kotani@github.com/sbs-kotani/blogprj.git
git push origin main


ユーザ名、emailアドレスが必要な場合には、登録時の物を使用して下さい。
git config --global user.name "kotani kazumi"
git config --global user.email "sbs@kkotani.net"

