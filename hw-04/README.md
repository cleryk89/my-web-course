налаштовано npm and prettier

налаштовані скріпти prettier
"format": "prettier --write .",
"format:check": "prettier --check ."

запуск

npm run format
npm run format:check

настройка

1. npm init -y
2. npm install --save-dev prettier
3. файл .prettierrc в корені репозиторію:
   {
   "semi": true,
   "singleQuote": true,
   "tabWidth": 2
   }

4. package.json зміни секцію scripts:
   {
   "scripts": {
   "format": "prettier --write .",
   "format:check": "prettier --check ."
   }
   }
