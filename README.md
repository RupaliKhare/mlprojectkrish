#END to END  https://www.youtube.com/watch?v=Rv6UFGNmNZg&list=PLZoTAELRMXVPS-dOaVbAux22vzqdgoGhG&index=2
#conda environment
conda create -p venv python==3.8 -y
conda activate D:\mlproject\venv

Git cmd
echo "# mlproject-krishnaik" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/RupaliKhare/mlproject-krishnaik.git
git push -u origin main

#create .gitignore file in repository by choosing python as language

git pull #in terminal