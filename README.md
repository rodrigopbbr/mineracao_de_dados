## Exemplo com o Dataset Titanic

Contém 891 passageiros reais do Titanic que afundou em 15/04/1912 matando 1502 de 2224 passageiros e tripulação que estavam a bordo.

- `survived`: *dummy* `0` ou `1`

- ```
  pclass
  ```

  : Classe do Passageiro

  - `1`: Primeira Classe
  - `2`: Segunda Classe
  - `3`: Terceira Classe

- `sex`: Sexo `male` ou `female`

- `age`: Idade

- `sibsp`: Número de Irmãos (*Siblings*) e Esposas (*spouse*) a bordo

- `parch`: Número de pais/filhos a bordo

- `fare`: Valor pago pela passagem em libras

- ```
  embarked
  ```

  : Porto que embarcou

  - `C`: Cherbourg
  - `Q`: Queenstown
  - `S`: Southampton)

- `class`: Mesmo que `pclass` só que em texto

- `adult_male`: *dummy* para `age > 16` e `sex == 'male'`

- `deck`: Qual deck a cabine do passageiro se situava

- `alive`: Mesmo que survived só que com `yes` ou `no`

- `alone`: *dummy* para se viajava sozinho