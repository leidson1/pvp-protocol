# PVP — Especificação Core 1.0

**Protocolo de Versionamento Pedagógico**
Versão: 1.0.0 · Data: 2026-03-04 · Autor: Leidison Lima dos Santos · Licença: CC BY 4.0

---

## 1. Definição

O PVP (Protocolo de Versionamento Pedagógico) é um conjunto mínimo de regras para registro, versionamento e acúmulo de melhorias em planos de aula. Inspira-se nos princípios do controle de versão de software (Git), transpondo-os para a realidade do planejamento pedagógico.

O PVP é **protocolo** — não metodologia, framework ou sistema. Um professor que segue as 5 regras está usando o PVP. Um professor que não segue, não está.

## 2. Justificativa

O professor brasileiro trabalha em média 9,3 horas semanais em planejamento (OECD TALIS, 2024), atende múltiplas turmas, e opera em contexto de alta rotatividade. Melhorias identificadas após cada aula são voláteis: existem na mente do professor por segundos e se perdem sem registro. O conhecimento pedagógico prático (PCK — Shulman, 1986) permanece tácito e desaparece com a mudança de escola, turma ou ano letivo.

O PVP propõe infraestrutura mínima para que esse conhecimento seja registrado, acumulado e rastreável.

## 3. Regras

### Regra 1 — Versão explícita
Todo plano de aula sob o PVP carrega número de versão no formato `X.Y.Z` ou `X.Y`.

### Regra 2 — Mudança registrada
Toda melhoria é documentada em um Registro de Melhoria (RM) contendo obrigatoriamente três campos: (a) o que mudou, (b) por que mudou, (c) sinal de sala que motivou a mudança.

### Regra 3 — Contexto declarado
O plano declara seu contexto de aplicação: série/ano, tempo de aula, recursos disponíveis e perfil da turma.

### Regra 4 — Evidência mínima
Cada RM requer pelo menos um sinal de sala observado — evidência empírica coletada durante ou após a aplicação da aula.

### Regra 5 — Proveniência preservada
O histórico de versões e a autoria permanecem rastreáveis ao longo do tempo. Nenhuma versão anterior é apagada; são substituídas por versões novas.

## 4. Entidades

### 4.1 PAV — Plano de Aula Versionado

Qualquer plano de aula que passa a carregar número de versão e histórico de mudanças. O formato é agnóstico: pode ser caderno, documento digital, planilha, slide ou qualquer suporte. O PAV é o **artefato** do protocolo.

**Campos mínimos do PAV:**
- Identificação (disciplina, tema, série, autor)
- Versão atual (X.Y.Z ou X.Y)
- Contexto (Regra 3)
- Conteúdo do plano (formato livre)
- Histórico de versões

### 4.2 RM — Registro de Melhoria

A unidade atômica de mudança do protocolo. Cada RM documenta uma melhoria específica com tempo estimado de preenchimento de 90 segundos.

**Campos obrigatórios:**
1. **O que mudou** — Descrição concreta da alteração
2. **Por que mudou** — Justificativa conectada à prática
3. **Sinal de sala** — Evidência observacional que motivou a mudança

**Campos opcionais:**
- Data de registro
- Tipo de mudança (X, Y ou Z)
- Resultado observado após implementação

### 4.3 VC — Variação Contextual

Adaptação de um PAV para contexto diferente do original, mantendo conexão rastreável com o plano base. A VC resolve o problema de professores que atuam em múltiplos contextos (regular/EJA, matutino/noturno, presencial/remoto, regular/PEI).

**Características:**
- Identifica o PAV base de origem
- Declara o contexto específico da variação
- Mantém histórico próprio de versões
- Melhorias universais podem ser reintegradas ao PAV base

**Nomenclatura sugerida:** VC-[contexto] (ex: VC-EJA, VC-PEI, VC-Noturno)

## 5. Versionamento Semântico Pedagógico

Baseado no Semantic Versioning (Preston-Werner, 2013), adaptado:

| Posição | Nome | Incrementa quando... | Exemplo |
|---------|------|----------------------|---------|
| X | Major | Reestruturação significativa: mudança de abordagem, público-alvo, redesenho da sequência | 1.3.0 → 2.0.0 |
| Y | Minor | Ajuste dentro da mesma estrutura: troca de atividade, adição de exemplo, redistribuição de tempo | 1.2.0 → 1.3.0 |
| Z | Patch | Micro-correção: link quebrado, clareza de instrução, correção de enunciado | 1.3.0 → 1.3.1 |

**Regras de incremento:**
- Quando X incrementa, Y e Z voltam a zero
- Quando Y incrementa, Z volta a zero
- O formato simplificado X.Y é aceito (Z implícito = 0)
- A versão inicial é 1.0.0 (ou 1.0)

## 6. Escala de Evidência

Escala de maturidade do plano baseada no nível de validação empírica:

| Nível | Nome | Critério | Indicador |
|-------|------|----------|-----------|
| E0 | Rascunho | Plano nunca aplicado em sala | Planejamento teórico |
| E1 | Aplicado 1× | Aplicado pelo menos uma vez com observação do professor | Observação docente informal |
| E2 | Aplicado 2+× | Aplicado duas ou mais vezes com checagem de aprendizagem | Exercício, atividade diagnóstica ou avaliação |
| E3 | Multicontexto | Aplicado em contextos diferentes com Variação Contextual documentada | VC registrada e funcional |

**Notação:** A evidência é indicada após a versão. Exemplo: `v3.2.1 — E3`

## 7. Camadas de Implementação

O protocolo é implementável em quatro camadas progressivas. Cada camada funciona de forma autônoma.

| Camada | Nome | Descrição | Requisitos |
|--------|------|-----------|------------|
| 1 | Essencial | Professor preenche RM com 3 campos em 90s após a aula | Caneta e caderno |
| 2 | Estruturado | Uso do Canvas PVP, organização em planilha, histórico formal | Canvas impresso ou planilha |
| 3 | Colaborativo | Compartilhamento institucional, contribuições entre pares, curadoria | Repositório compartilhado, coordenação |
| 4 | Plataforma | Sistema digital com automações, busca, integração BNCC, análise de dados | Plataforma web/app |

## 8. Sinal de Sala

Conceito central do PVP. Sinal de sala é qualquer evidência observacional que o professor coleta durante ou após a aula e que motiva uma melhoria. Não exige instrumento formal, pesquisa padronizada ou análise estatística.

**Exemplos válidos:**
- "70% dos alunos erraram a questão 3 no exercício de fixação"
- "A turma dispersou após 20 minutos de exposição"
- "Os alunos do fundo se engajaram quando troquei o exemplo abstrato por concreto"
- "Nenhum aluno conseguiu iniciar a atividade sem pedir ajuda"
- "Dois alunos perguntaram a mesma dúvida independentemente"

**O sinal de sala torna o PVP um sistema puxado:** a melhoria é puxada pela realidade observada, não empurrada por teoria, plataforma ou diretriz externa.

## 9. Transposição Git → PVP

| Git | PVP | Função | Divergência |
|-----|-----|--------|-------------|
| Repository | PAV | Artefato versionado | PAV é format-agnostic |
| Commit | RM | Registro atômico de mudança | RM exige sinal de sala |
| Branch | VC | Variação para outro contexto | VC tem motivação pedagógica/legal |
| Semantic Versioning | Versionamento Pedagógico | Convenção X.Y.Z | Categorias adaptadas |
| Pull Request | SC | Proposta de melhoria | Curadoria humana obrigatória |
| Merge | Integração | Incorporação de contribuição | Sem merge automático |
| Changelog | Histórico de Versões | Registro cronológico | — |
| Automated tests | Sinais de Sala | Validação | Escala qualitativa E0-E3 |

## 10. Referências

1. SHULMAN, L. S. Those who understand: knowledge growth in teaching. *Educational Researcher*, v. 15, n. 2, p. 4-14, 1986.
2. SHULMAN, L. S. Knowledge and teaching: foundations of the new reform. *Harvard Educational Review*, v. 57, n. 1, p. 1-22, 1987.
3. NONAKA, I.; TAKEUCHI, H. *The Knowledge-Creating Company*. Oxford University Press, 1995.
4. OHNO, T. *Toyota Production System: Beyond Large-Scale Production*. Productivity Press, 1988.
5. PRESTON-WERNER, T. *Semantic Versioning 2.0.0*. 2013. Disponível em: https://semver.org.
6. LEWIS, C. *Lesson Study: A Handbook of Teacher-Led Instructional Change*. Research for Better Schools, 2002.
7. OECD. *TALIS 2024 Results*. OECD Publishing, 2024.
8. INEP. *Censo Escolar da Educação Básica 2024*. Brasília: MEC/INEP, 2024.
9. CETIC.BR. *TIC Educação 2024*. São Paulo: CGI.br, 2024.
10. McNIFF, J. *Action Research: Principles and Practice*. 3rd ed. Routledge, 2013.

---

*PVP Core 1.0 · Leidison Lima dos Santos · CC BY 4.0 · 2026*
