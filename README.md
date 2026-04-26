
BACKEND SETUP

cd backend
npm install
npm run dev


FRONTEND SETUP

cd ../frontend
npm install
npm run dev


GIT SETUP + PUSH

cd ..
git init
git add .
git commit -m "lab test complete"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main

git pull origin main --rebase
git push origin main
