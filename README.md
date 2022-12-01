# Aprendendo variáveis e operadores.

## Programa para calcular o valor gasto em uma viagem de carro.

```ruby
/* calcular quanto custa uma viagem de carro

  variaveis: 
  1 - preço do combustivel
  2 - gasto medio de combustivel por km
  3 - distancia em km da viagem

  */

  const precoComb = 5.25;
  const gastoMedioCombPorKm = 14.7;
  const distKm = 3662;

  const litrosGastos = distKm / gastoMedioCombPorKm;
  const reaisGastos = litrosGastos * precoComb
  
  console.log(reaisGastos.toFixed(2))
```
