## **1 Operadores Relacionais**

São símbolos especiais quais são capazes de realizar comparações entre determinados operandos e, em seguida, retornar um resultado.

Tipos:

- Similaridade: igual, diferente
- Tamanho: maior, maior igual, menor, menor igual

Simbologia

- Igualdade: ==
- Diferença: !=
- Maior: >
- Maior igual: >=
- Menor: <
- Menor igual: <=

## **2 Operadores Lógicos**

São símbolos especiais quais são capazes de realizar comparações lógicas entre operandos lógicos ou expressões e, em seguida, retorna um resultado.

Tipos:

- Conjunção
- Disjunção
- Disjunção exclusiva
- Negação

Conjunção: operação lógica que só é verdadeira quando ambos os operandos ou expressões envolvidas são verdade

Simbologia: &&

Terminologia: and (e)

 Disjunção: operação que só é falsa quando ambos os operandos ou expressões envolvidas são falsos

Simbologia: ||

Terminologia: or (ou)

Disjunção exclusiva: operação que só é verdade quando ambos os operandos ou expressões são opostos

Simbologia: ^

Terminologia: xor

Negação: operação que inverte o valor lógico de um operando ou expressão

Simbologia: !

Terminologia: inversão

- Operadores bitwise: & e | (não são operadores lógicos)
- Operadores shift: ~, >>, >>>, << (não são operadores lógicos)

Boas práticas

Crie variáveis auxiliares para guardar resultados intermediários



## **3 Controle de fluxo**

São estruturas que tem a capacidade de direcionar o fluxo da execução do código.

Tipos:

- Decisão: if, if-else, if-else-if, switch e operador ternário
- Repetição: for, while, do while
- Interrupção: break continue e return

Decisão: estrutura que avalia uma condição booleana ou variável para direcionar o fluxo de execução

Opções: if (se), switch (escolha) e operador ternário

![img](en-cache://tokenKey%3D%22AuthToken%3AUser%3A161997714%22+ab976d91-8905-766d-ec2c-cbf7fa2cf59c+71decc3f782a23c95cad5e36fb07a454+https://www.evernote.com/shard/s365/res/e1d1f1c5-f7fe-3ba8-d19d-d53ea306e666)![img](en-cache://tokenKey%3D%22AuthToken%3AUser%3A161997714%22+ab976d91-8905-766d-ec2c-cbf7fa2cf59c+2934c9ab538fcfa00a2ce0f089580436+https://www.evernote.com/shard/s365/res/fb8c8a0e-f87a-cdc2-db6f-815f3c69916a)![img](en-cache://tokenKey%3D%22AuthToken%3AUser%3A161997714%22+ab976d91-8905-766d-ec2c-cbf7fa2cf59c+143090fe7dff7ea92f26aaca1239cb89+https://www.evernote.com/shard/s365/res/e8f41323-ecce-9ce2-ad63-34211d5116e6)![img](en-cache://tokenKey%3D%22AuthToken%3AUser%3A161997714%22+ab976d91-8905-766d-ec2c-cbf7fa2cf59c+ee8fb8ab423b86e519f6a177c01c0bdc+https://www.evernote.com/shard/s365/res/973f4cbb-3136-082e-a4d0-a9518316df1c)![img](en-cache://tokenKey%3D%22AuthToken%3AUser%3A161997714%22+ab976d91-8905-766d-ec2c-cbf7fa2cf59c+ebec5f0d32f68d3bba41560f4b9901b9+https://www.evernote.com/shard/s365/res/0d82565e-ef35-a02b-22e1-a418f7452241)

Boas práticas

- Switch é para valores exatos e if para expressões booleanas
- Evitar usar default do switch para "casos genéricos"
- Evitar o efeito "flecha" dos if's
- Evitar muitos if's aninhados
- Usar a boa prática da aula 2 para diminuir o tamanho do if

## **Blocos**

É um grupo de 0 ou mais códigos quais trabalham em conjunto para executar uma operação.

Tipos:
- Locais: dentro de métodos
- Estáticos: dentro de classes
- Instância: dentro de classes

Locais:

	{
	
	...
	
	}