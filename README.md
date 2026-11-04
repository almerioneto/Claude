# Comparador de carros: combustão × híbrido × elétrico

Calculadora em uma única página (`index.html`, sem dependências) que compara o custo de uso de
um carro a combustão, um híbrido (HEV ou plug-in) e um elétrico.

## Como usar

Abra o `index.html` no navegador e preencha:

1. **Trajeto e preços**: estado (define a alíquota de IPVA sugerida), km por dia, dias de uso por mês,
   km extras, % do trajeto na cidade, período em anos, preço da gasolina/etanol/diesel, tarifa de
   energia em casa, preço da recarga pública, % das recargas em casa, perdas na recarga e
   desvalorização anual (reduz a base do IPVA a cada ano).
2. **Quais carros**: escolha um modelo de exemplo ou digite nome, preço, alíquota de IPVA,
   consumo na cidade/estrada (km/l ou km/kWh), manutenção e seguro (opcionais).
   No híbrido plug-in, informe a % dos km rodados no modo elétrico.

## O que é calculado

- Custo de combustível/energia por mês e por km
- IPVA ano a ano (base desvalorizada)
- Custo total de uso, custo mensal e custo por km no período
- Compra + uso, e em quanto tempo a economia paga a diferença de preço em relação ao carro a combustão
- Gráfico do custo acumulado ao longo dos anos

Os dados ficam salvos no navegador para a próxima visita.

> Valores de exemplo e alíquotas de IPVA são aproximados — confira a tabela FIPE, o consumo do
> Inmetro (PBEV) e a Sefaz do seu estado.
