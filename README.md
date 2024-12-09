Avaliação da Detecção de Árvores Urbanas em Imagens Aéreas com RT-DETR

A detecção de objetos em tempo real é uma tecnologia essencial para diversas aplicações, incluindo monitoramento ambiental e planejamento urbano. Dentro dessas aplicações, a detecção precisa de copas de árvores urbanas em imagens aéreas tem ganhado crescente importância. As árvores desempenham um papel fundamental na sustentabilidade das cidades, contribuindo para a mitigação de impactos ambientais, a melhoria da qualidade do ar e o planejamento eficiente de áreas verdes. Contudo, a detecção rápida e precisa dessas estruturas enfrenta desafios significativos, especialmente em cenários de alta densidade urbana.
Modelos de aprendizado profundo, como o YOLO (You Only Look Once) e o DETR (Detection Transformer), têm sido amplamente utilizados para essa tarefa devido à sua eficiência e precisão. No entanto, o equilíbrio entre alta acurácia e velocidade de inferência continua sendo uma limitação importante, especialmente em sistemas que exigem respostas em tempo real. Nesse cenário, surge o RT-DETR, uma versão otimizada do DETR, projetada para superar esses desafios. Apresentado no estudo "DETRs Beat YOLOs on Real-time Object Detection" (Zhao et al., 2024), o RT-DETR combina alta precisão com eficiência computacional, posicionando-se como uma alternativa promissora aos modelos tradicionais.

Este trabalho explora o desempenho do RT-DETR na detecção de copas de árvores urbanas, utilizando um subconjunto adaptado do conjunto de dados COCO. Foram avaliadas quatro variantes do modelo—rtdetr_r18vd_6x_coco, rtdetr_r34vd_6x_coco, rtdetr_r50vd_dsp_6x_coco e rtdetr_r101vd_6x_coco—com base na métrica de Precisão Média (AP50), amplamente empregada para quantificar a eficácia de modelos de detecção. Os resultados revelaram que a variante rtdetr_r101vd_6x_coco obteve o melhor desempenho, alcançando um AP50 de 0.768 no conjunto de validação e 0.749 no conjunto de teste, destacando-se pela sua capacidade de generalização e precisão em contextos urbanos.
Além disso, os resultados obtidos foram comparados com benchmarks estabelecidos, como o YOLO, evidenciando a superioridade do RT-DETR tanto em termos de acurácia quanto de velocidade de inferência. Esses achados ressaltam o grande potencial do RT-DETR para aplicações de monitoramento ambiental e urbano, abrindo novas possibilidades para estudos futuros em cenários mais complexos e variados.

Nos arquivos abaixo, temos os resultados para cada modelo:
  rtdetr_r18vd_6x_coco, 
  rtdetr_r34vd_6x_coco, 
  rtdetr_r50vd_dsp_6x_coco e 
  rtdetr_r101vd_6x_coco

Logo em seguida se utilizou os resultados obtidos em cada modelo para a geração dos gráficos, que se encontram no link a seguir:
  gráficos_tabelas_novaversao

