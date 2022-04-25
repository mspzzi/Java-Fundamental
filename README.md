# 📔 Variáveis, Tipos de Dados e Operadores Matemáticos em Java

O que é uma variável - um espaço na memória do computador onde se pode guardar valores.

Existem 4 tipos:

- Instância: objeto

- Classe: classe

- Local: dentro de métodos

- Parâmetro: na assinatura do método

##  Criação
###### Padrão de definição:

visibilidade, modificador, tipo, nome, valorInicial.

- V: “public”, “protected”, “private”

- M: “static”, “final”

- T: tipo de dado 

- N: nome que é fornecido a variável 

- VI: um valor inicial, caso deseje


###### Regras:

- Não devem começar com números;

- “$” e “_” devem ser evitados;

- São case-sensitive;

- Sem espaços;

- Não pode ser as palavras reservadas do Java.

###### Boas práticas:

- Sempre começar com letra minúscula,

- Nomes expressivos;

- Notação camelo; (ex: quantidadeProduto)

- Quando constante(final) maiúscula e separada por “_”. (ex: NUMERO_TENTATIVAS = 5)

## Tipos de Dados

“São os valores e consequentemente operações que as variáveis podem assumir e sofrer, respectivamente.”

#### Tipificação:

- Estática(forte) vs Dinâmica(fraco)

- Primitivo vs Composto

#### Opções de tipos:

- Textual

- Numeral

- Lógico

- Objeto

###### Exemplos textual:

- char: caracteres de 16-bit unicode -> char c = ‘/0084’; ou char c = ‘T’;

- String: um tipo “especial” -> String s = “T”;


###### Exemplos numeral:

- byte: -128 até 127 -> byte b = 15;

- short: -32.768 até 32.767 -> short s = -15785;

- int: -2.147.483.648 até 2.147.483.647 -> int i = 8515785;

- long: -9.223.372.036.854.775.808 até 9.223.372.036.854.775.808 -> long l = 5938515785L;

- float: ±3.40282347E+38F -> float f = 3.14…(f);

- double: ±1.79769313486231570E+308 -> double d = 3.14… (d);


###### Exemplo lógico:

- boolean: true e false -> boolean s = false;


