# Plataforma de Dados da Spotlar

## Resumo

Este projeto teve como objetivo transformar o ambiente de dados da Spotlar em uma plataforma mais organizada, confiável e preparada para escalar.

Minha atuação envolveu a evolução da arquitetura analítica, a centralização de regras de negócio, a automação de processos de dados e a estruturação de modelos que permitissem maior autonomia aos usuários de negócio.

Mais do que desenvolver dashboards ou consultas SQL, o foco foi construir uma base reutilizável que facilitasse a geração de informações consistentes e preparasse a plataforma para iniciativas futuras, incluindo o uso de Inteligência Artificial sobre os dados da empresa.

---

## Contexto

Quando ingressei na Spotlar, a empresa ainda não possuía uma plataforma de dados estruturada.

Grande parte do conhecimento utilizado nas análises e na operação estava concentrada em uma única planilha, conhecida internamente como Planilha Central. Ela reunia informações de diferentes áreas, servia como base para diversas decisões e era constantemente atualizada de forma manual.

Embora atendesse às necessidades da empresa naquele momento, esse modelo dificultava a escalabilidade, aumentava a dependência de processos manuais e tornava mais complexo garantir consistência, rastreabilidade e reutilização das informações.

Com o crescimento da empresa e da demanda por dados, surgiu a necessidade de transformar esse conhecimento em uma plataforma estruturada, capaz de centralizar regras de negócio, integrar diferentes fontes de dados e fornecer informações confiáveis para apoiar a operação e a tomada de decisão.

Foi nesse contexto que passei a atuar na construção e evolução da plataforma de dados da Spotlar.

---

## Problema

A Planilha Central era o principal ponto de consolidação das informações da empresa. Embora a maior parte dos dados fosse proveniente do sistema desenvolvido em AppSheet, o conhecimento de negócio permanecia concentrado nessa planilha, onde eram realizadas consolidações, tratamentos e aplicações de regras utilizadas pela operação.

Esse modelo foi suficiente durante a fase inicial da empresa, mas passou a apresentar limitações à medida que a operação cresceu. As regras de negócio estavam distribuídas entre o AppSheet, a Planilha Central e os processos executados pelas pessoas, dificultando a padronização das informações, a escalabilidade da plataforma e a evolução das análises.

O desafio não era apenas substituir uma planilha, mas transformar esse conhecimento em uma plataforma de dados estruturada, na qual as regras de negócio fossem centralizadas, os processos fossem automatizados e as informações estivessem disponíveis de forma confiável para análises, dashboards e futuras aplicações de Inteligência Artificial.

---

## Objetivos

- Estruturar uma plataforma de dados que reduzisse a dependência da Planilha Central como principal ambiente analítico da empresa.
- Centralizar as regras de negócio em uma camada de dados consistente, documentada e reutilizável.
- Automatizar a ingestão, transformação e disponibilização dos dados provenientes do AppSheet e de outras fontes.
- Disponibilizar uma base confiável para dashboards, análises e indicadores utilizados pela operação.
- Construir uma arquitetura escalável, capaz de acompanhar o crescimento da empresa e servir de base para futuras iniciativas de Inteligência Artificial.

---

## Arquitetura da solução

### Visão geral

A solução foi concebida para transformar uma arquitetura baseada em uma planilha central em uma plataforma de dados organizada em camadas, onde cada componente tivesse uma responsabilidade bem definida.

O AppSheet permaneceu como sistema transacional da operação, responsável pelo registro das informações. A plataforma de dados passou a concentrar a ingestão, transformação e disponibilização desses dados para consumo analítico.

As regras de negócio deixaram de estar concentradas na Planilha Central e passaram a ser implementadas de forma estruturada nas transformações da plataforma, permitindo maior rastreabilidade, reutilização e governança das informações.

Essa arquitetura também reduziu a dependência de processos manuais e criou uma base preparada para suportar novas aplicações analíticas e iniciativas de Inteligência Artificial.

---

## Principais decisões

> TODO

---

## Desafios

> TODO

---

## Resultados

> TODO

---

## Aprendizados

> TODO

---

## O que faria diferente hoje?

> TODO