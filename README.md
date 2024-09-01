# Teste_Software_Mutantes_2024_Andrade_Rodrigo

Instalação

Crie um ambiente venv e então execute o comando:
pip install -r requirements.txt

## Para executar os testes com relátorio de cobertura de branches
pytest -vv test_todos.py --cov=todos --cov-branch --cov-report html

## Para executar os testes com mutmut
mutmut run

## Para ver os resultados
mutmut results

## #Para gerar um html exibindo as mudanças feitas pelo mutmut
mutmut html
