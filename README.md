# Descrição do Desafio

## Descubra as melhores notas de matemática do ENEM 2016

Você deverá criar um modelo para prever a nota da prova de matemática de quem participou do ENEM 2016. 

## Detalhes sobre a resolução
Fiz o modelo baseado num regressor de Floresta Aleatória e em um regressor linear simples, os dois tiveram resultados excelentes. 


## Detalhes

O contexto do desafio gira em torno dos resultados do ENEM 2016 (disponíveis no arquivo train.csv). Este arquivo, e apenas ele, deve ser utilizado para todos os desafios. Qualquer dúvida a respeito das colunas, consulte o [Dicionário dos Microdados do Enem 2016](https://s3-us-west-1.amazonaws.com/acceleration-assets-highway/data-science/dicionario-de-dados.zip).

Muitas universidades brasileiras utilizam o ENEM para selecionar seus futuros alunos e alunas. Isto é feito com uma média ponderada das notas das provas de matemática, ciências da natureza, linguagens e códigos, ciências humanas e redação. Determine os 20 melhores colocados, por ordem, para os pesos abaixo:

- matemática: 3
- ciências da natureza: 2
- linguagens e códigos: 1.5
- ciências humanas: 1
- redação: 3

No arquivo test.csv crie um modelo para prever nota da prova de matemática (coluna **NU_NOTA_MT**) de quem participou do ENEM 2016. 

Salve sua resposta em um arquivo chamado answer.csv com duas colunas: **NU_INSCRICAO** e **NU_NOTA_MT**.

Faça o upload do arquivo answer.csv usando o botão "Submeter resposta".

## Observações

Os outputs foram os arquivos answer sendo 
- answer_49LR_20linhas.csv # 1ª tentativa, Linear Regressor e 20 primeiras linhas do resultado
- answer_49LR_2_20linhas.csv # 2ª tentativa, Linear Regressor e 20 primeiras linhas do resultado 
- answer_49_3RF_20linhas.csv # 3ª tentativa, Random Forest e 20 primeiras linhas
- answer.csv # ultima submissão enviada, Random FOrest com Dummies nas questõs socioeconomicas e ~3000 linhas [Submetido] Socore 93%