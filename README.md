# Para subir repositorios a Github desde git 

…or create a new repository on the command line

README siempre se escribe con mayusculas

echo "# 1-Passanger-Counter-App-JS" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/DavidMorenoDev/1-Passanger-Counter-App-JS.git
git push -u origin main


…or push an existing repository from the command line

git remote add origin https://github.com/DavidMorenoDev/1-Passanger-Counter-App-JS.git
git branch -M main
git push -u origin main
