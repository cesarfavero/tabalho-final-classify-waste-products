# Trabalho Final - Classificar Waste Products

Este repositório contém o projeto final de classificação de resíduos usando transfer learning com o modelo VGG16.

## Objetivo

Desenvolver um modelo de classificação de imagens para ajudar a EcoClean a automatizar a triagem de resíduos recicláveis e orgânicos.

## Conteúdo

- `Projeto Final Classificar Produtos de Resíduos.ipynb`: notebook principal com todo o fluxo do projeto, incluindo:
  - impressão da versão do TensorFlow
  - criação de geradores de dados de treino, validação e teste
  - construção de modelo VGG16 com extração de recursos e fine-tuning
  - compilação do modelo
  - treinamento e plotagem de métricas de precisão e perda
  - visualização de predições em imagens de teste

## Como usar

1. Abra o projeto no VS Code.
2. Ative o ambiente virtual:

```bash
cd "/Users/cesarfavero/Documents/IBM/Tabalho Final - Classify Waste Products"
source .venv311/bin/activate
```

3. Execute o notebook `Projeto Final Classificar Produtos de Resíduos.ipynb` com Jupyter.

## Dependências

As principais dependências são:

- tensorflow-macos
- matplotlib
- pillow

## Observações

- O notebook gera imagens sintéticas automaticamente se não houver um conjunto de dados real disponível.
- O diretório `.venv311` não deve ser commitado no repositório.
- Este repositório foi criado especificamente para o projeto "Tabalho Final - Classify Waste Products".
