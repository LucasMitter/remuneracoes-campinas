# Trabalho de Conclusão de Curso - IFSP Campinas
## Graduação em Análise e Desenvolvimento de Sistemas - 2023.6

**Banca:**
Profa. Dr. Bianca Maria Pedrosa  - bpedrosa@ifsp.edu.br <br>
Prof. Ms. Everton Josué da Silva - everton.silva@ifsp.edu.br <br>
Swift Yaguchi                    - yaguchi.swift@aluno.ifsp.edu.br


**Junho de 2022**

**Autor:**
Aluno: Lucas Mittermayer Oliveira Reis - CP3000559
# Projeto desenvolvido: Análise Exploratória de Remunerações de Servidores Públicos de Campinas

## **Descrição:**
Esse trabalho de conclusão de curso resume-se na elaboração de uma análise exploratória dos dados (EDA) na remuneração dos servidores públicos, visando deixar os dados mais interpretáveis ao leitor e fomentar novas políticas públicas que promovam a transparência e facilite a participação cidadã. A Lei 12.527, Lei de acesso à informação, regulamenta por parte dos municípios a disponibilização dos dados de remuneração dos servidores públicos. Devido ao grande volume desses dados, não é possível uma interpretação intuitiva por parte do usuário, principalmente se tratando da remuneração dos funcionários. Esse trabalho facilitará o acesso à informação que a LAI propõe. Este trabalho utiliza ferramentas estatísticas, como a análise exploratória dos dados (EDA), gerando visualizações que pretendem dar mais entendimento dos dados, ao detalhar de forma gráfica e visual a distribuição de remunerações e as suas tendências ao longo do tempo. Foram geradas análises como remuneração média e mediana geral, por agrupamento de secretaria e requisitos (nível de ensino, cargos comissionados, com experiência ou sem requisitos), com suas tendências ao longo dos anos, utilizando gráficos de linhas, barras, boxplot e mapas de calor para um melhor entendimento. Esse trabalho será públicado no sistema Pergamum da Faculdade e será disponibilizada uma cópia na nuvem no mesmo link onde é possível baixar as bases de dados (https://drive.google.com/drive/folders/1XMHivg6Xq0jVLJAP493dO8Ei381AZRHy?usp=sharing).


## **Objetivos:**
- Levantar informações sobre remuneração dos servidores públicos e informações relacionadas aos cargos. 
- Entregar uma análise exploratória dos dados, criando tabelas e gráficos para as visualizações relevantes para a sociedade previamente levantadas.
- Estudar técnicas de análise exploratória de dados (EDA).
- Aplicar processos de extração, carga e transformação (ETL) de dados.
- Aplicar técnicas de visualização de dados.
- Gerar relatório com resultados nesse documento e em um arquivo IPYNB (formato jupyter notebook), hospedado no github, contendo as visualizações criadas, juntamente de todo o código utilizado, além de links para download dos dados já extraídos.

## **Dados Utilizados:**
- Remunerações Públicas entre 2016 e 2023, juntamente da composição das remunerações.
- Dados de cargos públicos (experiência necessária, escolaridade mínima, entre outros).
- Lista de cargos em comissão.
- Dados de despesas por secretarias.

# Como executar:
## **> Instalação de requisitos:**
#### **1. Instalar Python**
- Foi utilizada a versão 3.11 do python: https://www.python.org/downloads/release/python-3110/

&nbsp;&nbsp; **(OPCIONAL) Também é possível baixar a versão mais atual através desse link:** https://www.python.org/downloads/

#### **2. Baixar Chromium e webdriver**
- é necessário baixar o navegador Chromium e o driver para poder utilizar o seleium (chrome-win.zip e chromedriver_win32.zip) a versão utilizada pode ser encontrada nesse link: https://commondatastorage.googleapis.com/chromium-browser-snapshots/index.html?prefix=Win/991466/

&nbsp;&nbsp; **(OPCIONAL) Também é possível baixar a versão mais atual através desses links:**
- Navegador Chromium: https://download-chromium.appspot.com/?platform=Win_x64&type=snapshots
- Webdriver Chromium: https://chromedriver.chromium.org/downloads

#### **3. Instalar bibliotecas do arquivo requirements:**
- Para instalar as bibliotecas python utilizadas, basta executar o comando
```
    pip install -r requirements.txt
```
## **> Download das bases de dados utilizadas:**
- Baixar e extrair arquivos na mesma pasta do projeto: https://drive.google.com/drive/folders/1XMHivg6Xq0jVLJAP493dO8Ei381AZRHy?usp=sharing

## **> Execução: está dividida em 3 etapas, a extração e o tratamento e análise, análise adicional:** 
- **1. Extração:** As 3 subetapas etapas da extração fazem o download da base de salarios, cargos em comissao e dados dos cargos respectivamente.
- **2. Tratamento e análise:** O notebook de tratamentos e análise pode ser executado sem a execução prévia da extração, com os dados ja baixados no projeto. Nessa etapa são realizadas os tratamentos da base de dados, e união das informações, juntamente da parte principal da análise.
- **3. Análise adicional:** Aqui foi cruzada a informação de gastos das secretarias com das remunerações e conta com novas comparações.
