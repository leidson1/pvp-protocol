# PVP — Transposição Git → Educação

**Por que o problema é estruturalmente idêntico**

---

## A Premissa

Antes de 2005, desenvolvedores de software enfrentavam um problema simples e devastador: toda vez que alguém melhorava um código e salvava por cima, a versão anterior desaparecia. Não havia histórico. Não havia como saber o que mudou, quando mudou, por que mudou, ou quem mudou. Se a mudança causasse um bug, não havia como voltar atrás.

Em 2005, Linus Torvalds criou o Git para resolver esse problema no desenvolvimento do kernel Linux. A ideia central: **todo artefato que evolui ao longo do tempo precisa de histórico, registro de mudança e rastreabilidade.**

Professores enfrentam exatamente o mesmo problema com planos de aula.

## O Mapeamento

| Git | PVP | O que faz |
|-----|-----|-----------|
| **Repository** | **PAV** (Plano de Aula Versionado) | Artefato central que carrega histórico. No Git, é o projeto com todos os arquivos. No PVP, é o plano de aula com todas as suas versões. |
| **Commit** | **RM** (Registro de Melhoria) | Unidade atômica de mudança. No Git, registra alteração no código com mensagem explicativa. No PVP, registra melhoria no plano com 3 campos (o quê, por quê, sinal de sala). |
| **Branch** | **VC** (Variação Contextual) | Linha paralela de desenvolvimento. No Git, permite trabalhar em funcionalidade nova sem afetar o código principal. No PVP, permite adaptar o plano para outro contexto (EJA, PEI) sem perder o original. |
| **Semantic Versioning** | **Versionamento Pedagógico** | Convenção de numeração X.Y.Z. No Git, comunica tipo de mudança (breaking/feature/fix). No PVP, comunica tipo de evolução (reestruturação/ajuste/micro-correção). |
| **Pull Request** | **SC** (Sugestão de Contribuição) | Proposta de mudança para revisão. No Git, outro desenvolvedor propõe alteração no repositório. No PVP, outro professor sugere melhoria no plano de um colega. |
| **Merge** | **Integração** | Incorporação de contribuição. No Git, pode ser automático. No PVP, requer curadoria humana do professor-autor. |
| **Changelog** | **Histórico de Versões** | Registro cronológico de todas as mudanças. |
| **Automated tests** | **Sinais de Sala** (E0-E3) | Validação de qualidade. No Git, testes automatizados verificam se o código funciona. No PVP, sinais de sala verificam se a aula funciona — mas em escala qualitativa, não binária. |

## O Que Diverge

A transposição é **conceitual, não técnica**. Os princípios foram transportados; a implementação é original.

| Aspecto | Git | PVP |
|---------|-----|-----|
| **Evidência** | Commit não exige prova de funcionamento | RM exige sinal de sala (Regra 4) |
| **Tecnologia** | Exige linha de comando e infraestrutura | Funciona com caneta e caderno |
| **Natureza do artefato** | Código (determinístico) | Aula (complexa, contextual, humana) |
| **Merge** | Automático (ou semi-automático) | Curadoria humana obrigatória |
| **Sintaxe** | Exige sintaxe exata | Aceita linguagem natural |
| **Contexto** | Ignora contexto de uso | Exige declaração de contexto (Regra 3) |
| **Conflitos** | Merge conflicts técnicos | Decisões pedagógicas contextuais |
| **Barreira de entrada** | Alta (curva de aprendizagem) | Baixa (90 segundos, 3 campos) |

## A Variação Contextual como Inovação

No Git, um branch é puramente técnico — pode ser criado, deletado, e recriado sem consequência. No PVP, uma VC tem motivação pedagógica e, em alguns casos, obrigação legal:

- **VC-EJA**: Adaptação para Educação de Jovens e Adultos (público diferente, tempo diferente, contexto diferente)
- **VC-PEI**: Plano Educacional Individualizado (obrigação legal para alunos com deficiência)
- **VC-Noturno**: Adaptação para turno noturno (alunos trabalhadores, tempo reduzido)
- **VC-Indígena**: Adaptação para escolas indígenas (bilinguismo, contexto cultural)

Cada VC mantém conexão rastreável com o PAV base. Melhorias que funcionam em qualquer contexto podem ser reintegradas ao base — como um merge reverso motivado por evidência.

## A Frase-Síntese

> Git transformou código-fonte de arquivo sobrescrito em artefato com memória.
> O PVP faz o mesmo com o plano de aula.

---

*PVP Core 1.0 · Leidison Lima dos Santos · CC BY 4.0 · 2026*
