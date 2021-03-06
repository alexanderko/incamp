# Стек сетевых протоколов

![&#x421;&#x442;&#x435;&#x43A; &#x43C;&#x435;&#x440;&#x435;&#x436;&#x435;&#x432;&#x438;&#x445; &#x43F;&#x440;&#x43E;&#x442;&#x43E;&#x43A;&#x43E;&#x43B;&#x456;&#x432;](../../.gitbook/assets/image%20%281%29.png)

## Слои стека протоколов \(современный/упрощенный вариант\)

### Network Interface Layer

Отвечает за передачу данных в физическом пространстве в рамках одной сети. Включает разные протоколы преобразование физических сигналов в последовательность битов. Также определяет адресация в сети. Самые распространенные протоколы: Ethernet, WiFi, 4G. 

### Network Layer

Отвечает за межсетевую адресацию узлов и в глобальной сети Интернет. Ключевые протоколы Internet Protocal \(IP\), Address Resolution Protocol \(ARP\). 

### Transport Layer

Отвечает за указание программы получателя данных \(порт\). В случае с Transmission Control Protocol \(TCP\) открывает канал связи между приложениями, а также контролирует и гарантирует доставку данных. User Datagram Protocol \(UDP\) дает возможность отправлять данные с меньшими задержками \(чем TCP\), но при этом не гарантирует их доставку. 

### Application Layer

Протокол уровня приложений. Взаимодействие приложение с сервером происходит на этом уровне. Работа браузера \(HTTP\), почтовых клиентов \(SMPT\), потокового видео \(RTMP, WebRTC\), веб серверов происходит на этом уровне. 

## Структура пакетов и взаимодействия 

{% embed url="https://docs.google.com/presentation/d/1ElIhd\_IWJhQwPI1i8MHQ1RRUeqwUc7lhGiuUtSHXA\_E/edit?usp=sharing" %}

