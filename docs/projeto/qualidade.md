# Plano de Qualidade do Produto
<style>body {text-align: justify}</style>

## 1. Introdução

A ISO 25010, disponibilizada em 2011, que padroniza a qualidade de produtos de software e surgiu em substituição a ISO9126, define qualidade como  o nível em que um sistema atende às necessidades expressas e não expressas dos stakeholders, resultando em geração de valor.

Esta ISO25010 define 8 características para a qualidade, sendo elas: adequação funcional, eficiência de desempenho, compatibilidade, usabilidade, confiabilidade, segurança, manutenção e portabilidade.

## 2. Objetivo

O objetivo da elaboração deste plano de qualidade é especificar as ferramentas que serão utilizadas e as métricas analisadas pela equipe para que seja definida a qualidade do produto e tomadas decisões. Assim, os objetivos deste documento são:

- Definir os objetivos de qualidades.

- Apresentar formas de atingir os objetivos de qualidade.

- Selecionar e coletar métricas

- Apresentar a interpretação e uso das métricas para o produto.

- Especificar procedimentos, técnicas e ferramentas

## 3. Objetivos de qualidade

No contexto dos objetivos definidos pela norma ISO 25010:2011, a análise de qualidade do projeto se concentra em três áreas principais: qualidade interna, qualidade externa e qualidade de uso.

A qualidade interna e externa visa avaliar o produto em si e está centrada em seis características principais: funcionalidade, confiabilidade, usabilidade, eficiência, manutenibilidade e portabilidade. Cada uma dessas características abrange diversas subcaracterísticas. Essas subcaracterísticas são observáveis externamente quando o software é utilizado e são influenciadas pelos atributos internos do produto.

Por sua vez, a qualidade de uso se concentra em quatro características principais: eficácia, produtividade, segurança e satisfação. Essas características são derivadas da combinação das seis características de qualidade (interna e externa) previamente definidas pela norma ISO.

A análise de qualidade do projeto aborda tanto os aspectos internos quanto os externos do software, levando em consideração as seis características de qualidade. Avalia também a experiência do usuário final por meio das quatro características específicas de qualidade de uso. Ao adotar essas abordagens complementares, busca-se realizar uma avaliação abrangente da qualidade do produto em diferentes perspectivas.

## 4. Verificação e validação

Para alcançar os objetivos de qualidade do projeto, foram adotadas três técnicas de verificação e validação:

- Análise estática do código: Essa técnica utiliza o Sonar Cloud como ferramenta de análise estática de código, para obter métricas mensuráveis. Essa ferramenta identifica potenciais problemas no código e fornece informações relevantes para a gestão da qualidade do projeto, que colabora para a tomada de decisões e pontos a serem atacados pela equipe.

- Testes automatizados: Foram realizados testes automatizados, incluindo testes unitários e de integração. Essa abordagem permite validar tanto os cenários esperados quanto situações de erro, garantindo o funcionamento adequado do software em diversas condições.

- Validações com os POs do projeto: Além das técnicas baseadas em código, é essencial envolver os donos ou usuários do projeto na validação. Reuniões semanais foram realizadas para validar o progresso e obter feedback. 

Essas três técnicas combinadas permitem abordar tanto aspectos técnicos, por meio da análise estática e dos testes automatizados, quanto considerações mais amplas, ao envolver os stakeholders do projeto. Dessa forma, busca-se garantir a qualidade do projeto de forma abrangente e satisfatória.

## 5. Padrões, práticas, convenções e métricas

### ISOs e modelos de qualidade

A principal ISO e modelo utilizados no projeto são:
- NBR - ISO/IEC 25010
- Modelo de Qualidade Q-Rapids

### Métricas para o produto

Através do uso de métricas, é possível identificar as subcaracterísticas relacionadas e, por consequência, avaliar a qualidade do produto. Essa avaliação também permite analisar a produtividade do projeto e obter resultados que podem influenciar as decisões tomadas em relação ao seu desenvolvimento.

As métricas definidas para o SINDPOL foram:

| Métrica                  | Descrição                                           |
| ------------------------ | --------------------------------------------------- |
| Functions                | Quantidade de funções no código                     |
| Complexity               | Complexidade ciclomática                            |
| Comment Lines Density    | Densidade (%) de linhas comentadas                  |
| Duplicated Lines density | Densidade (%) de linhas duplicadas                  |
| Coverage                 | Cobertura de código pelos testes                    |
| Ncloc                    | Quantidade de linhas de código                      |
| Tests                    | Testes unitários e de integração                    |
| Test Errors              | Testes que possuem erros                            |
| Test Failures            | Testes que falharam                                 |
| Test Execution Time      | Tempo de execução dos testes                        |
| Security Rating          | Avaliação de segurança de falhas e vulnerabilidades |
| User Satisfaction        | Índice de satisfação do usuário com o produto       |

A partir das métricas especificadas no SonarCloud e dos valores coletados pelas métricas definidas, foram estabelecidos valores mínimos aceitáveis para cada métrica no projeto conforme tabela abaixo.

| Métrica                      | Valor        |
| ---------------------------- | ------------ |
| Complexity                   | até 10       |
| Comment Lines Density (%)    | até 30%      |
| Duplicated Lines Density (%) | até 5%       |
| Coverage                     | acima de 80% |
| Test Failures                | 0            |
| Test Errors                  | 0            |
| Security Rating              | 0 (A)        |
| Satisfação do usuário        | acima de 3   |

## 6. Testes

O software é uma das construções mais complexas dos humanos por isto está sujeito a inconsistências e erros. O conjunto de processos para validar o correto funcionamento de um software são chamados testes e as atividades de teste surgiram justamente para evitar que estes erros cheguem ao usuário final.

* Testes de unidade: a maior parte dos testes se encontram nesta categorização e são utilizados para verificar pequenas partes de um código, normalmente uma classe somente.

* Testes de integração: estes testes verificam uma transação completa ou uma funcionalidade

* Testes de sistema: testes que simulam uma sessão com usuário real

## 7. Ferramentas

[SonarCloud](https://www.sonarsource.com/products/sonarcloud/?gads_campaign=SC-Class01-Brand&gads_ad_group=SonarCloud&gads_keyword=sonarcloud&gclid=Cj0KCQjwyLGjBhDKARIsAFRNgW_ldned9rPbZ6BecorNDUxvGxjLbdoawwMROpUJnpr5qGlKr3oBOh0aAnZlEALw_wcB): Ferramenta de varredura de código para analisar o código de acordo com as regras e métricas definidas.

## 8. Controle de código 

A fim de assegurar a execução de procedimentos de qualidade, utilizamos uma combinação de tarefas automatizadas e manuais. 

As tarefas automatizadas incluem: documentação, controle de versão, controle de código, controle de commits, testes automatizados. Essas tarefas são realizadas por ferramentas e sistemas que auxiliam na garantia da qualidade do software.

## 9. Referências

ENGSOFTMODERNA. Engenharia de Software Moderna. Disponível em: https://engsoftmoderna.info/. Acesso em: 22 de Out. 2023.

Importância dos testes de software na qualidade do sistema. TreinaWeb. Disponível em: https://www.treinaweb.com.br/blog/importancia-dos-testes-de-software-na-qualidade-do-sistema. Acesso em: 22 de Out. 2023.

ISO/IEC 25010. ISO 25000. Software and data quality. 2011. Disponível em: https://iso25000.com/index.php/en/iso-25000-standards/iso-25010. Acesso em: 22 de Out. 2023.

Quality-aware Rapid Software Development Project: The Q-Rapids Project. FRANCH X.; LOPEZ L.; FERNÁNDEZ S. M.; ORIOL M.; RODRÍGUEZ P.; TRENDOWICZ A. Acesso em: 22 de Out. 2023.

## 5. Histórico de Revisão

| Data       | Versão | Modificação | Autor |
| :--------- | :----- | :---------- | :---- |
|22/10/2023| 1.0 | Criação do documento | Victor Amaral |