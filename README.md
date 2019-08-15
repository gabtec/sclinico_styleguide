# SClínico: guia de uso

## Índice:
  1. [Alimentação](#alimentação)
  2. [Eliminação](#eliminação)
     1. [**[Foco:] Eliminação Intestinal**](#foco-eliminação-intestinal)
     2. [**[Foco:] Eliminação Urinária**](#foco-eliminação-urinária)


## Alimentação
### Foco: Eliminação Intestinal
* Quando o que queremos é manter uma vigilância do número de dejecções, não devemos abrir um foco onde declaramos o utente como incontinente intestinal

_Porquê?:_  Porque o foco não permite a criação de um diagnóstico correcto, por falta de parametrização

``` 
/* evitar */

Usar o foco

```

``` 
/* recomendado*/

Usar o foco "Obstipação" e avaliar "Avaliar Risco de Obstipação"
Um utente acamado, por exemplo, vai ter risco de obstipação.

Seleccionar pelo menos as seguintes intervenções:
- [x] Vigiar eliminação intestinal (Sem horário)
- [x] Avaliar Risco de Obstipação (3/3 dias) 
 - Nesta avaliação devo consultar as "Vigilâncias" e ver a frequências das dejecções nos últimos 3 dias
```

## Eliminação
### Foco: Eliminação Urinária
* Quando o que queremos é manter uma vigilância do número e caracteristicas das micções, não devemos abrir um foco onde declaramos o utente como incontinente urinário

_Porquê?:_  1º Porque o foco não permite a criação de um diagnóstico correcto, por falta de parametrização

``` 
/* evitar */

Usar o foco

```

``` 
/* recomendado*/

Usar o foco "Maceração" e avaliar "Avaliar Risco de Maceração"
Um utente que use fralda e tenha uma elevada frequência urinária, fica exposto a um maior risco de maceração da pele perineal.

Seleccionar pelo menos as seguintes intervenções:
- [x] Vigiar eliminação urinária(Sem horário)
- [x] Optimizar fralda (Sem horário)
 - Verificar se está funcional, e bem adaptada ao utente
- [x] Trocar fralda (SOS)
 - Deve ficar em SOS pela impossibilidade de prever a hora das micções
- [x] Avaliar Risco de Maceração(SOS) 

```

