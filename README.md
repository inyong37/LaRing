# LaRing
Smart Buoyant Band

2017 Spring to Winter

# Bluetooth
## Noraml HM-10
"line encoding 없음" 또는 "Both NL & CL"

Baudrate = "9600"
## Yellow sticker HM-10
"line encoding 없음"

Baudrate = "115200"
## AT Command

AT+를 입력하고 COMMAND를 입력하고 ?를 붙이면 세팅된 정보를 가져오고 PARAMETER를 입력하면 원하는 값으로 세팅한다.

ex)AT+NAME? -> 세팅된 NAME을 보여줌

ex)AT+NAMEB01 -> NAME을 B01로 


NAME 설정: AT+NAME

UUID 설정: AT+UUID

ex) AT+UUID0x0001

MAJOR 설정: AT+MARJ

ex) AT+MARJ0x0001

MINOR 설정: AT+MINO

ex) AT+MINO0x0001


iBeacon 설정: AT+IBEA 0이면 disable 1이면 enabled

advertisement 주기 설정: AT+ADVI5 5이면 0.5초 간격

AT+DELO2 : broadcast only

AT+RESET

AT+PWRM0 하면 auto sleep 이고 wake 시킬려면 80자 이상을 보내면 된다.

