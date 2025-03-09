# Simulador de loteria

Esse projeto se baseia em um simples sistema que simula o funcionamento de uma loteria com um simples algoritmo desenvolvido em Java por meio da orientação a objetos. Esse sisteminha permite com que o usuário possa escolher os números de seus bilhetes e por meio do sorteio observar o seu resultado.

## Estrutura do projeto

Para a criação desse projeto foram desenvolvidas duas classes importantes que interagem entre si para que a experiência de simulação seja bem próxima da realidade, sendo elas a classe Bilhete e classe SimuladorLoteria.

- Bilhete: Essa classe será responsável pela criação dos bilhetes usados para a realização dos sorteios que serão realizados na classe principal "SimuladorLoteria".

- SimuladorSorteio: Essa classe será responsável por grande parte das funcionalidades do sistema, pois ela é responsável por obter a quantidade de bilhetes que o usuário deseja, como também os respectivos números escolhidos para casa um Bilhete. Após isso, essa classe realizará um sorteio de alguns números aleatório e com o resultado, irá fazer uma comparação com os bilhetes escolhidos para poder apresentar o resultado obtido pelo usuário.

## Futuras melhorias

Meu objetivo é futuramente adicionar mais funcionalidades a esse pequeno sistema e deixá-lo mais próximo da realidade dos sorteios de loterias, afim de torná-lo um sistema mais completo e poder aplicar novos conhecimentos do Java.

## Como executar

### Pré-requisitos

1. Possuir instalação do JDK em sua máquina.
   
2. Possuir uma IDE que permita a utilização do Java, como por exemplo o VSCode.

### Execução

1. Clone o repositório em sua máquina local:
   ```bash
   git clone https://github.com/Walmir07/loteria-simulador.git
   ```
2. Compile o arquivo:

   ```bash
   javac SimuladorLoteria.java
   ```
3. Execute o arquivo:
   ```bash
   Java SimuladorLoteria.java
   ```
