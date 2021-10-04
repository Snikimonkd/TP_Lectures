# Лекции 3 семестра [Технопарка mail.ru](https://park.mail.ru/feed/) осень 2021 года

## HighLoad

### Лекция №1

Запись:

[Видео](https://cloud.mail.ru/public/ieQu/9sGzpUpBX)

[Слайды, PDF](https://cloud.mail.ru/public/pQrk/vhXqDnZrY)

[Слайды, PPTX](https://cloud.mail.ru/public/HJBy/mk4zu4xCs)

Литература:

 - [Site Reliability Engineering (ISBN: 978-1-4919-2912-4)](https://cloud.mail.ru/public/LpRS/2wsG3XPpZ) 
[(русский перевод)](https://cloud.mail.ru/public/5mh8/5DMudM3jT)

 - [The Site Reliability Workbook: Practical Ways to Implement SRE (ISBN: 978-1-492-02945-8)](https://cloud.mail.ru/public/JaZR/J4iA6Cv3d)

 - [The Art of Capacity Planning (ISBN: 978-0-596-51857-8)](https://cloud.mail.ru/public/6c57b78b5c36/The-Art-of-Capacity-Planning.pdf)

### Лекция №2

Запись:

[Видео](https://cloud.mail.ru/public/a7sH/beHQgQraL)

[Слайды, PDF](https://cloud.mail.ru/public/8Mau/tKmAN3kqb)

[Слайды, PPTX](https://cloud.mail.ru/public/wuEW/emkYAHoKT)

Литература:

 - [Netflix CDN (отдача 40 Gbps с сервера)](https://events.yandex.ru/lib/talks/2396/) (video, 46 min, Yac/2014)

 - [Serving 100 Gbps from an Open Connect Appliance](https://medium.com/netflix-techblog/serving-100-gbps-from-an-open-connect-appliance-cdb51dda3b99)

 - [How to receive a million packets per second](https://blog.cloudflare.com/how-to-receive-a-million-packets/)

 - [Тюним память и сетевой стек в Linux (Одноклассники)](https://habrahabr.ru/company/odnoklassniki/blog/266005/)

 - [Making Linux TCP Fast](https://netdevconf.org/1.2/papers/bbr-netdev-1.2.new.new.pdf) (Google's [BBR](https://twitter.com/igrigorik/status/777559295315501057) and [RACK](https://tools.ietf.org/html/draft-ietf-tcpm-rack-02))

 - [Статистика по использованию](https://www.google.com/intl/en/ipv6/statistics.html) IPv6 от Google

 - [Scaling memcached at Facebook](https://code.facebook.com/posts/148355178704920/scaling-memcached-at-facebook/) (with UDP)

 - [www.internetexchangemap.com](http://www.internetexchangemap.com/) — точки обмена трафиком]

 - [www.submarinecablemap.com](https://www.submarinecablemap.com/) — карта подводных кабелей]

 - [global-internet-map-2018.telegeography.com](https://global-internet-map-2018.telegeography.com/) — карта интернета

 - [arstechnica.com/security/2014/11/wtf-russias-domestic-internet-traffic-mysteriously-passes-through-china/](http://arstechnica.com/security/2014/11/wtf-russias-domestic-internet-traffic-mysteriously-passes-through-china/)

 - [https://blog.cloudflare.com/how-verizon-and-a-bgp-optimizer-knocked-large-parts-of-the-internet-offline-today/](https://blog.cloudflare.com/how-verizon-and-a-bgp-optimizer-knocked-large-parts-of-the-internet-offline-today/) - поломка интернета через аноск кривых маршрутов BGP

 - [https://www.netscout.com/blog/asert/netscout-arbor-confirms-17-tbps-ddos-attack-terabit-attack-era](https://www.netscout.com/blog/asert/netscout-arbor-confirms-17-tbps-ddos-attack-terabit-attack-era) - 1,7 Tbit/s DDoS attack

 - [http://bgp.he.net/](http://bgp.he.net/) - просмотр peering стыков между AS

 - [https://stat.lookinglass.org/](https://stat.lookinglass.org/) - график количества маршрутов IPv4/IPv6 и количества AS  

 - [Curose-Ross - Computer Networking](https://cloud.mail.ru/public/ETzs/dHNbgbkYs) - хорошая книга по устройству сетей (PDF)

### Лекция №3

Запись:

[Видео](https://cloud.mail.ru/public/Cvcq/ykmSeN5aS)

[Слайды, PDF](https://cloud.mail.ru/public/bMaH/B4LLiL7Fh)

[Слайды, PPTX](https://cloud.mail.ru/public/FmnV/RYdG6y5ap)

Материалы к лекции:

 - [Curose-Ross - Computer Networking](https://cloud.mail.ru/public/ETzs/dHNbgbkYs) - раздел 2.5, DNS

 - [Google Public DNS](https://developers.google.com/speed/public-dns/docs/intro)

 - [Client Subnet in DNS Queries (IETF Draft)](https://tools.ietf.org/html/draft-ietf-dnsop-edns-client-subnet-04) ([анонс в блоге Google](http://googlecode.blogspot.ru/2010/01/proposal-to-extend-dns-protocol.html))

 - [Geo Based DNS](https://en.wikipedia.org/wiki/Geodns) (пример самостятельной реализации)

 - [Latency Based DNS](https://aws.amazon.com/blogs/aws/latency-based-multi-region-routing-now-available-for-aws/) (AWS)

 - [CloudFlare: A Brief Primer on Anycast](https://blog.cloudflare.com/a-brief-anycast-primer/)

 - [LinkedIn: Geo-Based DNS vs TCP Anycast](https://engineering.linkedin.com/network-performance/tcp-over-ip-anycast-pipe-dream-or-reality) ([доклад на Velocity 2015](http://conferences.oreilly.com/velocity/devops-web-performance-2015/public/schedule/detail/42026), [слайды](http://www.slideshare.net/rmaheshw/velocity-2015-pops-and-rum))

 - [Пример использования Anycast в CDN Яндекса](http://habrahabr.ru/company/yandex/blog/176893/)

 - [Heroku: пример сервиса где надо использовать Least-connection балансировку](http://genius.com/James-somers-herokus-ugly-secret-annotated)

 - [Google Maglev, программный высокопроизводительный L4 балансировщик](https://research.google.com/pubs/pub44824.html)

 - [Сбор фактической статистики по использованию ssl session tickets через tcpdump](http://vincent.bernat.im/en/blog/2011-ssl-session-reuse-rfc5077.html)

 - [Badoo: автоматический подбор весов в балансировщике](https://habr.com/company/oleg-bunin/blog/310366/)

 ### Лекция №4

Запись:

[Видео](https://cloud.mail.ru/public/8Ck4/S79Fcm8mw)

[Слайды, PDF](https://cloud.mail.ru/public/pF76/yAuuaRA4r)

[Слайды, PPTX](https://cloud.mail.ru/public/hFXo/DCPTJxmrx)

Литература:

 - [What Every Programmer Should Know About Memory](http://people.redhat.com/drepper/cpumemory.pdf)

 - [SMART планировщик от Яндекс](https://events.yandex.ru/lib/talks/2396/)

 - [What's New in CPUs Since the 80s and How Does It Affect Programmers?](http://danluu.com/new-cpu-features/)

 - [Пример проблемы с распределением памяти в NUMA-подсистеме (Одноклассники)](https://habrahabr.ru/company/odnoklassniki/blog/266005/)

 - [Optimizing web servers for high throughput and low latency](https://blogs.dropbox.com/tech/2017/09/optimizing-web-servers-for-high-throughput-and-low-latency/) ([плохой перевод от Badoo](https://habrahabr.ru/company/badoo/blog/338226/))

 - [Статистика Backblaze, научный подход к анализу надёжности накопителей](https://habrahabr.ru/post/348754/)

 - [Linux Page Cache Basics](https://www.thomas-krenn.com/en/wiki/Linux_Page_Cache_Basics)

## Безопасность интернет-приложений

### Лекция №1

Запись:

[Видео](https://mailru.zoom.us/rec/share/EMdJuWDwmQeqC3HaJz8CjNyvHtx-oUOt6x_pIONaopieZXGrzQIktYSdln-q-8Op.pXzQC276abBhArBP?startTime=1631027123000)

[Слайды](https://docs.google.com/presentation/d/1HCbLcJnQlPDQ6ql4O0IS23du8KaBdHLuSGJ320ht33o/edit?usp=sharing)

Домашнее задание:
1. Зарегистрироваться в Portswigger web security academy https://portswigger.net/web-security 
2. Пройти лабы по темам:
     - command injection
     - sql injection
     - xxe

### Лекция №2

Запись:

[Видео](https://mailru.zoom.us/rec/share/kpW4mj54A5u5TTViE_u0RabWqsNA0kBr4jLqCd8lNDCeR88zVQQeZVrbsRNIRBo.3yTIl0jCyd-pf4oW?startTime=1631631916000)

[Слайды](https://docs.google.com/presentation/d/1WExqWrXz2DuVTmaHeQuIhoQXl80dl8khdZV27RsHnDY/edit?usp=sharing)

### Лекция №3

Запись:

[Видео](https://mailru.zoom.us/rec/share/XSc3M-FRRXru3IwwJySnOWbqlpthMEcjg6SXDmlTD9kYtKDh5NC-hO0qc-HQ7J36.-D29DIGXzpleirIf)

[Слайды](https://docs.google.com/presentation/d/1BcH3qAOdIpUgDv6OT3RITNVA2cJtfe9AxI9SbFlFrUc/edit?usp=sharing)

Для успешного решения контрольной работы на следующем занятии рекомендую научиться решать задания https://portswigger.net/web-security/all-labs из разделов 
 - SQL injection
 - Command injection
 - XSS
 - XXE
 - SSRF

Так же напоминаю, что до 5 октября жду от вас решения домашнего задания
https://docs.google.com/document/d/1QaQ-Nc_eE4dBKZwQbA4E2o8pOJ3CktgsKDAn375iY24/edit#

