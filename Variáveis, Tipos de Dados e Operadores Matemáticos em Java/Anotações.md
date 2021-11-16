# **1 Conceituação e Criação**

São quatro tipos de variáveis:

- Instância: objeto
- Classe: classe
- Local: dentro dos métodos
- Parâmetro: na assinatura do método

Padrão de definição:

- Visibilidade: public, protected e private
- Modificador: static e final
- Tipo de dado
- Nome: nome que é fornecido a variável
- Valor inicial: valor inicial, caso deseje

Convenções e regras:

- Não devem começar com números
- $ e _ devem ser evitados
- São case-sensitive
- Sem espaços
- Não pode ser as palavras reservadas Java



Boas práticas

- Sempre começar com letra minúscula
- Nomes expressivos
- Notação camelo
- Quando constante (final) maiúscula e separada por _

# **2 Tipos de Dados**

São os valores e consequentemente operações que as variáveis podem assumir e sofrer, respectivamente.

Tipificação:

- Estática (forte) vs Dinâmica (fraco)
- Primitivo vc Composto

Opções de tipos:

- Textual
- Numeral
- Lógico
- Objeto

Exemplos numeral:

- byte
- short
- int
- long
- float
- double

Exemplos textual:

- char
- String

Exemplo lógico:

- boolean

Boas práticas

Usar de forma adequada cada tipo de dado para cada informação

# **3 Operadores Aritméticos**

São símbolos especiais quais são capazes de realizar ações específicas em um, dois ou mais operandos e, em seguida, retornar um esultado.

Tipos:

- pós-fixado: expressão++ ou expressão--
- prefixado: ++expressão ou --expressão
- aritmético:+, -, *, / e %
- atribuição: =, +=, -=, *=, /= e %=



# **4 Conversões (casting)**

É a transformação de uma determinada variável de tipo menos específico para um tipo mais específico ou vice-versa.

Tipos:

- Upcast (implícito)
- Downcast (explícito)



 Para fazer castings explícitos é necessário colocar o nome da variável = (novo tipo de dado)valor da variável.