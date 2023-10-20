# Análise de riscos

## 1. Introdução

O desenvolvimento de software não está livre de riscos que podem se tornar empecilhos e, por isso, requer atividades de gerência de projetos como gerenciamento de riscos. Identificar os riscos, analisar a probabilidade e o impacto de cada um deles pode ajudar a minimizar o impacto destes no projeto.

Por isso, esse documento tem como objetivo principal identificar os riscos e planejar as respostas da equipe frente a eles.

## 2. Categorização de riscos

A EAR (Estrutura Analítica de Riscos) fornece uma estrutura de identificação de riscos com nível de detalhe consistente e categoriza os riscos em técnico, externo, organizacional e gerenciamento de projetos.

Assim, a equipe elaborou uma EAR para visualizar a categorização dos riscos do projeto SINDPOL.

<iframe src="https://miro.com/app/live-embed/uXjVNYFcXqg=/?moveToViewport=-768,-373,1536,744&embedId=635581029201" scrolling="no" allowfullscreen style="width: 100%; height: 500px" frameborder="0"></iframe>

## 3. Métricas e análise quantitativa

## 3.1 Probabilidade
A probabilidade indica a chance do risco acontecer.

| Probabilidade         | Intervalo | Valor | 
| --------------- | :---------: | :---: | 
| **Nenhuma**        |     Não há chance de acontecer    |   0   | 
| **Rara**        |      Menor que 20% de chance de ocorrer     |   1   |  
| **Improvável**  |      Entre 21% e 40% de chance de ocorrer      |  2   |   
| **Pouco provável**  |      Entre 41% e 60% de chance de ocorrer     |   3   |   
| **Muito provável**        |      Entre 61% e 80% de chance de ocorrer     |   4  | 
| **Quase certa**  |      Entre 81% e 100% de chance de ocorrer      |  5  |  

## 3.2 Impacto
O impacto refere-se ao prejuízo que o risco gera ao projeto, se acontecer.

| Impacto         | Descrição | Valor |
| --------------- | :---------: | :---: | 
| **Nenhum** |      Nenhum impacto ao projeto    |   0   |  
| **Muito pequeno** |      Quase sem impactos ao projeto      |   1   |  
| **Pequeno**       |      Pequeno impacto ao projeto      |   2   |   
| **Médio**       |     Representa algum impacto ao projeto      |   3   |   
| **Alto**        |      Compromete o andamento do projeto     |   4   | 
| **Altíssimo**  |      Inviabiliza o andamento do projeto      |  5   |  

## 3.3 Matriz de probabilidade/impacto

A partir da multiplicação das métricas de probabilidade e impacto, chegamos na matriz de probabilidade/impacto.

| P / I           | Muito baixo | Baixo | Médio | Alto | Muito alto |
| --------------- | :---------: | :---: | :---: | :--: | :--------: |
| **Muito Baixo** |      1      |   2   |   3   |  4   |     5      |
| **Baixo**       |      2      |   4   |   6   |  8   |     10     |
| **Média**       |      3      |   6   |   9   |  12  |     15     |
| **Alto**        |      4      |   8   |  12   |  16  |     20     |
| **Muito Alto**  |      5      |  10   |  15   |  20  |     25     |

## 3.4 Intervalo de nível de prioridade 

Dada a matriz de probabilidade/impacto define-se um nível de prioridade para os riscos determinando a urgência de medidas a serem tomadas para responder a estes.

| Prioridade      |  Intervalo  | 
| --------------- | :---------: | 
| **Muito Baixo** |    1 a 5    |  
| **Baixo**       |    6 a 10   | 
| **Média**       |   11 a 15   | 
| **Alto**        |   16 a 20   |   
| **Muito Alto**  |   21 a 25   |

## 3.5 Planejamento de resposta aos riscos

A equipe pode responder aos riscos de diferentes maneiras, são elas:

* **Prevenir**: alguns riscos são muito altos e surgem cedo, por isso é essencial prevenir o projeto eliminando a ameaça.

* **Transferir**: transferir o risco trata-se de realocar o impacto e responsabilidade para uma terceira parte.

* **Mitigar**: para mitigar o risco, a equipe age visando reduzir probabilidade de ocorrência ou consequência de determinado risco para dentro de limites aceitáveis.

* **Aceitar**: a aceitação do risco ocorre quando a equipe decide não agir para diminuir a ocorrência de um risco ou não é possível identificar outra estratégia de resposta apropriada.

## 3.6 Identificação dos riscos

Para acompanhar os riscos identificados durante o projeto e sua evolução ao longo das Sprints [acesse a planilha](https://docs.google.com/spreadsheets/d/1tjqTNX4kpeswjg6keff2Q26yAwQ0TaFlJjsf5iSzj5M/edit?usp=sharing)

<iframe width="1200" height="900" style="-webkit-transform:scale(0.8);-moz-transform-scale(0.8);" frameborder="0" scrolling="yes" src="https://docs.google.com/spreadsheets/d/1tjqTNX4kpeswjg6keff2Q26yAwQ0TaFlJjsf5iSzj5M/edit?usp=sharing"></iframe>

## Referências

Guia PMBOK 6a. ed. EUA: Project Management Institure, 2017. Disponível em: https://www.site.com. Acesso em: 19 out. 2023.

Plano de Resposta ao Risco. Disponível em: https://www.cin.ufpe.br/~if717/Pmbok2000/pmbok_v2p/wsp_11.5.html#:~:text=O%20plano%20de%20resposta%20ao,acordo%20de%20resposta%20ao%20risco. Acesso em: 19 out. 2023.

PLANO de Resposta ao Risco. [S. l.: s. n.], 2010. Disponível em: http://moodle.stoa.usp.br/file.php/877/08_Monografia_Gerenciamento_Riscos.pdf. Acesso em: 19 out. 2023.

EQUIPE ALECTRION 2022-2. Planejamento de Gerenciamento de Riscos. Disponível em: https://fga-eps-mds.github.io/2022-2-Alectrion-DOC/#/./Planejamento/riscos. Acesso em: 19 out. 2023.

Gerência de riscos em desenvolvimento de software. Disponível em: https://www.devmedia.com.br/gerencia-de-riscos-em-desenvolvimento-de-software/28506. Acesso em: 19 out. 2023.

RODRIGUES, Eli. EAR para projetos de software. Disponível em [https://www.elirodrigues.com/2013/09/21/gerenciamento-de-riscos-ear-para-projetos-de-software/](https://www.elirodrigues.com/2013/09/21/gerenciamento-de-riscos-ear-para-projetos-de-software/). Acesso em: 19 out. 2023.


## 4. Histórico de versão

## Histórico de Revisão
| Data       | Versão | Modificação | Autor |
| :--------- | :----- | :---------- | :---- |
|18/10/2023| 0.1 | Criação do documento | Victor Amaral |