# Guia de Copywriting para Sites de Alta Conversão na Saúde
## Conformidade CFM (Res. 2.336/2023 + Manual Codame 2024) × Persuasão

**Versão 1.0** · Base normativa: Resolução CFM nº 2.336/2023 (publicada 13/09/2023, vigente desde 11/03/2024) e Manual de Publicidade Médica do CFM (Codame, 2024, 132 p.).

---

## 0. Como usar este guia

Este documento é o padrão de produção para todo site médico entregue. Ele tem três funções:

1. **Blindagem** — impedir que uma peça de copy exponha o cliente a processo ético na Codame do CRM dele.
2. **Conversão** — usar as permissões da norma (que são muito mais amplas do que a maioria dos médicos imagina) como alavancas reais de venda.
3. **Diferenciação comercial** — a conformidade em si é argumento de venda do seu serviço. Concorrentes genéricos de web design não conhecem essa norma.

**Escopo:** este guia cobre **médicos** (CFM). Odontólogos (CFO), psicólogos (CFP), nutricionistas (CFN), fisioterapeutas (COFFITO), enfermeiros (COFEN) e biomédicos têm normas próprias, algumas mais restritivas. Não aplique este guia a eles sem checar o conselho correspondente — ver §10.

**Aviso:** não sou advogado e este guia não é parecer jurídico. Para casos de fronteira, o próprio Art. 13, V da resolução dá ao médico o direito de consultar a Codame do seu CRM previamente. Use isso: uma consulta prévia protocolada é a melhor defesa que existe.

---

## 1. Camada obrigatória — o que precisa existir em TODO site

Sem isso, o site é irregular independente do quão bom seja o copy.

### 1.1 Bloco de identificação (Art. 4º e 6º)

O Art. 6º determina que os dados do Art. 4º estejam **na página principal** do site. Na prática, implemente em três lugares (redundância barata):

- **Footer global** (todas as páginas)
- **Hero ou seção "Sobre" da home**
- **Página do profissional**

**Médico pessoa física — formato obrigatório:**

```
Nome Completo
MÉDICO(A): CRM-DF 00.000
Oftalmologista: RQE 00000
```

Regras do Manual:
- A palavra **MÉDICO / MÉDICA** é obrigatória e explícita.
- Se atua em mais de um estado, listar todos os CRMs.
- RQE obrigatório quando houver especialidade registrada.
- **Não pode haver diferença de fonte, tamanho ou cor** entre as linhas do bloco.

**Clínica / estabelecimento (Art. 5º) — formato obrigatório:**

```
Nome da Clínica
Registro: 00000          ← "Registro" se privado; "Cadastro" se público
Diretor Técnico-Médico: Nome Completo
MÉDICO: CRM-DF 00.000
Oftalmologista: RQE-DF 00000    ← se estabelecimento especializado
```

### 1.2 Especificações tipográficas do Manual

O Manual traz critérios gráficos que quase ninguém cumpre. Vale codificar no seu design system:

- **Famílias recomendadas:** Humanist — Centaur, Frutiger, Gill Sans, **Open Sans**, Optima, Palatino, Verdana. (Open Sans resolve: gratuita, web-native, boa performance.)
- **Tamanho mínimo:** 35% do maior corpo de letra da peça.
- **Contraste:** sobre fundos claros, versão positiva (preta); sobre fundos escuros ou vívidos, versão negativa (branca). Em cinzas: até 30% de benday usa positivo, a partir de 40% usa negativo.
- Se o fundo dificultar leitura, o bloco vai dentro de retângulo branco com filete.

> **Nota de implementação:** o Manual fala de peças gráficas, mas o Art. 6º estende as regras ao ambiente digital. Trate como requisito de acessibilidade — WCAG AA já te leva a 90% do caminho.

### 1.3 Peças compartilháveis

Manual, §6: peças individuais não precisam repetir CRM/RQE se o perfil já tem. **Mas se a peça for compartilhável** (WhatsApp, download, card de OG image), os dados obrigatórios têm que estar **dentro da peça**. Aplique a: cards de blog, PDFs de download, imagens de OG/Twitter.

### 1.4 Vídeos

Manual, §5: em vídeo para internet, a identificação deve aparecer **em todos os quadros** de forma legível. Em vídeo de TV, cartela final estática. Se o site tem vídeo hero ou depoimento em vídeo, aplicar lower third permanente.

### 1.5 Quem responde (Art. 3º) — implicação contratual pra você

Responde perante o CRM: o **médico** (pessoa física) ou o **Diretor Técnico-Médico** (pessoa jurídica). **Você, desenvolvedor, não é o responsável ético — mas é o responsável contratual.**

Blinde-se: inclua no contrato (a) cláusula de aprovação formal do conteúdo pelo cliente antes do go-live, (b) declaração de que o cliente forneceu CRM/RQE corretos e conferiu os dados, (c) obrigação do cliente de fornecer o TCLE de imagem de pacientes quando aplicável.

---

## 2. Lista negra — estruturas de copy que geram infração

Cada item traz o dispositivo e a **substituição que converte igual ou mais**.

### 2.1 Promessa, garantia ou insinuação de resultado — Art. 11, XII

O item mais violado e o mais perigoso. A nota da Codame é explícita sobre por quê: a medicina é **obrigação de meio**, e publicidade que promete resultado pode gerar **responsabilidade civil objetiva** — o CDC (art. 14, §4º) obriga o fornecedor a entregar o que a publicidade prometeu. Ou seja: não é só multa ética. É o cliente sendo processado com a landing page como prova.

| ❌ Proibido | ✅ Substituição |
|---|---|
| "Liberdade total dos óculos" | "O objetivo do procedimento é reduzir a dependência de óculos. O grau de independência varia conforme o caso." |
| "Resultado garantido" | "Protocolo com [N] etapas de avaliação antes de indicar." |
| "Volte a enxergar como aos 20 anos" | "Entenda o que a cirurgia pode e o que não pode corrigir." |
| "Recupere sua visão" | "Como funciona a cirurgia de catarata" |
| "Você vai amar o resultado" | "O que esperar nos primeiros 30 dias." |

**Teste rápido:** se a frase descreve o *estado final do paciente* em vez do *processo do médico*, reescreva.

### 2.2 Superlativo sobre equipamento — Art. 11, II e IX

Proibido "atribuir capacidade privilegiada a aparelhagens" e anunciar técnica de modo a se atribuir capacidade privilegiada — **mesmo que seja o único a fazê-la** (isso é literal no inciso IX).

Permitido: anunciar o aparelho usando **as informações, indicações e propriedades do portfólio aprovado pela Anvisa** (Art. 9º, II e IX).

| ❌ Proibido | ✅ Substituição |
|---|---|
| "Tecnologia de ponta / mais avançada do Brasil" | "Equipamento X, registro Anvisa nº 00000. Indicações conforme portfólio: [lista literal do fabricante]." |
| "O único com este laser em Brasília" | "Realizamos [procedimento] com [equipamento], registro Anvisa nº 00000." |
| "Aparelho revolucionário" | "Utilizado para [indicação aprovada]." |

> Regra operacional: **copie a indicação do registro Anvisa. Não adjetive.** Peça ao cliente o número de registro de cada equipamento no briefing.

### 2.3 Funil com conteúdo gated — Art. 11, §4º, "a" ⚠️ CRÍTICO PARA SITES

Este é o dispositivo mais relevante e menos conhecido para quem faz site de conversão. É configurado como **concorrência desleal**:

> *"reportar em suas redes próprias, ou nas de terceiros, insinuações de haver feito descobertas milagrosas ou extraordinárias cujo acesso é condicionado à abertura sucessiva de novas abas, fornecimento de informações pessoais ou pagamento"*

A nota da Codame reforça: alcança "aquelas que criam uma expectativa de resposta com a abertura de abas sucessivas que culmina invariavelmente com o pedido de informação de dados pessoais ou pagamento."

**Leitura precisa:** o gate em si não é proibido. O que é proibido é o gate **combinado com insinuação de descoberta milagrosa/extraordinária**. Ou seja, a estrutura clássica de infoproduto — "descubra o segredo que os oftalmologistas não contam → clique → deixe seu email → agora seu WhatsApp" — é exatamente o que a norma mira.

**Padrões proibidos:**
- Headline de curiosity gap + hard gate ("O método que devolveu a visão de 500 pacientes — baixe o guia")
- Multi-step funnel com escalada de informação pessoal
- Conteúdo "revelador" pago

**Padrões seguros:**
- Conteúdo educativo **aberto**, sem gate. Formulário só para **agendamento** (finalidade legítima e declarada).
- Se quiser lead magnet: material claramente educativo, título descritivo e não sensacionalista ("Guia de preparo para cirurgia de catarata"), gate simples de 1 etapa, sem promessa de revelação.
- Deixe explícito o que o usuário recebe antes de pedir o dado.

### 2.4 Escassez e urgência

Correção importante: a norma **não proíbe escassez literalmente**. O que se aplica:

- **Escassez falsa** → propaganda enganosa (Art. 11, VI). Proibida sem discussão. Contador que reinicia, "últimas 3 vagas" permanente: infração clara e também infração ao CDC.
- **Escassez real, comunicada com sobriedade** → não vedada. "Agenda cirúrgica com previsão de 6 semanas" é fato.
- **Sorteio, premiação, consórcio, venda casada** → proibidos expressamente (Art. 9º, VIII; Art. 11, X). O Manual dá os exemplos: "faça a consulta e ganhe o exame", "concorra a prêmio se se submeter ao procedimento".

**Recomendação de produção:** não use contadores regressivos em site médico. O ganho de conversão não paga o risco de enquadramento em sensacionalismo (Art. 11, §2º, "f" — "usar de forma abusiva, enganosa ou **sedutora** representações visuais e informações").

### 2.5 Medo como gatilho — Art. 11, §2º, "e"

Vedado veicular informação "que possa causar intranquilidade, insegurança, pânico ou medo de forma coletiva ou individual, **mesmo que para fatos conhecidos**".

| ❌ Proibido | ✅ Substituição |
|---|---|
| "Você pode estar ficando cego e nem sabe" | "Glaucoma costuma ser assintomático na fase inicial. O exame de campo visual detecta antes da perda perceptível." |
| "Não deixe para depois — pode ser tarde demais" | "A avaliação de rotina é recomendada a partir dos 40 anos." |

A informação é a mesma. O registro emocional é o que muda. **Fato clínico neutro converte; alarme converte e gera processo.**

### 2.6 Não especialista anunciando doença específica — Art. 11, I

Médico sem RQE não pode divulgar que trata de sistemas orgânicos, órgãos ou doenças específicas. Isso **restringe a arquitetura de informação do site**: se o cliente não tem RQE em oftalmologia, você não pode montar páginas "Tratamento de Glaucoma", "Cirurgia de Catarata".

**Checagem obrigatória no briefing:** confirme RQE antes de projetar o sitemap. Peça o número.

### 2.7 Prêmios e selos — Art. 11, XIII

Nada de "Melhor Médico", "Top of Mind", "Destaque da Especialidade", "Doctoralia Awards" e similares. Vedado inclusive **não impedir** que o nome seja incluído. Se o cliente mandar selo de premiação para o site: recuse e explique.

### 2.8 Gratuidade anunciada — Art. 11, §4º, "c"

Não pode anunciar serviço médico gratuito em consultório privado. A Codame esclarece: o médico **pode** atender de graça, só não pode **divulgar** isso para formar clientela. Então nada de "primeira consulta gratuita", "avaliação sem custo".

**Substituição que converte:** ofereça algo que não é ato médico. "Ligue para tirar dúvidas sobre convênio e agendamento" ou "orçamento cirúrgico sem compromisso após a consulta" (o orçamento não é consulta).

### 2.9 Valores de procedimento — Art. 9º, VII

Pode divulgar **valor de consulta** e de **exames que não dependam de diagnóstico prévio**. **Não pode** divulgar valor de procedimento cirúrgico — o Manual é explícito: "Os valores desses procedimentos não deverão ser colocados em anúncios publicitários."

Isso mata a página de preços de cirurgia. Mas veja §3.1 — a permissão de anunciar valor de consulta é uma alavanca de conversão subestimada.

### 2.10 Comparação com concorrentes — Art. 11, §4º, "b"

Vedado dirigir-se a outros médicos, especialidades, técnicas ou procedimentos de forma desrespeitosa. Copy do tipo "diferente das clínicas de fábrica de cirurgia" ou "enquanto outros usam tecnologia ultrapassada": fora.

**Substituição:** diferencie pelo **seu processo**, descrito positivamente. "Todo pré-operatório inclui topografia de córnea com análise de ectasia" comunica a mesma superioridade sem atacar ninguém.

---

## 3. Lista verde — permissões que a maioria não usa (e que convertem)

Aqui está o valor real da 2.336/2023. Ela **ampliou** muito o que se pode fazer.

### 3.1 Transparência de preço da consulta — Art. 9º, VI ⭐

Permitido informar valor de consultas, meios e formas de pagamento. A nota da Codame explicita a intenção: prestação de serviço à sociedade, que "já saberá quanto vai despender".

**Por que converte:** remove a maior fricção não declarada do agendamento particular. Sites que escondem preço criam ansiedade e geram ligação de triagem — que é onde o lead esfria.

**Restrições:** não pode caracterizar pacote ou consórcio. O valor deve estar alinhado aos custos e ser auditável.

**Implementação:** bloco "Consulta particular: R$ XXX · Parcelamos em até Xx · Convênios atendidos: [lista]" próximo ao CTA principal.

### 3.2 Descontos e campanhas promocionais — Art. 9º, VIII

Permitido anunciar abatimentos e descontos. **Condição operacional que quase ninguém sabe:** o médico é obrigado a deixar acessível para auditoria os preços praticados **até três meses antes** da data promocional.

**Implicação para você:** se o site vai ter campanha promocional, monte junto um registro de histórico de preços. Vira entregável extra vendável.

Proibido: vincular a venda casada, premiação ou sorteio.

### 3.3 Ambiente, equipe e equipamentos — Art. 9º, I, III, IX

Permitido foto e vídeo do ambiente de trabalho, da própria imagem, da equipe clínica e auxiliares. Permitido anunciar serviços agregados executados por profissionais de área correlata sob supervisão médica.

**Alerta da Codame (e é sério):** o material precisa **retratar fielmente** o ambiente. "O que for veiculado tem obrigação de fins e poderá haver reclamação" — CDC. Não use banco de imagens genérico de consultório passando por consultório do cliente. Sessão fotográfica real é requisito, não luxo.

**Por que converte:** reduz incerteza. O paciente de alto ticket está comprando ambiente, equipe e processo — não só o ato cirúrgico.

### 3.4 Logística e acesso — Art. 9º, IV e V

Permitido detalhar: forma de marcação, horários, dinâmica de funcionamento, estacionamento, segurança, privacidade, conforto, localização, portfólio de convênios.

A nota da Codame diz que isso "de tão óbvio, parecia irrelevante. Mas, não."

**Por que converte:** é remoção pura de fricção. Cada dúvida logística não respondida é um abandono. Uma seção "Como é sua visita" bem feita levanta conversão mais que headline nova.

### 3.5 Qualificação técnica — Art. 13, VI ⭐

Autoridade é o gatilho de Cialdini que a norma **incentiva**. Permitido divulgar:

- Diploma, instituição, data de formatura
- Especialidade com RQE (até **duas** especialidades + áreas de atuação relacionadas)
- Pós-graduação lato e stricto sensu cadastradas no CRM

**Regra crítica:** quem **não tem RQE** e divulga pós-graduação deve escrever `NÃO ESPECIALISTA` em **caixa-alta**, mesma fonte, tamanho e cor. Exemplo do Manual:

```
✅ Permitido                          ❌ Vedado
Júlia Dutra Araújo                    Júlia Dutra Araújo
MÉDICA: CRM-RS 10.850                 MÉDICA: CRM-RS 10.850
Pós-graduação em pediatria na FMUSP   Pediatra com pós-graduação na FMUSP
NÃO ESPECIALISTA
```

Detentor de RQE com mestrado/doutorado divulga normalmente. Titular de dois RQEs: até duas especialidades e as áreas de atuação **a elas relacionadas** (o Manual mostra que agrupar áreas de atuação sob a especialidade correta importa).

### 3.6 Conteúdo educativo — Art. 13, III

Direito expresso de usar rede própria (inclusive site) para **formar, manter ou aumentar clientela**, e também dar informação acadêmica/educativa. A Codame compara a rede própria a um "grande painel ou outdoor" do médico.

Isso legitima explicitamente o marketing de conteúdo. É o motor de autoridade e o principal veículo de tratamento de objeção — sem nunca prometer resultado.

**Limites:** respaldo na literatura médica; não pode ensinar ato privativo de médico (Res. 1.718/2004); não pode divulgar método não reconhecido pelo CFM; não pode substituir consulta (Art. 11, XI).

### 3.7 Resultados comprováveis — Art. 9º, XVI

Permitido "revelar resultados comprováveis de tratamentos e procedimentos, desde que não identifique pacientes".

Esta é a base ética para **especificidade numérica** — desde que o dado seja verificável, não manipulado (Art. 11, §2º, "c" veda adulteração de dado estatístico) e apresentado com sobriedade.

**Uso correto:** dados de literatura citados com fonte, ou estatísticas próprias auditáveis, sempre sem induzir garantia. "Segundo [estudo/fonte], a taxa de X é Y%" > "Nossos resultados são excelentes".

### 3.8 Depoimentos e repostagem — Art. 8º, §3º e Art. 14, II, "g"

Permitido, com três travas:

1. **Limite de frequência:** repostagem "reiterada" = mais de **duas por semestre**. Acima disso pode ser enquadrado como sensacionalismo e concorrência desleal.
2. **Tom:** sóbrio, sem adjetivos que denotem superioridade ou induzam promessa de resultado. ("Melhor médico do Brasil, me devolveu a visão" → não pode. "Fui bem atendida e todas as minhas dúvidas foram respondidas" → pode.)
3. **Responsabilidade:** ao repostar, o conteúdo passa a ser **publicação do médico** para todos os efeitos.

⚠️ **Atenção especial:** o Art. 8º, §4º diz que elogios de pacientes, **mesmo sem serem compartilhados pelo médico**, devem ser investigados pela Codame quando ocorrerem de modo reiterado e sistemático. Ou seja: campanha organizada de depoimentos é risco mesmo que o médico não reposte nada.

**Implicação para o site:** um carrossel com 30 depoimentos é arriscado. Prefira: poucos depoimentos, sóbrios, com autorização documentada, sem identificação, e sem esquema de coleta sistemática.

### 3.9 Antes e depois — Art. 14 ⭐ OPORTUNIDADE COMERCIAL

Aqui está a descoberta mais valiosa para o seu negócio.

O antes/depois é permitido, mas **exclusivamente com caráter educativo** e cumprindo **quatro etapas obrigatórias**, textualmente descritas na nota da Codame ao Art. 14:

1. **Quando sinais e sintomas apontam para procurar um médico**
2. **Fotos/vídeos de pacientes ANTES do tratamento — de ao menos QUATRO pacientes diferentes**
3. **Fotos/vídeos APÓS a intervenção — de ao menos QUATRO pacientes diferentes**, mostrando resultados possíveis; quando viável, diferentes biotipos e faixas etárias
4. **Descrição de possíveis resultados insatisfatórios e complicações**

Os itens 2 e 3 devem ser fotos reais; 1 e 4 podem ser de terceiros ou referência bibliográfica.

Requisitos adicionais:
- Texto educativo com indicações terapêuticas, fatores que influenciam resultados e complicações da literatura
- Quando aplicável: evolução imediata, mediata e tardia
- Sem edição que distorça (recorte, luz, nitidez e tarja são permitidos; Photoshop/Lightroom que "melhore" o resultado, não)
- Paciente não identificável; TCLE de imagem documentado; **vedado dar desconto ou qualquer vantagem em troca da autorização**
- Paciente pode revogar a autorização a qualquer momento
- Deve se relacionar à especialidade registrada do médico
- Se vídeo: mínimo **2 segundos por imagem**, tempo equivalente para todas
- Imagens de mama, glúteo ou região íntima: somente em **landing page com aviso de acesso restrito a maiores de 18 anos**

### 🎯 O ponto de virada comercial

A Codame afirma textualmente:

> *"Postagens isoladas de resultados em redes sociais como Facebook, Instagram e redes sociais similares não podem ser utilizadas, uma vez que não atendem ao formato proposto por esta resolução."*

E logo antes:

> *"É permitida a elaboração do referido conjunto de imagens por meio da compilação de fotografias em um vídeo, **ou em um website**, para o qual ocorra direcionamento por intermédio das redes sociais."*

**Traduzindo:** o Instagram é estruturalmente inadequado para antes/depois. O **site é o único lugar onde o antes/depois é plenamente legítimo** — e a norma prevê expressamente que a rede social direcione para ele.

Isso é o seu pitch de venda. Você não está vendendo "um site bonito". Está vendendo **a única infraestrutura em que o cliente pode legalmente mostrar resultados** — com o Instagram funcionando como topo de funil que direciona pra lá.

Monte isso como produto: **"Módulo Galeria Educativa de Resultados"**. Componentes: template das 4 etapas, gestão dos 4+ casos, redação do texto educativo de complicações, TCLE de imagem, controle de revogação, aviso 18+ quando aplicável, gate etário. É um upsell caro, defensável, e que exige exatamente o conhecimento normativo que você acabou de adquirir.

---

## 4. Arquitetura de páginas com fórmulas de copy

### 4.1 Home

| Bloco | Função | Regra |
|---|---|---|
| Hero | Nomear o público e o problema | Sem promessa de resultado. Descreva o serviço, não o desfecho. |
| Prova de credencial | Autoridade | Nome + MÉDICO + CRM + RQE, formatação uniforme |
| Como funciona o atendimento | Reduz incerteza | Art. 9º, IV/V — detalhe o processo |
| Ambiente e equipe | Prova visual | Fotos reais obrigatoriamente |
| Condições atendidas | Navegação | Só se houver RQE (Art. 11, I) |
| Preço da consulta + convênios | Remove fricção | Art. 9º, VI |
| Conteúdo educativo em destaque | Autoridade + SEO | Aberto, sem gate |
| CTA único | Ação | Uma ação por página |
| Footer legal | Obrigatório | Art. 4º/5º + LGPD |

**Fórmula de headline segura e forte:**
> `[Procedimento/Condição] + [para quem] + [em que cidade/contexto]`
>
> "Cirurgia de catarata com avaliação individualizada de lente intraocular — Brasília"

Sem adjetivo, sem promessa, com especificidade. Passa no filtro e comunica competência.

### 4.2 Página de procedimento (a página que vende)

Estrutura na ordem que respeita níveis de consciência de Schwartz e trata objeção:

1. **O que é** — definição neutra
2. **Quando é indicado** — sinais e sintomas que motivam avaliação (é literalmente a etapa 1 do Art. 14)
3. **Como é o processo** — pré-op, exames, dia da cirurgia, pós-op. *Aqui mora a especificidade que substitui o superlativo.*
4. **O que a cirurgia pode e o que não pode corrigir** — tratamento de objeção + proteção jurídica no mesmo bloco
5. **Riscos e complicações possíveis** — obrigatório se houver imagem (Art. 14, II, "a"); recomendável sempre
6. **Equipamentos utilizados** — nomenclatura do portfólio Anvisa, sem adjetivo
7. **Galeria educativa** (se contratada) — as 4 etapas completas
8. **FAQ** — objeções restantes
9. **CTA de agendamento**

> **O bloco 4+5 é contraintuitivo mas é o maior ativo de conversão da página.** Um paciente de alto ticket que lê limitações e riscos declarados abertamente calibra a decisão e confia mais. Além disso, ele é a prova documental de que não houve promessa de resultado.

### 4.3 Página do médico

- Bloco de identificação completo
- Formação (Art. 13, VI) com `NÃO ESPECIALISTA` quando aplicável
- Filosofia de atendimento em tom sóbrio (Art. 9º, XV permite comentário genérico sobre prazer com o trabalho, desde que não identifique pacientes e não seja sensacionalista)
- Foto real, não corporativa genérica
- **Sem** selos de premiação (Art. 11, XIII)

### 4.4 Conteúdo educativo / blog

Motor de autoridade e principal ativo de SEO. Cada artigo:
- Título descritivo, nunca curiosity gap sensacionalista
- Fonte/referência da literatura
- Aberto, sem gate
- CTA de agendamento no rodapé, não interstitial
- Sem ensino de ato privativo

### 4.5 Agendamento / contato

- CTA único e claro
- Formulário mínimo: nome, contato, motivo. Cada campo extra derruba conversão e aumenta exposição LGPD.
- Deixar explícito o que acontece depois do envio (prazo de retorno)
- Sem multi-step com escalada de dados (§2.3)

### 4.6 Footer legal (template)

```
[Nome da Clínica] · Registro CRM-DF nº 00000
Diretor Técnico-Médico: [Nome] · MÉDICO: CRM-DF 00.000 · [Especialidade]: RQE 00000

Este site tem finalidade informativa e não substitui consulta médica.
Resultados variam conforme cada caso; a medicina é atividade-meio e não
comporta garantia de resultado.

Política de Privacidade · Tratamento de dados conforme a LGPD (Lei 13.709/2018)
```

---

## 5. LGPD — camada obrigatória paralela

O Manual é explícito: toda publicidade médica deve cumprir a LGPD, e dados de saúde são **dados pessoais sensíveis** (art. 5º, II).

Entregáveis mínimos por site:
- Política de Privacidade específica para dados de saúde
- Banner de consentimento de cookies com opção real de recusa
- Base legal declarada para o formulário de contato
- TCLE de imagem separado e documentado para qualquer imagem de paciente, com finalidade, abrangência, ausência de contrapartida financeira e canal de revogação
- Retenção definida para leads de formulário

---

## 6. Tabela mestra de substituição

| Categoria | Proibido | Permitido equivalente |
|---|---|---|
| Resultado | "Livre dos óculos para sempre" | "Objetivo do procedimento é reduzir dependência de óculos" |
| Equipamento | "Laser mais avançado do país" | "[Equipamento], registro Anvisa nº X, indicado para [indicação do portfólio]" |
| Exclusividade | "Único que realiza esta técnica" | "Realizamos [técnica]" |
| Urgência | "Últimas vagas! Só até sexta" | "Agenda cirúrgica com previsão de X semanas" |
| Medo | "Você pode ficar cego" | "[Condição] costuma ser assintomática na fase inicial" |
| Prova social | "Melhor médico de Brasília" | Credenciais + RQE + formação verificável |
| Prêmio | Selo "Top Doctor 2025" | Título de especialista com RQE |
| Gratuidade | "Primeira consulta grátis" | "Ligue para esclarecer convênio e agendamento" |
| Preço | "Cirurgia a partir de R$ X" | "Consulta: R$ X. Valor cirúrgico definido após avaliação" |
| Concorrência | "Diferente das clínicas de linha de produção" | "Cada pré-operatório inclui [exames específicos]" |
| Funil | "Descubra o segredo — clique aqui" | "Guia de preparo para cirurgia de catarata" |
| Depoimento | "Ele devolveu minha visão!" | "Fui bem atendida e minhas dúvidas foram respondidas" |
| Antes/depois | 2 fotos no Instagram | Galeria de 4 etapas, 4+ pacientes, no site |

---

## 7. Princípios de persuasão que sobrevivem ao filtro CFM

O que resta dos grandes nomes do copywriting depois da norma — e é mais do que parece:

**Especificidade > adjetivo (Hopkins).** A norma proíbe o superlativo mas não o dado. Como todo concorrente usa adjetivo, a especificidade vira diferencial competitivo *e* compliance ao mesmo tempo. Esse é o eixo central deste guia.

**Níveis de consciência (Schwartz).** Sitemap organizado por consciência: conteúdo educativo para inconscientes do problema → página de condição para conscientes do problema → página de procedimento para conscientes da solução → agendamento para conscientes do produto. Nenhum conflito com a norma.

**Razão-porquê.** Explicar *por que* o processo é como é constrói confiança sem prometer nada. "Fazemos topografia em todos os candidatos porque X% das ectasias são subclínicas na lâmpada de fenda."

**Objeção antecipada (Halbert/Kennedy).** Convergente com a exigência de declarar complicações. A norma te obriga a fazer o que o bom copy já faria.

**Cliente como herói (StoryBrand).** Compatível — desde que a jornada descreva o *processo*, não garanta o *desfecho*.

**Autoridade (Cialdini).** Único gatilho que a norma ativamente incentiva, via Art. 13, VI e Art. 13, III.

**CTA único.** Sem restrição normativa. Aplicar sempre.

**Aversão à perda.** Usar com cuidado extremo. Perda concreta e factual ("perda de campo visual no glaucoma é irreversível" — fato clínico correto) pode passar; dramatização emocional cai no Art. 11, §2º, "e". Na dúvida, não use.

**Reciprocidade.** Via conteúdo educativo aberto. Nunca via gratuidade de ato médico anunciada.

---

## 8. Checklist de QA pré-lançamento

**Identificação**
- [ ] Nome + palavra MÉDICO/MÉDICA + CRM na página principal
- [ ] RQE presente quando há especialidade
- [ ] Fonte, tamanho e cor uniformes no bloco
- [ ] Dados do estabelecimento + Diretor Técnico-Médico (se PJ)
- [ ] Identificação em peças compartilháveis e OG images
- [ ] Identificação em todos os quadros de vídeo
- [ ] `NÃO ESPECIALISTA` em caixa-alta onde aplicável
- [ ] Máximo 2 especialidades divulgadas

**Copy**
- [ ] Zero promessa, garantia ou insinuação de resultado
- [ ] Zero superlativo sobre equipamento; indicações do portfólio Anvisa
- [ ] Zero "único/exclusivo/pioneiro"
- [ ] Zero apelo a medo
- [ ] Zero comparação depreciativa
- [ ] Zero selo de premiação
- [ ] Zero anúncio de gratuidade
- [ ] Zero valor de procedimento cirúrgico
- [ ] Doenças/órgãos citados só se há RQE correspondente
- [ ] Métodos citados reconhecidos pelo CFM

**Estrutura**
- [ ] Sem funil de gate escalonado
- [ ] Sem contador regressivo
- [ ] Sem venda casada, sorteio ou consórcio
- [ ] Conteúdo educativo aberto
- [ ] CTA único por página

**Imagens**
- [ ] Fotos do ambiente são reais e fiéis
- [ ] Se há antes/depois: 4 etapas completas, ≥4 pacientes em cada, texto educativo com complicações
- [ ] Sem edição que distorça resultado
- [ ] Paciente não identificável
- [ ] TCLE arquivado para cada imagem
- [ ] Vídeo: mínimo 2s por imagem, tempo equivalente
- [ ] Gate 18+ se região íntima/mama/glúteo
- [ ] Banco de imagens com fonte citada e licença

**Depoimentos**
- [ ] Tom sóbrio, sem superlativo, sem promessa
- [ ] Sem identificação do paciente
- [ ] Volume compatível com o limite de 2 repostagens/semestre
- [ ] Sem esquema de coleta sistemática

**LGPD**
- [ ] Política de Privacidade publicada
- [ ] Consentimento de cookies com recusa real
- [ ] Formulário com base legal e finalidade declaradas
- [ ] Retenção de leads definida

**Preço**
- [ ] Valor de consulta claro, sem pacote/consórcio
- [ ] Se há desconto: histórico de 3 meses arquivado

---

## 9. Briefing padrão — o que coletar de cada cliente

**Identificação e habilitação**
1. Nome completo como consta no CRM
2. Número(s) de CRM + estado(s)
3. Especialidade(s) com RQE — **número exato**
4. Áreas de atuação com RQE
5. Pós-graduações cadastradas no CRM (e se há RQE)
6. Se PJ: nome, registro/cadastro CRM, Diretor Técnico-Médico + CRM + RQE

**Serviços**
7. Procedimentos oferecidos (checar contra o RQE)
8. Equipamentos: nome, fabricante, **número de registro Anvisa**, indicações do portfólio
9. Profissionais de áreas correlatas na equipe
10. Convênios atendidos

**Comercial**
11. Valor da consulta e formas de pagamento
12. Há campanha promocional? (se sim: histórico de preços dos 3 meses anteriores)

**Operacional**
13. Como agendar, horários, tempo médio de resposta
14. Estacionamento, acessibilidade, localização

**Imagens**
15. Fotos reais do ambiente disponíveis? (se não, orçar sessão)
16. Deseja galeria de resultados? (se sim: há 4+ casos com TCLE? Módulo à parte)

**Compliance**
17. Já teve alguma orientação ou processo na Codame?
18. Aceita submeter peça de dúvida à Codame antes do go-live?

---

## 10. Outros conselhos profissionais

Este guia vale para **médicos**. Se você vende para outros profissionais de saúde, cada conselho tem norma própria e não são intercambiáveis:

| Profissão | Conselho | Observação |
|---|---|---|
| Odontologia | CFO | Regras próprias de publicidade; tratamento distinto para antes/depois |
| Psicologia | CFP | Historicamente mais restritivo; cuidado com prova social |
| Nutrição | CFN | Regras próprias sobre antes/depois e resultados corporais |
| Fisioterapia / T.O. | COFFITO | Norma própria |
| Enfermagem | COFEN | Norma própria |
| Biomedicina | CFBM | Norma própria |

**Ação recomendada:** antes de vender para uma nova categoria, produza um anexo específico com a mesma estrutura deste documento. Isso vira ativo reutilizável e justifica preço.

**Transversal a todos:** LGPD, CDC e a regra de que publicidade que promete obriga a entregar valem para qualquer profissional de saúde.

---

## 11. Posicionamento comercial do seu serviço

Três argumentos que decorrem diretamente do conteúdo acima:

**1. Risco.** O responsável ético é o médico, não o desenvolvedor. Um site irregular expõe o CRM do cliente. Você entrega conformidade documentada — checklist assinado, briefing arquivado, TCLEs organizados.

**2. Exclusividade estrutural do site.** O Manual estabelece que o Instagram não comporta antes/depois. O site é o único canal legítimo para demonstração de resultados. Isso não é opinião sua — é texto da Codame.

**3. Permissões não exploradas.** A maioria dos médicos ainda opera com a mentalidade da 1.974/2011. Preço de consulta, ambiente, equipe, equipamentos, campanhas promocionais, participação em peças de terceiros — tudo liberado e quase ninguém usa.

**Estrutura de oferta sugerida:**

- **Base:** site institucional em conformidade + páginas de procedimento + blog + LGPD
- **Módulo Galeria Educativa de Resultados:** as 4 etapas, gestão de casos, TCLE, gate 18+
- **Módulo Conteúdo:** produção editorial contínua (motor de autoridade)
- **Retainer de Compliance:** revisão trimestral, atualização de RQE, arquivo de histórico de preços, monitoramento de mudanças normativas

---

## Fontes

- Resolução CFM nº 2.336/2023 — texto integral e exposição de motivos
  `https://sistemas.cfm.org.br/normas/arquivos/resolucoes/BR/2023/2336_2023.pdf`
- Manual de Publicidade Médica — CFM/Codame, 2024, 132 p., ISBN 978-65-87360-17-1
- Portal de Publicidade Médica do CFM: `https://publicidademedica.cfm.org.br`
- Normas correlatas citadas: Res. CFM 1.718/2004 (ensino de ato médico), 2.056/2013 (prontuário), 2.147/2016 (diretor técnico), 2.318/2022 (órteses e próteses), 2.321/2022 (eventos), Lei 13.709/2018 (LGPD), Lei 8.078/1990 (CDC, art. 14, §4º)
