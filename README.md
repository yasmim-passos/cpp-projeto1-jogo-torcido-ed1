# 🎮 Jogo Torcido

Projeto desenvolvido em **C++** com **interface gráfica utilizando a biblioteca raylib**, criado para a disciplina **Estruturas de Dados I (EDI)** da **Universidade Federal de Sergipe (UFS)**.

O jogo é baseado na ideia de palavras embaralhadas, onde o jogador deve descobrir o maior número possível de palavras válidas antes que o tempo acabe.

---

## 📌 Descrição do Jogo

O **Jogo Torcido** seleciona aleatoriamente uma palavra de um dicionário (Português ou Inglês) e exibe suas letras embaralhadas.  
O objetivo do jogador é adivinhar palavras válidas utilizando essas letras, sem repetição.

Cada acerto:
- Soma pontos à pontuação
- Acrescenta tempo extra à partida

O jogo termina quando o tempo se esgota.

---

## 🧠 Conceitos Trabalhados

- Estrutura de dados **Pilha (implementada por arranjo)**
- Manipulação de arquivos `.txt`
- Programação em C++
- Lógica de jogos
- Interface gráfica e áudio com **raylib**

---

## 🛠️ Funcionalidades

- 🎲 Escolha de dicionário (Português ou Inglês)
- 🔤 Letras embaralhadas da palavra base
- ⌨️ Entrada de palavras pelo teclado
- 🕒 Sistema de tempo regressivo
- ⭐ Sistema de pontuação (exemplo: +10 pontos por acerto)
- ⏱️ Bônus de tempo a cada palavra correta
- 📋 Controle de palavras já utilizadas
- 🔊 Sons e gráficos utilizando raylib

---

## 📚 Estrutura de Dados Utilizada

O jogo utiliza **Pilha por Arranjo**, aplicada para:
- Gerenciamento das letras disponíveis
- Controle das palavras formadas pelo jogador

---

---

## 🚀 Possíveis Melhorias Futuras

- Integração com APIs de dicionários online
- Sistema de níveis/fases
- Ranking de jogadores
- Suporte a mais idiomas
- Melhorias na interface gráfica

---

## ▶️ Como Executar

### Pré-requisitos
- Compilador C++ (g++ ou equivalente)
- Biblioteca **raylib** instalada

### Compilação (exemplo)
```bash
g++ main.cpp -o jogo -lraylib -lopengl32 -lgdi32 -lwinmm
