# Laboratório AI-900 DIO


Criação de um endpoint de machine learning na azure.

## Etapas




## Etapas

- Criar um Azure Machine Learning Workspace

- Criar um Aumtomated ML job, importando o data set a ser utilizado e configurando o job
- Aguarde o termino do treino do modelo
- Revise o melhor modelo encontrado e realize o deploy do endpoint
- Realize testes e valide os resultados

### Exemplo de entrada

ˋˋˋJson

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

ˋˋˋ


### Exemplo de saída


ˋˋˋJson
{
  "Results": [
    361.70271965673726
  ]
}
ˋˋˋ