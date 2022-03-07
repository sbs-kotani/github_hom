git clone https://github.com/各自のgithub名/blogprj.git
  VS codeでソース修正                            
  
cd blogprj                            

git init                            
git add  .                            
git status                            
git commit -m "2022.3.7"                            

git remote rm origin
git remote add origin https://各自のgithub名@github.com/各自のgithub名/blogprj.git
git push origin main


ユーザ名、emailアドレスが必要な場合には、登録時の物を使用して下さい。                            
git config --global user.name "各自の名前"                            
git config --global user.email "sbsN@kkotani.net"   
　　注）sbsN　：　各自の番号
　　

