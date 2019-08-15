# SClínico: recomendações de uso
###### Aviso: tratam-se de recomendações e não de um guia oficial de uso

## Índice:
  1. [Alimentação](#alimentação)
     1. [Coloquei uma SNG](#colocação-de-SNG)
  2. [Eliminação](#eliminação)
     1. [Uso do foco Eliminação Intestinal](#uso-do-foco-eliminação-intestinal)
     2. [Uso do foco Eliminação Urinária](#uso-do-foco-eliminação-urinária)
     3. [O utente traz sonda vesical do domicilio](#sonda-vesical-domicilio)


## Alimentação

### Colocação de SNG
> *FOCO:* Deglutição
> *Avaliação Diagnóstica:* Avaliar deglutição (basta registar os que têm asterisco vermelho)
> *Diagnóstico:* Deglutição comprometida, me grau elevado

* Quando se coloca uma SNG porque o utente não deglute (e.g. por estar prostrado ou comatoso)
* Outra forma de registar é quando o médico prescreve "Intubação nasogástrica" (será abordado futuramente)
* Outra forma de registar é quando o utente não ingere alimentos em quantidade e qualidade, para as suas necessidades (será abordado futuramente)

_Porquê?:_  Porque não deglutindo tem risco de aspiração de conteúdo alimentar para as vias aéreas
_Porquê?:_  Porque não deglutindo tem risco de desnutrição


``` 
/* recomendado*/

Usar o foco "Deglutição" e avaliar "Avaliar Deglutição"

Seleccionar pelo menos as seguintes intervenções:
- [x] Avaliar deglutição (SOS ou semanalmente, se for expectável que o diagnóstico se altere)
- [x] Inserir sonda gástrica (Agora)
- [x] Optimizar sonda gástrica (Sem horário)
- [x] Trocar sonda gástrica (Dia e hora fixa, e.g. 30 dias)
- [x] Vigiar referição (Sem horário)
  - Embora esta intervenção pareça não fazer sentido, permite registar que foi alimentado por SNG e escrever alguma outra observação em trexto normal (usar com ponderação)
```

```
/* recomendado */
Usar foco "Autocuidado: Comer"

... em construção ...
Intervenções:
- Alimentar por sonda (Sem horário)

```

[Back to top](#índice)

## Eliminação
### Uso do foco Eliminação Intestinal
##### FOCO: Obstipação
##### Avaliação Diagnóstica: Avaliar risco de obstipação

* Quando o que queremos é manter uma vigilância do número de dejecções, não devemos abrir um foco onde declaramos o utente como incontinente intestinal

_Porquê?:_  Porque o foco não permite a criação de um diagnóstico correcto, por falta de parametrização

``` 
/* evitar */

Usar o foco

```

``` 
/* recomendado*/

Usar o foco **"Obstipação"** e avaliar **"Avaliar Risco de Obstipação"**
Um utente acamado, por exemplo, vai ter risco de obstipação.

Seleccionar pelo menos as seguintes intervenções:
- [x] Vigiar eliminação intestinal (Sem horário)
- [x] Avaliar Risco de Obstipação (3/3 dias) 
  - Nesta avaliação devo consultar as "Vigilâncias" e ver a frequências das dejecções nos últimos 3 dias
```

[Back to top](#índice)

### Uso do foco Eliminação Urinária
##### FOCO: Maceração
##### Avaliação Diagnóstica: Avaliar risco de maceração

* Quando o que queremos é manter uma vigilância do número e caracteristicas das micções, não devemos abrir um foco onde declaramos o utente como incontinente urinário

_Porquê?:_  Porque o foco não permite a criação de um diagnóstico correcto, por falta de parametrização

``` 
/* evitar */

Usar o foco

```

``` 
/* recomendado*/

Usar o foco **"Maceração"** e avaliar **"Avaliar Risco de Maceração"**
Um utente que use fralda e tenha uma elevada frequência urinária, fica exposto a um maior risco de maceração da pele perineal.

Seleccionar pelo menos as seguintes intervenções:
- [x] Vigiar eliminação urinária (Sem horário)
- [x] Optimizar fralda (Sem horário)
  - Verificar se está funcional, e bem adaptada ao utente
- [x] Trocar fralda (SOS)
  - Deve ficar em SOS pela impossibilidade de prever a hora das micções
- [x] Avaliar Risco de Maceração (SOS, dado que o utente irá continuar a usar fralda e assim não é expectável que o risco se altere) 

```

[Back to top](#índice)

### Sonda Vesical Domicilio
##### FOCO: Infecção
##### Avaliação Diagnóstica: Avaliar risco de infecção

* Neste caso o Foco principal de atenção do enfermeiro é o Risco de Infecção (associado com a sonda vesical) 
* Outra preocupação é saber a data de colocação da sonda, bem como o tipo de sonda, para depois calcular a data da sua substituição

_Porquê?:_  Porque o simples facto de se ter uma sonda vesical já aumenta o risco de vir a ter uma infecção urinária
_Porquê?:_  Porque uma sonda vesical carece de cuidados de higiene e posicionamento do saco colector, diários
_Porquê?:_  Porque se a urina for concentrada, infere-se daí, uma diminuição da ingestão hidrica
_Porquê?:_  Porque se o utente apresentar piúria ou urina com odor fétido, infere-se daí, existência de infecção urinária

``` 
/* Recomendação 1*/

Dado que no SClínico, o consultar de informações prévias, nem sempre é fácil e intuitivo, 
sugere-se como boa prática, registar no campo de "Observações" da Avaliação Inicial, se 
tem sonda, que tipo, que tamanho e qual a data de colocação

```

``` 
/* Recomendação 2*/

Usar o foco "Infecção" e avaliar "Avaliar Risco de Infecção"

Seleccionar pelo menos as seguintes intervenções:
- [x] Optimizar cateter urinário (Sem horário) [NORMA]
  - Nas "Normas" deve ser selecionado:
	- algaliação crónica
  	- manter saco abaixo do nível
	- higiene no meato 
- [x] Trocar cateter urinário (Dia e turno fixo, e.g. 30dias após data de colocação)
- [x] Avaliar Risco de Infecção (SOS, dado que o utente irá manter a sonda e assim não é expectável que o risco se altere) 

```

``` 
/* Em Falta */

Associado com o diagnóstico de "Risco de Infecção presente (associado com sonda vesical)", 
deveria ser possível seleccionar a intervenção "Vigiar eliminação urinária" para se poder 
registar as características da urina. A presença de piúria, por exemplo, é sugestivo de infecção.

```

[Back to top](#índice)

