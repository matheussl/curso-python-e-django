Aula 01 - Python
==================

Nos exemplos de código deste capítulo, sempre que encontrar ">>>" no código, indica que o código está sendo executado no terminal através do **Shell Interativo do Python**.

Introdução
-----------
Python é uma linguagem de alto nível, interpretada, imperativa e orientada a objetos, mutiplataforma, de tipagem dinâmica e forte.

Foi criada em 1989 por Guido Van Rossum, com uma filosofia de enfatizar a importância do esforço do programador sobre o esforço computacional.

A cultura da linguagem Python gira em torno do **Zen Of Python**, um poema que faz parte do **PEP 20**. O poema pode ser visualizado com o comando abaixo:


    >>> import this
    The Zen of Python, by Tim Peters

    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts.
    Special cases aren't special enough to break the rules.
    Although practicality beats purity.
    Errors should never pass silently.
    Unless explicitly silenced.
    In the face of ambiguity, refuse the temptation to guess.
    There should be one-- and preferably only one --obvious way to do it.
    Although that way may not be obvious at first unless you're Dutch.
    Now is better than never.
    Although never is often better than *right* now.
    If the implementation is hard to explain, it's a bad idea.
    If the implementation is easy to explain, it may be a good idea.
    Namespaces are one honking great idea -- let's do more of those!



Sintaxe
-----------
Python possui uma sintaxe muito simples e objetiva. Nessa sessão vamos mostrar alguns exemplos de códigos, com algumas explicações.

```python
# este é o primeiro comentário
SPAM = 1 # e este é o segundo comentário
# ... e agora um terceiro!
STRING = "# Isto não é um comentário."
```

#### Operações matemáticas

    >>> 2+2
    4
    >>> # Isto é um comentário
    ... 2+2
    4
    >>> 2+2  # em um comentário na mesma linha do código
    4
    >>> (50-5*6)/4
    5
    >>> # A divisão entre inteiros arredonda para baixo:
    ... 7/3
    2
    >>> 7/-3
    -3

#### Atribuição de valores

    >>> largura = 20
    >>> algura = 5*9
    >>> largura * altura
    900
    >>> x = y = z = 0  # Zerar x, y, z
    >>> x
    0
    >>> y
    0
    >>> z
    0

#### Strings

    >>> 'spam eggs'
    'spam eggs'
    >>> 'doesn\'t'
    "doesn't"
    >>> "doesn't"
    "doesn't"
    >>> '"Yes," he said.'
    '"Yes," he said.'
    >>> "\"Yes,\" he said."
    '"Yes," he said.'
    >>> '"Isn\'t," she said.'
    '"Isn\'t," she said.'

#### Concatenação de Strings

    >>> palavra = 'Ajuda' + 'Z'
    >>> palavra
    'AjudaZ'
    >>> '<' + palavra*5 + '>'
    '<AjudaZAjudaZAjudaZAjudaZAjudaZ>'
    >>> 'str' 'ing'             #  <-  Isto funciona
    'string'
    >>> 'str'.strip() + 'ing'   #  <-  Isto funciona
    'string'
    >>> 'str'.strip() 'ing'     #  <-  Isto é inválido
      File "<stdin>", line 1, in ?
        'str'.strip() 'ing'
                          ^
    SyntaxError: invalid syntax

    >>> palavra[4]
    'a'
    >>> palavra[0:2]
    'Aj'
    >>> palavra[2:4]
    'ud'
    >>> palavra[:2]     # Os dois primeiros caracteres
    'Aj'
    >>> palavra[2:]     # Tudo menos os dois primeiros caracteres
    'udaZ'


Strings não podem ser alteradas, veja no exemplo abaixo:

    >>> palavra[0] = 'x'
    Traceback (most recent call last):
      File "<stdin>", line 1, in <module>
    TypeError: 'str' object does not support item assignment
    >>> palavra[:1] = 'Splat'
    Traceback (most recent call last):
      File "<stdin>", line 1, in <module>
    TypeError: 'str' object does not support item assignment



Blocos
-----------

Tipos builtin
----------------

Operadores
-------------

Listas
-------------

Tuplas
------------

Dicionários
---------------

Funções
------------

Classes
------------

Iteradores
--------------

