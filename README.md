# Projeto de Segmentação de Imagens com UNet

Este projeto foi desenvolvido como trabalho final para a disciplina de Inteligência Artificial da Universidade Católica de Petrópolis (UCP). O objetivo foi criar um modelo capaz de reconhecer e segmentar padrões em imagens utilizando Deep Learning.

## Estrutura do Projeto

- **data/**: Dados brutos e processados
- **models/**: Modelos treinados e históricos
- **results/**: Resultados de avaliação e predições
- **src/**: Scripts principais (download_dataset.py, train.py, evaluate.py, inference.py, unet_model.py)

## Requisitos

- Python 3.8+
- numpy, pandas, matplotlib, seaborn, scikit-learn, tensorflow, keras, opencv-python

Instale as dependências com:
```bash
pip install -r requirements.txt
```

## Como Usar

1. Baixe e prepare os dados:
   ```
   python src/download_dataset.py
   ```
2. Treine o modelo:
   ```
   python src/train.py
   ```
3. Avalie o modelo:
   ```
   python src/evaluate.py
   ```
4. Faça inferências:
   ```
   python src/inference.py
   ```

## Resultados

- results/classification_report.txt: Relatório de classificação
- results/confusion_matrix.png: Matriz de confusão
- results/sample_predictions.png: Exemplos de predições

## Referências

- UNet: Convolutional Networks for Biomedical Image Segmentation (arXiv:1505.04597)
- Documentação TensorFlow/Keras

---

Projeto acadêmico para segmentação de imagens utilizando Deep Learning.
