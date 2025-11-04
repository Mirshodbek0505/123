# 0) (ixtiyoriy) Loyihaga kir
cd "C:\path\to\your\project"   # Windows
# yoki Linux/Mac:
# cd /path/to/your/project

# 1) Git init
git init

# 2) .gitignore (Python loyihasi bo‘lsa) va README yarating
echo "__pycache__/
*.pyc
.env
venv/
.env.*
" > .gitignore

echo "# My Project" > README.md

# 3) Birinchi commit
git add .
git commit -m "Initial commit"

# 4) GitHub’da bo‘sh repo yarating va URL ni shu yerga qo‘ying:
git remote add origin https://github.com/USERNAME/REPO.git

# 5) Asosiy branch nomini 'main' qilib push qiling
git branch -M main
git push -u origin main
# 123
