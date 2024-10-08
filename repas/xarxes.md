# Repàs de xarxes

## Tipus de xarxes:

![image](https://github.com/user-attachments/assets/16f3b886-4a49-4fe8-b8f9-7c42e205e08c)

![image](https://github.com/user-attachments/assets/753709ea-5f41-4f5d-ae8d-5e21cf599f7f)

# Exercicis

1. Què és una adreça IP?
    IPv4 - És un conjunt de números format per quatre octets de números binaris, que identifiquen      de forma ÚNICA un dispositiu connectat a una xarxa.
2. Per a què serveixen les adreces IP dins d'una xarxa?
    Per indicar que estan dins d'una xarxa determinada, i per enviar i rebre informació del     
    dispositiu concret que es vol.
3. Tens la xarxa 192.168.180.0 amb una màscara de subxarxa de 255.255.255.0.
  - Quantes adreces IP pots tenir en aquesta xarxa? 254
  - Quin serà el rang d'IP usables? 192.168.180.1 a 192.168.180.254
  - Quina és la IP de broadcast? 192.168.180.255
  - Quina és la adreça de xarxa? 192.168.180.0
4. Tens una xarxa domèstica amb l'adreça IP 192.168.1.25 assignada al teu ordinador, i la teva màscara de subxarxa és 255.255.255.0. Els teus amics es connecten a la mateixa xarxa, però tenen problemes per accedir a Internet. Després d'examinar-ho, t'adones que tenen adreces IP com 169.254.x.x.
- Què indica una adreça IP com 169.254.x.x? Que el servidor DHCP no funciona correctament.
- Com es pot solucionar aquest problema? Mirar si el servidor DHCP està ben configurat, mirar si el switch està mal configurat.
5. Quina és la funció de cada dispositiu a una xarxa:
  - Router: Connecta diferents xarxes entre sí.
  - Switch: Connectar dispositius a UNA xarxa.
  - Servidor DHCP: Dona la informació de connexió als equips, IP, màscara de xarxa, DNS...
  - Firewall: Sistema de defensa contra intrusions de tercers a una xarxa.
6. Identifica quines de les següents adreces IP són privades i quines són públiques:
  - 172.16.0.10 (Privada)
  - 8.8.8.8 (Pública)
  - 192.168.1.50 (Privada)
  - 203.0.113.10 (Pública)
7. Identifica si les següents adreces IP són de classe A, B o C:
  - 192.168.0.1 C
  - 10.0.0.1 A
  - 172.16.5.4 B
  - 203.0.113.5 C
8. Dividir una xarxa classe C en 4 subxarxes
  - Tens la xarxa 192.168.1.0/24.
  - Divideix-la en 4 subxarxes i determina les adreces IP disponibles per a cada subxarxa, incloent la IP de xarxa, la primera i última adreça usable, i la IP de broadcast.
