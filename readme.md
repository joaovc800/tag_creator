# API para cria��o de etiquetas com c�digos de barras

Este reposit�rio cont�m um projeto em Python para uma API que gera etiquetas com c�digos de barras. A arquitetura do software � escal�vel e utiliza Flask como framework web, al�m de outras ferramentas mencionadas abaixo.

## Ferramentas utilizadas

- **Python**: Linguagem de programa��o utilizada para desenvolver o c�digo.
- **Flask**: Framework web em Python para construir a API.
- **Barcode**: Biblioteca Python para a gera��o de c�digos de barras.
- **Pytest**: Framework de testes para realizar testes automatizados.
- **Virtualenv**: Ferramenta para cria��o de ambientes virtuais Python isolados.
- **Pre-commit**: Utilizado para configurar ganchos de pr�-commit para manter a qualidade do c�digo.
- **Cerberus**: Biblioteca de valida��o de dados para Python.

## Como usar

1. Clone este reposit�rio:

https://github.com/joaovc800/tag_creator.git


2. Crie um ambiente virtual e instale as depend�ncias:

cd nome-do-repositorio
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt


3. Execute a aplica��o:

py run.py


4. A API estar� dispon�vel em `http://127.0.0.1:3000`.

## Endpoints da API

- **POST /http://127.0.0.1:3000/create_tag**: Retorna a etiqueta com o c�digo de barras correspondente ao c�digo fornecido.

- body json **{"product_code": "123"}**