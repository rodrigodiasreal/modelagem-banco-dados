MER - Modelo Entidade Relacionamento.
DER - Diagrama Entidade Relacionamento. (Representação gráfica do MER).

O Diagrama facilita a comunicação entre todos.

Entidade é um objeto único no mundo real.
Exemplos>

Clientes de uma empresa.
Carros que são vendidos.
Departamento de vendas.

Tipos de relacionamentos:

Quando se tem dois relacionamentos: Relacionamento binário.
Quando se tem três relacionamentos: Relacionamento ternário.
Quando se tem quatro relacionamentos: Relacionamento N-ário.

Cardinalidade = Conectividade.

Atributos sempre são ligados a entidade.

Primeiramente se identifica a entidade e seus relacionamentos.

Os **atributos descrevem as propriedades das entidades**. Por exemplo, a entidade `pessoa` pode ter como atributos: `nome`,`data de nascimento`, `idade`, `endereço`. Assim como as entidades, também existem alguns tipos de atributos. São eles:

### Atributo simples

É um tipo de atributo indivisível, ou seja, é um atributo atômico. Um exemplo deste tipo é o atributo `CPF`, pois ele não pode ser dividido em partes menores para formar outros atributos.

### Atributo composto

Pode ser dividido em partes menores que representam outros atributos, como `endereço`. Ele pode ser subdividido em atributos menores, como: `cidade`,`estado`, `rua`, `CEP`.

### Atributo multivalorado

É aquele que pode ter um ou N (vários) valores associados a ele. Por exemplo: o atributo `telefone` de um cliente. Este pode ter um ou vários `telefones`.

### Atributo derivado e armazenado

Atributos derivados dependem de outro atributo ou até mesmo outra entidade para existir, como, `idade` e `data de nascimento`. Para descobrirmos a idade de uma pessoa, precisamos da sua `data de nascimento`. Então, consideramos o atributo `idade` como **derivado** do atributo `data de nascimento`, chamado, por sua vez, de atributo **armazenado**.

### Atributo chave

É utilizado para identificar de forma única uma entidade, ou seja, os valores associados a esse atributo são distintos entre o conjunto de entidades. Como exemplo, podemos utilizar o `Código do Produto`. Ele é único e pode ser utilizado como atributo chave, uma vez que cada produto recebe apenas um `Código` distinto.

Chaves:

Chave Primária - Valores não se repetem, não pode se repetir e apenas entidades fortes podem ter chave primária.

