### 8.3 описание Playbook YandexCloud


#### Install Elasticsearch
На сервере «el-instance»

*  Загрузка rpm-пакета для установки elasticserch версии 7.14.1
* Установка rpm пакета с помощью yum
* Настройка elasticserch: копируем конфиг в «/etc/elasticsearch/» 
* перезапускаем сервис  elasticserch


#### Install Kibana
На сервере «k-instance»

* Загрузка rpm-пакета для установки kibana версии 7.14.1
* Установка rpm пакета с помощью yum
* Настройка kibana копируем конфиг в «/etc/kibana/»
* Перезапускаем сервис kibana


#### Install Filebeat
На сервере «application-instance»

* Загрузка rpm-пакета для установки filebeat версии 7.14.1
* Установка rpm пакета с помощью yum
* Настройка kibana копируем конфиг в «/etc/filebeat/»
* Перезапускаем сервис filebeat
* Включаем модуль system
* Загружаем данные dashboard для kibana
* Перезапускаем сервис filebeat

