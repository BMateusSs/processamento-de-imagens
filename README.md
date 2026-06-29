# Detecção Automática de Buracos em Vias Urbanas Utilizando Processamento Digital de Imagens

Este projeto contém o notebook `processamento.ipynb`, que realiza a detecção de buracos em imagens de vias utilizando técnicas de Processamento Digital de Imagens.

## Pré-requisitos

- Python 3.10 ou superior
- Jupyter Notebook ou JupyterLab

Instale as bibliotecas necessárias:

```bash
pip install opencv-python numpy matplotlib pandas notebook
```

## Como executar os experimentos

1. Clone o repositório:

```bash
git clone <https://github.com/BMateusSs/processamento-de-imagens.git>
cd <processamento-de-imagens>
```

2. Inicie o Jupyter Notebook:

```bash
jupyter notebook
```

ou

```bash
jupyter lab
```

3. Abra o arquivo:

```
notebooks/processamento.ipynb
```

4. Execute todas as células na ordem em que aparecem (`Run → Run All Cells`).

5. O notebook irá:
   - carregar as imagens da pasta `imgs`;
   - processar cada imagem;
   - detectar possíveis buracos;
   - exibir os resultados durante a execução;
   - salvar as imagens processadas e as máscaras geradas na pasta `resultados`.

## Observações

As imagens utilizadas nos experimentos devem estar na pasta `imgs`. Os resultados serão salvos automaticamente na pasta `resultados`.