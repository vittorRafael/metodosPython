# Documentação Python

## Comandos
- Para receber a entrada do usuário declara a variavel assim: `variavel = tipo(input("pergunta ao usuário?"))`
- If: é formado pela seguinte estrutura `if condicao: retorno, elif segundacondicao: retorno, else: retorno`
- For: o for pode ser interado em uma lista ou string seguindo a estrutura `for item in items: retorno`
- Break: sai imediatamente do laço de repetição
- Else para `for` ou `while`: em um laço for, a cláusula else é executada após o laço atingir sua iteração final. Em um laço while, ele é executado após a condição do laço se tornar falsa, em qualquer um dos laços o else não é executado se for parado por um `break`.
- Continue: continua com a próxima iteração do laço.

## Funções embutidas

- `len(prt)` -> "prt" pode ser uma string ou uma lista, a função len irá retornar seu comprimento/tamanho.
- `range(inicio, final, intervalo)` -> "inicio" é um inteiro de onde irá iniciar a contagem senão for passado irá ser 0, "final" é um inteiro de a progressão irá parar, "intervalo" é um inteiro que representa o intervalo entra os números se não for passado irá ser 1, a função range é utilizada para criar progressões aritméticas.
- `sum(lista)` -> "lista" seria uma lista de inteiros, a função sum irá somar todos os inteiros da lista e retornar o resultado. 

## String

### Métodos
- `str.upper()` -> Deixa tudo maiúsculo.
- `str.lower()` -> Deixa tudo minúsculo.
- `str.capitalize()` -> Primeira letra maiúscula.
- `str.title()` -> Deixa todas as palavras com primeira letra maiúscula.
- `str.lstrip()` -> elimina espaços ao lado esquerdo.
- `str.rstrip()` -> elimina espaços ao lado direito.
- `str.strip()` -> elimina espaços de ambos os lados.

## Lista

### Observações

1. Passando um número negativo, irá retornar elementos a partir do último index.
2. Passando `[indexInicial:indexFinal]` irá pegar o intervalo desses elementos (ambos estarão inclusos).

### Métodos

- `lista.count(prt)` -> "prt" é o valor a ser achado, verifica o parâmetro e retorna quantas vezes aparece na lista.
- `lista.clear()` -> Limpa a lista.
- `lista.index(prt)` -> "prt" é o valor a ser achado, verifica o parâmetro e retorna o index se existir na lista.
- `lista.append(prt)` -> "prt" é o valor a ser adicionado, verifica o parâmetro e adiciona ao final da lista.
  
