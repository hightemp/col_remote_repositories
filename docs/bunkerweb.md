# Bunkerweb

Уже защищенный образ nginx в Docker🤔

BunkerWeb — веб-сервер,  основанный на небезызвестном NGINX и ориентированный на безопасность.

 Он интегрируется в существующие среды ( Linux ,  Docker ,  Swarm ,  Kubernetes ,  …),  чтобы сделать ваши веб-сервисы «безопасными по умолчанию» без каких-либо проблем.  

Передовые методы обеспечения безопасности применяются автоматически,  при этом сохраняется контроль над каждым параметром в соответствии с вашим вариантом использования.

 BunkerWeb содержит основные функции безопасности как часть ядра,  но может быть легко расширен дополнительными благодаря системе плагинов.

 ▫️Поддержка HTTPS с прозрачной автоматизацией Let's Encrypt
▫️Современная веб-безопасность:  заголовки безопасности HTTP,  предотвращение утечек,  усиление защиты TLS и многое другое
▫️Интегрированный ModSecurity WAF с набором основных правил OWASP
▫️Автоматический запрет странного поведения с помощью fail2ban
▫️Вызов Antibot с помощью файлов cookie,  javascript,  captcha или recaptcha v3
▫️Возможность блокировать TOR,  прокси,  плохие пользовательские агенты,  страны и многое другое
▫️Блокируйте известный плохой IP-адрес с помощью DNSBL и CrowdSec
▫️Предотвращение атак грубой силы с ограничением скорости
▫️Обнаружение плохих файлов с помощью ClamAV
▫️Легко настроить с помощью переменных среды
▫️Обман автоматических инструментов/сканеров
и многое другое...