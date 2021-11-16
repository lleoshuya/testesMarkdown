# Exemplos em Markdown
Testando comandos em Markdown

### Texto em Itálico
Para escrever algo em *itálico* é necessário escrever o texto em questão entre *, por exemplo: \*texto de exemplo\*.

Comando:

* \*texto de exemplo\*

Resultado

* *texto de exemplo*

<hr>

### Texto em Negrito
Para escrever algo em **negrito** é necessário escrever o texto em questão entre **, por exemplo: \*\*texto de exemplo\*\*.

Comando:

* \*\*texto de exemplo\*\*

Resultado

* **texto de exemplo**

<hr>

### Texto Riscado
Para escrever um texto ~~riscado~~ é necessário escrever o texto em questão entre \~~, por exemplo: \~~texto de exemplo\~~.

Comando:

* \~~texto de exemplo\~~

Resultado

* ~~texto de exemplo~~

<hr>

### Lista de Tarefas

Para criar Listas de Tarefas em Markdown, é necessário usar o modelo - [ ] Item 1, e para marcar o item como concluído, utilizar - [x] Item 2.

Exemplos: 

- [ ] Mercury
- [x] Venus
- [x] Earth (Orbit/Moon)
- [x] Mars
- [ ] Jupiter
- [ ] Saturn
- [ ] Uranus
- [ ] Neptune
- [ ] Comet Haley

<hr>

### Citação de Texto

Para incluir uma citação de texto, é necessário utilizar o caractere ">" antes de um texto, por exemplo: \>Citação de Exemplo.

Comando:

* \>texto de exemplo

Resultado

* >texto de exemplo

<hr>

### Citação de Códigos

Para citar trechos de códigos com um destaque no texto, é necessário escrever o código em questão entre três \` (crases).

Comando:

*       ```print ("Código de Exemplo")```

Resultado

*   ```
        print ("Código de Exemplo")
    ```

Neste tipo de citação, é possível também especificar a linguagem que estará sendo citada, para que o Markdown "estileze" o mesmo com algumas cores, para melhor vizualização do código.

Para esta validação, logo após as três \` (crases) iniciais, deve-se informar o nome da linguagem em questão, conforme exemplo abaixo:

Exemplos:

*       ```python
            # Código em python
            print ("Texto de exemplo em MarkDown")
        ```

Resultaods:

* Código **Python**

```python
import os, subprocess

# Abrir o Chrome
subprocess.Popen([r"C:\Program Files\Google\Chrome\Application\chrome.exe"])

# Abrir Calculadora
os.system('calc.exe')
```

* Código **C++**

```c++
int continua, contador;
continua = 's';
contador = 0;

while (continua == 's')  // enquanto for igual a 's'
{
// comandos a serem repetidos

   printf("Repentindo....\n");

   contador = contador + 1;

   printf("Tecle 's' se deseja continuar\n");
   continua = getch();
}

if (contador == 0)
   printf("O bloco NAO foi repetido.");
else printf("O bloco foi repetido %d vezes", contador);
```

* Código HTML

```html
<!DOCTYPE html>
<html lang="pt_BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>Exemplo</p>
</body>
</html>
```


<hr>

### Listas

É posível criar uma lista não ordenada ao utilizar em uma ou mais linhas ao utilizar no inicio de uma lonha, - ou * antes de um texto, separando-os por um espaço.

Exemplo:

- George Washington
- John Adams
- Thomas Jefferson

Para ordenar a lista, colocar um número na frente de cada linha.

Exemplo: 

1. Primeiro item da lista
    - Primeiro item de lista aninhado
        - Segundo item de lista aninhada
2. Segundo item da lista
    - Primeiro item da segunda lista aninhado
        - Segundo item da segunda lista aninhada


<hr>

### Títulos

É possível definir títulos em Markdown ao utilizar o caractere # no inicio da linha, separando o mesmo do texto a esquerda ao utilizar um espaço.
Existem também, seis níveis de títulos, assim como no HTML conforme exemplos abaixo.

Exemplos:

# Título de nível 1
## Título de nível 2
### Título de nível 3
#### Título de nível 4
##### Título de nível 5
###### Título de nível 6

<hr>

