# Plano de Gerenciamento de Custos
<style>body {text-align: justify}</style>

## 1. Introdução 
O plano de custos descreve como os custos do projeto serão planejados, estruturados e controlados, fornecendo detalhes dos processos e ferramentas usadas. A primeira etapa é a estimativa de custos, realizada para estimar o custo dos recursos necessários para a execução do projeto. Depois é determinado o orçamento, agregando todos os custos estimados. Por fim, é feito o controle desses custos para monitorar e possivelmente atualizar o orçamento.

Este documento apresenta a estimativa de custos, orçamentos e controle, para que o projeto possa ser realizado dentro do orçamento planejado.

## 2. Custos
### 2.1 Aluno
Segundo a plataforma [Glassdoor](https://www.glassdoor.com.br/Salários/desenvolvedor-júnior-salário-SRCH_KO0,20.htm), o custo semanal de um desenvolvedor júnior (_Cj_) é de aproximadamente R$4000,00, com a carga horária de 40 horas semanais, utilizaremos isso para calcular os custos dos alunos de MDS. 

Também segundo o Glassdoor, temos o custo mensal de um desenvolvedor pleno (_Cp_) é de aproximadamente R$8000,00, também com a carga horária de 40 horas semanais, utilizaremos isso para o cálculo dos alunos de EPS.

Com esses dados o custo hora _Ch_ do aluno pode ser calculado como:

**Chm = Cd ÷ N = 4000 ÷ 160 = 25**

**Che = Cp ÷ N = 8000 ÷ 160 = 50**

*N sendo a quantidade de horas trabalhadas por semana x semanas no mês (considerando que um mês tenha 4 semanas)*

Considerando o _Ch_ do aluno e que o estimado de trabalho semanal seja de 10 horas, temo que o custo semanal do aluno (_Cs_) é calculado como:

**Csm = Chm x 10 = 25 x 10 = 250**

**Cse = Che x 10 = 50 x 10 = 500**

Dividindo por 7 dias, temos o custo diário do aluno (_Cd_) calculado como:

**Cdm = Cs ÷ 7 = 250 ÷ 7 = 35,71**

**Cde = Cs ÷ 7 = 500 ÷ 7 = 71,43**

E o custo total de cada aluno (_Ct_) estipulado para o período letivo de 2023.2 é calculado por:

**Ctm = Cd x D = 35,71 x 120 = 4285**

**Cte = Cd x D = 71,43 x 120 = 8571,6**

**D sendo o total de dias no semestre letivo**

> \* Considerando o período letivo do semestre 2023/2 da UnB (25/08/2023 até 23/12/2023) como 120 dias.  

### 2.2 Equipamento
Para a estimativa de custos dos equipamento será considerado o preço de um _notebook_ custo-benefício com as configurações adequadas para o desenvolvimento do projeto em 2023. Segundo a [Tecmundo](https://www.tecmundo.com.br/produto/266771-10-melhores-notebooks-custo-beneficio-comprar-2023.htm) [7], o preço de um notebook com essas características está em torno de R$ 2400,00. Considerando os 15 integrantes da equipe:

**Custo TOTAL dos equipamentos**
* custo médio do notebook x quantidade de integrantes da equipe
* 2400 x 17 = R$**36.000,00**

### 2.3 Ferramentas
A estimativa de custos com ferramentas será considerado como R$0, pois as plataformas e ferramentas utilizadas pela equipe são gratuitas.

### 2.4 Capacitação
A estimativa de custos com cursos de capacitação será considerado como R$0, pois as plataformas e ferramentas utilizadas pela equipe foram gratuitas.


### 2.5 Infraestrutura
A estimativa de custos de infraestrutura foi planejada considerando o uso de energia elétrica e internet.

#### 2.5.1 Internet
A moperadora mais bem avaliada para a prestação de serviço de internet banda larga no Distrito Federal é a [Oi](https://www.oi.com.br/internet) (ANATEL, 2022). Portanto, considerando o plano mais barato da operadora, o custo mensal de internet por aluno seria de R$99,90

**Custo semanal de internet por integrante**
* custo mensal da internet ÷ quantidade de semana no mês
* 99,90 ÷ 4 = **R$24,98**

#### 2.5.2 Energia
Para a estimativa de energia, seguiu-se os dados da [tabela de tarifas](https://www.neoenergiabrasilia.com.br/residencial-e-rural/Documents/tafiras%20vigentes/01_nbsb_tarifas_energia_eletrica_grupoB_nov_2022_reh3134.pdf) da [neoenergiabrasilia](https://www.neoenergiabrasilia.com.br/Paginas/default.aspx), com os dados vigentes de Dezembro de 2022 à outubro de 2023. Segundo essa tabela, o custo do KW/h residencial, consumo ativo, de Brasília é cerca de R$0,70.

Segundo dados de 2021 da [cultura uol](https://cultura.uol.com.br/noticias/26097_6-maneiras-de-economizar-na-conta-de-luz-do-home-office.html), um notebook consome em média cerca de 65W/h, conectado ao carregador. Consideramos que cada integrante da equipe trabalhará 10 horas por semana em sua residência, ao longo de 17 semanas (Total do semestre). Utilizando esses dados para cálculo, temos:

**Consumo do notebook em KW/h:**
* potência x horas ÷ 1000  
* 65 x 1 ÷ 1000 = **0,065KW/h**

**Custo semanal de energia por integrante**

* horas de trabalho x consumo do notebook x tarifa
* 10h x 0,065KW/h x R$0,70
* 10 x 0,065 x 0,70 = **R$0,46**

**Custo semanal de energia por equipe**
* custo semanal por aluno x quantidade de integrantes da equipe
* 0,46 x 17 = **R$7,82**


## 3. Planilha de custos
Para acompanhar a consolidação dos cuscos e sua evolução no projeto ao longo das sprints [acesse a planilha](https://docs.google.com/spreadsheets/d/1NGDqhFQa5XDPp-3fmC6r5sc7z3ChM2rYw2H5mmErnWk/edit?usp=sharing).

<iframe width="1200" height="600" style="-webkit-transform:scale(0.8);-moz-transform-scale(0.8);" frameborder="0" scrolling="yes" src="https://docs.google.com/spreadsheets/d/1NGDqhFQa5XDPp-3fmC6r5sc7z3ChM2rYw2H5mmErnWk/edit?usp=sharing"></iframe>

## 4. Referências
ALMEIDA, A. **Os 7 melhores notebooks custo-benefício para comprar em 2023**. Disponível em: <https://www.tecmundo.com.br/produto/266771-10-melhores-notebooks-custo-beneficio-comprar-2023.htm>. Acesso em: 18 out. 2023. 

ANATEL. **Pesquisa de Satisfação e Qualidade**. Disponível em: <https://informacoes.anatel.gov.br/paineis/consumidor/pesquisa-de-satisfacao>. Acesso em: 18 out. 2023.

DPO; DAI. **Relatório de Gestão 2021: Apresentação e análise dos indicadores de desempenho conforme deliberações do Tribunal de Contas da União**, Quadro 2. Brasília: [s.n.]. Disponível em: <https://www.dpo.unb.br/images/dpl/2021/Indicadores_de_Desempenho_TCU_2021.pdf>. Acesso em: 18 out. 2023.

OI. **Internet fibra ótica: planos de internet banda larga**. Disponível em: <https://www.oi.com.br/internet>. Acesso em: 18 out. 2023.

## Histórico de Revisão
| Data       | Versão | Modificação | Autor |
| :--------- | :----- | :---------- | :---- |
| 18/10/2023 | 0.1    | Criação e estruturação do documento | Victor Amaral |
| 19/10/2023 | 1.0    | Revisão de documento | Victor Amaral |
