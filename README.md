💡 Sistema de Controle de LEDs com Botões utilizando MicroPython
Descrição

Este projeto foi desenvolvido em MicroPython para controlar LEDs através de botões conectados a uma placa microcontroladora. O sistema monitora continuamente o estado dos botões e, quando um deles é pressionado, executa uma sequência de acionamento dos LEDs com diferentes intervalos de tempo.

O objetivo é demonstrar o funcionamento de entradas e saídas digitais, além da interação entre componentes eletrônicos utilizando programação embarcada.

Funcionalidades
Leitura do estado dos botões em tempo real;
Controle de múltiplos LEDs;
Acionamento sequencial dos LEDs;
Utilização de temporização com diferentes intervalos;
Aplicação de resistores internos Pull-Up;
Execução contínua através de laço infinito.
Tecnologias Utilizadas
MicroPython
ESP32 / Microcontrolador compatível
LEDs
Botões (Push Buttons)
Protoboard e Jumpers
Objetivo do Projeto

O principal objetivo deste projeto é praticar conceitos de eletrônica básica e sistemas embarcados, utilizando MicroPython para controlar dispositivos físicos através das portas GPIO do microcontrolador.

Além disso, o projeto permite compreender a comunicação entre hardware e software por meio da leitura de sinais digitais e acionamento de componentes eletrônicos.

Como Funciona

O sistema monitora constantemente três botões conectados às portas digitais da placa.

Quando o primeiro botão é pressionado:

O LED 1 é acionado por 1 segundo;
Em seguida, o LED 2 é acionado por 3 segundos;
Por fim, o LED 3 é acionado por 5 segundos;
Após a execução da sequência, todos os LEDs são desligados.

A leitura dos botões é realizada continuamente dentro de um laço while, permitindo que o sistema responda às interações do usuário em tempo real.

Conceitos Aplicados
Sistemas embarcados;
Entradas digitais (botões);
Saídas digitais (LEDs);
GPIO (General Purpose Input/Output);
Estruturas condicionais;
Laços de repetição;
Temporização com time.sleep();
Programação em MicroPython.
Aprendizados

Durante o desenvolvimento deste projeto foram praticados conhecimentos relacionados a:

Programação de microcontroladores;
Controle de componentes eletrônicos;
Manipulação de sinais digitais;
Integração entre hardware e software;
Desenvolvimento de aplicações embarcadas.
Melhorias Futuras
Utilização dos três botões para funções independentes;
Implementação de semáforo inteligente;
Adição de buzzer sonoro;
Controle por display LCD;
Uso de interrupções para melhor desempenho;
Criação de efeitos luminosos mais avançados.
Autor

Projeto desenvolvido para fins acadêmicos e de aprendizagem, explorando conceitos de eletrônica, automação e programação embarcada com MicroPython.








![Captura de tela 2026-05-31 193143](https://user-images.githubusercontent.com/...)
