# PSOS (process status over snmp) - Статус процесса через snmp запрос

Данный скрипт выводит объем оперативной памяти потребляемый определенным процессом.

## Использование

## Настройка

Для ОС Linux необходимо в конфигурационный файл **/etc/snmp/snmpd.conf** добавить следующую строчку:

```
view   systemonly  included   .1.3.6.1.2.1.25.4
view   systemonly  included   .1.3.6.1.2.1.25.5
```
