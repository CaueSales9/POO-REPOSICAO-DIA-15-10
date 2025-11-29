📦 Sistema de Gerenciamento de Estoque
Este é um script simples em Python desenvolvido para gerenciar o estoque de alimentos e bebidas de uma lanchonete. O sistema funciona via terminal (CLI) e permite o controle total de entrada e saída de produtos, além de funcionalidades de relatórios e reposição automática.

🚀 Funcionalidades
O sistema oferece um menu interativo com as seguintes opções:

1 - Adicionar Produto: Cadastra novos produtos (comida ou bebida) ou incrementa a quantidade de itens já existentes.

2 - Remover Produto: Permite dar baixa no estoque. Se a quantidade a remover for igual ou superior ao estoque atual, o item é deletado da lista.

3 - Consultar Produto: Busca por um item específico pelo nome e exibe sua quantidade e categoria.

4 - Mostrar Estoque: Exibe a lista completa de todos os itens disponíveis (Bebidas e Comidas).

5 - Salvar Arquivo: Exporta o estado atual do estoque para um arquivo de texto chamado POO_Aula.txt.

6 - Repor Automático: Verifica itens com estoque baixo (3 unidades ou menos) e adiciona automaticamente 5 unidades a eles.

🛠️ Tecnologias Utilizadas
Python 3

Manipulação de arquivos de texto (.txt)

Estruturas de dados: Dicionários e Listas

Tratamento de exceções (try/except) para entradas inválidas.

📋 Pré-requisitos
Para executar este projeto, você precisa ter o Python instalado em sua máquina.

▶️ Como Executar
Clone este repositório ou baixe o arquivo atv2.py.

Abra o terminal na pasta onde o arquivo está salvo.

Execute o comando:

Bash

python atv2.py
📂 Estrutura do Relatório
Ao utilizar a opção 5 - Salvar arquivo, o sistema gerará um arquivo POO_Aula.txt no mesmo diretório, formatado da seguinte maneira:

Plaintext

Relatório de Estoque:
sanduiche: 15
bolo: 10
...
refrigerante: 25
suco: 2
...
