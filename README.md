# 
Здравствуйте! В данном репозитории собраны все файлы для запуска кластера указанного в ТЗ, а также ansible-roles для автоматизации запуска.
Буду честен, многие вещи делал впервые, но было интересно, спасибо за такой опыт! Буду рад выйти на связь и прояснить непонятные вам моменты, а также услышать критику. 
В целом всё работает, кроме ingress. Он рабочий, но так и не получилось сделать редирект на 443 порт (сертификаты самоподписанные бьыли выпущены и создан secret).
Также не получилось решить проблему с nfs. Предполагаю, что из-за монтирования одной и той же директории на одну из реплик, не может создаться другая реплика.


Касаемо всех манифестов. Вырезал из них все использованные мною ip-адреса и доменные имена, чтобы можно было подставить любые другие
