# Sistema de Recomendação por Imagens - COCO128 + Gradio

Projeto rápido para recomendar imagens similares por aparência usando embeddings extraídos de uma CNN pré-treinada.

## Como usar

### No Google Colab

1. Abra o notebook `notebooks/image_recommendation_coco_gradio.ipynb` no Colab.
2. Execute as células em ordem para instalar dependências, baixar COCO128, treinar e usar a interface.
3. Envie uma imagem na interface Gradio para receber as imagens mais similares do dataset.

### Localmente

- Instale as dependências:
pip install tensorflow tensorflow_hub numpy scikit-learn matplotlib gradio opencv-python


- Execute o notebook no Jupyter.

---

## Estrutura do Projeto

- `notebooks/`: notebook Colab com código completo
- `README.md`: este arquivo
- `LICENSE`: licença MIT

---

## Referências

- COCO128 dataset (subset do COCO)
- Tutorial baseado em: https://github.com/sparsh-ai/rec-tutorials

