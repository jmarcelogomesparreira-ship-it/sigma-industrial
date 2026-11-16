# SIGMA Industrial

Painel de operação de uma usina de açúcar e etanol, com dados simulados: planta 3D, moenda, caldeira e energia, fábrica de açúcar, fermentação, destilaria, laboratório, perdas, manutenção, pessoas e segurança.

Abra o `index.html` no navegador ou publique pelo GitHub Pages. Não precisa instalar nada.

## Origem do dado

Cada indicador mostra de onde vem o valor:

- **Online**: instrumento de campo. Atualiza a cada 2 s.
- **Laboratório**: análise de amostra. O valor fica parado até sair o próximo resultado e mostra a hora da análise, o analista e quando sai a próxima.
- **Calculado**: obtido a partir de outras variáveis (balanço).

## Laboratório: pontos sem medição online

Esses são os pontos que hoje dependem só do laboratório:

- Etanol na vinhaça, com a perda em L/dia e em R$/dia
- Pol da torta de filtro, com o açúcar perdido em sacas/dia e em R$/dia
- Qualidade do açúcar (pol, cor ICUMSA, umidade) por lote
- Físico-química das 8 dornas: teor alcoólico, ART residual, pH, acidez, Brix, viabilidade, brotamento e bastonetes

O formulário **Lançar análise** registra um resultado. O valor entra na hora no painel, nos alarmes e no cálculo de perdas.

Os preços usados nas perdas (etanol R$ 2,85/L, açúcar R$ 125/saca) são referências simuladas.
