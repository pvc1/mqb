disqus: https-mqb-readthedocs-io
# Принципы кодирования битов

Нумерация байтов и битов всегда начинается с 0.

В битах можно вручную проставлять "1" для включения определенного бита в двоичном коде. 
Порядок в битах идет с конца, например,  
00000001 - включенный бит "0"  
00000010 - включенный бит "1"  

### Программа LCode

Для быстрого редактирования битов существует программа LCode

<button class="pure-material-button-contained" type="button" id="generate" onclick="window.location.href = '../LCode.exe';">Скачать</button>

В неё можно внести 16-ричную hex кодировку определенного блока. Программа сама разобъет кодировку на байты, и в нужном байте уже включить нужный бит.

![Screenshot](./images/lcode.png) 






