# diagnostico-de-pacientes-com-pneumonia


Este projeto implementa e treina uma Rede Neural Convolucional (CNN) para classificar imagens de Raio-X de tórax como NORMAL ou PNEUMONIA.

O principal foco deste trabalho foi resolver o desbalanceamento de classes inerente ao conjunto de dados original e a falta de confiabilidade no conjunto de validação, visando otimizar as métricas de diagnóstico, especialmente o Recall (Sensibilidade).

Conjunto de DadosO dataset utilizado consiste em imagens de Raio-X de tórax.Origem: Dataset Kaggle: Chest X-Ray Images (Pneumonia)

Pré-processamento: Todas as imagens foram convertidas para escala de cinza (grayscale) e redimensionadas para 224x224 pixels.

Estrutura Final do Conjunto de DadosPara garantir um treinamento justo e uma avaliação confiável, foi aplicada a técnica de Undersampling (Subamostragem)

Metodologia e TreinamentoO modelo utilizado é uma CNN simples (Sequential Model) com camadas Conv2D, MaxPooling2D e Dropout, treinado ao longo de 23 épocas.E

estrategias para reduzir o overfitting: Dropout, rotações e zons aleatorios para aumentar o conjunto de treinamento.

utilizei o tensorflow e keras
