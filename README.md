# RECONHECIMENTO DE EPI

`PPC-CC: PUC Poços de Caldas - Ciência da Computação`
`Disciplina: VISÃO COMPUTACIONAL`
`2024 - Semestre 2`

## Integrantes

- Luanne Zati de Lima

## Professor

- Will Machado

# Documentação

<ol>
<li><a href="docs/1-Documentação de Contexto.md"> Documentação de Contexto</a></li>
  Projeto visa identificar a presença de pessoas que utilizam ou não EPI (Equipamento de Proteção Individual).
Os projeto possui 3 códigos, um que faz a identificação através da webcan, outro que faz a detecção na própria tela do computador e no outro código
 foi desenvolvido uma API que permite carregar imagens, que faz o reconhecimento de pessoas utilizando EPI, ou não.
 Para esse projeto, foi utilizado o modelo "datsetpropriov2.pt" do repositório [EzPoint](https://github.com/rodriguezruan/EzPoint/tree/main/Vis%C3%A3o%20Computacional%20%2B%20Firestore).
 Esse projeto foi desenvolvido para a matéria: Visão Computacional do curso de ciência da computação da Puc Minas.
  

<li><a href="docs/6-Template padrão do Site.md"> Template padrão do Site</a></li>
![image](https://github.com/user-attachments/assets/4ae72149-9755-4f14-8a7e-4ec3d117c657)

<li><a href="docs/7-Programação de Funcionalidades.md"> Programação de Funcionalidades</a></li>
Reconhecimento dentro de fábricas, industrias e laboratório o uso correto de equipamentos de proteção individual dos funcionários, com a finalidade de evitar acidentes de trabalho nesses ambientes.

<li><a href="docs/9-Registro de Testes de Software.md"> Registro de Testes de Software</a></li>
Conclusões sobre o teste do modelo

Precisão geral: 0.79 (muito bom, o modelo evita muitas predições erradas).
Recall geral: 0.543 (moderado; há objetos reais que o modelo não está detectando).
mAP50 geral: 0.655 (bom desempenho considerando o limiar de IoU de 0.5).
mAP50-95 geral: 0.432 (desempenho cai com limiares mais rigorosos, sugerindo que o modelo precisa melhorar em casos mais complexos).

Conclusões sobre o teste do modelo
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


Conclusões sobre o teste do modelo
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


Conclusões sobre o teste do modelo
Óculos:
Precisão: 0.84 (muito bom).
Recall: 0.61 (bom, detecta uma boa parte dos óculos reais).
mAP50: 0.754 (muito bom).
mAP50-95: 0.411 (moderado, mas cai em limiares mais altos).



<li><a href="docs/10-Plano de Testes de Usabilidade.md"> Plano de Testes de Usabilidade</a></li>
Conclusões sobre o teste do modelo
O modelo está se saindo bem com capacetes, máscaras e óculos. Estes itens têm boa precisão e recall.
O desempenho com coletes é moderado, mas ainda razoável.
O desempenho com luvas é o ponto mais fraco, tanto na precisão quanto no recall. Isso pode ser devido a:
Poucas amostras de luvas no dataset.
Variabilidade nas imagens (diferentes tipos de luvas, iluminação, ou poses).
Necessidade de mais refinamento no treinamento.

<li><a href="docs/12-Apresentação do Projeto.md"> Apresentação do Projeto</a></li>
![Captura de tela 2024-11-16 165044](https://github.com/user-attachments/assets/61841cae-1807-46c3-858c-2bc6676da61f)

<li><a href="docs/13-Referências.md"> Referências</a></li>
[EzPoint](https://github.com/rodriguezruan/EzPoint/tree/main/Vis%C3%A3o%20Computacional%20%2B%20Firestore)
</ol>

# Código

<li><a href="src/README.md"> Código Fonte</a></li>

# Apresentação

<li><a href="presentation/README.md"> Apresentação da solução</a></li>
