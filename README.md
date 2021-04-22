# Микрофронтенды #
Распространение идеи микросервисов на фронтенд-разработку.
перевод [статьи Майкла Гирса](https://micro-frontends.org/)

Техники, стратегии и решения для разработки современных веб-приложений с участием нескольких команд, способных реализовывать фичи независимо друг от друга.

## Что такое микрофронтенды? ##
Термин микрофронтенды (Micro Frontends) впервые появился в конце 2016 года, на [радаре технологий ThoughtWorks](https://www.thoughtworks.com/radar/techniques/micro-frontends). Он расширял концепцию микросервисов на мир фронтенда. Сейчас уже популярен тренд, при котором single-page приложения взаимодействуют с бэком, построенном на принципах микросервисной архитектуры. При этом сам клиентский код, часто разрабатываемый отдельной командой, со временем всё больше разрастается и его становится трудно поддерживать. Именно его мы называем [монолитом фронтенда](https://www.youtube.com/watch?v=pU1gXA0rfwc&ab_channel=microXchg).

Идея микрофронтендов заключается в восприятии сайта или веб-приложения как композиции фичей, которые разрабатывают отдельные команды. Каждая команда имеет четко определенную зону ответственности в функционале приложения и специализируется на ней. При этом сами команды универсальны, работают full-stack и реализуют свои фичи end-to-end, от базы данных до пользовательского интерфейса.

Впрочем, эта идея не нова. Они имеет много общего с концепцией [автономных систем](https://scs-architecture.org/)(Self-contained Systems). Раньше аналогичный подход уже появлялся под названием [“клиентская интеграция для вертикализированных систем”](https://www.otto.de/jobs/technology/techblog/artikel/scaling-with-microservices-and-vertical-decomposition_2014-07-29.php) (Frontend Integration for Verticalised Systems). Однако термин микрофронтенды менее громоздкий и гораздо дружелюбней.
