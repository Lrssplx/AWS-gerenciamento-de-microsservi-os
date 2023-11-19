# Projeto Orquestração de Microsserviços com AWS :
1. Step Functions 
1. S3 
1. DynamoDB 
1. Lambda 
1. Cloud Trail 
1. Cloud Watch 
1. Rekognition 

## Objetivos do projeto

Desenvolver uma aplicação a partir dos serviços da AWS e efetuar a orquestração por meio da AWS Step Functions.

### A aplicação

A aplicação desenvolvida consiste em:
1. Fazer upload de uma imagem para o bucket S3
2. Chamar duas funções Lambda, onde a primeira fará a extração dos metadados do arquivo e a outra função chamará uma API de IA para extração de padrões em imagens.
3. Após execução cada função Lambda será chamada por meio da máquina de estado criada por meio da AWS Step Functions.
4. Por fim, o executado da execução é gravado na tabela do DynamoDB.

## Exemplo de resultado ![image](https://github.com/Lrssplx/AWS-gerenciamento-de-microsservicos/assets/40647391/1040bba0-278d-41da-bd37-efc30cf93e39)
![image](https://github.com/Lrssplx/AWS-gerenciamento-de-microsservicos/assets/40647391/52e00090-02eb-4b20-828b-ec805e72b93a)

