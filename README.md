# relatorio
1.	Introdução
Este trabalho é a implementação de uma sistemática de atualização de um ranking de pontuação. Nele, temos um arquivo header(.h) com a função de gerar o ranking de todos os jogadores de um jogo hipotético e a demarcação das melhores pontuações. Foram utilizadas em um arquivo header as listas estática, encadeada simples e duplamente encadeada para a organização do ranking. No main.cpp temos a implementação de todas as listas e funções utilizadas no projeto.
2.	Desenvolvimento
2.1.	  Listas
2.1.1.	Lista estática
A lista estática foi escolhida nos casos em que o ranking tem um tamanho definido (ex.: top 10, top 50). Nela foi criada uma classe genérica que contém as funções de inicialização, inserção, remoção, obtenção, contenção, descobrir índice e imprimir. Quando inicializada, o tamanho recebe o valor zero. Na inserção e remoção, a função recebe por parâmetro um inteiro “pos”(posição) e um tipo genérico “dado”. Se a posição for maior que o tamanho ou menor que 0, é lançado um erro de índice. O dado é inserido ou removido na posição declarada, seja no início, fim ou meio da lista. A lista é então deslocada de acordo com o dado inserido/removido e a variável de controle “tamanho” é alterada.
Função contains: percorre a lista e retorna true se o dado está contido na mesma.
Função at: retorna o dado armazenado na posição informada.
Função find: percorre a lista até encontrar o dado desejado, retornando o mesmo. Caso não exista, retorna -1.
