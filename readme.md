# API para criação de etiquetas com códigos de barras

Este repositório contém um projeto em Python para uma API que gera etiquetas com códigos de barras. A arquitetura do software é escalável e utiliza Flask como framework web, além de outras ferramentas mencionadas abaixo.

## Ferramentas utilizadas

- **Python**: Linguagem de programação utilizada para desenvolver o código.
- **Flask**: Framework web em Python para construir a API.
- **Barcode**: Biblioteca Python para a geração de códigos de barras.
- **Pytest**: Framework de testes para realizar testes automatizados.
- **Virtualenv**: Ferramenta para criação de ambientes virtuais Python isolados.
- **Pre-commit**: Utilizado para configurar ganchos de pré-commit para manter a qualidade do código.
- **Cerberus**: Biblioteca de validação de dados para Python.

## Como usar

1. Clone este repositório:

https://github.com/joaovc800/tag_creator.git


2. Crie um ambiente virtual e instale as dependências:

cd nome-do-repositorio
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt


3. Execute a aplicação:

py run.py


4. A API estará disponível em `http://127.0.0.1:3000`.

## Endpoints da API

- **POST /http://127.0.0.1:3000/create_tag**: Retorna a etiqueta com o código de barras correspondente ao código fornecido.

- body json **{"product_code": "123"}**