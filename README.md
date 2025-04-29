# 🧩 Jogo Sudoku em Java

Este projeto é uma implementação do jogo **Sudoku** em Java, desenvolvido como parte de um desafio prático da **Digital Innovation One (DIO)**. O jogo pode ser executado no terminal com entrada personalizada de tabuleiro e também possui uma versão com interface gráfica.

## 🎯 Objetivo

Reforçar os conhecimentos de Programação Orientada a Objetos (POO) e lógica de programação com um projeto prático e desafiador, utilizando Java puro.

## 🧠 Conceitos Aplicados

- Programação Orientada a Objetos (POO)  
- Estruturas condicionais e de repetição  
- Validação de regras do Sudoku  
- Interface gráfica com Java Swing (na branch `ui`)  
- Recebimento de argumentos via linha de comando  

## 🚀 Como Executar

### ✔️ Pré-requisitos

- Java 17+ instalado  
- VS Code ou outra IDE Java  
- Terminal (PowerShell, CMD ou Git Bash)  

### 🕹️ Executar no Terminal

1. Compile o projeto:  
   `javac -d bin src/*.java`

2. Execute com argumentos representando o tabuleiro (exemplo abaixo):  
   `java -cp bin Main 0,0;4,false 1,0;7,false 2,0;9,true ...`

   Cada argumento segue a estrutura:  
   `coluna,linha;valor,fixo`

   Exemplo:  
   `1,2;5,true → posição (1,2) recebe o número 5 e é fixo (não editável)`

### 🖥️ Executar Interface Gráfica

1. Mude para a branch com UI:  
   `git checkout ui`

2. Compile e execute a interface:  
   `javac -d bin src/ui/*.java`  
   `java -cp bin ui.SudokuUI`

## 🧪 Exemplo de Argumentos para Rodar no Terminal

```
0,0;4,false 1,0;7,false 2,0;9,true 3,0;5,false 4,0;8,true 5,0;6,true 6,0;2,true 7,0;3,false 8,0;1,false 0,1;1,false 1,1;3,true 2,1;5,false 3,1;4,false 4,1;7,true 5,1;2,false 6,1;8,false 7,1;9,true 8,1;6,true 0,2;2,false 1,2;6,true 2,2;8,false 3,2;9,false 4,2;1,true 5,2;3,false 6,2;7,false 7,2;4,false 8,2;5,true ...
```

Argumento completo disponível no [README do repositório original da DIO](https://github.com/digitalinnovationone/sudoku)

## 📁 Organização do Código

```
├── src
│   ├── Main.java           # Ponto de entrada
│   ├── Tabuleiro.java      # Lógica do jogo
│   └── ui/                 # (opcional) Interface gráfica com Swing
├── bin/                    # Arquivos compilados
└── README.md
```

## 👨‍💻 Autor

Desenvolvido por [AadrielL](https://github.com/AadrielL) para o desafio "Criando um jogo Sudoku em Java" da [Digital Innovation One](https://www.dio.me/).

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
