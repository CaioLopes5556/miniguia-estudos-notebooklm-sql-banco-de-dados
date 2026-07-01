# 🗄️ SQL & Banco de Dados: Guia de Estudos e Curadoria

Bem-vindo(a) a este repositório dedicado ao meu [Notebook](https://) de **Banco de Dados** e à linguagem de consulta **SQL**. 

Escolhi este tema por ser extremamente útil tanto para a minha jornada profissional atual quanto para apoiar outras pessoas que estão ingressando na área de Tecnologia da Informação. Desde os tempos de curso técnico e faculdade, Banco de Dados e SQL sempre estiveram entre as minhas disciplinas favoritas.

Naquela época, antes do advento e da popularização de soluções de LLM (Modelos de Linguagem), centralizar e consumir conteúdos desse nicho exigia pesquisas exaustivas em livros e artigos na web. Com este recurso, meu objetivo é aprofundar os estudos, revisar conhecimentos consolidados e dominar novas técnicas avançadas para otimização de performance.

---

## 🎯 Objetivos do Repositório

* 🔄 **Revisão Contínua:** Fortalecer os fundamentos e conceitos essenciais já adquiridos.
* 📈 **Evolução Técnica:** Aprender novos conceitos, boas práticas de modelagem e técnicas de tuning para consultas mais rápidas.
* 🤝 **Compartilhamento:** Disponibilizar uma base sólida e organizada para estudantes e entusiastas de T.I.

---

## 📚 Curadoria de Fontes

Este projeto conta com uma seleção rigorosa de **30 fontes confiáveis** para embasamento teórico e prático.

### 🎥 Curso de Destaque
* **Curso de SQL (Prof. Gustavo Guanabara - Curso em Vídeo):** Uma escolha pautada na confiança e admiração de anos por este criador de conteúdo, que desempenha um papel fundamental na democratização do ensino de tecnologia no Brasil.
  * 🔗 [Acessar Playlist Completa no YouTube](https://youtube.com/playlist?list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r&si=zcY9dDFAjU5I26OY)

### 📖 Leituras Recomendadas e Documentações
* 📄 [Apostila de SQL — USP (FFCLRP)](https://sites.ffclrp.usp.br/cid/docentes/edberto/Apostilas/Apostila%20SQL.pdf): Material acadêmico completo para fundamentação teórica.
* 🌐 [Guia Completo da Linguagem SQL — DataGeeks](https://www.datageeks.com.br/linguagem-sql/): Artigo prático cobrindo desde a introdução até consultas intermediárias.
* 💡 [Subdivisões do SQL (DDL, DML, DQL e DCL) — LearnSQL](https://learnsql.com.br/blog/o-que-sao-ddl-dml-dql-e-dcl-em-sql/): Entenda detalhadamente a categorização dos comandos SQL.


## 🧠 Engenharia de Prompts e "Cicatrizes"

Um dos meus principais objetivos neste projeto foi personalizar profundamente a experiência com a Inteligência Artificial, especialmente na aba de conversas. Minha intenção era tornar a interação com o usuário muito menos robótica e mais próxima de uma relação dinâmica entre **Aluno e Professor**.

Para alcançar esse resultado, apliquei conceitos práticos de **Engenharia de Prompts** desenvolvidos no curso de IA da DIO. Estruturei a persona da IA definindo claramente:
* 🎭 **Papel (Persona):** Atuação como um instrutor didático e acessível.
* ⚙️ **Comportamento:** interação humanizada, empática e focada no aprendizado.
* 🛡️ **Limitações e Guardrails:** Barreiras de segurança para garantir respostas precisas e dentro do escopo.

Para assegurar que a IA não desviasse dessas diretrizes ao longo do tempo (evitando o alinhamento inadequado), implementei uma instrução de verificação contínua: a IA revisa silenciosamente esses tópicos essenciais antes de emitir cada resposta.

---

## 📸 Principais Prompts Testados

Abaixo estão os registros dos testes e iterações estruturadas durante o desenvolvimento:

| Iteração | Registro Visual do Prompt |
| :---: | :--- |
| **01** | `[Inserir PRINT 1]` |
| **02** | `[Inserir PRINT 2]` |
| **03** | `[Inserir PRINT 3]` |
| **04** | `[Inserir PRINT 4]` |
| **05** | `[Inserir PRINT 5]` |

---

## 🚀 Resultados Obtidos

Ao final dos testes, a IA entregou o conteúdo exatamente conforme as instruções fornecidas, apresentando os seguintes comportamentos padronizados:

1. **Apresentação Contextualizada:** Em toda primeira interação, ela se posiciona como um profissional experiente no assunto, pronto para ensinar e desmistificar diversos tópicos com uma linguagem natural e menos mecanizada.
2. **Feedback Ativo e Validação:** Na conclusão de cada resposta, a IA adota uma postura pedagógica, perguntando se o conteúdo foi bem compreendido pelo usuário (aluno).
3. **Cadeia de Pensamento (*Chain-of-Thought*):** Caso o usuário indique que restaram dúvidas, a IA ativa uma estrutura lógica de contingência — semelhante ao conceito de `if/else` da programação tradicional. Ela passa então a detalhar minuciosamente cada etapa do raciocínio lógico por trás do tema.

> 💡 **Insights de Desenvolvimento:** Foi extremamente gratificante aplicar lógica condicional complexa de forma tão intuitiva e fluida utilizando apenas linguagem natural. Isso reforça como os fundamentos da programação continuam sendo conceitos-chave essenciais e altamente aplicáveis na era da Inteligência Artificial Generativa.


## 📖 Miniguia de Estudos

Neste [Notebook](https://) estão concentrados os principais conceitos de modelagem de dados e bancos de dados relacionais. Este material foi estruturado tanto para quem está iniciando sua jornada na área de Tecnologia da Informação quanto para profissionais que buscam revisar fundamentos e se aprofundar em técnicas avançadas de otimização.

---

## 🗺️ O que você vai aprender?

### 🏗️ Fundamentos e Modelagem
* **SGBD (Sistema Gerenciador de Banco de Dados):** Software responsável por gerenciar o acesso, a segurança, a concorrência e a organização estrutural dos dados (Ex: MySQL, PostgreSQL, SQL Server).
* **Modelagem de Dados (MER e DER):** Compreensão do Modelo Entidade-Relacionamento e seu respectivo diagrama para documentar a arquitetura do banco.
* **Modelo Relacional:** Estrutura que organiza as informações em tabelas (relações), compostas por linhas (registros ou tuplas) e colunas (atributos).

### 🔑 Chaves e Consistência
* **Chave Primária (Primary Key - PK):** Atributo que identifica de forma única e exclusiva cada registro em uma tabela, sendo obrigatório (`NOT NULL`) e não repetível.
* **Chave Estrangeira (Foreign Key - FK):** Campo que aponta para a chave primária de outra tabela, estabelecendo o vínculo lógico entre elas.
* **Integridade Referencial:** Mecanismo de consistência que garante a validade dos relacionamentos, impedindo a existência de registros "órfãos" no banco de dados.

### 🔤 Subdivisões da Linguagem SQL
* **🛠️ DDL (*Data Definition Language*):** Comandos que definem, modificam ou eliminam a estrutura dos objetos do banco. *Exemplos:* `CREATE`, `ALTER`, `DROP`.
* **✍️ DML (*Data Manipulation Language*):** Comandos voltados à manipulação do conteúdo e dos dados armazenados nas tabelas. *Exemplos:* `INSERT`, `UPDATE`, `DELETE`.
* **🔍 DQL (*Data Query Language*):** Focada exclusivamente na consulta e extração de dados através do comando `SELECT`.

### 🔄 Consultas Avançadas e Agrupamentos
* **🔗 JOINs:** Cláusulas utilizadas para combinar colunas de duas ou mais tabelas em um único resultado, com base em um relacionamento comum (Ex: `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`).
* **📊 Funções de Agregação:** Ferramentas para realizar cálculos matemáticos e estatísticos sobre um conjunto de valores. *Exemplos:* `COUNT`, `SUM`, `AVG`, `MAX`, `MIN`.
* **🎛️ Filtros e Agrupamentos:** Cláusulas essenciais para refinar buscas:
  * `WHERE`: Filtra linhas antes do agrupamento.
  * `GROUP BY`: Agrupa registros com valores idênticos.
  * `HAVING`: Filtra os resultados após o agrupamento baseado em funções agregadas.
  * `ORDER BY`: Ordena o resultado final.

---

## 🤖 Prompts Reutilizáveis para Revisão

Para potencializar seus estudos utilizando este repositório em conjunto com uma IA, utilize a lista de comandos testados abaixo:

* 📝 *"Faça um resumo didático sobre os principais conceitos da modelagem de dados (MER e DER)."*
* 🛠️ *"Quais são as diferenças práticas entre os comandos de definição (DDL) e manipulação (DML)?"*
* 🔑 *"Explique com exemplos práticos o papel das chaves primárias, chaves estrangeiras e a importância da integridade referencial."*
* 🔄 *"Como funcionam as chaves estrangeiras no ecossistema de banco de dados e quais as diferenças entre os tipos de JOIN?"*
* 🧼 *"Quais são os principais padrões de nomenclatura, indentação e boas práticas para queries SQL?"*
* ⚠️ *"Qual é a diferença conceitual e de performance entre os comandos DELETE e TRUNCATE?"*
* 💻 *"Escreva um exemplo prático de como usar o comando INNER JOIN para relacionar duas tabelas."*
