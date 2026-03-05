# PVP — Protocolo de Versionamento Pedagógico

> *Não é correção. É nova versão.*

O **PVP** é um protocolo aberto de melhoria contínua do planejamento pedagógico. Ele propõe que toda melhoria feita em um plano de aula seja tratada como nova versão de um artefato profissional — registrada de forma mínima, versionada semanticamente e acumulável ao longo da carreira.

**Codinome:** EduGit · **Versão:** Core 1.0 · **Licença:** CC BY 4.0

---

## O Problema

Todo professor, ao sair da sala, já sabe o que faria diferente. Esse pensamento dura segundos e desaparece. Quando muito, o professor ajusta o material e segue em frente — sem registro, sem histórico, sem acúmulo.

O resultado: décadas de conhecimento prático se perdem com a rotatividade, a aposentadoria ou simplesmente o esquecimento. Sem histórico, toda aula recomeça do zero.

O desenvolvimento de software enfrentou o mesmo problema até 2005, quando o Git transformou código-fonte de arquivo sobrescrito em artefato com memória. **O PVP faz o mesmo com o plano de aula.**

## A Solução

Um protocolo mínimo — **5 regras, 3 entidades, 90 segundos por registro** — que qualquer professor pode adotar com caneta e caderno.

### As 5 Regras

| # | Regra | Descrição |
|---|-------|-----------|
| 1 | **Versão explícita** | Todo plano carrega número de versão (X.Y.Z ou X.Y) |
| 2 | **Mudança registrada** | Toda melhoria vira um RM: o que mudou, por que, qual sinal de sala |
| 3 | **Contexto declarado** | O plano declara série, tempo, recursos e perfil da turma |
| 4 | **Evidência mínima** | Cada mudança requer pelo menos um sinal de sala observado |
| 5 | **Proveniência preservada** | Histórico de versões e autoria permanecem rastreáveis |

### As 3 Entidades

- **PAV** (Plano de Aula Versionado) — Qualquer plano que carrega número de versão e histórico. Formato livre.
- **RM** (Registro de Melhoria) — Anotação mínima de 90s com 3 campos: *o que mudou*, *por que mudou*, *sinal de sala observado*.
- **VC** (Variação Contextual) — Adaptação para outro contexto (EJA, PEI, noturno) mantendo conexão com o plano base.

### Versionamento Semântico Pedagógico

```
X . Y . Z
│   │   └── Patch: micro-correção (link, clareza, enunciado)
│   └────── Minor: ajuste (atividade, recurso, tempo)
└────────── Major: reestruturação (abordagem, público, sequência)
```

Formato simplificado `X.Y` é aceito.

### Escala de Evidência

| Nível | Nome | Critério |
|-------|------|----------|
| E0 | Rascunho | Nunca aplicado em sala |
| E1 | Aplicado 1× | Com observação do professor |
| E2 | Aplicado 2+× | Com checagem de aprendizagem |
| E3 | Multicontexto | Com Variação Contextual documentada |

## Instrumentos

### PVP Canvas

Instrumento de registro pós-aula. Três versões disponíveis:

| Versão | Formato | Uso |
|--------|---------|-----|
| [Completo](canvas/pvp-canvas-completo.html) | A4 paisagem, colorido | Canvas + Guia Rápido |
| [Monocromático](canvas/pvp-canvas-monocromatico.html) | A4 paisagem, P&B | Impressão econômica |
| [Mini](canvas/pvp-canvas-mini.html) | A5 paisagem, P&B | Versão de bolso para anexar |

## Transposição Git → PVP

| Git | PVP | Função |
|-----|-----|--------|
| Repository | PAV | Artefato versionado |
| Commit | RM | Registro atômico de mudança |
| Branch | VC | Variação contextual |
| Semantic Versioning | Versionamento Pedagógico | Convenção X.Y.Z |
| Pull Request | SC (Sugestão de Contribuição) | Proposta de melhoria |
| Changelog | Histórico de Versões | Registro cronológico |
| Automated tests | Sinais de Sala (E0-E3) | Validação por evidência |

**O que diverge:** O PVP exige sinal de sala (Git não exige evidência), funciona sem tecnologia, aceita linguagem natural, e opera com curadoria humana.

## Exemplo Rápido

**Aula:** Equação do 2º grau · v1.2.0

**Sinal de sala:** 70% dos alunos travaram na transição Bhaskara → problema contextualizado.

**RM (90 segundos):**

| Campo | Conteúdo |
|-------|----------|
| O que mudou | Inserir exemplo-ponte entre Bhaskara mecânico e problema contextualizado |
| Por que mudou | Transição direta pula etapa cognitiva; alunos precisam de passo intermediário |
| Sinal de sala | 70% travaram; após exemplo improvisado, 85% resolveram |

**Resultado:** v1.2.0 → **v1.3.0** · Ajuste (Y) · **E2**

## Fundamentação Teórica

- **Shulman (1986, 1987)** — PCK: o RM externaliza conhecimento tácito do professor
- **Nonaka & Takeuchi (1995)** — O RM transforma conhecimento tácito em explícito
- **Ohno (1988)** — Sistema puxado: melhoria puxada por sinais de sala, não empurrada por plataforma
- **Preston-Werner (2013)** — Semantic Versioning transposto para contexto pedagógico

## Documentação

| Documento | Descrição |
|-----------|-----------|
| [Especificação Core 1.0](docs/especificacao-core-1.0.md) | Especificação formal do protocolo |
| [FAQ](docs/faq.md) | Perguntas frequentes |
| [Defesa do Protocolo](docs/defesa.md) | Respostas a objeções e perguntas críticas |
| [Transposição Git](docs/transposicao-git.md) | Análise da transposição Git → PVP |

## Camadas de Implementação

| Camada | Nome | Requisitos | Tempo |
|--------|------|------------|-------|
| 1 | Essencial | Caneta e caderno | 90 segundos |
| 2 | Estruturado | Planilha ou Canvas impresso | 5 minutos |
| 3 | Colaborativo | Repositório compartilhado | Variável |
| 4 | Plataforma | Sistema digital com automações | Variável |

Cada camada funciona sozinha. A camada 1 é suficiente.

## Status

- [x] Protocolo Core 1.0 especificado
- [x] Canvas desenvolvido (3 versões)
- [x] Fundamentação teórica consolidada
- [x] FAQ e documentação de defesa
- [ ] Registro Biblioteca Nacional (EDA)
- [ ] Registro OSF + timestamp
- [ ] Integração Zenodo → DOI
- [ ] Revisão de escopo (JBI)
- [ ] Piloto UFT
- [ ] Publicação do artigo

## Como Citar

```bibtex
@misc{santos2026pvp,
  author       = {Santos, Leidison Lima dos},
  title        = {{PVP} — Protocolo de Versionamento Pedagógico (Core 1.0)},
  year         = {2026},
  howpublished = {\url{https://github.com/leidson1/pvp-protocol}},
  note         = {Licença CC BY 4.0}
}
```

## Licença

Este trabalho está licenciado sob [Creative Commons Attribution 4.0 International](LICENSE).

Você pode usar, adaptar e compartilhar livremente, desde que atribua a autoria original.

---

**Autor:** Leidison Lima dos Santos
**Instituição:** UFT
**Orientador:** Prof. Fernando Rodrigues Peixoto Quaresma

*Melhoria contínua puxada por sinais reais de sala, registrada minimamente, versionada semanticamente, acumulável ao longo da carreira.*
