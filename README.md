# Compilator

Compilador simples escrito em C, desenvolvido como projeto da disciplina de Compiladores na faculdade.

## Sobre o projeto

O projeto implementa as primeiras etapas de um compilador:

- **Analisador léxico (lexer):** lê o código-fonte e o divide em tokens.
- **Analisador sintático (parser):** verifica se a sequência de tokens segue a gramática da linguagem.

## Estrutura do projeto

```
.
├── main.c        # Ponto de entrada do programa
├── lexer.c       # Implementação do analisador léxico
├── lexer.h       # Declarações do analisador léxico
├── parser.c      # Implementação do analisador sintático
├── parser.h      # Declarações do analisador sintático
├── teste.txt     # Arquivo de exemplo para testes
└── compilador.exe  # Executável já compilado (Windows)
```

## Como compilar

É necessário ter o [GCC](https://gcc.gnu.org/) instalado. Na pasta do projeto, execute:

```bash
gcc main.c lexer.c parser.c -o compilador
```

## Como executar

```bash
./compilador teste.txt
```

No Windows, também é possível rodar o executável direto:

```bash
compilador.exe teste.txt
```

## Status

- [x] Analisador léxico
- [x] Analisador sintático
- [x] Exemplos de teste funcionando

## Autor

**Guilherme Fernandes**
Estudante de Ciência da Computação na UFRRJ

[LinkedIn](https://www.linkedin.com/in/guilherme-fernandes-17a185328/)
