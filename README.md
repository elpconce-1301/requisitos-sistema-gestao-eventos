# Engenharia de Requisitos com GenAI — Sistema de Gestão de Eventos (Eventus)

## 1. Descrição do projeto

A empresa Eventus organiza congressos, workshops e eventos corporativos.  
Atualmente, as inscrições são gerenciadas por meio de formulários on-line e planilhas eletrônicas, o que dificulta o controle de vagas, pagamentos, cancelamentos e emissão de certificados.  
Com o crescimento do número de eventos, a empresa decidiu desenvolver um sistema de gestão de eventos para centralizar essas atividades, oferecendo melhor experiência aos participantes e maior controle para os organizadores.

## 2. Objetivo da atividade

Esta atividade faz parte da unidade de **Análise e Especificação de Requisitos com IA Generativa**.  
A partir do documento de elicitação do Sistema de Gestão de Eventos, foram realizadas as seguintes tarefas:

- Identificação de requisitos funcionais, requisitos não funcionais e regras de negócio.
- Mapeamento de ambiguidades, inconsistências e lacunas que ainda precisam ser esclarecidas com os stakeholders.
- Seleção dos artefatos de especificação mais adequados para representar os requisitos do projeto.
- Elaboração dos artefatos escolhidos com apoio de uma ferramenta de IA generativa, sempre com revisão crítica humana.

## 3. Organização do repositório

O repositório segue a estrutura sugerida na atividade:

```text
engenharia-requisitos-genai/
├── README.md
├── analise/
│   ├── requisitos-funcionais.md
│   ├── requisitos-nao-funcionais.md
│   ├── regras-de-negocio.md
│   └── duvidas-e-lacunas.md
└── especificacao/
    ├── ...


A pasta **analise/** contém os artefatos derivados diretamente do documento de elicitação.  
A pasta **especificacao/** contém os artefatos escolhidos para representar o sistema.

---

# Reflexão sobre o Uso da Inteligência Artificial

## 4. Ferramenta de GenAI Utilizada

Foi utilizada a ferramenta **Microsoft Copilot (IA Generativa)** para apoiar a análise e a especificação dos requisitos.  
A IA atuou como suporte, enquanto as decisões finais foram tomadas manualmente para garantir alinhamento com o documento de elicitação.

## 5. Como a IA Apoiou as Etapas da Atividade

- Organizou as informações do documento de elicitação, ajudando a estruturar requisitos e regras de negócio.
- Auxiliou na identificação de ambiguidades e pontos indefinidos.
- Sugeriu artefatos adequados para representar o sistema (histórias de usuário, casos de uso, critérios de aceitação).
- Gerou versões iniciais dos artefatos, posteriormente revisadas e ajustadas manualmente.
- Contribuiu para melhorar clareza, padronização e completude dos requisitos.

## 6. Sugestões da IA Aceitas, Modificadas e Descartadas

### Sugestões Aceitas
- Estrutura de organização dos requisitos (RF, RNF, regras de negócio, lacunas).
- Formatos de artefatos (histórias de usuário, casos de uso, critérios de aceitação).
- Identificação de pontos indefinidos no documento.

### Sugestões Modificadas
- Requisitos reescritos para refletir fielmente o documento de elicitação.
- Ajustes nos casos de uso para representar fluxos específicos da Eventus.

### Sugestões Descartadas
- Funcionalidades não mencionadas pelos stakeholders.
- Requisitos que extrapolavam o escopo do sistema.

## 7. Justificativa dos Artefatos Escolhidos

Os artefatos selecionados foram:

- **Histórias de Usuário:** representam necessidades dos diferentes perfis (participantes, organizadores, equipe financeira, palestrantes).
- **Casos de Uso:** detalham fluxos críticos como inscrição, cancelamento, pagamento, emissão de certificados e lista de espera.
- **Critérios de Aceitação:** tornam os requisitos testáveis e claros, especialmente em funcionalidades com regras específicas.

Esses artefatos foram considerados os mais adequados porque:

- o sistema possui múltiplos perfis de usuários;
- há regras de negócio importantes (vagas, cancelamento, reembolso, conflitos de horário);
- os fluxos são transacionais e exigem clareza para implementação e testes;
- facilitam comunicação entre equipe de TI, organizadores e demais stakeholders.

