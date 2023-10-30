
# Case: Classification

## Etapas:

- Crie um arquivo `requirements.txt` com as bibliotecas necessárias para execução deste projeto;
- Crie um ambiente virtual (e.g. `case_classification`);
- Desenvolva o modelo utilizando as etapas do CRISP-DM;
- Crie um App no Streamlit para prever o dataset `new_customers.csv`;


## Dicionário dos dados

O dicionário dos dados pode ser encontrado [neste link](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset).  
[Fonte original dos dados](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113).


``` bash
conda create -n classification python=3.8
conda activate classification
pip install -r requirements.txt

pip install streamlit
pip install altair==4.0
```

## Utilização

- Selecione o Python 3.8 de classificação criado
- Confira a modelagem e execute por completo
- Confira se o app.py na pasta app.py está configurado como desejado
- No terminal, digite $ streamlit run app/app.py para rodas o modelo
- Insira a planilha de novos clientes para classificação.