as ações criminais serão disponiveis por meio de um sistema de nivel, determinado pelo mafioso que estiver fazendo a ação, o algoritimo será o nivel de aptidão no tipo da ação sobre o nivel geral


em caso de assalto por exemplo

```js
let competencia = mafioso.nivel.assalto + (mafioso.nivel.geral / 2) //exemplo

if (requisito < competencia) {
	actions.assalt(mafioso)
}

```

as ações e tipos são:

vender droga
roubar transeunte
roubar carro
roubar loja de armas
roubar restaurante
roubar carro forte
cobrar a segurança
vandalizar região
batedor (procurar informações)
roubar loja de quimicos / farmacia

evento:
assasinar alguem
mandar um recado

atacar outra familia
tomar restaurante
tomar refinaria

vingança
entregar um corvo morto
assassinar alguem da familia


| **Ação**                             | **Tipo**           | **Requisito**                                                  | **Causa/Efeito**                                                                              | **Estatísticas Envolvidas pela Ação** |
| ------------------------------------ | ------------------ | -------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------- |
| **Vender droga**                     | Administrativo     | Recursos de refinaria                                          | Transforma recursos de droga em recursos de dinheiro sujo a uma taxa de conversão estatística | Gestão, stealth                       |
| **Roubar transeunte**                | Assalto            | Nenhum                                                         | Rouba pessoas, perdendo moral e ganhando dinheiro sujo                                        | Força, assalto, violência             |
| **Roubar carro**                     | Assalto            | Nenhum                                                         | Rouba carros, perdendo moral e ganhando dinheiro sujo                                         | Força, assalto, violência             |
| **Roubar loja de armas**             | Assalto            | Nenhum                                                         | Recebe recursos de munições e chance de receber armas                                         | Violência, assalto, estratégia        |
| **Roubar restaurante**               | Assalto            | Nenhum                                                         | Rouba dinheiro sujo de restaurantes                                                           | Violência, assalto, estrategia        |
| **Roubar carro forte**               | Assalto            | evento (sorte ou informação privilegiada)                      | Ganha grande quantidade de dinheiro sujo, mas alerta as autoridades                           | Estratégia, assalto, força            |
| **Cobrar a segurança**               | violencia          | 1 vez por tempo (a definir)                                    | recolhe o dinheiro (sujo) da região, a depender de sua influencia                             | Gestão, violência, persuasão          |
| **Vandalizar região**                | violencia          | Nenhum                                                         | diminui o preço medio dos imoveis e construções por um tempo limitado                         | violencia, força                      |
| **Batedor**                          | Espionagem, rivals | Influência local                                               | Obtém informações sobre famílias ou negócios adversários                                      | Gestão, stealth, persuasão            |
| **Roubar loja de químicos/farmácia** | Assalto            | nenhum                                                         | Obtém itens para fabricação de drogas                                                         | Estratégia, assalto, gestão           |
| **Assassinar alguém**                | evento             | pedido ou ordem de missão                                      | Remove um alvo específico, mas aumenta o risco de retaliação                                  | Violência, stealth, estratégia        |
| **Mandar um recado**                 | evento             | pedido ou ordem de missão                                      | Intimida e da porrada em alguem especifico, diminuindo sua moral                              | violencia, estrategia                 |
| **Atacar outra família**             | rivals             | corvo ou planejamento                                          | efeito cross player                                                                           | Estratégia, violência, assalto        |
| **Tomar restaurante**                | rivals             | encontrar e diminuir segurança de restaurante de outra familia | recebe um restaurante com 1 nivel a menos do tomado                                           | Gestão, violência, estratégia         |
| **Tomar refinaria**                  | rivals             | encontrar e diminuir segurança de refinaria de outra familia   | recebe uma refinaria com 1 nivel a menos do tomado                                            | Gestão, violência, estratégia         |
| **Vingança**                         | rivals             | ter enviado um corvo ou ter sido atacado por assasinato        | tenta matar um mafioso da familia rival                                                       | Violência, stealth, estratégia        |
| **Entregar um corvo morto**          | rivals             | ter sido atacado                                               | declara guerra contra outra familia                                                           | Estratégia, persuasão, violencia      |
| **Assassinar alguém da família**     | rivals             | entregar o corvo                                               | mata um mafioso da familia rival                                                              | Violência, stealth, estratégia        |
