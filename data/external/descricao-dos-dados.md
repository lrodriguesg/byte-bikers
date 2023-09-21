# **Descrição dos Dados** #
Este conjunto de dados contém a contagem horária e diária de bicicletas de aluguel entre os anos de 2011 e 2012 no sistema de bikeshare Capital, com as informações meteorológicas e sazonais correspondentes.

## **Variáveis do Dataset**
* instant: índice do registro
* dteday : data
* season : estação do ano (1:inverno, 2:primavera, 3:verão, 4:outono)
* yr : ano (0: 2011, 1:2012)
* mnth : mês (1 a 12)
* holiday : indica se o dia é feriado ou não
* weekday : dia da semana
* workingday : se o dia não é nem fim de semana nem feriado é 1, caso contrário é 0.
* weathersit :
  * 1: Claro, Poucas nuvens, Parcialmente nublado, Parcialmente nublado
  * 2: Neblina + Nublado, Neblina + Nuvens esparsas, Neblina + Poucas nuvens, Neblina
  * 3: Neve fraca, Chuva leve + Trovoada + Nuvens esparsas, Chuva leve + Nuvens esparsas
  * 4: Chuva forte + Granizo + Trovoada + Neblina, Neve + Nevoeiro
* temp : Temperatura normalizada em Celsius. Os valores são derivados por (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (apenas em escala horária)
* atemp: Temperatura "sentida" normalizada em Celsius. Os valores são derivados por (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (apenas em escala horária)
* hum: Umidade normalizada. Os valores são divididos por 100 (máximo)
* windspeed: Velocidade do vento normalizada. Os valores são divididos por 67 (máximo)
* casual: contagem de usuários casuais
* registered: contagem de usuários registrados
* cnt: contagem total de bicicletas alugadas, incluindo usuários casuais e registrados

# Fonte e Origem
* Os dados foram retirados do [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset)
* Criador: [**Hadi Fanaee-T**](https://github.com/fanaee?tab=repositories), Ph.D., Professor Associado, Centro de Pesquisa em Sistemas Inteligentes Aplicados , Universidade Halmstad, Suécia
