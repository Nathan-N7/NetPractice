🌐 Redes IP – IPv4 e IPv6

📌 Introdução
IPv4: usa números decimais e tem 32 bits

IPv6: usa números hexadecimais e tem 128 bits

Neste material vamos focar apenas no IPv4, como utilizado no Netpractice.

🧠 Como o computador interpreta um endereço IPv4?
Exemplo: 192.168.0.1

Um endereço IPv4 é dividido em 4 partes, chamadas de octetos, cada uma com 8 bits:

scss
Copiar
Editar
192 → 8 bits (1 octeto)  
168 → 8 bits (1 octeto)  
  0 → 8 bits (1 octeto)  
  1 → 8 bits (1 octeto)
🔢 Total: 32 bits = 4 octetos

🏷️ Classes de Rede IPv4
Classe	Intervalo do 1º Octeto	Uso
Classe A	0 a 127	Grandes redes (ex: provedores)
Classe B	128 a 191	Redes de tamanho médio
Classe C	192 a 223	Pequenas redes (residencial, escritórios)
Classe D	224 a 239	📡 Multicast
Classe E	240 a 255	🧪 Reservada para testes e futuras tecnologias

📡 Tipos de Comunicação IP
Unicast 🧍: Comunicação entre um emissor e um receptor específico

Multicast 👥: Envio de dados para vários computadores ao mesmo tempo, mas não todos

Broadcast 📢: Envio para todos os dispositivos da mesma rede

Anycast 📍: A mensagem é entregue para o destinatário mais próximo (em termos de rota)
