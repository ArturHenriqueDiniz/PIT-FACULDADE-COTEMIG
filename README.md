# ConectaFuturo

**Plataforma inteligente para orientar escolhas acadêmicas e aproximar estudantes de seus futuros.**

## Sobre o projeto

O ConectaFuturo é uma plataforma web que tem como objetivo auxiliar estudantes na escolha de cursos de graduação e instituições de ensino superior. A proposta é centralizar informações acadêmicas e oferecer recomendações personalizadas com base nos interesses, nas preferências e no histórico escolar informado pelos usuários.

Além de apoiar a pesquisa e a comparação entre cursos e faculdades, a plataforma pretende oferecer recursos para salvar opções favoritas, consultar informações sobre valores, bolsas e benefícios e compartilhar experiências por meio de uma rede social educacional.

## Problema abordado

Estudantes que estão se preparando para ingressar no ensino superior podem encontrar dificuldades para reunir e comparar informações sobre cursos e instituições. Dados sobre modalidades, turnos, custos e oportunidades de bolsas podem estar dispersos, enquanto a falta de orientação personalizada aumenta a insegurança durante a escolha.

O ConectaFuturo busca enfrentar esse problema reunindo informações em um único ambiente e oferecendo ferramentas para tornar a decisão mais informada e consciente.

## Objetivo geral

Desenvolver uma plataforma que auxilie estudantes a identificar cursos e faculdades compatíveis com seus perfis, interesses e histórico escolar, por meio de recomendações personalizadas e de recursos de interação educacional.

## Objetivos específicos

- Identificar as principais dificuldades enfrentadas pelos estudantes ao escolher cursos e instituições.
- Permitir a pesquisa e a filtragem de cursos por critérios relevantes, como modalidade e turno.
- Oferecer recomendações personalizadas de cursos e instituições.
- Facilitar a comparação entre alternativas acadêmicas.
- Reunir informações disponíveis sobre valores, bolsas e benefícios.
- Permitir que usuários salvem cursos e instituições como favoritos.
- Promover a troca de experiências e conteúdos entre estudantes.
- Permitir que representantes de instituições cadastrem e atualizem informações sobre seus cursos.

## Funcionalidades previstas

- Cadastro e gerenciamento do perfil do estudante.
- Recomendações personalizadas de cursos e instituições.
- Pesquisa e filtros de cursos.
- Comparação de cursos e instituições.
- Consulta a valores, bolsas e benefícios disponíveis.
- Lista de cursos e instituições favoritos.
- Publicação de experiências e conteúdos educacionais.
- Comentários, respostas e interação entre usuários.
- Cadastro e apresentação de cursos por instituições de ensino.
- Atualização das informações institucionais.

## Product Backlog

Os itens estão organizados por prioridade inicial, considerando o valor para o usuário e as dependências entre funcionalidades. A prioridade poderá ser revista durante o desenvolvimento.

| Prioridade | ID | História de usuário | Critério de aceite resumido |
|---|---|---|---|
| Alta | US01 | Como estudante, quero criar meu perfil informando interesses, desempenho e preferências, para receber recomendações compatíveis comigo. | O perfil pode ser criado com os dados básicos e as preferências informadas. |
| Alta | US09 | Como representante de uma instituição, quero cadastrar e apresentar informações dos cursos oferecidos, para que estudantes encontrem dados claros. | A instituição consegue cadastrar cursos e exibir suas informações básicas. |
| Alta | US10 | Como representante de uma instituição, quero manter as informações institucionais atualizadas, para evitar decisões baseadas em dados desatualizados. | A instituição consegue editar informações e visualizar os dados atualizados. |
| Alta | US02 | Como estudante em processo de escolha, quero receber recomendações personalizadas, para tomar uma decisão mais consciente. | O sistema apresenta cursos e instituições recomendados com base no perfil. |
| Alta | US03 | Como estudante que trabalha, quero filtrar cursos por modalidade, turno e outros critérios, para encontrar opções compatíveis com minha rotina. | Os filtros selecionados limitam os resultados exibidos. |
| Alta | US04 | Como estudante, quero comparar cursos e instituições lado a lado, para identificar as diferenças entre as opções. | O sistema apresenta critérios relevantes das opções selecionadas. |
| Média | US05 | Como estudante com preocupações financeiras, quero consultar valores, bolsas e benefícios, para avaliar opções dentro do meu planejamento. | As informações financeiras disponíveis são exibidas claramente. |
| Média | US06 | Como estudante, quero salvar cursos e faculdades como favoritos, para revisar minhas opções posteriormente. | É possível adicionar e remover itens da lista de favoritos. |
| Média | US07 | Como estudante universitário, quero publicar minha experiência sobre curso e instituição, para ajudar outros estudantes. | O estudante consegue publicar um relato ou conteúdo acadêmico. |
| Média | US08 | Como participante da rede educacional, quero responder perguntas e interagir com outros usuários, para trocar experiências e conhecimentos. | O estudante consegue comentar, responder e participar das interações. |

### Critérios de priorização

- **Alta:** funcionalidades fundamentais para viabilizar o serviço principal e disponibilizar informações confiáveis sobre cursos e instituições.
- **Média:** funcionalidades que ampliam a experiência, a organização das escolhas e a interação entre usuários.
- **Observação:** a ordem é uma proposta inicial para o Product Backlog e pode ser ajustada pela equipe conforme dependências técnicas, validações e evolução do projeto.

## Tecnologias previstas

As tecnologias abaixo são as previstas no planejamento do projeto; sua implementação poderá ser detalhada e confirmada durante o desenvolvimento.

- **React.js:** desenvolvimento da interface web interativa.
- **Node.js e Express.js:** implementação do backend, das regras de negócio e das APIs.
- **PostgreSQL:** armazenamento estruturado de usuários, perfis, cursos, instituições, favoritos, publicações e comentários.
- **HTML, CSS e JavaScript:** estrutura, estilo e funcionalidades da interface web.
- **Algoritmo de recomendação personalizada:** análise de interesses, preferências e histórico escolar informado para sugerir cursos e instituições compatíveis.
- **Git e GitHub:** controle de versões e colaboração entre integrantes.

## Arquitetura prevista

O sistema utilizará uma arquitetura cliente-servidor. O frontend, desenvolvido com React.js, apresentará a interface ao usuário e se comunicará com o backend por meio de uma API. O backend, planejado com Node.js e Express.js, processará as solicitações, aplicará as regras de negócio e acessará o banco de dados PostgreSQL.

## Integrantes

- **Gustavo Lima**
- **Artur Diniz**

## Instituição e disciplina

- **Instituição:** Faculdade COTEMIG
- **Disciplina:** Projeto de Inovação Tecnológica I (PIT 1)
- **Área de concentração:** Tecnologia e Educação
- **Orientador:** Humberto Fernandes Villela
- **Local e ano:** Belo Horizonte, 2026

## Status do projeto

Projeto em fase de planejamento e organização dos requisitos. As tecnologias e funcionalidades descritas são previstas para a implementação.

---

*Projeto acadêmico desenvolvido para fins educacionais.*
