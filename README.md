# ATHENA

Plataforma web para gestão, manutenção e rastreabilidade de requisitos de software.

## Integrantes

- Ana Clara Rocha Gomes
- Bárbara Oliveira Fonseca
- Fernando Chaves Scarabeli
- Jhennifer Hellen Campos Silva
- José Vítor Machado de Oliveira

## Problema

Durante o desenvolvimento de software, requisitos, histórias de usuário, regras de negócio, critérios de aceitação e outros artefatos estão relacionados entre si. Quando um requisito é alterado, essa mudança pode impactar outros requisitos, funcionalidades, cenários de teste e artefatos utilizados pela equipe. Entretanto, essas relações frequentemente permanecem implícitas ou distribuídas entre diferentes documentos, ferramentas e conversas. Como consequência, a identificação dos impactos de uma mudança pode depender da memória e do conhecimento de pessoas específicas da equipe. Isso pode fazer com que alterações sejam incorporadas apenas parcialmente, deixando requisitos ou artefatos desatualizados e gerando retrabalho, perda de tempo e consumo adicional de recursos.

## Público-alvo

O ATHENA é voltado principalmente para profissionais e equipes envolvidos na especificação, desenvolvimento e manutenção de software, incluindo:

- Analistas de requisitos;
- Product Owners;
- Desenvolvedores;
- Profissionais de qualidade e testes;
- Gestores de projetos;
- Equipes de desenvolvimento de software.

## Proposta de valor

O ATHENA busca ajudar equipes de software a identificar o que pode precisar ser revisado quando um requisito é alterado.

A plataforma funciona como uma camada complementar às ferramentas já utilizadas pela equipe, organizando documentos e requisitos, explicitando as relações entre eles e apoiando a identificação e análise dos possíveis impactos de mudanças.

Seu objetivo não é substituir ferramentas como Google Drive, GitHub, Jira ou OpenProject, mas conectar informações e artefatos já existentes, tornando dependências e impactos mais visíveis.

Com isso, o ATHENA pretende reduzir:

- A dependência da memória individual;
- A consulta manual a múltiplas ferramentas;
- O risco de alterações serem propagadas apenas parcialmente;
- Inconsistências entre requisitos e outros artefatos;
- O esforço necessário para analisar mudanças.

## Descrição do MVP

O MVP do ATHENA deverá permitir o fluxo principal de manutenção e análise de requisitos:

1. Cadastrar ou importar documentos e requisitos;
2. Registrar relações entre requisitos;
3. Visualizar relações por meio de rastreabilidade;
4. Alterar e versionar um requisito;
5. Analisar possíveis impactos provocados pela alteração;
6. Apresentar sugestões de itens potencialmente afetados;
7. Permitir que o usuário aceite, rejeite ou corrija as sugestões;
8. Registrar a decisão tomada durante a revisão.

### Funcionalidades previstas para o MVP

- Cadastro e importação de requisitos;
- Requisitos estruturados;
- Registro manual de relações;
- Mapa de rastreabilidade;
- Histórico e versionamento;
- Comparação entre versões;
- Análise assistida de impacto;
- Fluxo básico de revisão;
- Integração inicial com uma fonte de documentação;
- Integração inicial com uma ferramenta de gestão do trabalho.
- Sincronização com ferramentas populares, como o google drive, open project e o github.


## Tecnologias utilizadas

> As tecnologias ainda estão em processo de definição e poderão ser refinadas durante o desenvolvimento.

### Front-end

- Angular;
- TypeScript.

### Back-end

- Java 17;
- Spring Boot.

### Banco de dados

- PostgreSQL.

### APIs

- APIs HTTP;
- OpenAPI / Swagger.

### Inteligência Artificial

A inteligência artificial será utilizada para apoiar:

- Análise de alterações em requisitos;
- Identificação de possíveis relações;
- Detecção de problemas de qualidade;
- Sugestão de possíveis impactos de mudanças.

As sugestões produzidas pela IA não serão aplicadas automaticamente. A decisão final permanecerá sob responsabilidade dos usuários.

### Infraestrutura e DevOps

- Docker;
- Kubernetes;
- Git;
- GitHub;
- Possível utilização de CI/CD;
- SonarQube;
- Prometheus;
- Grafana.

## Como executar

> Esta seção será atualizada conforme a implementação do sistema avançar.

### Pré-requisitos

- Java 17;
- Node.js;
- Angular CLI;
- Docker;
- PostgreSQL.

### Execução

```bash
git clone [URL_DO_REPOSITORIO]
cd athena

# Instruções de execução serão adicionadas durante o desenvolvimento.
