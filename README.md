 clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
npm install
npx cap add android
npx cap add ios  # if you want iOS too
npm run build
npx cap sync
