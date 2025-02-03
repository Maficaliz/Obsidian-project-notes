tecnicamente será o "personagem principal", a sua familia é você jogador, pois os mafiosos podem morrer, serem presos ou sairem da familia, então seu papel é de gestão de pessoas.

a familia vive enquanto tiver ao menos 1 mafioso, se não tiveres mais nenhum você deu conta de perder no jogo kkkkkk


no geral as coisas armazenadas ao[ banco de dados do player](players) afeta a familia


```ts
mafioso[]

for each{
	mafioso.moral // propria moral  -100 0 100
	mafioso.influencia // o quanto ele é importante na familia
}


familia.moral (
	mafiosos.map(mafioso.influencia * mafioso.moral)
)
```