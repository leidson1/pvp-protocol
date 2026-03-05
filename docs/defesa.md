# PVP — Defesa do Protocolo

**Respostas a objeções e perguntas críticas · Core 1.0**

---

— PERGUNTAS CAPCIOSAS E DEFESA

Perguntas que um avaliador, banca, colega cético ou crítico pode fazer para tentar desqualificar ou questionar a validade do protocolo. As respostas refletem a visão honesta de defesa, incluindo limitações reconhecidas.

---

### C1. "Pra que isso? O professor já melhora suas aulas naturalmente. Você está inventando burocracia."

**Essa é a objeção mais previsível e a mais importante de responder bem.**

Sim, o professor já melhora naturalmente. Esse é exatamente o ponto. O PVP não propõe que o professor faça algo novo — propõe que o que ele já faz ganhe registro, estrutura e acúmulo. A melhoria natural acontece, mas é volátil: existe por segundos na mente do professor e desaparece. Quando ele muda de escola, de turma, de ano, décadas de conhecimento prático se perdem.

A analogia direta: um programador também "melhorava" código antes do Git. Salvava por cima, perdia versões, não sabia o que tinha mudado ou por quê. O Git não inventou a melhoria de código — deu infraestrutura para que ela fosse rastreável, reversível e compartilhável. Hoje 94% dos desenvolvedores usam controle de versão. Ninguém diria que é burocracia.

A diferença entre "já faço isso" e burocracia é o custo do registro. O RM leva 90 segundos. Se 90 segundos após a aula é burocracia, então anotar o diário de classe também é.

---

### C2. "Isso é só um commit do Git com outro nome. Não tem contribuição original."

A contribuição não é reinventar o commit — é demonstrar que o princípio do commit é transponível para o planejamento pedagógico e que essa transposição resolve um problema real e documentado.

A originalidade está em três pontos:
1. **A transposição em si.** Ninguém na literatura fez essa ponte formalmente. A revisão de escopo mostrará isso. Existem trabalhos sobre Git na educação, mas como ferramenta para ensinar programação — não como modelo conceitual para planejamento de aulas.
2. **O campo "sinal de sala".** O commit do Git não exige evidência de funcionamento. O RM exige. Isso transforma o protocolo em sistema puxado pela prática, não apenas registro mecânico.
3. **A Variação Contextual (VC).** A noção de branch no Git é técnica. A VC resolve um problema pedagógico real: o mesmo professor que dá aula de manhã no regular e à noite no EJA precisa de variações rastreáveis do mesmo plano, com conexão com o base. Isso não existe em nenhum modelo atual de planejamento.

Se a objeção é "já existe no software", a resposta é: Kanban também já existia na Toyota antes de ser transposto para o desenvolvimento de software. A transposição é a contribuição.

---

### C3. "O professor não tem tempo pra isso. A carga horária já é insuficiente."

Resposta honesta: essa é uma objeção legítima e parcialmente verdadeira. A carga horária do professor brasileiro é pesada. Mas o argumento tem uma falha: ele assume que o PVP adiciona tempo. O PVP substitui tempo desperdiçado.

Hoje, o professor que quer melhorar sua aula gasta tempo tentando lembrar o que deu errado, procurando a versão anterior do arquivo, recriando material que já existia em outro formato. Esse tempo é invisível mas real.

O RM leva 90 segundos. Três campos. Pode ser preenchido no celular entre uma aula e outra, na volta pra sala dos professores, ou no final do turno. Se o professor consegue preencher o diário de classe, consegue preencher o RM.

Além disso, o nível 1 (Essencial) foi desenhado para funcionar com o mínimo absoluto. Se 90 segundos ainda for demais, o professor pode anotar apenas os sinais de sala mais impactantes — e já está gerando valor.

---

### C4. "Já existem plataformas de planejamento de aula. O PVP não é redundante?"

Plataformas de planejamento (Nova Escola, Google Classroom, sistemas estaduais) resolvem o problema de armazenamento, não de versionamento. Elas permitem que o professor guarde o plano, mas não registram por que ele mudou, o que motivou a mudança, nem mantêm histórico das versões anteriores.

A analogia: o Google Docs permite editar um texto. O Git permite versionar o texto. São problemas diferentes. O PVP define o protocolo de versionamento — e pode funcionar dentro de qualquer plataforma existente, ou fora de todas elas.

Nenhuma plataforma de planejamento atual oferece: versionamento semântico, registro de mudança com sinal de sala, variação contextual rastreável, ou escala de maturidade por evidência. Isso foi verificado empiricamente e pode ser demonstrado.

---

### C5. "Versionamento semântico é coisa de programador. O professor não vai entender."

Três números separados por pontos não exigem conhecimento de programação. O professor já lida com sistemas de numeração mais complexos: códigos BNCC (EF06MA01), classificação de habilidades, diários com códigos de frequência.

"v1.3.0" comunica: "esse plano já passou por uma reestruturação, três ajustes, e nenhuma micro-correção desde o último ajuste." Essa informação é imediatamente útil e intuitivamente compreensível.

Além disso, o formato simplificado X.Y é aceito pelo protocolo para quem preferir. A barreira é percebida, não real. Nos testes piloto, a expectativa é demonstrar isso empiricamente.

---

### C6. "Lesson Study já faz isso. Qual a diferença?"

Lesson Study (Lewis, 2002) é um modelo colaborativo de melhoria de aula desenvolvido no Japão. É um modelo excelente e o PVP não se opõe a ele — se complementa.

As diferenças concretas:
- **Lesson Study exige grupo.** Mínimo 3-4 professores, com tempo dedicado, planejamento conjunto, observação cruzada. O PVP funciona sozinho.
- **Lesson Study é cíclico e intensivo.** Cada ciclo leva semanas. O PVP é contínuo e leve — 90 segundos por aula.
- **Lesson Study não versiona.** Não há numeração, histórico rastreável ou escala de evidência. As melhorias ficam no relatório do ciclo.
- **Lesson Study não viaja com o professor.** Quando o professor muda de escola, o ciclo de Lesson Study fica na escola antiga. O PVP viaja com o PAV.
- **Lesson Study exige infraestrutura institucional.** Coordenação, tempo protegido, cultura colaborativa. O PVP funciona na ausência de tudo isso.

Um professor que participa de Lesson Study pode usar o PVP para registrar as melhorias de cada ciclo com versionamento semântico. Os dois são compatíveis. A diferença é que o PVP é o protocolo mínimo que funciona quando o Lesson Study não é viável — que é a maioria dos contextos na educação pública brasileira.

---

### C7. "Onde está a validação empírica? Sem dados, isso é só opinião."

Essa é uma objeção legítima e precisa ser tratada com honestidade. O PVP, neste momento, é uma proposição teórica com fundamentação conceitual. Não tem dados empíricos de implementação ainda.

A resposta é que a validação empírica está planejada como próxima etapa (piloto na UFT), e que a contribuição atual é conceitual, não empírica. Muitos protocolos e frameworks foram publicados primeiro como proposição teórica e depois validados: o próprio Semantic Versioning (Preston-Werner, 2013) foi publicado como especificação antes de ser adotado em massa; o Kanban foi descrito como modelo antes de ser medido empiricamente no software.

No artigo, o enquadramento correto é: "Este trabalho propõe e descreve formalmente o protocolo. A validação empírica é indicada como trabalho futuro." Isso é academicamente legítimo — desde que o autor não faça claims empíricos que não possui.

O que já pode ser demonstrado sem piloto:
- Que o problema existe (dados TALIS, TIC Educação, literatura sobre PCK tácito)
- Que nenhum modelo existente combina versionamento semântico + micro-documentação + rastreabilidade (revisão de escopo)
- Que a transposição Git → Educação é conceitualmente coerente (análise teórica)

---

### C8. "O professor vai abandonar em duas semanas. Não é sustentável."

Possível. E essa é a pergunta certa a fazer. A resposta tem três camadas:

**Camada 1 — Design para abandono parcial.** O PVP foi desenhado para que mesmo o uso parcial gere valor. Se o professor preencher 10 RMs em dois meses e depois parar, ele tem 10 registros que antes não existiam. Não é tudo ou nada.

**Camada 2 — A barreira é baixa o suficiente.** 90 segundos, 3 campos, sem plataforma obrigatória. A maioria das ferramentas educacionais falha por exigir demais. O PVP exige o mínimo que ainda produz resultado. Se o mínimo ainda for demais, o problema é maior do que qualquer protocolo pode resolver.

**Camada 3 — Sustentabilidade depende de valor percebido.** Se o professor vê que o v1.3.0 da sua aula funciona melhor que o v1.0.0 e consegue explicar por quê, ele tem incentivo para continuar. Se não percebe valor, abandona — e isso é informação legítima sobre o protocolo, não sobre o professor.

O piloto vai medir exatamente isso: taxa de adesão, taxa de abandono, momento de abandono, e motivos declarados. Se a sustentabilidade for baixa, isso é resultado, não fracasso.

---

### C9. "Isso não é protocolo. Protocolo tem padrão técnico, RFC, especificação formal."

A palavra "protocolo" não pertence exclusivamente à ciência da computação. Protocolos médicos (protocolo de Manchester, protocolos de triagem) são conjuntos de regras acordadas para padronizar procedimentos. Protocolos de pesquisa (revisão sistemática, ensaio clínico) definem passos obrigatórios e critérios de qualidade.

O PVP é protocolo no sentido preciso: conjunto mínimo de regras que, se seguidas, produzem resultado previsível e replicável. Tem entidades definidas (PAV, RM, VC), convenção de numeração (X.Y.Z), campos obrigatórios, e escala de maturidade. Quem segue as 5 regras está usando o PVP. Quem não segue, não está. Isso é protocolo.

Se a objeção for que "protocolo precisa de RFC", a resposta é que RFC é formato de publicação, não definição de protocolo. O PVP tem sua especificação formal publicada em repositório aberto — que é, aliás, mais do que a maioria dos protocolos educacionais possui.

---

### C10. "Versionar plano de aula é mecanizar o ensino. Educação não é software."

Essa objeção confunde ferramenta com filosofia. Versionar um plano não mecaniza o ensino — mecanizar seria padronizar o plano e impedir variação. O PVP faz o oposto: incentiva variação (VC), registra adaptação contextual, e valoriza a decisão profissional do professor como motor da evolução.

O versionamento é infraestrutura, não ideologia. Da mesma forma que um músico pode usar partitura sem que isso mecanize sua interpretação, o professor pode usar versionamento sem que isso mecanize sua prática.

A analogia inversa: sem versionamento, o que temos é justamente a mecanização — o professor usando o mesmo plano toda vez, sem registro de que algo mudou ou deveria mudar. O PVP é a ferramenta da anti-mecanização: o mecanismo que torna a adaptação visível.

---

### C11. "Se é tão simples, por que ninguém fez antes?"

Essa é uma boa pergunta, e a resposta honesta é: provavelmente porque as comunidades de software e educação não conversam o suficiente.

Professores de educação básica geralmente não conhecem Git, versionamento semântico, ou princípios de controle de versão. Desenvolvedores de software geralmente não conhecem os problemas do planejamento pedagógico. A interseção — alguém que vive nos dois mundos e percebe a analogia estrutural — é rara.

Além disso, existe um viés cultural: a educação tende a buscar soluções "da educação" (teorias pedagógicas, modelos didáticos), e a tecnologia tende a buscar soluções "da tecnologia" (plataformas, software). A transposição de princípio processual — sem plataforma, sem software — é um espaço conceitual pouco explorado.

A revisão de escopo confirmará se realmente ninguém fez antes. Se alguém fez, o PVP se posiciona como extensão ou alternativa.

---

### C12. "O RM é superficial. 3 campos não capturam a complexidade da prática docente."

Correto — e intencional. O RM não pretende capturar a complexidade completa da prática docente. Pretende capturar o mínimo que, acumulado ao longo do tempo, gera valor.

A alternativa ao "registro superficial de 90 segundos" não é o "registro profundo de 30 minutos" — é "nenhum registro". O professor que não tem 30 minutos para um relatório reflexivo tem 90 segundos para 3 campos. O RM é a micro-intervenção que funciona porque é micro.

Se o professor quiser registrar mais, pode. O RM é o mínimo, não o máximo. A profundidade pode crescer com o tempo, com a formação, com o suporte institucional. Mas o chão é 3 campos, e esse chão é intencional.

O paralelo: o commit do Git também é "superficial" — uma mensagem de uma linha. Mas milhões de commits acumulados ao longo de anos criam a história completa de um projeto. A profundidade emerge do acúmulo, não do registro individual.

---

### C13. "Isso funciona em escola particular com infraestrutura. Na pública, não funciona."

O PVP foi desenhado *para* a escola pública. O nível 1 (Essencial) funciona com caneta e caderno. Não exige internet, computador, plataforma, coordenação institucional, ou tempo protegido além dos 90 segundos.

Na verdade, o argumento se inverte: é na escola pública — com alta rotatividade, contratos temporários, professores que mudam de escola todo ano — que o PVP é mais necessário. Porque na ausência de infraestrutura institucional, o único lugar onde o conhecimento prático pode sobreviver é no registro individual do professor. E hoje esse registro não existe.

O Canvas PVP é uma folha A4 imprimível. A convenção de versionamento funciona escrita à mão. O RM cabe em um post-it. Se a objeção é infraestrutura, o PVP é a resposta de infraestrutura mínima.

---

### C14. "Você está transpondo Git sem considerar que educação tem especificidades que software não tem."

Excelente ponto — e por isso a transposição não é literal. O PVP não é Git para professores. É um protocolo inspirado nos princípios do Git, com adaptações deliberadas:

- Git não exige evidência; PVP exige (sinal de sala).
- Git é técnico; PVP funciona sem tecnologia.
- Git trata código (determinístico); PVP trata aulas (complexas, contextuais, humanas).
- Git tem merge automático; PVP tem curadoria humana.
- Git exige sintaxe exata; PVP aceita linguagem natural.
- Git ignora contexto de uso; PVP exige declaração de contexto.

A VC (Variação Contextual) é o exemplo mais claro: no Git, um branch é técnico e pode ser deletado sem consequência pedagógica. No PVP, uma VC-PEI é uma obrigação legal (Plano Educacional Individualizado) que precisa existir como variação rastreável do plano base.

A transposição é conceitual, não técnica. Os princípios foram transposto; a implementação é original.

---

### C15. "Como você mede se o PVP funciona?"

Essa pergunta é essencial e a resposta precisa ser específica. O PVP "funciona" se:

**Métricas de adesão:**
- O professor preenche RMs com regularidade (taxa de registro por aula aplicada)
- O professor usa a convenção de versão (compliance com X.Y ou X.Y.Z)
- O professor mantém o protocolo após período inicial (taxa de retenção em 30, 60, 90 dias)

**Métricas de qualidade do registro:**
- Os RMs contêm sinais de sala reais (não genéricos como "foi bom" ou "precisa melhorar")
- As versões refletem mudanças verificáveis no plano (não numeração inflada sem alteração real)
- As VCs quando criadas refletem adaptação contextual real

**Métricas de impacto percebido (qualitativo):**
- O professor declara que o PVP ajudou a identificar padrões na sua prática
- O professor declara que reutilizou melhorias de versões anteriores
- O professor percebe evolução rastreável nos seus planos

**Métrica de impacto indireto (longo prazo):**
- Planos de evidência E2 e E3 apresentam melhor qualidade percebida que planos E0 e E1

O piloto na UFT deve medir pelo menos as métricas de adesão e impacto percebido. As métricas de impacto indireto são para pesquisa futura.

---

### C16. "Isso não é contribuição para um mestrado. É só uma ideia organizada."

Essa objeção precisa ser respondida com firmeza e precisão:

1. **A revisão de escopo** demonstrará que a interseção "versionamento + planejamento pedagógico" é um espaço vazio ou quase vazio na literatura. Identificar e formalizar um espaço conceitual inexplorado é contribuição acadêmica.

2. **A especificação formal do protocolo** — com entidades definidas, regras explícitas, convenção de numeração e escala de evidência — vai além de "ideia organizada". É artefato técnico replicável.

3. **O enquadramento teórico** conecta Shulman (PCK), Nonaka & Takeuchi (conversão de conhecimento tácito), Ohno (sistema puxado), e Preston-Werner (versionamento semântico) em uma síntese original que justifica por que a transposição funciona.

4. **O piloto** produzirá dados empíricos sobre adesão, uso e percepção — que é exatamente o que se espera de uma dissertação em nível de mestrado.

Se a objeção persistir, a resposta final é: Kanban, quando descrito pela primeira vez, também era "só uma ideia organizada". A formalização e validação é que transformam ideia em contribuição.

---

### C17. "E se a revisão de escopo encontrar algo parecido?"

Possível e não seria catastrófico. Se a revisão encontrar trabalhos que:

- **Usam Git como ferramenta na educação** (para ensinar programação): Não é o mesmo. O PVP usa Git como modelo conceitual para planejamento, não como ferramenta para alunos. O PVP diferencia-se claramente.

- **Propõem versionamento de material didático** (sem formalização): O PVP se posiciona como a formalização que faltava — com protocolo, entidades, e escala de evidência.

- **Propõem algo muito próximo do PVP**: Aí o posicionamento muda para "extensão" ou "alternativa com diferenças X, Y, Z". Isso é risco real, mas a probabilidade é baixa dado o caráter interdisciplinar da proposta.

A revisão de escopo não é só para provar que "ninguém fez". É para mapear o que existe e posicionar o PVP com precisão no espaço conceitual.

---

### C18. "O professor não vai querer que outros vejam que sua aula é v1.0."

Essa é uma objeção cultural profunda. A profissão docente opera sob um mito de competência instantânea — o professor "bom" já chega pronto, e admitir que a aula precisa de melhoria é visto como fraqueza.

O PVP propõe justamente a inversão desse mito. Um plano v1.0 não é sinal de fraqueza — é sinal de começo. Um plano v3.2 não é sinal de que as versões anteriores eram ruins — é sinal de 3 reestruturações e 2 ajustes de experiência acumulada.

A mudança de linguagem é deliberada: de "corrigi minha aula" (linguagem de erro) para "liberei a v1.3" (linguagem de evolução profissional). Isso não é cosmético — é reframing cultural.

Na defesa: se a objeção é "o professor vai ter vergonha", a resposta é "o programador também tinha antes do Git normalizar o versionamento. Hoje, código sem versionamento é o que causa vergonha."

---

### C19. "E se o professor mentir no RM? Inventar sinais de sala?"

Pode acontecer, assim como pode acontecer em qualquer auto-relato profissional. O diário de classe depende de honestidade. O relatório de atividades depende de honestidade. O PVP não é exceção.

Mas o design do protocolo mitiga isso de duas formas:
1. **Acúmulo expõe inconsistência.** Um professor que fabrica sinais de sala vai produzir RMs genéricos e repetitivos. O padrão é visível ao longo do tempo — para o próprio professor, para o coordenador, ou para quem analisa os dados.
2. **O incentivo é perverso.** Mentir no RM não beneficia o professor — ele é o principal consumidor do próprio registro. Fabricar sinais de sala é sabotar a própria memória profissional. Não há nota, não há ranking, não há punição por v1.0.

Na defesa: reconheça a limitação, aponte os mecanismos de mitigação, e contextualize que todo instrumento de auto-relato tem essa limitação.

---

### C20. "Isso é neoliberalismo na educação. Você está importando lógica de mercado para a escola."

Essa objeção é ideológica e precisa ser respondida com cuidado.

O PVP não importa lógica de mercado. Não há métricas de produtividade, ranking de professores, gamificação competitiva, ou qualquer mecanismo de controle externo. O PVP é instrumento do professor para o professor. O PAV pertence ao professor. O RM é preenchido pelo professor. O histórico viaja com o professor.

Se a transposição de princípios de uma área para outra fosse inerentemente ideológica, então usar Kanban na saúde seria "importar lógica da Toyota para o hospital", e usar PDCA na educação seria "importar lógica industrial para a escola" — e ambos são amplamente aceitos.

A origem de uma ideia não define sua ideologia. A aplicação define. O PVP é open source, CC BY 4.0, sem plataforma proprietária, sem coleta de dados, sem ranking. É o oposto de captura de mercado.

Na defesa: não entre na discussão ideológica abstrata. Aponte o design concreto: o protocolo é aberto, gratuito, e centrado na autonomia do professor. Se isso é neoliberalismo, a palavra perdeu o significado.

---


---

*PVP Core 1.0 · Leidison Lima dos Santos · CC BY 4.0 · 2026*
