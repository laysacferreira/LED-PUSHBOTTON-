# 🤖 Sistema de Controle de LEDs com Botões (MicroPython)

## 🧠 Sobre o Projeto

Este projeto foi desenvolvido utilizando MicroPython com o objetivo de controlar LEDs por meio de botões físicos. Ele permite ao usuário escolher diferentes modos de funcionamento, tornando o sistema interativo.

## 📄 Descrição

O sistema utiliza:

* 3 LEDs conectados aos pinos 12, 13 e 14
* 3 botões conectados aos pinos 3, 4 e 5

Cada botão ativa um tipo de sequência diferente:

### 🔴 Botão 1 – Modo Semáforo

Simula o funcionamento de um semáforo:

* LED 1 acende (3 segundos)
* LED 2 acende (5 segundos)
* LED 3 acende (1 segundo)

### ✨ Botão 2 – Pisca Sequencial

Os LEDs acendem um por um em sequência rápida, criando um efeito animado.

### 💡 Botão 3 – Todos os LEDs

Todos os LEDs acendem ao mesmo tempo por alguns segundos e depois apagam.

O sistema identifica qual botão foi pressionado e executa a ação correspondente. Após cada execução, os LEDs são desligados automaticamente.

O projeto utiliza conceitos como:

* Leitura de entradas digitais (`Pin.IN`)
* Controle de saídas (`Pin.OUT`)
* Uso de resistores internos (`PULL_UP`)
* Estruturas condicionais (`if`)
* Laço infinito (`while True`)
* Temporização com `time.sleep()`

## ▶️ Execução
![imagemsemáforo](https://github.com/laysacferreira/LED-PUSHBOTTON-/blob/main/sem%C3%A1foro.png)

## 🎯 Conclusão

Este projeto é ideal para quem está aprendendo programação embarcada e eletrônica, pois demonstra como criar sistemas interativos com entrada (botões) e saída (LEDs).
