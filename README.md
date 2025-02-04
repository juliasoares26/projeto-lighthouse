# projeto-lighthouse

## Descrição

Este projeto analisa dados de precificação de imóveis utilizando técnicas de análise exploratória de dados (EDA) e um modelo de machine learning para previsão de preços.

## Requisitos

Antes de executar o projeto, é necessário instalar algumas dependências. Este projeto foi desenvolvido utilizando **Python 3.12** e requer a instalação do **Miniconda** para gerenciamento de ambientes virtuais.

### Instalando o Python

Caso ainda não tenha o Python instalado, baixe a versão mais recente em:

- [Python.org - Download](https://www.python.org/downloads/)

Durante a instalação, marque a opção **"Add Python to PATH"** para facilitar o uso no terminal.

### Instalando uma IDE

Para facilitar o desenvolvimento e execução do código, recomendo o uso de uma IDE como:

- [VS Code](https://code.visualstudio.com/)
- [PyCharm](https://www.jetbrains.com/pycharm/download/)
- [Jupyter Notebook](https://jupyter.org/install)

### Instalando o Miniconda

1. Baixe e instale o Miniconda de acordo com seu sistema operacional:
   - [Windows](https://docs.conda.io/en/latest/miniconda.html)
   - [Mac](https://docs.conda.io/en/latest/miniconda.html)
   - [Linux](https://docs.conda.io/en/latest/miniconda.html)

### Criando e ativando um ambiente virtual com Conda

Execute os seguintes comandos no terminal ou prompt de comando:

```bash
conda create --name ambiente_precificacao python=3.9
conda activate ambiente_precificacao
```

### Instalando o pip

O `pip` geralmente já vem instalado com o Python. Para garantir que ele está disponível, execute:

```bash
python -m ensurepip --default-pip
```

Caso precise atualizar o `pip`, utilize:

```bash
pip install --upgrade pip
```

### Instalando as dependências

Com o ambiente ativado, execute:

```bash
pip install -r requirements.txt
```

Isso garantirá que todas as bibliotecas necessárias sejam instaladas.

## Estrutura do Projeto

O projeto contém os seguintes arquivos:

- `desafio_light.py` - Script principal do projeto.
- `requirements.txt` - Lista de dependências necessárias.
- `modelo_precos.pkl` - Modelo treinado salvo.

## Executando o Projeto

1. Certifique-se de que o ambiente virtual está ativado:
   ```bash
   conda activate ambiente_precificacao
   ```
2. Execute o script principal:
   ```bash
   python desafio_light.py
   ```

O script realizará a análise exploratória de dados, treinará um modelo de machine learning e salvará o modelo treinado no arquivo `modelo_precos.pkl`.

## Autor

Este projeto foi desenvolvido como parte do Desafio Cientista De Dados da Indicium

