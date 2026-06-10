# Miniguia financeiro - Projeto Bootcamp Bradesco - Plataforma DIO

Projeto integrante do curso de IA Generativa no Bootcamp Bradesco na plataforma DIO. Criação de um miniguia sobre um assunto financeiro utilizando a ferramenta NotebookLM, reunindo de 3 a 5 fontes abertas.

* **Tema escolhido:** Finanças - um guia básico para a vida adulta
* **Objetivo:** um miniguia com conceitos e práticas para uma boa administração das finanças:
* **Público alvo:** adolescentes/jovens brasileiros que estão concluindo o Ensino Médio, ingressando no Ensino Superior ou iniciando em seu primeiro emprego.

### 🎥 Fontes de vídeo:
1. **COMO SE ORGANIZAR COM POUCO DINHEIRO? | NATH ENSINA** - [Assistir no YouTube](https://www.youtube.com/watch?v=1vGVHGyqg0U)
2. **B3 Explica | Como começar a investir?** - [Assistir no YouTube](https://www.youtube.com/watch?v=pW_z9HAY-tk)
3. **Gustavo Cerbasi: como planejar a vida financeira sem atalhos | Na Ponta do Lápis (FastCo Money)** - [Assistir no YouTube](https://www.youtube.com/watch?v=x_TPAzFMEp4)

### 📄 Fontes de texto:
4. **Caderno de Educação Financeira – Gestão de Finanças Pessoais (Conteúdo Básico)** – *Banco Central do Brasil* - [Acessar PDF](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf)
5. **Livro TOP Planejamento Financeiro Pessoal** – *Comissão de Valores Imobiliários* - [Acessar Link](https://www.gov.br/investidor/pt-br/educacional/publicacoes-educacionais/livros-cvm/livro-top-planejamento-financeiro-pessoal)

---

## 🤖 Principais Prompts e respostas no desenvolvimento do projeto:

### Prompt inicial para seleção de fontes

> "Quero criar um miniguia com conceitos e práticas para uma boa administração de finanças. O público-alvo é o seguinte: adolescentes/jovens brasileiros que estão concluindo o Ensino Médio, ingressando no Ensino Superior ou iniciando em seu primeiro emprego. Quero que a busca seja filtrada para limitar a no máximo 5 fontes, entre textos e vídeos, para serem utilizadas em um caderno do NotebookLM. As fontes devem ser de pessoas especialistas ou instituições reconhecidas por notório conhecimento na área de finanças. Peço que sejam pessoas brasileiras ou instituições que atuam no Brasil para uma melhor adequação do conteúdo à realidade do público-alvo. Saiba que o leitor precisará, no miniguia, receber orientações sobre renda, gastos, investimentos, como economizar, definição de prioridades financeiras. Então esta será sua tarefa. Selecionar as 5 melhores fontes que possam ser utilizadas aqui neste Notebook."

**Feedback:** Testei esse prompt no próprio NotebookLM utilizando a ferramenta Deep Search, mas o retorno não foi bom. Trouxe um resumo genérico sem indicação de fontes. Então fiz o mesmo pedido ao Gemini 3.1 Pro. O retorno foi bem melhor, com indicação de dois especialistas e três instituições (citados nas fontes). Porém, as fontes não foram específicas. Então fui ao próximo prompt.

---

### Prompt 2 e 3: Buscando fontes específicas

> "Gostei das indicações. Preciso que se limite a uma fonte específica de cada um dos autores/instituições. Se tivesse de escolher apenas 5 fontes no total, qual cartilha/vídeo/texto selecionaria. Lembrando que preciso que o material seja de acesso aberto/gratuito".

Algumas fontes eram inexistentes, então prossegui e especifiquei:

> "As fontes 1 e 4 consegui encontrar. Os vídeos das fontes 2 e 3 parecem não existir. E o 5 é um curso que parece não estar mais disponível. Não me dê uma fonte em formato de curso, pois não é possível enviá-la ao NotebookLM. Revise essas três fontes e traga-me algo que posso utilizar"

**Feedback:** Tive, então, um retorno bem-sucedido com as fontes.

---

### Prompt 4: Estrutura do miniguia

Com as fontes inseridas no Notebook, solicitei a estrutura de um miniguia com os requisitos de meu projeto ao NotebookLM:

> "Quero criar um miniguia com conceitos e práticas para uma boa administração de finanças. O público-alvo é o seguinte: adolescentes/jovens brasileiros que estão concluindo o Ensino Médio, ingressando no Ensino Superior ou iniciando em seu primeiro emprego. Saiba que o leitor precisará, no miniguia, receber orientações sobre renda, gastos, investimentos, como economizar, definição de prioridades financeiras. Inicialmente, me responda: qual a melhor estrutura para o miniguia? Quero saber as seções em tópicos, incluindo as seções 'glossário' e 'prompts para aprofundar os estudos com o auxílio de IA'"

**Feedback:** A resposta foi satisfatória. Obtive uma estrutura com tópicos e subtópicos.

---

### Prompt 5: A geração do miniguia

Com a estrutura pronta, solicitei ao NotebookLM a geração de um miniguia seguindo essa estrutura:

> "Com base nos materiais fornecidos, crie um miniguia voltado a jovens brasileiros que deve ser **prática, visual e focada em comportamento**, já que a educação financeira para esse público vai além de números, envolvendo a **estratégia de carreira e a realização de sonhos**. Utilizar linguagem amigável, como numa conversa, mas mantendo um tom levemente formal, sem gírias que possam limitar o alcance de público. Abaixo, apresento a proposta de seções em tópicos:
> [Seguindo a solicitação acima, deixei a estrutura a ser seguida]"

**Feedback:** Um miniguia financeiro da vida adulta para jovens brasileiros muito bem elaborado e contextualizado.

*Nota: Solicitei apenas uma melhora no glossário, que estava muito resumido e com palavras que não apareciam no miniguia. Acrescentei um índice e pedi que me entregasse tudo no formato markdown para colocar no README do Github.*

---

# 📘 Miniguia completo:

> A leitura pode ser feita aqui no README.md ou no PDF, de formatação agradável, gerado pelo Gemini, que também se encontra neste repositório: [Acessar PDF](https://github.com/marcosilvafilho/miniguia-financeiro-projeto-dio/blob/main/miniguia_estrategico_prosperidade.pdf)

## Título: Guia Estratégico de Prosperidade: Carreira, Finanças e Realização de Sonhos

A educação financeira no contexto brasileiro não deve ser encarada como uma mera lista de restrições ou privações, mas sim como uma ferramenta fundamental de liberdade e autonomia estratégica. Para o jovem que inicia sua trajetória, o domínio sobre os recursos funciona como um mapa de navegação: ele permite converter o suor do trabalho em projetos concretos, garantindo que você seja o autor da sua própria história, com segurança contra imprevistos e poder real de escolha.

---

### Índice
1. **Mentalidade e Propósito:** O Diferencial entre Sonhar e Realizar
2. **Carreira:** O Investimento com Maior Potencial de Retorno
3. **Engenharia de Fluxo de Caixa:** Organização sem Privações Excessivas
4. **Psicologia do Consumo e Defesa do Patrimônio**
5. **O Labirinto do Crédito:** Como Não se Perder no Juro Composto Negativo
6. **A Jornada do Investidor:** Da Proteção à Rentabilidade
7. **Dicionário do Mercado Financeiro:** Glossário Essencial
8. **IA como Mentor Financeiro:** Prompts de Aprofundamento

### 1. Mentalidade e Propósito: O Diferencial entre Sonhar e Realizar

A distância entre o desejo e a conquista é preenchida pelo planejamento. Frequentemente, confundimos "Sonhos" — desejos abstratos e sem data — com "Projetos", que são planos estruturados com prazos e metas. Gustavo Cerbasi ensina que a prosperidade é construída através do "curto caminho longo": um processo previsível, passo a passo, onde cada tijolo é colocado com intenção. Fuja do "longo caminho curto", que é a busca perigosa por atalhos, apostas milagrosas e ganhos rápidos que costumam terminar em frustração e perda de tempo.

Para transformar seus sonhos em projetos, utilize a metodologia de metas **SMART**:

* **S (Específica):** O que exatamente você quer? *(Ex: "Comprar um notebook para o curso técnico")*.
* **M (Mensurável):** Quanto custa em reais? *(Ex: "R$ 3.500,00")*.
* **A (Atingível):** É possível com sua renda ou planejamento de carreira?
* **R (Relevante):** Por que isso é importante para o seu futuro?
* **T (Prazo):** Qual a data limite? *(Ex: "Dezembro de 2025")*.

Para manter o foco, aprenda a diferenciar o que é essencial do que é impulso:

| Necessidades Indispensáveis | Desejos Passageiros |
| :--- | :--- |
| Aluguel, alimentação básica e saúde | O modelo de celular "top de linha" do ano |
| Educação e qualificação técnica | Roupas de marca apenas para ostentação |
| Reserva de segurança e transporte | Assinaturas de serviços que você nem usa |

Essa clareza mental é o que permite focar no motor principal de qualquer patrimônio: sua carreira.

---

### 2. Carreira: O Investimento com Maior Potencial de Retorno

Se você é jovem, você está começando a "pintar o seu quadro em branco". Sua profissão não é apenas um meio de pagar boletos, mas o eixo central da sua acumulação de riqueza. O investimento em si mesmo oferece retornos que nenhum ativo financeiro pode bater no início da vida. A prosperidade real exige uma coordenação estratégica entre o que você estuda e o que o mercado precisa.

Mantenha o foco no seu valor de mercado. Procure identificar quais competências são escassas na região em que você vive ou tenha prontidão para a mobilidade geográfica, buscando locais onde sua mão de obra seja mais valorizada. Utilize a "engenharia reversa" da carreira: mire no cargo que deseja ocupar em 10 anos e mapeie agora quais certificações e cursos técnicos (como os do Sistema S) são os degraus necessários para chegar lá.

#### 🛠️ Guia de Viabilidade Profissional:
* **Mapeamento de Escassez:** Identifique áreas técnicas na sua região onde faltam profissionais. Se a oferta é baixa e a demanda é alta, seu salário tende a subir.
* **Educação Estratégica:** Não acumule diplomas inúteis; busque qualificações práticas que aumentem seu valor de entrega imediata.
* **Coordenação de Ganhos:** Ao receber um aumento, não eleve seu padrão de vida na mesma hora. Segure os gastos por alguns meses para financiar seu próximo nível de especialização.

---

### 3. Engenharia de Fluxo de Caixa: Organização sem Privações Excessivas

O controle financeiro é um instrumento de saúde mental. A metodologia de Nath Finanças ensina que você não deve "cortar" o lazer, mas sim dimensioná-lo. A grande sacada é a Regra de Ouro: **pague-se primeiro**. Trate seu investimento mensal como o seu boleto mais importante — você é sua conta prioritária.

Categorize seus gastos para ter o comando do mapa:
* **Fixas:** Sobrevivência (aluguel, condomínio, mensalidades).
* **Variáveis:** Recorrentes que você pode otimizar (luz, água, internet, mercado).
* **Extras:** Gastos sazonais previstos (matrícula escolar, IPVA, IPTU).
* **Lazer:** Essencial para o bem-estar; defina um valor que caiba no orçamento sem culpa.

| Categoria | Exemplo Prático | Estratégia de Ganho |
| :--- | :--- | :--- |
| **Variável** | Conta de Luz | Retirar aparelhos da tomada e vigiar o tempo de banho. |
| **Variável** | Plano de Internet | Renegociar anualmente ou reduzir o pacote para o uso real. |
| **Lazer** | Streaming/Saídas | Trocar o transporte por aplicativo por transporte público ou carona. |

> 📌 **Nota de Destaque:** Renegociar serviços é "ganhar dinheiro" parado. Se sua internet oscila ou não entrega a velocidade, ligue para a operadora. Caso não resolvam, use o protocolo na Anatel ou no portal Consumidor.gov. Nath Finanças relata que isso pode gerar descontos ou faturas zeradas, economizando centenas de reais por ano.

---

### 4. Psicologia do Consumo e Defesa do Patrimônio

O marketing moderno usa inteligência de dados para explorar seus gatilhos emocionais. A decisão de compra é sempre uma troca intertemporal: você escolhe entre pagar juros hoje para antecipar um prazer que não pode pagar (empréstimo) ou receber juros amanhã por ter tido a disciplina de esperar para comprar à vista.

#### 📋 Checklist do Consumidor Consciente (5 Perguntas Críticas):
1. Eu realmente preciso disso agora ou fui seduzido pelo marketing?
2. Tenho o dinheiro hoje ou vou me escravizar em parcelas?
3. Este gasto me aproxima ou me afasta do meu projeto SMART?
4. É uma necessidade real ou apenas vontade de ostentar para os outros?
5. Já pesquisei o preço com calma ou estou cedendo ao gatilho da pressa?

Se o consumo foge do controle, o crédito vira uma armadilha de juros compostos negativos.

---

### 5. O Labirinto do Crédito: Como Não se Perder no Juro Composto Negativo

É vital diferenciar "estar endividado" (ter parcelas a vencer de forma saudável, como um financiamento imobiliário) de "estar inadimplente" (contas atrasadas e incidência de multas). Evite o cheque especial e o rotativo do cartão; eles são os vilões da sua prosperidade.

Ao avaliar qualquer crédito, olhe para o **Custo Efetivo Total (CET)**. Ele é o preço real, incluindo taxas, seguros e impostos, e é sempre maior que a taxa de juros nominal.

> ⚠️ **Aviso Prioritário:** Quitar dívidas caras é o seu melhor "investimento". Não faz sentido buscar rentabilidade de 1% ao mês se você paga 15% ao mês no cartão de crédito. Limpe seu passado financeiro antes de construir seu futuro.

---

### 6. A Jornada do Investidor: Da Proteção à Rentabilidade

Investir é colocar o dinheiro para trabalhar e proteger seu poder de compra contra a inflação. O primeiro passo é a **Reserva de Emergência** (ou "colchão de segurança"). O tamanho depende da sua estabilidade:
* **3 meses** do custo de vida para funcionários públicos estáveis.
* **6 meses** (ou mais) para profissionais liberais e do setor privado.

Este valor deve estar em ativos de **Liquidez Diária** (disponibilidade imediata), como o Tesouro Selic ou CDBs de bancos sólidos. Entenda o "Tripé dos Investimentos": Risco, Liquidez e Rentabilidade. É impossível ter o máximo dos três ao mesmo tempo (se o risco é baixo e a liquidez é alta, a rentabilidade será menor).

#### 📊 Resumo Comparativo de Ativos (B3):
* **ETFs (Fundos de Índice):** Você compra uma cesta inteira de ações (como o Ibovespa) de uma vez. É a forma mais fácil de diversificar com pouco dinheiro.
* **BDRs:** Recibos que permitem investir em empresas gigantes de fora (como Apple ou Google) diretamente pela bolsa brasileira, em reais.
* **FIIs (Fundos Imobiliários):** Você se torna "dono" de pedaços de shoppings e galpões, recebendo aluguéis mensais isentos de IR na sua conta.

#### 🛡️ Mecanismos de Proteção:
* **FGC (Fundo Garantidor de Créditos):** Protege depósitos bancários e CDBs até R$ 250 mil em caso de falência do banco.
* **MRP (Mecanismo de Ressarcimento de Prejuízos):** Proteção específica da B3 que ressarce até R$ 120 mil por erros operacionais, fraudes ou falhas das corretoras (não cobre perdas por oscilação de mercado).

---

### 7. Dicionário do Mercado Financeiro: Glossário Essencial

Dominar os termos é o primeiro passo para a sua autonomia:

*   **Custo Efetivo Total (CET):** É o percentual que representa o **custo real de um empréstimo ou financiamento**, indo além da simples taxa de juros ao incluir tarifas bancárias, impostos (como o IOF), seguros e outros encargos da operação.
*   **CDB (Certificado de Depósito Bancário):** Título de renda fixa que funciona como um **empréstimo que o investidor faz a um banco** por um prazo determinado, recebendo em troca o valor investido acrescido de juros.
*   **Engenharia Reversa de Carreira:** Estratégia de planejamento que consiste em **mirar em um cargo ou objetivo profissional de longo prazo** e mapear, de trás para frente, quais cursos, certificações e experiências técnicas são necessários hoje para chegar lá.
*   **FGC (Fundo Garantidor de Créditos):** Entidade privada que funciona como um **"seguro" para o investidor**; caso o banco onde você investiu venha a falir, o FGC garante a devolução de até R$ 250 mil por CPF em ativos como CDB e Poupança.
*   **IPCA (Índice Nacional de Preços ao Consumidor Amplo):** É o principal índice utilizado para medir a **inflação oficial no Brasil**, refletindo a variação do custo de vida e do poder de compra das famílias.
*   **Juros Compostos:** Conhecidos como **"juros sobre juros"**, ocorrem quando o rendimento de um período é incorporado ao valor principal para o cálculo dos juros do período seguinte, fazendo o dinheiro crescer de forma exponencial ao longo do tempo.
*   **Liquidez:** Refere-se à **facilidade e rapidez com que um investimento pode ser transformado em dinheiro** disponível na sua conta, a um preço justo, sem perdas financeiras significativas.
*   **Metas SMART:** Metodologia para criar objetivos claros baseada em cinco critérios: devem ser **E**specíficas, **M**ensuráveis, **A**tingíveis, **R**elevantes e com prazo (**T**emporal) definido.
*   **SELIC:** É a **taxa básica de juros da economia brasileira**, definida pelo Banco Central, que serve como referência para todas as outras taxas de juros e para a rentabilidade de diversos investimentos de renda fixa.
*   **Troca Intertemporal:** Conceito que analisa o impacto das escolhas de hoje no futuro; envolve avaliar se é mais vantajoso **poupar agora para consumir melhor depois** ou antecipar o consumo através de crédito, pagando mais caro devido aos juros.

---

### 8. IA como Mentor Financeiro: Prompts de Aprofundamento

A Inteligência Artificial pode ser sua consultora gratuita. Copie e cole estes comandos:

#### 💼 Simulação de Carreira
> **O que você aprenderá:** Como planejar seus próximos passos profissionais com foco em ganhos reais.
```text
Atue como um mentor de carreira. Eu quero tener uma renda líquida de [Inserir Valor] em 5 anos. Faça uma engenharia reversa para a profissão de [Inserir Profissão], listando os 3 cursos técnicos ou certificações mais valorizados hoje e as regiões do Brasil com maior demanda por essa função.
```

#### 📊 Organização de Gastos
> **O que você aprenderá:** Como distribuir seu salário seguindo as categorias de Nath Finanças.
```text
Com base em uma renda de [Inserir Salário], crie uma tabela de orçamento dividida em Fixas (50%), Variáveis (20%), Lazer (20%) e Investimento (10%). Sugira 3 metas práticas para reduzir as despesas variáveis de uma casa com duas pessoas.
```

#### ⏳ Poder do Tempo e Disciplina
> **O que você aprenderá:** Que a consistência mensal vale mais do que começar com muito dinheiro.
```text
Simule o acúmulo de patrimônio investindo [Inserir Valor Mensal] todos os meses durante 10, 20 e 30 anos, com taxa de 1% ao mês. Destaque como a disciplina de manter os aportes supera o valor inicial investido para mostrar o efeito dos juros compostos.
```

#### 🔍 Análise de Crédito
> **O que você aprenderá:** A enxergar as taxas escondidas antes de assinar um contrato.
```text
Explique a diferença entre uma taxa de juros de 2% ao mês e um CET (Custo Efetivo Total) de 3,5% ao mês em um empréstimo de R$ 5.000,00 parcelado em 24 vezes. Quanto eu pagarei de juros reais ao final do período?
```

---

A prosperidade não é um evento de sorte, mas o resultado da consistência e disciplina. Cada pequena vitória — seja um plano de internet renegociado ou os primeiros reais investidos — deve ser celebrada. Foco no longo prazo e calma no presente.
