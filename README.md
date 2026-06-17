# 🚦 Semáforo composto com Arduino

Projeto utilizando Arduino para simular o funcionamento de um semáforo em um cruzamento.

## 🧠 Descrição

Este projeto demonstra o controle de múltiplos LEDs utilizando saídas digitais do Arduino, simulando dois semáforos que funcionam de forma sincronizada.

## 🎯 Objetivo

O objetivo deste projeto é aplicar conceitos de eletrônica e programação com Arduino, como:

* Controle de múltiplos pinos digitais
* Lógica de temporização
* Simulação de sistemas do mundo real
* Uso de estruturas básicas (setup e loop)

## 🔌 Componentes utilizados

* Arduino Uno
* 6 LEDs (vermelho, amarelo e verde para cada semáforo)
* 6 Resistores (220Ω)
* Jumpers
* Protoboard

## 🔧 Montagem do circuito

* Conecte os LEDs aos pinos digitais do Arduino
* Utilize resistores em série com cada LED
* Conecte todos os cátodos ao GND
* Organize os LEDs em dois conjuntos (dois semáforos)

## ⚙️ Funcionamento

O sistema alterna entre dois semáforos:

* Enquanto um está verde, o outro permanece vermelho
* O sinal amarelo é acionado antes da troca
* O processo ocorre em ciclos contínuos com intervalos de 2,5 segundos

## 📷 Circuito




