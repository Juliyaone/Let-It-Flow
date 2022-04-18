# Let-It-Flow

<img width="1440" alt="главная страница" src="https://user-images.githubusercontent.com/29165987/163837380-89e21af3-f7df-42fb-a08f-2f9d5ad5675d.png">


После клонирования репозитория откройте два терминала и запустите следующие команды из корня проекта:

В первом терминале:
cd client
npm install
npm start

Во втором:
cd server
npm install
npx sequelize db:create
npx sequelize db:migrate
npx sequelize db:seed:all
npm start
