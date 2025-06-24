🌐 Redes IP – IPv4 e IPv6

📌 Introdução

IPv4 👉 Usa números decimais e tem 32 bits

IPv6 👉 Usa números hexadecimais e tem 128 bits

Neste material, vamos focar apenas no IPv4, que é o padrão utilizado no NetPractice.

🧠 Como o computador entende um endereço IPv4?

Exemplo: 192.168.0.1

Um endereço IPv4 é formado por 4 blocos de 8 bits chamados octetos:


192 → 8 bits (1 octeto)
168 → 8 bits (1 octeto)
  0 → 8 bits (1 octeto)
  1 → 8 bits (1 octeto)
🔢 Total: 32 bits = 4 octetos


192.168.0.1 → 11000000.10101000.00000000.00000001


🏷️ Classes de Rede IPv4
Classe	Intervalo do 1º Octeto	Uso
A	0 a 127	Grandes redes 🏢 (provedores)
B	128 a 191	Redes médias 🏫
C	192 a 223	Pequenas redes 🏠 (residências/escritórios)
D	224 a 239	Multicast 📡
E	240 a 255	Reservada para testes 🧪

📡 Tipos de Comunicação IP



Unicast 🧍
Envio de dados para um único destino

Multicast 👥
Envio para vários computadores ao mesmo tempo, mas não todos

Broadcast 📢
Envio para todos os dispositivos da mesma rede

Anycast 📍
A mensagem é entregue para o destino mais próximo, em termos de rota

🔐 IPs Privados (RFC 1918) – usados em redes internas

`10.0.0.0/8      
172.16.0.0/12   
192.168.0.0/16`
Esses IPs não são roteáveis na internet pública, ou seja, servem para redes locais como Wi-Fi doméstico, LANs e redes escolares.

🚫 IPs Reservados
IP	Uso
`127.0.0.0/8`	Localhost (loopback) 🔁
`169.254.0.0/16`	APIPA – IP automático quando não há DHCP ⚠️
`0.0.0.0`	IP de inicialização 🛠️
`255.255.255.255`	Broadcast geral 🌎
