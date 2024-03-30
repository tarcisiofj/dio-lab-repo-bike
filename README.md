
## Documentação
Segue o link da Base de Dados:
[Base de Dados](https://raw.githubusercontent.com/MicrosoftLearning/mslearn-ai-fundamentals/main/data/ml/daily-bike-share.csv)

### Passo a Passo

1. Inicialmente foi criado via linha de comando um diretório:
    ```
    > mkdir dio-lab-repo-bike

    ```
2. Entra no diretório criado e executa os comandos de criação do git :
    ```
    > cd dio-lab-repo-bike
    > git init

    ```
3. Cria o arquivo de modelo de previsão com seus devidos pontos de extremidade configurados. Utilize o seu editor de texto preferiso. Neste exemplo foi usado o vim :
    ```
    > vim daily-bike.json

    ```
3.1 Conteúdo do arquivo com os dados de previsão:
```
 {
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2012,
         "season": 2,
         "holiday": 0,
         "weekday": 2,
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

```
4. Acicionar o arquivo para ficar rastreado pelo git, e fazer um com:mit.  :
    ```
    > git add daily-bike.json
    > git commit -m"Criacao do arquivo de previsao com seus dados"

    ```
5. No Github copie o link do repositórioi remote e logo depois  adicione a URL do repositório remoto ao qual o repositório local será enviado.
```
> git remote add origin URL-COPIADA
```
6. Envia o conteúdo local para o remoto:
```
> git push origin main

```

