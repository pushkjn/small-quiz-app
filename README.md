# small-quiz-app

Улучшенная версия приложения, созданного мной для вузовской конференции. </br>
Приложение предназначено для проведения тестирований на различные темы. </br>
Можно добавлять свои темы квизов и вопросы к ним, для этого в файле
src/db.json в массиве themes нужно создать тему с уникальным значением поля id, а в массиве questions создать вопросы к теме, также с уникальными значениями id 
и в поле qIds объекта темы прописать id вопросов </br>
Запуск приложения - yarn start, предварительно нужно запустить сервер: yarn start:api
