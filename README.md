#Projeto de Previsão de Aluguel de Bicicletas usando Azure Machine Learning

Visão Geral do Projeto:
Este projeto utiliza técnicas de Machine Learning para prever a demanda de aluguel de bicicletas com base em dados históricos. A plataforma Azure Machine Learning foi empregada para criar e implementar o modelo de previsão, tornando o processo de desenvolvimento e implantação mais eficiente.

Conjunto de Dados:
O conjunto de dados utilizado para treinar e avaliar o modelo está disponível no seguinte URL: https://aka.ms/bike-rentals.


Azure Machine Learning
Criação do Modelo:
Acesse a plataforma Azure Machine Learning.
Importe o conjunto de dados fornecido na URL mencionada acima.
Explore e prepare os dados, identificando as variáveis relevantes para a previsão.


Teste da Previsão:
Utilize o código JSON abaixo para realizar testes de previsão:

json
Copy code
{
  "Inputs": { 
    "data": [
      {
        "day": 1,
        "mnth": 1,   
        "year": 2022,
        "season": 2,
        "holiday": 0,
        "weekday": 1,
        "workingday": 1,
        "weathersit": 2, 
        "temp": 0.3, 
        "atemp": 0.3,
        "hum": 0.3,
        "windspeed": 0.3 
      }
    ]    
  },   
  "GlobalParameters": 1.0
}
Execute o teste para obter previsões de aluguéis de bicicletas com base nos parâmetros fornecidos.

Resultados
O projeto fornece gráficos e dados preditivos com base em dias, meses, anos, horários e condições climáticas. Os resultados são apresentados de forma visual e tabular para facilitar a interpretação.
