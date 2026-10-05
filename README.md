cd enterprise-document-assistant
printf "chroma_db/\ndata/\n__pycache__/\n.env\nmlruns/\nnode_modules/\n*.keras\n" > .gitignore
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/enterprise-document-assistant.git
git push -u origin main
