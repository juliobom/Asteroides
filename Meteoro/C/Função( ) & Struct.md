
## ~={azulin}Struct=~

o que é uma struct? e como funciona.

Imagine que você queira registrar os dados de um **Livro**. Em vez de criar variáveis soltas como `char titulo[50];`, `char autor[50];` e `float preco;` para cada livro, você cria uma `struct Livro` que junta tudo isso.

```
struct Livro {
    char titulo[50];
    char autor[50];
    float preco;
};
```

tambem ah outra forma de declarar uma struct, utilizando metodo com ~={green}typedef=~.

```
typedef struct{
	char nome[50];
	int idade;
	float altura;
}Pessoa;
```

ambas formas funcionam basicamente da mesma forma porem declarando o tipo com ~={pink}typedef=~, deixa o codigo mais limpo, e mais atualizado que o struct normal em c.