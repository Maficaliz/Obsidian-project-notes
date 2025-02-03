
para converter dinheiro sujo em dinheiro limpo precisa ter um negocio que faça isso.

todos os negocios vão ter sua propria "intenção" mas vão servir para tudo basicamente.

os negocios "restaurante italiano" e "cassinos" vão ser os melhores para a lavagem de dinheiro passiva

algoritimo de lavagem de dinheiro
```ts
let toWash = washing ? money.dirt < washing : money.dirt // seleciona a capacidade
money.clear += toWash - payout // payout vem de algoritimo de contabilidade
money.dirt -= toWash - payout
```

```ts
const wash = (toWash : number) => {
	money.dirt -= toWash
	money.clear += toWash
}
```

o payout é um valor que deduz no processo de lavagem de acordo com a gerencia contabil da familia