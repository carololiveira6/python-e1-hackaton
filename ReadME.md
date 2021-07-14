## **Table of Contents**
- [E1 - Hackathon](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_e_01_hackathon.html&ref=master#mcetoc_1f3biil3d5) 
  - [Objetivo](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_e_01_hackathon.html&ref=master#mcetoc_1f33pqfa47)
  - [Preparativos](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_e_01_hackathon.html&ref=master#mcetoc_1f33pqfa48)
  - [Desafio](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_e_01_hackathon.html&ref=master#mcetoc_1f33pqfa49)
- [Entregáveis](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_e_01_hackathon.html&ref=master#mcetoc_1egvoav555j) 
  - [Repositório](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_e_01_hackathon.html&ref=master#mcetoc_1egvrpv6k1l4)
- [Critérios de aceitação](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_e_01_hackathon.html&ref=master#mcetoc_1eh146n6m3)
# **E1 - Hackathon**
Nessa entrega você criará uma função que processa uma lista de strings.
## **Objetivo**
O objetivo dessa atividade é trabalhar seus conhecimentos de listas e outros conceitos básicos no python. 
## **Preparativos**
Você deverá criar um arquivo chamado **hackathon.py** e copiar o código abaixo para este arquivo. Dessa forma, cada variável que inicia com o nome **hackathon** guarda uma lista de equipes que participaram do evento e suas respectivas classificações.

A equipe vencedora se encontra na **posição 0**, o segundo lugar na **posição 1**, e assim por diante.

hackathon\_1 = ["Team Kenzie", "Team Ateliware", "Team VHSYS", "Team Mirum"]

hackathon\_2 = ["Team Ateliware", "Team Kenzie", "Team VHSYS", "Team Mirum"]

hackathon\_3 = ["Team Mirum", "Team Ateliware","Team VHSYS", "Team Kenzie"]
## **Desafio**
Em seguida, escreva as funções seguindo as orientações:

- **get\_score(team\_name, teams)**
  - **Parâmetros:** 
    - **team\_name**: Uma **string** com o nome de uma equipe que participou.
    - **teams**: Uma das listas declaradas acima
  - **Procedimento:**  
    - Crie uma lógica que obtém a classificação da equipe para o evento.
  - **Retorno:** 
    - A função tem um **return** que mostra uma **string formatada,** conforme o exemplo abaixo:

get\_score\_1 = get\_score("Team Ateliware", hackathon\_1)

print(get\_score\_1)

// A Team Ateliware ficou classificada em 2

get\_score\_2 = get\_score("Team Kenzie", hackathon\_1)

print(get\_score\_2)

// A Team Kenzie ficou classificada em 1

get\_score\_3 = get\_score("Team Mirum", hackathon\_3)

print(get\_score\_3)

// A Team Mirum ficou classificada em 1

-----
# **Entregáveis**
## **Repositório**
- Link do **repositório** do **GitLab.**
- **Código fonte:** 
  - Arquivo **hackathon.py**.
- **Privacidade** 
  - Incluir **ka-br-out-2020-correcoes** como reporter.
### -----
# **Critérios de aceitação**

|**pts**|**Dado**|**Quando**|**É esperado**|
| :-: | :-: | :-: | :-: |
|2.5|Criação de arquivo **hackathon.py** com variáveis hackathon\_1 hackathon\_2 e hackathon\_3|Verificada pela equipe de ensino|Esteja de acordo com o solicitado|
|2.5|Função **get\_score(team\_name, teams)**|Executada a bateria de testes semelhante ao que foi especificado nas **Entradas e Saídas**|O retorno seja de acordo com o especifícado|


**Boa diversão, devs! ⛩**








