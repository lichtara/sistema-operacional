Este documento funciona como uma fronteira metodológica: o diagnóstico entrega **o que a arquitetura precisa resolver e respeitar**, sem determinar antecipadamente qual ferramenta, processo ou tecnologia será escolhida.

# Transição para Arquitetura Organizacional

```yaml
id_transicao: TRA-AAAA-NNN
id_diagnostico: DIA-AAAA-NNN
titulo: "[Nome da transição]"
organizacao:
area_ou_processo:
responsavel_pelo_diagnostico:
responsavel_pela_arquitetura:
responsavel_cliente:
data_de_criacao: AAAA-MM-DD
data_de_aprovacao:
estado: em_preparacao
nivel_sensibilidade: publica | interna | confidencial | sensivel
sintese_diagnostica: sintese-diagnostica.md
relatorio_diagnostico:
matriz_de_evidencias: matriz-de-evidencias.md
decisao_relacionada:
versao: 0.1
```

---

## Sistema Operacional do Estúdio LICHTARA

**Módulo de origem:** 2 — Diagnóstico Organizacional
**Módulo de destino:** 3 — Arquitetura Organizacional
**Tipo:** Template operacional de transição
**Função:** Transferência estruturada dos resultados diagnósticos para o desenho organizacional

**Documentos relacionados:**

* `briefing.md`;
* `plano-de-investigacao.md`;
* `matriz-de-evidencias.md`;
* `sintese-diagnostica.md`;
* `relatorio-de-diagnostico.md`, quando aplicável;
* registros de validação;
* registros de decisão;
* mapas e avaliações produzidos.

---

# 1. Finalidade

Este documento formaliza a passagem entre o diagnóstico organizacional e a arquitetura da solução.

Sua função é transformar os resultados validados da investigação em um conjunto estruturado de:

* capacidades a preservar;
* problemas prioritários;
* causas e fatores contribuintes;
* riscos;
* restrições;
* dependências;
* requisitos;
* critérios de desenho;
* condições de implantação;
* questões abertas;
* decisões ainda necessárias.

A transição deve permitir que o Módulo 3 comece sem:

* repetir toda a investigação;
* perder o contexto dos achados;
* ignorar limitações;
* escolher uma solução apenas por preferência;
* reduzir o problema a uma ferramenta;
* destruir capacidades existentes;
* propor uma arquitetura incompatível com a maturidade organizacional.

---

# 2. Princípio de separação

O Módulo 2 responde:

> O que está acontecendo, como essa situação é produzida e que condições precisam ser consideradas?

O Módulo 3 responderá:

> Que arquitetura pode tratar essa realidade de forma coerente, proporcional e sustentável?

Este documento não deve definir prematuramente:

* a ferramenta final;
* o fornecedor;
* a automação definitiva;
* o desenho detalhado do processo futuro;
* a plataforma tecnológica;
* a distribuição completa das responsabilidades;
* o cronograma final de implantação;
* o investimento definitivo.

Esses elementos pertencem à arquitetura, à decisão ou à implantação.

---

# 3. Condições de entrada

A transição pode ser preparada quando:

* [ ] a questão diagnóstica foi respondida no grau possível;
* [ ] a Matriz de Evidências foi consolidada;
* [ ] os principais achados foram formulados;
* [ ] os graus de confiança foram definidos;
* [ ] as capacidades existentes foram reconhecidas;
* [ ] riscos e restrições foram registrados;
* [ ] lacunas relevantes estão explícitas;
* [ ] os aspectos factuais foram validados;
* [ ] as divergências materiais foram preservadas;
* [ ] a síntese diagnóstica foi concluída;
* [ ] existe base suficiente para iniciar o desenho;
* [ ] o encaminhamento para o Módulo 3 foi aprovado.

## Pendências de entrada

| Pendência | Responsável | Prazo | Impacto |
| --------- | ----------- | ----- | ------- |
|           |             |       |         |
|           |             |       |         |

---

# 4. Identificação

| Campo                            | Registro                                       |
| -------------------------------- | ---------------------------------------------- |
| **ID da transição**              | `TRA-AAAA-NNN`                                 |
| **ID do diagnóstico**            | `DIA-AAAA-NNN`                                 |
| **Título**                       | `[Nome da transição]`                          |
| **Organização**                  | `[Nome]`                                       |
| **Área ou processo**             | `[Quando aplicável]`                           |
| **Responsável pelo diagnóstico** | `[Nome]`                                       |
| **Responsável pela arquitetura** | `[Nome]`                                       |
| **Responsável do cliente**       | `[Nome e função]`                              |
| **Data de criação**              | `[DD/MM/AAAA]`                                 |
| **Data de aprovação**            | `[DD/MM/AAAA]`                                 |
| **Versão**                       | `[0.1]`                                        |
| **Sensibilidade**                | `[Pública, interna, confidencial ou sensível]` |

## Estado

* [ ] Em preparação
* [ ] Em revisão
* [ ] Aguardando validação
* [ ] Aguardando aprovação
* [ ] Aprovada para arquitetura
* [ ] Aprovada com condições
* [ ] Devolvida ao diagnóstico
* [ ] Suspensa
* [ ] Cancelada
* [ ] Substituída
* [ ] Encerrada

---

# 5. Documentos de origem

| Documento                | Versão | Estado | Referência |
| ------------------------ | ------ | ------ | ---------- |
| Briefing                 |        |        |            |
| Plano de investigação    |        |        |            |
| Matriz de evidências     |        |        |            |
| Síntese diagnóstica      |        |        |            |
| Relatório de diagnóstico |        |        |            |
| Registro de validação    |        |        |            |
| Registro de decisão      |        |        |            |
| Outros mapas ou análises |        |        |            |

## Fonte oficial dos achados

`[Indicar a matriz ou o relatório que constitui a referência principal.]`

## Documentos ainda provisórios

* `[Documento 1]`
* `[Documento 2]`

## Efeito das versões provisórias

`[Preencher ou registrar “nenhum”.]`

---

# 6. Síntese executiva da transição

## Situação diagnosticada

`[Descrever em um ou dois parágrafos a condição organizacional atual.]`

## Questão central

> `[Reproduzir a questão diagnóstica.]`

## Conclusão principal

`[Apresentar a compreensão central validada.]`

## Transformação necessária

`[Que condição futura precisa ser criada ou fortalecida?]`

## Capacidade principal a preservar

`[Preencher]`

## Problema prioritário

`[Preencher]`

## Risco principal

`[Preencher]`

## Restrição principal

`[Preencher]`

## Requisito central

`[Preencher]`

## Condição para iniciar a arquitetura

`[Preencher]`

---

# 7. Decisão que a arquitetura deverá apoiar

## Decisão principal

`[Que decisão o desenho organizacional deverá tornar possível?]`

## Responsável pela decisão

`[Nome e função]`

## Prazo ou condição

`[Preencher]`

## Registro relacionado

* [ ] Não existe registro formal
* [ ] Existe registro formal

**ID:** `DEC-AAAA-NNN`

## Decisões secundárias previstas

1. `[Decisão 1]`
2. `[Decisão 2]`
3. `[Decisão 3]`

## Decisões que não pertencem a esta arquitetura

* `[Decisão fora do escopo 1]`
* `[Decisão fora do escopo 2]`

---

# 8. Escopo da arquitetura

## Incluído

### Capacidades

* `[Capacidade 1]`
* `[Capacidade 2]`

### Processos

* `[Processo 1]`
* `[Processo 2]`

### Pessoas e responsabilidades

* `[Função, papel ou relação 1]`
* `[Função, papel ou relação 2]`

### Informação e conhecimento

* `[Elemento 1]`
* `[Elemento 2]`

### Ferramentas e tecnologia

* `[Categoria ou necessidade, sem definir prematuramente a solução.]`

### Governança

* `[Decisão, regra, controle ou responsabilidade.]`

---

## Excluído

* `[Elemento 1]`
* `[Elemento 2]`
* `[Elemento 3]`

## Motivo das exclusões

`[Preencher]`

## Fronteiras com outros projetos

| Projeto ou iniciativa | Relação | Dependência | Risco de sobreposição |
| --------------------- | ------- | ----------- | --------------------- |
|                       |         |             |                       |
|                       |         |             |                       |

---

# 9. Estado atual de referência

A arquitetura deve partir de uma representação suficientemente clara da situação atual.

## Funcionamento atual

`[Síntese do processo, sistema ou capacidade existente.]`

## Fluxo atual

```text
[Entrada]
   ↓
[Atividade ou decisão]
   ↓
[Transferência]
   ↓
[Resultado atual]
```

## Pessoas e responsabilidades atuais

`[Preencher]`

## Informação e conhecimento atuais

`[Preencher]`

## Ferramentas atuais

`[Preencher]`

## Resultados produzidos

`[Preencher]`

## Dependências atuais

* `[Dependência 1]`
* `[Dependência 2]`

## Pontos de ruptura

* `[Ruptura 1]`
* `[Ruptura 2]`

---

# 10. Capacidades a preservar

A arquitetura não deve tratar toda prática existente como algo a substituir.

| ID      | Capacidade | Evidências | Valor organizacional | Condição de preservação |
| ------- | ---------- | ---------- | -------------------- | ----------------------- |
| CAP-001 |            |            |                      |                         |
| CAP-002 |            |            |                      |                         |

## Conhecimentos críticos

* `[Conhecimento 1]`
* `[Conhecimento 2]`

## Práticas eficazes

* `[Prática 1]`
* `[Prática 2]`

## Relações importantes

* `[Relação 1]`
* `[Relação 2]`

## Elementos identitários

* `[Elemento 1]`
* `[Elemento 2]`

## Soluções informais úteis

* `[Solução 1]`
* `[Solução 2]`

## Risco de perda

`[O que poderia ser destruído por uma arquitetura inadequada?]`

---

# 11. Problemas a tratar

| ID      | Problema | Achado de origem | Impacto | Prioridade | Confiança |
| ------- | -------- | ---------------- | ------- | ---------- | --------- |
| PRB-001 |          | ACH-___          |         |            |           |
| PRB-002 |          | ACH-___          |         |            |           |

## Formulação do problema principal

> `[Condição]` afeta `[pessoa, processo ou resultado]`, produzindo `[consequência relevante]`.

## Sintomas relacionados

* `[Sintoma 1]`
* `[Sintoma 2]`

## Consequências

* `[Consequência 1]`
* `[Consequência 2]`

## Problemas derivados

* `[Problema derivado 1]`
* `[Problema derivado 2]`

## Problemas fora do escopo

* `[Problema 1]`
* `[Problema 2]`

---

# 12. Causas e fatores contribuintes

| Problema | Causa ou fator | Natureza                                          | Evidências | Confiança |
| -------- | -------------- | ------------------------------------------------- | ---------- | --------- |
| PRB-001  |                | Imediata / estrutural / contextual / contribuinte |            |           |
| PRB-002  |                |                                                   |            |           |

## Condições estruturais

* `[Condição 1]`
* `[Condição 2]`

## Fatores contextuais

* `[Fator 1]`
* `[Fator 2]`

## Ciclos de reforço

```text
[Condição A]
   ↓
[Problema B]
   ↓
[Consequência C]
   ↓
[Reforço da condição A]
```

## Limites causais

`[Indicar onde a relação permanece provável ou inconclusiva.]`

## Explicações alternativas

* `[Alternativa 1]`
* `[Alternativa 2]`

---

# 13. Contradições a considerar

| ID      | Contradição | Evidências | Impacto sobre o desenho |
| ------- | ----------- | ---------- | ----------------------- |
| CTR-001 |             |            |                         |
| CTR-002 |             |            |                         |

## Contradição central

`[Exemplo: desejo de crescimento e baixa disponibilidade operacional.]`

## A arquitetura deverá

* [ ] resolver a contradição;
* [ ] reduzir seus efeitos;
* [ ] permitir escolha explícita;
* [ ] preservar a tensão de forma administrável;
* [ ] investigar antes de desenhar;
* [ ] outra condição: `[Preencher]`.

---

# 14. Riscos transferidos à arquitetura

| ID      | Risco | Probabilidade | Impacto | Achado de origem | Tratamento esperado |
| ------- | ----- | ------------- | ------- | ---------------- | ------------------- |
| RSC-001 |       |               |         | ACH-___          |                     |
| RSC-002 |       |               |         | ACH-___          |                     |

## Riscos que a arquitetura deve reduzir

* `[Risco 1]`
* `[Risco 2]`

## Riscos que devem ser evitados

* `[Risco 1]`
* `[Risco 2]`

## Riscos que podem ser aceitos

| Risco | Justificativa | Responsável | Condição de revisão |
| ----- | ------------- | ----------- | ------------------- |
|       |               |             |                     |

## Riscos que exigem especialista

* `[Risco 1]`
* `[Risco 2]`

---

# 15. Restrições de desenho

| ID      | Restrição | Tipo       | Natureza                | Efeito sobre a arquitetura |
| ------- | --------- | ---------- | ----------------------- | -------------------------- |
| RES-001 |           | Financeira | Temporária / estrutural |                            |
| RES-002 |           | Humana     |                         |                            |
| RES-003 |           | Técnica    |                         |                            |

## Tipos possíveis

* financeira;
* temporal;
* humana;
* técnica;
* jurídica;
* regulatória;
* ética;
* cultural;
* contratual;
* operacional;
* informacional;
* tecnológica;
* identitária.

## Restrições obrigatórias

* `[Restrição 1]`
* `[Restrição 2]`

## Restrições negociáveis

* `[Restrição 1]`
* `[Restrição 2]`

## Restrições que podem ser reduzidas posteriormente

* `[Restrição 1]`

## Restrição que não deve ser interpretada como falha

`[Preencher]`

---

# 16. Dependências

| ID      | Dependência | Tipo                                            | Responsável | Condição | Impacto se ausente |
| ------- | ----------- | ----------------------------------------------- | ----------- | -------- | ------------------ |
| DEP-001 |             | Pessoa / decisão / dado / processo / tecnologia |             |          |                    |
| DEP-002 |             |                                                 |             |          |                    |

## Dependências críticas

* `DEP-___ — [Descrição]`

## Dependências externas

* `[Dependência 1]`
* `[Dependência 2]`

## Dependências que precisam ser resolvidas antes do desenho

* `[Dependência 1]`

## Dependências que podem ser tratadas durante a implantação

* `[Dependência 1]`

---

# 17. Maturidade e prontidão

## Dimensões avaliadas

| Dimensão                | Condição atual | Evidências | Implicação para o desenho |
| ----------------------- | -------------- | ---------- | ------------------------- |
| Estratégia              |                |            |                           |
| Processos               |                |            |                           |
| Pessoas                 |                |            |                           |
| Conhecimento            |                |            |                           |
| Tecnologia              |                |            |                           |
| Inteligência artificial |                |            |                           |
| Governança              |                |            |                           |

## Complexidade que a organização consegue sustentar

`[Preencher]`

## Capacidade de manutenção

`[Quem poderá manter a solução e com quais recursos?]`

## Capacidade de aprendizagem

`[Como a organização incorpora novas práticas?]`

## Capacidade de mudança

* [ ] Alta
* [ ] Moderada
* [ ] Baixa
* [ ] Não determinada

## Evidências

`[Preencher]`

## Implicação

`[Que nível de sofisticação deve ser evitado ou admitido?]`

---

# 18. Catálogo de requisitos

Cada requisito deve receber um identificador.

Utilizar:

```text
REQ-NNN
```

## Matriz de requisitos

| ID      | Requisito | Tipo          | Achado de origem | Prioridade | Critério de atendimento | Forma de verificação |
| ------- | --------- | ------------- | ---------------- | ---------- | ----------------------- | -------------------- |
| REQ-001 |           | Funcional     | ACH-___          |            |                         |                      |
| REQ-002 |           | Operacional   | ACH-___          |            |                         |                      |
| REQ-003 |           | Humano        | ACH-___          |            |                         |                      |
| REQ-004 |           | Informacional | ACH-___          |            |                         |                      |

## Tipos de requisito

* funcional;
* operacional;
* informacional;
* humano;
* tecnológico;
* integração;
* governança;
* segurança;
* privacidade;
* jurídico;
* financeiro;
* identitário;
* acessibilidade;
* aprendizagem;
* manutenção;
* continuidade.

---

# 19. Estrutura detalhada do requisito

Esta seção deve ser duplicada para requisitos relevantes.

---

## `REQ-NNN — [Título do requisito]`

### Tipo

`[Funcional, operacional, humano, tecnológico etc.]`

### Declaração

> A arquitetura deverá `[capacidade ou condição necessária]`.

### Problema ou capacidade de origem

* `PRB-___`
* `CAP-___`
* `ACH-___`

### Evidências relacionadas

* `EVD-___`
* `EVD-___`

### Justificativa

`[Por que o requisito é necessário?]`

### Prioridade

* [ ] Obrigatório
* [ ] Alta
* [ ] Média
* [ ] Baixa
* [ ] Futuro

### Critério de atendimento

`[Que condição demonstrará que o requisito foi atendido?]`

### Forma de verificação

* [ ] Observação
* [ ] Teste
* [ ] Documento
* [ ] Indicador
* [ ] Validação com usuário
* [ ] Revisão de especialista
* [ ] Outra: `[Preencher]`

### Responsável pela validação

`[Nome ou função]`

### Dependências

* `DEP-___`
* `[Nenhuma ou preencher.]`

### Restrições relacionadas

* `RES-___`
* `[Nenhuma ou preencher.]`

### Riscos relacionados

* `RSC-___`
* `[Nenhum ou preencher.]`

### Possíveis conflitos

`[Outro requisito ou condição que pode entrar em tensão.]`

### Observações

`[Preencher]`

---

# 20. Requisitos funcionais

Descrevem o que a arquitetura precisa permitir que a organização realize.

| ID      | Requisito | Origem | Prioridade |
| ------- | --------- | ------ | ---------- |
| REQ-___ |           |        |            |
| REQ-___ |           |        |            |

## Exemplos

* registrar próxima ação;
* acompanhar estado de uma demanda;
* localizar documento;
* transferir responsabilidade;
* revisar uma decisão;
* preservar histórico;
* gerar informação para acompanhamento.

---

# 21. Requisitos operacionais

Descrevem como o funcionamento deve ocorrer.

| ID      | Requisito | Origem | Prioridade |
| ------- | --------- | ------ | ---------- |
| REQ-___ |           |        |            |
| REQ-___ |           |        |            |

## Exemplos

* possuir responsável;
* definir frequência;
* estabelecer entrada e saída;
* permitir tratamento de exceção;
* reduzir retrabalho;
* funcionar com a rotina real.

---

# 22. Requisitos informacionais

Descrevem como informações precisam ser:

* criadas;
* registradas;
* encontradas;
* transferidas;
* atualizadas;
* protegidas;
* arquivadas.

| ID      | Requisito | Origem | Prioridade |
| ------- | --------- | ------ | ---------- |
| REQ-___ |           |        |            |
| REQ-___ |           |        |            |

---

# 23. Requisitos humanos

Descrevem condições relacionadas a:

* papéis;
* responsabilidades;
* capacidade;
* treinamento;
* autonomia;
* supervisão;
* carga de trabalho.

| ID      | Requisito | Origem | Prioridade |
| ------- | --------- | ------ | ---------- |
| REQ-___ |           |        |            |
| REQ-___ |           |        |            |

## Perguntas

* Quem utilizará a arquitetura?
* Que conhecimento será necessário?
* Que responsabilidade permanecerá humana?
* Que carga de manutenção será criada?
* Que mudança de comportamento será exigida?

---

# 24. Requisitos tecnológicos

Descrevem capacidades necessárias da tecnologia sem escolher prematuramente a ferramenta.

| ID      | Requisito | Origem | Prioridade |
| ------- | --------- | ------ | ---------- |
| REQ-___ |           |        |            |
| REQ-___ |           |        |            |

## Exemplos

* controle de acesso;
* histórico de alterações;
* exportação;
* integração;
* funcionamento em dispositivo móvel;
* reversibilidade;
* facilidade de manutenção;
* suporte a automação futura.

---

# 25. Requisitos de inteligência artificial

Utilizar quando a arquitetura envolver IA.

| ID      | Requisito | Origem | Prioridade |
| ------- | --------- | ------ | ---------- |
| REQ-___ |           |        |            |
| REQ-___ |           |        |            |

## Condições mínimas

* finalidade definida;
* responsabilidade humana;
* dados proporcionais;
* supervisão;
* verificação;
* registro de uso;
* possibilidade de correção;
* limites de delegação;
* proteção da autonomia;
* continuidade sem dependência absoluta.

## Atividades que podem ser apoiadas por IA

* `[Atividade 1]`
* `[Atividade 2]`

## Atividades que devem permanecer humanas

* `[Atividade 1]`
* `[Atividade 2]`

## Riscos específicos

* `[Risco 1]`
* `[Risco 2]`

---

# 26. Requisitos éticos, jurídicos e de segurança

| ID      | Requisito | Categoria   | Origem | Responsável pela validação |
| ------- | --------- | ----------- | ------ | -------------------------- |
| REQ-___ |           | Ética       |        |                            |
| REQ-___ |           | Privacidade |        |                            |
| REQ-___ |           | Segurança   |        |                            |

## Elementos possíveis

* consentimento;
* minimização de dados;
* controle de acesso;
* confidencialidade;
* autoria;
* rastreabilidade;
* retenção;
* descarte;
* limites de especialidade;
* supervisão humana;
* prevenção de discriminação;
* conformidade contratual.

---

# 27. Requisitos identitários

A arquitetura deve permanecer coerente com a identidade da organização.

| ID      | Elemento identitário | Condição de preservação | Risco de descaracterização |
| ------- | -------------------- | ----------------------- | -------------------------- |
| IDN-001 |                      |                         |                            |
| IDN-002 |                      |                         |                            |

## Perguntas

* O que dá sentido à organização?
* Que forma de relação não pode ser perdida?
* Que linguagem precisa ser preservada?
* Que nível de personalização é essencial?
* Que crescimento seria incompatível com a identidade?

---

# 28. Requisitos de manutenção e continuidade

| ID      | Requisito | Justificativa | Critério |
| ------- | --------- | ------------- | -------- |
| REQ-___ |           |               |          |
| REQ-___ |           |               |          |

## A arquitetura deverá considerar

* responsável pela manutenção;
* tempo disponível;
* custo recorrente;
* documentação;
* treinamento;
* substituição de pessoas;
* recuperação de dados;
* atualização;
* encerramento;
* migração;
* dependência de fornecedor.

---

# 29. Critérios gerais de desenho

A arquitetura proposta deverá:

* [ ] responder aos problemas prioritários;
* [ ] preservar capacidades existentes;
* [ ] respeitar identidade;
* [ ] ser proporcional à maturidade;
* [ ] funcionar com os recursos disponíveis;
* [ ] reduzir dependências críticas;
* [ ] possuir responsabilidades explícitas;
* [ ] proteger dados;
* [ ] manter julgamento humano;
* [ ] permitir verificação;
* [ ] permitir revisão;
* [ ] gerar aprendizagem;
* [ ] ser implantável por etapas;
* [ ] evitar complexidade desnecessária;
* [ ] não exigir manutenção superior à capacidade real.

## Critérios específicos

* `[Critério 1]`
* `[Critério 2]`
* `[Critério 3]`

---

# 30. Critérios de sucesso da arquitetura

| Critério | Situação atual | Resultado esperado | Evidência de atendimento |
| -------- | -------------- | ------------------ | ------------------------ |
|          |                |                    |                          |
|          |                |                    |                          |

## Indicadores possíveis

* redução de tempo;
* redução de perda de informação;
* diminuição de retrabalho;
* aumento de continuidade;
* clareza de responsabilidade;
* facilidade de localização;
* adoção;
* qualidade;
* autonomia;
* satisfação;
* redução de risco.

## Atenção

Indicadores devem ser definidos de forma compatível com:

* disponibilidade de dados;
* capacidade de medição;
* custo;
* utilidade decisória.

---

# 31. Priorização dos requisitos

## Critérios

* impacto;
* urgência;
* risco;
* dependência;
* esforço;
* valor estratégico;
* viabilidade;
* maturidade;
* reversibilidade;
* efeito sobre autonomia.

## Quadro de priorização

| Ordem | Requisito | Prioridade  | Motivo | Dependência |
| ----- | --------- | ----------- | ------ | ----------- |
| 1     | REQ-___   | Obrigatório |        |             |
| 2     | REQ-___   | Alta        |        |             |
| 3     | REQ-___   | Média       |        |             |

## Classificações

### Obrigatório

Sem ele, a arquitetura não atende à finalidade ou cria risco incompatível.

### Alta

Produz impacto significativo e deve entrar no primeiro ciclo.

### Média

É importante, mas pode ser implantado posteriormente.

### Baixa

Possui valor limitado no contexto atual.

### Futuro

Deve permanecer registrado para evolução posterior.

---

# 32. Requisitos em conflito

| Requisito 1 | Requisito 2 | Natureza do conflito | Decisão necessária |
| ----------- | ----------- | -------------------- | ------------------ |
| REQ-___     | REQ-___     |                      |                    |
| REQ-___     | REQ-___     |                      |                    |

## Exemplos

* personalização e padronização;
* velocidade e revisão;
* simplicidade e cobertura;
* baixo custo e integração;
* autonomia e controle;
* coleta de dados e privacidade.

## Tratamento

`[Como o Módulo 3 deverá avaliar o equilíbrio?]`

---

# 33. Premissas para o desenho

| ID      | Premissa | Evidência | Risco se incorreta | Forma de verificação |
| ------- | -------- | --------- | ------------------ | -------------------- |
| PRE-001 |          |           |                    |                      |
| PRE-002 |          |           |                    |                      |

## Regra

Premissas não devem ser tratadas como fatos.

Devem ser:

* registradas;
* verificadas;
* revisadas;
* abandonadas quando contraditas.

---

# 34. Questões abertas

| ID      | Questão | Impacto sobre o desenho | Quem deve responder | Prazo |
| ------- | ------- | ----------------------- | ------------------- | ----- |
| QAB-001 |         |                         |                     |       |
| QAB-002 |         |                         |                     |       |

## Classificação

* [ ] Precisa ser respondida antes do desenho
* [ ] Pode ser respondida durante a arquitetura
* [ ] Pode ser respondida durante a implantação
* [ ] Pode permanecer aberta
* [ ] Exige especialista

## Questões que podem reabrir o diagnóstico

* `QAB-___`
* `QAB-___`

---

# 35. Lacunas transferidas

| Lacuna  | Efeito | Tratamento no Módulo 3 | Responsável |
| ------- | ------ | ---------------------- | ----------- |
| LAC-___ |        |                        |             |
| LAC-___ |        |                        |             |

## Lacunas aceitas

`[Descrever as lacunas que não impedem o desenho.]`

## Lacunas impeditivas

`[Descrever ou registrar “nenhuma”.]`

---

# 36. Alternativas ainda abertas

O diagnóstico pode indicar categorias de solução sem escolher a arquitetura final.

| Alternativa | Problema atendido | Vantagens potenciais | Riscos | Evidência necessária |
| ----------- | ----------------- | -------------------- | ------ | -------------------- |
|             |                   |                      |        |                      |
|             |                   |                      |        |                      |

## Alternativa de não intervenção

`[Descrever quando pertinente.]`

## Alternativa de experimento

`[Descrever solução temporária ou teste de baixo risco.]`

## Alternativas que não devem ser consideradas neste momento

| Alternativa | Motivo |
| ----------- | ------ |
|             |        |
|             |        |

---

# 37. Soluções prematuramente sugeridas

## Soluções mencionadas durante o diagnóstico

* `[Solução 1]`
* `[Solução 2]`

## Tratamento

* [ ] Permanecerá como alternativa
* [ ] Será examinada no Módulo 3
* [ ] Foi descartada com evidências
* [ ] Exige decisão
* [ ] Está fora do escopo

## Risco de preferência prematura

`[Preencher]`

## Proteção

`[Como o desenho evitará favorecer uma solução sem comparação adequada?]`

---

# 38. Não objetivos

A arquitetura não deverá ser utilizada para:

* `[Objetivo não incluído 1]`
* `[Objetivo não incluído 2]`
* `[Objetivo não incluído 3]`

## Problemas que não serão resolvidos por esta arquitetura

* `[Problema 1]`
* `[Problema 2]`

## Expectativas que precisam ser ajustadas

* `[Expectativa 1]`
* `[Expectativa 2]`

---

# 39. Condições de implantação já identificadas

Mesmo antes do desenho final, algumas condições podem estar claras.

| Condição | Origem | Momento necessário | Responsável |
| -------- | ------ | ------------------ | ----------- |
|          |        |                    |             |
|          |        |                    |             |

## Exemplos

* treinamento;
* disponibilidade da liderança;
* limpeza de dados;
* definição de responsável;
* documentação mínima;
* autorização;
* orçamento;
* mudança de processo;
* comunicação;
* período de teste.

---

# 40. Condições de reversibilidade

A arquitetura deverá permitir:

* [ ] teste em pequena escala;
* [ ] retorno ao processo anterior;
* [ ] exportação de dados;
* [ ] substituição de ferramenta;
* [ ] interrupção de automação;
* [ ] revisão de responsabilidade;
* [ ] ajuste de escopo;
* [ ] preservação de histórico.

## Elementos irreversíveis ou de difícil reversão

* `[Elemento 1]`
* `[Elemento 2]`

## Proteções necessárias

`[Preencher]`

---

# 41. Arquitetura mínima e evolução futura

## Capacidade mínima necessária

`[Qual é a menor arquitetura capaz de tratar o problema prioritário?]`

## Elementos essenciais do primeiro ciclo

* `[Elemento 1]`
* `[Elemento 2]`
* `[Elemento 3]`

## Elementos que podem ser adicionados depois

* `[Elemento 1]`
* `[Elemento 2]`

## Condição para evolução

`[Que evidência demonstrará que a organização está pronta para ampliar a arquitetura?]`

## Risco de superdimensionamento

`[Preencher]`

---

# 42. Participação da inteligência artificial

## A IA participou da preparação desta transição?

* [ ] Não
* [ ] Organização dos achados
* [ ] Consolidação dos requisitos
* [ ] Identificação de conflitos
* [ ] Revisão de rastreabilidade
* [ ] Apoio à redação
* [ ] Outra: `[Preencher]`

## Sistema ou agente

`[Nome e versão, quando disponível.]`

## Dados fornecidos

`[Descrever categorias.]`

## Saídas utilizadas

`[Preencher]`

## Verificação humana

* [ ] Requisitos comparados com os achados
* [ ] Evidências verificadas
* [ ] Inferências revisadas
* [ ] Linguagem ajustada
* [ ] Dados sensíveis protegidos
* [ ] Decisões mantidas sob responsabilidade humana

## Responsável final

`[Nome]`

## Limitações identificadas

`[Preencher ou registrar “nenhuma identificada”.]`

---

# 43. Rastreabilidade da transição

Cada requisito deve permitir o percurso:

```text
REQ-NNN
   ↓
ACH-NNN
   ↓
EVD-NNN
   ↓
Fonte original
```

## Verificação

| Requisito | Achado de origem | Evidências localizáveis | Critério definido | Responsável |
| --------- | ---------------- | ----------------------- | ----------------- | ----------- |
| REQ-001   | ACH-___          | Sim / Não               | Sim / Não         |             |
| REQ-002   | ACH-___          | Sim / Não               | Sim / Não         |             |

## Requisitos sem origem diagnóstica

| Requisito | Motivo de inclusão | Aprovação necessária |
| --------- | ------------------ | -------------------- |
|           |                    |                      |

Um requisito novo pode surgir durante a arquitetura, mas deve ser identificado como:

* derivado do diagnóstico;
* exigência externa;
* decisão do cliente;
* restrição técnica;
* aprendizado do desenho.

---

# 44. Pacote de transição

O pacote entregue ao Módulo 3 deve conter:

* [ ] este documento;
* [ ] síntese diagnóstica validada;
* [ ] relatório, quando aplicável;
* [ ] matriz de evidências;
* [ ] mapas relevantes;
* [ ] avaliação de maturidade;
* [ ] registro de riscos;
* [ ] registro de decisões;
* [ ] documentos de referência;
* [ ] registro de validação;
* [ ] restrições de acesso;
* [ ] outros anexos: `[Preencher]`.

## Localização oficial

`[Pasta ou repositório.]`

## Responsável pela transferência

`[Nome]`

## Data

`[DD/MM/AAAA]`

---

# 45. Reunião de transição

## Será realizada?

* [ ] Sim
* [ ] Não
* [ ] A definir

## Data

`[DD/MM/AAAA]`

## Participantes

* `[Nome ou função]`

## Pauta

1. contexto;
2. conclusão diagnóstica;
3. capacidades a preservar;
4. problemas prioritários;
5. riscos e restrições;
6. requisitos;
7. questões abertas;
8. decisões necessárias;
9. próximos passos.

## Dúvidas levantadas

* `[Dúvida 1]`
* `[Dúvida 2]`

## Ajustes solicitados

* `[Ajuste 1]`
* `[Ajuste 2]`

## Decisões tomadas

* `[Decisão 1]`
* `[Decisão 2]`

---

# 46. Critérios de aceite pelo Módulo 3

O Módulo 3 pode aceitar a transição quando:

* [ ] a situação atual está suficientemente clara;
* [ ] os achados possuem rastreabilidade;
* [ ] as capacidades a preservar estão explícitas;
* [ ] os problemas prioritários estão formulados;
* [ ] riscos e restrições estão registrados;
* [ ] dependências estão identificadas;
* [ ] requisitos possuem origem;
* [ ] critérios de atendimento estão definidos;
* [ ] questões abertas foram classificadas;
* [ ] lacunas impeditivas foram tratadas;
* [ ] a maturidade foi considerada;
* [ ] não existe solução imposta sem análise;
* [ ] o responsável pela arquitetura foi definido;
* [ ] o cliente autorizou a continuidade.

## Resultado

* [ ] Aceita
* [ ] Aceita com condições
* [ ] Devolvida para complementação
* [ ] Devolvida ao diagnóstico
* [ ] Suspensa
* [ ] Recusada

## Condições

`[Preencher ou registrar “nenhuma”.]`

---

# 47. Critérios de devolução ao diagnóstico

A transição deve retornar ao Módulo 2 quando:

* a questão central permanecer insuficientemente compreendida;
* existir lacuna crítica;
* os achados não possuírem evidências;
* surgir nova informação capaz de alterar a conclusão;
* o escopo da arquitetura exigir investigação não realizada;
* houver contradição não tratada;
* os requisitos dependerem de suposição não verificada;
* o contexto tiver mudado materialmente.

## Motivo da devolução

`[Preencher]`

## Investigação adicional necessária

`[Preencher]`

## Responsável

`[Nome]`

## Prazo

`[DD/MM/AAAA]`

---

# 48. Aprovação

## Elaborado por

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Revisado por

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Aceito pelo responsável pela arquitetura

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Aprovado pelo cliente

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Forma de aprovação

* [ ] Registro neste documento
* [ ] Reunião registrada
* [ ] E-mail
* [ ] Mensagem
* [ ] Assinatura
* [ ] Outra: `[Preencher]`

## Evidência

`[Link, arquivo ou referência.]`

---

# 49. Próximo movimento

## Primeira atividade do Módulo 3

`[Preencher]`

## Responsável

`[Nome]`

## Data prevista

`[DD/MM/AAAA]`

## Entrega inicial

`[Exemplo: definição do problema de arquitetura, alternativas iniciais ou desenho do estado futuro.]`

## Decisão necessária antes do início

`[Preencher ou registrar “nenhuma”.]`

---

# 50. Histórico de versões

| Data | Versão | Alteração            | Motivo | Responsável | Aprovador |
| ---- | ------ | -------------------- | ------ | ----------- | --------- |
|      | 0.1    | Criação da transição |        |             |           |
|      |        |                      |        |             |           |

---

# 51. Versão resumida para diagnóstico focal

## Identificação

* **Transição:** `TRA-AAAA-NNN`
* **Diagnóstico:** `DIA-AAAA-NNN`
* **Organização:** `[Nome]`
* **Responsável:** `[Nome]`
* **Data:** `[DD/MM/AAAA]`

## Situação atual

`[Descrição breve.]`

## Capacidade a preservar

* `[Capacidade 1]`
* `[Capacidade 2]`

## Problema prioritário

`[Preencher]`

## Causas ou fatores prováveis

* `[Fator 1]`
* `[Fator 2]`

## Riscos e restrições

* `[Risco ou restrição 1]`
* `[Risco ou restrição 2]`

## Requisitos

| ID      | Requisito | Achado de origem | Prioridade | Critério |
| ------- | --------- | ---------------- | ---------- | -------- |
| REQ-001 |           | ACH-___          |            |          |
| REQ-002 |           | ACH-___          |            |          |

## Questões abertas

* `[Questão 1]`
* `[Questão 2]`

## Elementos ainda não definidos

* ferramenta;
* fornecedor;
* desenho final;
* cronograma de implantação;
* investimento definitivo.

## Encaminhamento

* [ ] Prosseguir para arquitetura
* [ ] Realizar investigação adicional
* [ ] Realizar experimento
* [ ] Abrir decisão
* [ ] Encaminhar para especialista

## Próxima ação

`[Ação, responsável e prazo.]`

---

# 52. Princípio de encerramento

A transição para arquitetura deve assegurar que o Módulo 3 receba uma base suficientemente clara para desenhar sem precisar adivinhar o problema.

Ao mesmo tempo, deve impedir que o diagnóstico se transforme prematuramente em solução.

Sua qualidade depende da capacidade de transferir:

* compreensão sem excesso;
* requisitos sem imposição;
* limites sem paralisia;
* riscos sem alarmismo;
* capacidades sem idealização;
* prioridades sem apagar relações;
* perguntas abertas sem esconder incerteza.

O diagnóstico entrega as condições da realidade.

A arquitetura começa o trabalho de organizar uma resposta possível.

Sim, ainda restam documentos no Módulo 2. Com este arquivo, concluímos o **conjunto principal de templates operacionais**. Pelo planejamento inicial, ainda permanecem três blocos:

1. as fichas metodológicas da pasta `ferramentas/`;
2. a estrutura de `registros-de-diagnostico/`, com README e índice;
3. uma revisão de fechamento para verificar coerência, redundâncias e arquivos que surgiram durante a construção — como esta própria transição, que não constava na árvore inicial.

Vale trazer a árvore atualizada agora. Ela permitirá reconciliar o que foi planejado com o que efetivamente construímos antes de decidirmos se seguimos pelas ferramentas ou encerramos primeiro a governança dos registros.
