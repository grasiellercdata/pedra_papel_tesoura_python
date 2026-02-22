🎮 Pedra, Papel e Tesoura (2 Jogadores)

Projeto simples em Python do clássico jogo Pedra, Papel e Tesoura, desenvolvido para praticar lógica de programação, estruturas condicionais e entrada de dados pelo usuário.

📌 Sobre o Projeto

Este jogo funciona no terminal e permite que dois jogadores escolham entre:

pedra

papel

tesoura

O sistema:

Recebe as jogadas

Valida as entradas

Compara as escolhas

Exibe o vencedor ou informa empate

🛠️ Tecnologias Utilizadas

Python 3

Jupyter Notebook (ipykernel)

▶️ Como Executar

Certifique-se de ter o Python 3 instalado.

Clone este repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git

Acesse a pasta do projeto:

cd seu-repositorio

Execute o arquivo:

python nome_do_arquivo.py

Ou abra o .ipynb no Jupyter Notebook.

🧠 Conceitos Praticados

Variáveis

Tuplas

Estruturas condicionais (if, elif, else)

Operadores lógicos (and, or)

Tratamento básico de entradas com .lower() e .strip()

Validação de dados

📷 Exemplo de Execução
----Jogo Pedra, Papel e Tesoura (2 Jogadores)----
Opções válidas: ('pedra', 'papel', 'tesoura')

Jogador1, digite sua jogada: pedra
Jogador2, digite sua jogada: tesoura

Resultado: Jogador 1 Venceu! PARABÉNS!
🚀 Próximas Melhorias

 Versão contra o computador (modo single player)

 Sistema de pontuação

 Loop para múltiplas rodadas

 Interface gráfica (Tkinter ou Web)

👩‍💻 Autora Grasielle Rodrigues Costa

{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "1666311d-ff04-4e3c-b59c-c9af0e2599b6",
   "metadata": {},
   "outputs": [],
   "source": [
    "print(\"-----------------------------------------------\")\n",
    "print(\"----Jogo Pedra, Papel e Tesoura (2 Jogadores)----\")\n",
    "print(\"-----------------------------------------------\")\n",
    "print(\"Bem-vindos! Cada jogador deve escolher uma das opções.\")\n",
    "opcoes_validas = (\"pedra\", \"papel\", \"tesoura\")\n",
    "print(f\"Opções válidas: {opcoes_validas}\")\n",
    "print(\"-\" * 25)\n",
    "jogada_jogador1_inicial = input(\"Jogador1, digite sua jogada: \")\n",
    "jogada_jogador2_inicial = input(\"Jogador2, digite sua joada: \")\n",
    "\n",
    "jogada_jogador1 = jogada_jogador1_inicial.lower().strip()\n",
    "jogada_jogador2 = jogada_jogador2_inicial.lower().strip()\n",
    "print(\"-\" * 25)\n",
    "print(f\"Jogador 1 escolheu: {jogada_jogador1}\")\n",
    "print(f\"Jogador 2 escolheu: {jogada_jogador2}\")\n",
    "print(\"-\" * 25)\n",
    "if jogada_jogador1 not in opcoes_validas or jogada_jogador2 not in opcoes_validas:\n",
    "    print:(\"OBS: Uma ou ambas as jogadas são inválidas! Por favor, insira um valor válido.\")\n",
    "elif jogada_jogador1 == jogada_jogador2:\n",
    "    print(\"Resultado: É um empate!\")\n",
    "elif (jogada_jogador1 == \"pedra\" and jogada_jogador2 == \"tesoura\") or \\\n",
    "(jogada_jogador1 == \"tesoura\" and jogada_jogador2 == \"papel\") or \\\n",
    "(jogada_jogador1 == \"papel\" and jogada_jogador2 == \"pedra\"):\n",
    "    print(\"Resultado: Jogador 1 Venceu! PARABÉNS!\")\n",
    "\n",
    "else:\n",
    "    print(\"Resultado: Jogador 2 venceu! PARABÉNS!\")\n",
    "print(\"\\n--- Fim de Jogo ---\")\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.9"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}

Grasielle Rodrigues Costa
Em transição de carreira para a área de Análise de Dados, desenvolvendo projetos práticos em Python para fortalecer lógica e programação.
