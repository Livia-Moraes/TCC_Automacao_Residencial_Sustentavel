<h1 align="center"> TCC - Automação Residencial Sustentável </h1>

<a id="Sumário"></a>

<p align="center">
  <b> Rastreador Solar </b></br>
  <sub> Este projeto busca automatizar a movimentação de um painel solar para captar a maior quantidade de luz solar possível e tornar mais eficiênte a geração.
  <sub>
</p>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)

<p align="center">
  <a href="#Sobre o Projeto"> 🧩 Sobre o Projeto </a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Tecnologias utilizadas"> 🚀 Tecnologias utilizadas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Estrutura do Projeto"> 🧪 Estrutura do Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Resultados"> 🏆 Resultados </a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Possíveis Melhorias"> 💡 Possíveis Melhorias </a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

<br/>

<br/>

<a id="Sobre o Projeto"></a>
## 🧩 Sobre o Projeto 

Bem-vindo ao meu projeto de rastreador solar! 

Este projeto faz parte do Trabalho de Conclusão de Curso e visa desenvolver um sistema de automação residencial sustentável. Utilizando o ESP32, sensores de luz e servos motores para controlar uma estrutura que terá um painel solar para otimizar a captação de energia solar, além de monitorar e enviar dados sobre a geração de energia via bot no telegram, permitindo o acompanhamento em tempo real.

<br/>

<a id="Tecnologias utilizadas"></a>
## 🚀 Tecnologias utilizadas 

Todos os testes realizados com o projeto foram bem-sucedidos. O rastreador solar ajusta a posição do painel com base na intensidade da luz detectada pelos sensores LDR.

### Exemplo de Funcionamento:

- **ESP32:** O microcontrolador controla e monitora o rastreador solar.
- **LDRs (Light Dependent Resistors):** Sensores de luz para detectar a posição do sol.
- **Servos:** Motores que ajustam a posição do painel solar.
- **Wi-Fi:** Conexão com a internet para enviar dados para o bot no telegram.
- **Plataformas e Ferramentas:** Arduino IDE (para programação), Proteus (para simulação), Telegram (Envio de dados).

<br/>

<a id="Estrutura do Projeto"></a>
## 🧪 Estrutura do Projeto

1. **Código para o ESP32:** Lógica de controle do rastreamento solar e comunicação com o telegram.

<p align="center">
  <a href="https://ibb.co/KjMHSfc">
    <img src="https://i.ibb.co/6R35LTc/Imagem-25.jpg" alt="Imagem-25" style="width: 600px; height: auto;">
  </a>
  <p align="center">Interface Arduino IDE.</figcaption>
</figure>

2. **Circuito Eletrônico:** Montagem do circuito com ESP32, LDRs e servos.

<p align="center">
  <a href="https://ibb.co/2Pz6N1b">
    <img src="https://i.ibb.co/nfX0CNW/Imagem-23.jpg" alt="Imagem-23" style="width: 600px; height: auto;">
  </a>
</p>
<p align="center">Montagem no Software Proteus.</p>
   
3. **Telegram:** Bot para saber as informações do rastreador.

 Start| Ambos | Informações | Comandos |
|---|---|---|---|
![Imagem-26](https://i.ibb.co/mFpBtV6/Imagem-26.jpg) | ![Imagem-27](https://i.ibb.co/CJ3SDSB/Imagem-27.jpg) | ![Imagem-28](https://i.ibb.co/KN50684/Imagem-28.jpg) | ![Imagem-29](https://i.ibb.co/pj8fkmX/Imagem-29.jpg)

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)

<a id="Resultados"></a>
## 🏆 Resultados

<a id="Possíveis Melhorias"></a>
## 💡 Possíveis Melhorias



