# Análise Microdados Enem 2020
[![NPM](https://img.shields.io/npm/l/react)]([https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE](https://github.com/Williams-Cabral/Enem_2020/blob/main/LICENSE)) 

# Sobre o projeto

https://app.powerbi.com/view?r=eyJrIjoiNWUxOGY5ZGMtOTY4Yy00Njk1LTk2NmEtZDRlN2Q1NmE1MTI2IiwidCI6ImRjMWMxYzExLTU5MDEtNDc3Mi05NmFmLTAyMWQ5YjViMDVkYyJ9

Os microdados reúnem um conjunto de informações detalhadas sobre pesquisas, avaliações e exames realizados pelo Inep, permitindo aos gestores, pesquisadores, instituições e interessados na área da educação realizar análises e tabulações de interesse para subsidiar diagnósticos, estudos, pesquisas e acompanhamento de estatísticas e informações educacionais.

Este projeto consiste em uma análise da base de dados referente ao exame do ensino médio (enem) de 2020. Para isso, após a a extração da base de dados (disponível em: 
https://download.inep.gov.br/microdados/microdados_enem_2020.zip ), foi realizada a anáise exploratória e modelagem dimensional posteriormente ao término do ETL necessário (realizado através da ferramenta apropriada para grandes volumes de dados, o Alteryx.


## Layout dashboard em Power Bi

O Dashboard foi desenvolvido em Power Bi e é composto por 2 páginas contendo um sobre panorama geral dos dados extraídos da base de dados do exame realizado em 2020 e uma outra contendo as principais informações. Sua proposta é responder as perguntas:

Responder às seguintes perguntas:

- Qual a escola com a maior média de notas?
- Qual o aluno com a maior média de notas e o valor dessa média?
- Qual a média geral?
- Qual o % de Ausentes?
- Qual o número total de Inscritos?
- Qual a média por disciplina?
- Qual a média por Sexo?
- Qual a média por Etnia?

![Capa_enem2020](https://github.com/Williams-Cabral/insues/assets/139514209/a09ed8b5-6dda-4a95-8477-b4c234bec8a8) ![geral_enem2020](https://github.com/Williams-Cabral/insues/assets/139514209/22ee719f-c406-41c5-9dda-0770023e3ee4)

## Tratamento dos Dados

Devido o grande volume de dados, a maior parte do ETL foi realizada através da plataforma Alteryx, onde foi realizado os primeiros tratamentos para finalização via DAX no proprio Power BI a fim de reduzir os impactos de performance.

![Projeto_alteryx](https://github.com/Williams-Cabral/insues/assets/139514209/a3d1f0c8-1554-4017-b897-c18635cf695b) ![etl_alteryx](https://github.com/Williams-Cabral/insues/assets/139514209/a45a70d8-fb64-4e28-b7b5-c0f9860e36f1)

# Tecnologias utilizadas
## Alteryx
A Alteryx é uma plataforma que permite automatizar tarefas de preparo de dados. Na A10, pode estar presente em soluções de Inteligência Artificial, Machine Learning e Data Science. A ferramenta é conhecida por se adaptar à necessidade de cada usuário, tanto em relação ao preparo de dados quanto ao enriquecimento deles.

## Power Query e DAX
Principais recursos de tratamento de dados do Power BI para o modelagem de dados dimensional em modelo Star Schema.

## Power BI
Usada para criar as visualizações e publicar na web.
Alguns codigos usados:

1-Calculo de Qt de inscritos

![DAX1](https://github.com/Williams-Cabral/insues/assets/139514209/a054562e-bcc1-48d5-b38b-77df9b9e4f68)

2- Média de Notas dos paricipantes

![DAX2JPG](https://github.com/Williams-Cabral/insues/assets/139514209/ca031ff2-332c-4e26-9c18-ace3aab1470e)

3- Quantidade de Ausências no 1º dia de provas

![DAX3](https://github.com/Williams-Cabral/insues/assets/139514209/288652f7-3ec3-4e92-a677-7363d49f1862)

4 - Quantidade de Ausências no 2º dia de provas

![DAX4](https://github.com/Williams-Cabral/insues/assets/139514209/469f09ea-988d-4f60-aecf-b0a4703a070f)

5- Média de notas da prova de Redação

![DAX5](https://github.com/Williams-Cabral/insues/assets/139514209/5201c026-0141-4f3c-884d-a3ed8598379f)

# Aprendizados

A análise de dados possibilitou responder s principais perguntas do negócio e identificar insights relevantes sobre a aplicação da prova.

Dentre eles, as ausências nas realizações das provas em ambos os dias, os participantes com melhores medias de notas, o volume de inscritos por UF entre outros.

# Relatório

O Dashboard está disponível no seguinte link: https://app.powerbi.com/view?r=eyJrIjoiNWUxOGY5ZGMtOTY4Yy00Njk1LTk2NmEtZDRlN2Q1NmE1MTI2IiwidCI6ImRjMWMxYzExLTU5MDEtNDc3Mi05NmFmLTAyMWQ5YjViMDVkYyJ9

# Autor

Williams Cabral Jr.

https://www.linkedin.com/in/williams-cabral-jr-a4b5b61b0/

