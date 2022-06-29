# Crear proyecto
npx create-react-app <name>

# Lanzar servidor
npm start

# Instalar bootstrap
npm i bootstrap@5.2.0-beta1

# Exportar para deploy
npm run build

# Añadimos a package,json
"homepage": "https://myusername.github.io/my-app",

# Instalar paquete para deploy en git-hup pages
npm install --save gh-pages

# Añadimos lo siguiente al archivo package.json
"scripts": {
+   "predeploy": "npm run build",
+   "deploy": "gh-pages -d build",

# Deploy
npm run deploy