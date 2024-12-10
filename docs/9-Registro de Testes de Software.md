# Registro de Testes de Software


Capacete:
Precisão: 0.917 (excelente, o modelo comete poucos erros ao detectar capacetes).
Recall: 0.752 (bom, está detectando a maioria dos capacetes reais).
mAP50: 0.865 (muito bom, limiar de 0.5).
mAP50-95: 0.574 (bom, mas ainda pode melhorar para limiares mais altos).
Colete:
Precisão: 0.796 (bom, mas há margem para redução de falsos positivos).
Recall: 0.532 (moderado, o modelo não está capturando muitos coletes reais).
mAP50: 0.665 (razoável).
mAP50-95: 0.483 (poderia melhorar para casos mais desafiadores).

Luvas:
Precisão: 0.498 (fraco, o modelo faz muitas predições erradas sobre luvas).
Recall: 0.0909 (muito baixo, o modelo quase não detecta luvas reais).
mAP50: 0.158 (fraco).
mAP50-95: 0.0831 (muito baixo, dificuldade em lidar com luvas).
Máscara:
Precisão: 0.901 (excelente).
Recall: 0.729 (bom, detecta muitas máscaras reais).
mAP50: 0.832 (muito bom).
mAP50-95: 0.608 (bom, mesmo em limiares mais rigorosos).

Óculos:
Precisão: 0.84 (muito bom).
Recall: 0.61 (bom, detecta uma boa parte dos óculos reais).
mAP50: 0.754 (muito bom).
mAP50-95: 0.411 (moderado, mas cai em limiares mais altos).

## Avaliação

Conclusões sobre o teste do modelo
O modelo está se saindo bem com capacetes, máscaras e óculos. Estes itens têm boa precisão e recall.
O desempenho com coletes é moderado, mas ainda razoável.
O desempenho com luvas é o ponto mais fraco, tanto na precisão quanto no recall. Isso pode ser devido a:
Poucas amostras de luvas no dataset.
Variabilidade nas imagens (diferentes tipos de luvas, iluminação, ou poses).
Necessidade de mais refinamento no treinamento.
Precisão geral: 0.79 (muito bom, o modelo evita muitas predições erradas).
Recall geral: 0.543 (moderado; há objetos reais que o modelo não está detectando).
mAP50 geral: 0.655 (bom desempenho considerando o limiar de IoU de 0.5).
mAP50-95 geral: 0.432 (desempenho cai com limiares mais rigorosos, sugerindo que o modelo precisa melhorar em casos mais complexos).
