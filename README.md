# 🎰 Simulador de loteria

Esse projeto se baseia em um simples sistema em Java que simula o funcionamento de uma loteria, utilizando conceitos de orientação a objetos. Esse sistema permite com que o usuário escolha os números de seus bilhetes e, após o sorteio, verifica os resultados de forma simples e intuitiva.

O objetivo deste projeto é praticar conceitos de Java e orientação a objetos, como encapsulamento, métodos, manipulação de listas e lógica de sorteio.

## 🗂 Estrutura do projeto

Para a criação desse projeto foram desenvolvidas duas classes importantes que interagem entre si para que a experiência de simulação seja bem próxima da realidade, sendo elas a classe Bilhete e classe SimuladorLoteria.

- Bilhete: Essa classe será responsável pela criação dos bilhetes usados para a realização dos sorteios que serão realizados na classe principal "SimuladorLoteria".

- SimuladorSorteio: Essa classe será responsável por grande parte das funcionalidades do sistema, pois ela é responsável por:

   - Criação de bilhetes;
   - Entrada de números escolhidos pelo usuário;
   - Realização de sorteio aleatório;
   - Comparação entre números sorteados e escolhidos;
   Exibição dos resultados;

## ⚙️ Funcionalidades

- Criar e armazenar bilhetes com números escolhidos pelo usuário.  
- Realizar sorteio de números aleatórios.  
- Comparar os números sorteados com os bilhetes do usuário.  
- Exibir resultados de forma clara no console.

## 🛠️ Tecnologias e Conceitos Abordados

- **Java** (JDK).
- **Orientação a Objetos** (Classes, métodos, encapsulamento).
- **Manipulação de listas** (`ArrayList`).
- **Entrada/Saída via console** (`Scanner`).
- **Lógica de sorteio aleatório** (`Random`).

## 💻 Demonstração

Exemplo de execução no console:

  ```console
Quantos bilhetes deseja criar? 2

Bilhete 1: 3, 15, 22, 28, 35, 42 
Bilhete 2: 1, 7, 19, 23, 31, 40

Números sorteados: 3, 7, 22, 28, 35, 42

Resultados: 

Bilhete 1: 5 acertos 
Bilhete 2: 3 acertos
   ```

## 💭 Futuras melhorias

Meu objetivo é futuramente adicionar mais funcionalidades a esse pequeno sistema e deixá-lo mais próximo da realidade dos sorteios de loterias, como também implementar uma interface gráfica (Swing ou JavaFX), afim de torná-lo um sistema mais completo e poder aplicar novos conhecimentos do Java.

## 🚀 Como executar?

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

## 📜 Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👤 Autor
- **Walmir Lima** – [@Walmir07](https://github.com/Walmir07)

