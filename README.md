# Let-It-Flow

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
