# SCl�nico: guia de uso

## �ndice:
  1. [Alimenta��o](#alimenta��o)
  2. [Elimina��o](#elimina��o)
     1. [**[Foco:] Elimina��o Intestinal**](#foco-elimina��o-intestinal)
     2. [**[Foco:] Elimina��o Urin�ria**](#foco-elimina��o-urin�ria)


## Alimenta��o
### Foco: Elimina��o Intestinal
* Quando o que queremos � manter uma vigil�ncia do n�mero de dejec��es, n�o devemos abrir um foco onde declaramos o utente como incontinente intestinal

_Porqu�?:_  Porque o foco n�o permite a cria��o de um diagn�stico correcto, por falta de parametriza��o

``` 
/* evitar */

Usar o foco

```

``` 
/* recomendado*/

Usar o foco "Obstipa��o" e avaliar "Avaliar Risco de Obstipa��o"
Um utente acamado, por exemplo, vai ter risco de obstipa��o.

Seleccionar pelo menos as seguintes interven��es:
- [x] Vigiar elimina��o intestinal (Sem hor�rio)
- [x] Avaliar Risco de Obstipa��o (3/3 dias) 
 - Nesta avalia��o devo consultar as "Vigil�ncias" e ver a frequ�ncias das dejec��es nos �ltimos 3 dias
```

## Elimina��o
### Foco: Elimina��o Urin�ria
* Quando o que queremos � manter uma vigil�ncia do n�mero e caracteristicas das mic��es, n�o devemos abrir um foco onde declaramos o utente como incontinente urin�rio

_Porqu�?:_  1� Porque o foco n�o permite a cria��o de um diagn�stico correcto, por falta de parametriza��o

``` 
/* evitar */

Usar o foco

```

``` 
/* recomendado*/

Usar o foco "Macera��o" e avaliar "Avaliar Risco de Macera��o"
Um utente que use fralda e tenha uma elevada frequ�ncia urin�ria, fica exposto a um maior risco de macera��o da pele perineal.

Seleccionar pelo menos as seguintes interven��es:
- [x] Vigiar elimina��o urin�ria(Sem hor�rio)
- [x] Optimizar fralda (Sem hor�rio)
 - Verificar se est� funcional, e bem adaptada ao utente
- [x] Trocar fralda (SOS)
 - Deve ficar em SOS pela impossibilidade de prever a hora das mic��es
- [x] Avaliar Risco de Macera��o(SOS) 

```

