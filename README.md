# Avaliação da Detecção de Árvores Urbanas em Imagens Aéreas com RT-DETR

A detecção de objetos em tempo real é uma tecnologia essencial para diversas aplicações, incluindo monitoramento ambiental e planejamento urbano. Dentro dessas aplicações, a detecção precisa de copas de árvores urbanas em imagens aéreas tem ganhado crescente importância. As árvores desempenham um papel fundamental na sustentabilidade das cidades, contribuindo para:

- Mitigação de impactos ambientais,
- Melhoria da qualidade do ar,
- Planejamento eficiente de áreas verdes.

Contudo, a detecção rápida e precisa dessas estruturas enfrenta desafios significativos, especialmente em cenários de alta densidade urbana.

## Contexto Tecnológico

Modelos de aprendizado profundo, como o **YOLO (You Only Look Once)** e o **DETR (Detection Transformer)**, têm sido amplamente utilizados para a detecção de objetos devido à sua eficiência e precisão. Entretanto, o equilíbrio entre alta acurácia e velocidade de inferência continua sendo uma limitação importante, especialmente em sistemas que exigem respostas em tempo real.

Nesse cenário, surge o **RT-DETR**, uma versão otimizada do DETR, projetada para superar esses desafios. Apresentado no estudo *"DETRs Beat YOLOs on Real-time Object Detection"* (Zhao et al., 2024), o RT-DETR combina:

- Alta precisão,
- Eficiência computacional.

Essas características posicionam o RT-DETR como uma alternativa promissora aos modelos tradicionais.

## Objetivo

Este trabalho explora o desempenho do **RT-DETR** na detecção de copas de árvores urbanas, utilizando um subconjunto adaptado do conjunto de dados COCO.

## Metodologia

Foram avaliadas quatro variantes do modelo RT-DETR com base na métrica de Precisão Média (**AP50**), amplamente empregada para quantificar a eficácia de modelos de detecção:

1. **rtdetr_r18vd_6x_coco**  
2. **rtdetr_r34vd_6x_coco**  
3. **rtdetr_r50vd_dsp_6x_coco**  
4. **rtdetr_r101vd_6x_coco**

## Resultados

Os resultados revelaram que a variante **rtdetr_r101vd_6x_coco** obteve o melhor desempenho:

- **Conjunto de validação:** AP50 = **0.768**  
- **Conjunto de teste:** AP50 = **0.749**

Este modelo destacou-se pela sua capacidade de **generalização** e **precisão** em contextos urbanos.

## Comparação com Benchmarks

Os resultados obtidos foram comparados com benchmarks estabelecidos, como o **YOLO**, evidenciando a superioridade do **RT-DETR** tanto em termos de:

- Acurácia,
- Velocidade de inferência.

## Conclusão

Esses achados ressaltam o grande potencial do RT-DETR para aplicações de monitoramento ambiental e urbano, abrindo novas possibilidades para estudos futuros em cenários mais complexos e variados.

---

## Documentação dos Resultados

### Arquivos de resultados dos modelos:

- [rtdetr_r18vd_6x_coco](#)  
- [rtdetr_r34vd_6x_coco](#)  
- [rtdetr_r50vd_dsp_6x_coco](#)  
- [rtdetr_r101vd_6x_coco](#)

### Gráficos e tabelas:

Os gráficos gerados a partir dos resultados podem ser acessados [aqui](#gráficos_tabelas_novaversao).

---
