# 🎯 Jogo de Adivinhação Numérica

## 📝 Descrição do Projeto
Este projeto é um jogo interativo de terminal desenvolvido em Python. O programa gera um número secreto aleatório entre 0 e 100 e o usuário deve tentar adivinhá-lo. O sistema fornece dicas se o número digitado é maior ou menor que o alvo, validando também se a entrada está dentro do intervalo permitido.

## 👥 Integrantes do Grupo
* **Felipe da Silva Santos ** - [github.com/Felipe01122](https://github.com/Felipe01122)
* **Paulo Thomaz Filho** - [github.com/paulo-thomaz-filho](https://github.com/paulo-thomaz-filho)
* **Kauan Bruno da Silva** - [github.com/kauanddz](https://github.com/kauanddz)
* **Bruno da Silva Salazar Pardo** - [github.com/brunosalazarse-lgtm](https://github.com/brunosalazarse-lgtm)
* **Enzo Costa Gomes** - [github.com/felipe838](https://github.com/felipe838)
* **Wallyson Johnny da Silva Siqueira** - [github.com/wallysonjoh](https://github.com/wallysonjoh)

## 🛠️ Pré-requisitos
Para rodar este jogo, você precisará de:
1. **Python 3.13:** O código utiliza recursos da versão mais recente da linguagem.
   - Para verificar sua versão, digite `py --version` ou `python --version` no terminal.
2. **Git:** Necessário para clonar o repositório (opcional, caso prefira baixar o arquivo manualmente).

## 🚀 Como Usar (Passo a Passo)
Siga as instruções abaixo para executar o jogo em sua máquina:

1. **Obter o código:**
   - Clone este repositório usando o comando: `git clone [LINK_DO_REPOSITORIO]`
   - Ou baixe o arquivo `.py` diretamente do GitHub.
2. **Abrir o Terminal:**
   - Navegue até a pasta onde o arquivo foi salvo.
3. **Executar o Jogo:**
   - Utilize o Python instalado para abrir o arquivo com o seguinte comando:
     ```bash
     python nome_do_arquivo.py
     ```
4. **Jogar:**
   - O menu aparecerá no terminal pedindo um número.
   - Digite seu palpite e pressione **Enter**.
   - O jogo informará se você acertou ou se deve tentar um número maior ou menor.
   - Caso digite um valor acima de 100, o sistema exibirá "Número inválido".

## 💻 Explicação Técnica
O grupo aplicou os conceitos da unidade para construir uma lógica eficiente e limpa:

* **Módulo Random:** Utilizamos `import random` e a função `randint(0, 100)` para que o computador escolha um número inteiro aleatório a cada nova execução.
* **Laço de Repetição:** O uso do `while True` permite que o jogo continue rodando indefinidamente até que o comando `break` seja acionado.
* **Estrutura Condicional (IF/ELIF/ELSE):**
    - `if num1 > 100`: Valida a regra de negócio de limite do jogo.
    - `elif num1 > num` e `elif num1 < num`: Fornecem o feedback lógico ao jogador.
    - `else`: Identifica o acerto exato.
* **Tipagem de Dados:** Utilizamos `float(input())` para garantir que o programa aceite entradas numéricas, permitindo a comparação lógica correta com o número gerado pelo sistema.
