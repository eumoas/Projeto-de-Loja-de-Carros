# Desafio_Indicium

Olá, eu sou a Miriam. 
Uma aspirante a carreira de cientista de dados do Programa Lighthouse da Indicium!


Análise Preditiva de Preços de Loja de Carros Automotivos

O conteúdo deste projeto trata-se da análise exploratória de um conjunto de dados (EDA) de revenda de veículos. O objetivo do estudo é responder perguntas iniciais sobre os aspectos e variáveis que envolvem a compra e venda, além de propor caminhos possíveis para a alavancagem de vendas na unidade. Ao final do estudo, um modelo de machine learning será capaz de predizer os valores ideias para venda. 


Arquivos

Lista de arquivos utilizados neste projeto:
Dataset de treinamento: ./dataset/cars_train2023.csv
Dataset de teste: ./dataset/cars_test2023.csv
Notebook EDA: ./notebooks/EDA.ipynb
Notebook modelagem: ./notebooks/modelagem_regressao.ipynb
Resultado do modelo: ./results/predicted.csv
Códigos de modelagem: ./src/

Link GitHub: 
Instalar e executar o projeto
Para utilizar este projeto deve-se clonar o repositório do github e executar o seguinte comando dentro da pasta do projeto:
pip install -r requirements.txt
Para treinar o modelo de regressão linear pode-se executar o comando abaixo:
python src/train.py
Para testar o modelo de regressão linear e salvar o arquivo ‘predicted.csv’ com o resultado do modelo pode-se executar o comando abaixo:
python src/test.py

