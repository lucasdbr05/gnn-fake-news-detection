# Detecção de Fake News com Graph Neural Networks (GNN)

Este projeto demonstra como utilizar Redes Neurais em Grafos (GNNs) para detectar fake news em plataformas de mídia social, analisando padrões de propagação e interação entre usuários.

## Descrição

- **Conjunto de Dados:** User Preference-aware Fake News Detection (UPFD)
- **Referência:** [UPFD: User Preference-aware Fake News Detection](https://arxiv.org/abs/2104.12259)
- **Principais Bibliotecas:** PyTorch Geometric, NetworkX, scikit-learn

O fluxo de trabalho inclui:
- Carregamento e exploração do conjunto de dados
- Visualização das estruturas de grafos de propagação
- Construção e treinamento do modelo GNN
- Avaliação de desempenho e análise dos resultados

## Como Executar

1. Instale as dependências:
   ```bash
   pip install torch torchvision torchaudio
   pip install torch-geometric torch-scatter torch-sparse torch-cluster torch-spline-conv
   pip install networkx scikit-learn pandas
   ```

2. Execute o notebook `main.ipynb` para reproduzir os experimentos.

