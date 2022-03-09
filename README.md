mkdir execicio-02 && cd execicio-02

git init

git config --global user.name "Klinton Sae Hyung Lee"

git config --global user.email "klinton.lee@mercadolivre.com"

touch teste1.txt

echo aleatorio > teste1.txt

git add teste1.txt

git remote add origin git@github.com:MeliKlin/Git-exercicio-02.git

git status

git branch -M main

git commit -m "commit do exercicio 02"
