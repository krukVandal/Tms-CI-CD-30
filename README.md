# Написать пайплайн для сборки и деплоя приложения https://github.com/AnastasiyaGapochkina01/cyberpunk-devops. Требования к пайплайну имеется этап линтера для кода (можно использовать pylint и выставить allow_failure: true) имеется этап сканирования кода на уязвимости (использовать библиотеку bandit https://github.com/pycqa/bandit ; allow_failure: true тоже разрешен) пуш собранного docker image осуществляется в container registry gitlab деплой запускается ТОЛЬКО в ручном режиме

1. Джоба Deploy, запущенный контейнер
<img width="1817" height="967" alt="image" src="https://github.com/user-attachments/assets/af55914f-58b0-4df3-abb1-1578bbd73cae" />
2. Пайплайн
<img width="1877" height="1037" alt="image" src="https://github.com/user-attachments/assets/14ffe93e-12ae-457e-aff0-5acfeffa038e" />
3. Curl localhost:8001
<img width="1299" height="656" alt="image" src="https://github.com/user-attachments/assets/aa0d3458-9235-46aa-8738-2c05e01451fc" />
4. Ссылка на репозиторий --- https://gitlab.com/tms-homework/less-30

