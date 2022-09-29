Corretor Ortográfico
Projeto realizado no curso Corretor Ortográfico em Python: aplicando técnicas de NLP (prof. Thiago G. Santos - Alura).

- Iniciamos com a leitura de um arquivo de texto.
- Fazendo a tokenização, dividimos todo o texto em palavras e contamos a quantidade de palavras que o modelo vai aprender a corrigir.
- Separando a palavra errada em dois, é possível inserir letras e testar, até encontrar a posição e letra corretas, isso para palavras que foram digitadas com uma letra a menos.
- Conseguimos encontrar a palavra correta por causa da frequência máxima em que a palavra aparece no texto inicial.
- Criação da avaliação do corretor para saber a taxa de acerto dele.
- Para palavras que foram digitadas com letra a mais, criamos uma função que deleta a letra.
- Para troca de letras ou letras invertidas, também há tratamento.
- Até então, a tratativa de palavras erradas era apenas para um caracter errado na string, com o Gerador Turbinado, ele faz o processo duplo de gerar palavras, então é possível corrigir palavras que estão até duas distâncias da palavra correta.
