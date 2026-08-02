# Termo de Abertura da Arquitetura Organizacional

**Identificação técnica no repositório**

```yaml
id_arquitetura: ARQ-AAAA-NNN
titulo: "[Nome claro e específico do projeto de arquitetura]"
organizacao:
area_ou_processo:
id_diagnostico: DIA-AAAA-NNN
id_transicao: TRA-AAAA-NNN
decisao_principal:
patrocinador:
responsavel_pela_arquitetura:
data_de_abertura: AAAA-MM-DD
data_de_aprovacao:
prazo_ou_condicao_de_conclusao:
estado: em_abertura
classificacao_preliminar: focal | funcional | sistemica | a_definir
nivel_sensibilidade: publica | interna | confidencial | sensivel
versao: 0.1
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 3 — Arquitetura Organizacional  
**Tipo:** Template operacional  
**Função:** Identificação, delimitação, autorização e governança inicial do projeto de arquitetura  
**Documento de referência:** Protocolo de Arquitetura Organizacional  
**Ponto de origem:** PC-1 — Aceite da transição  
**Próximo documento:** Plano de Arquitetura

**Documentos relacionados:**

- Transição para Arquitetura Organizacional;
- síntese diagnóstica;
- relatório de diagnóstico, quando aplicável;
- Matriz de Evidências;
- Matriz de Rastreabilidade da Arquitetura;
- Protocolo de Decisão;
- registros de aceite, validação e aprovação;
- políticas de confidencialidade, segurança e uso de inteligência artificial aplicáveis.

---

## 1. Finalidade

Este termo cria a identidade formal do projeto de arquitetura organizacional e registra as condições sob as quais o Estúdio LICHTARA está autorizado a planejá-lo e conduzi-lo.

Sua função é transformar uma transição aceita em um projeto:

- identificável;
- justificável;
- delimitado;
- responsável;
- autorizado;
- rastreável;
- governável;
- proporcional à transformação necessária.

O termo deve permitir que qualquer pessoa autorizada compreenda, antes do início do desenho:

1. de que diagnóstico e transição o projeto se origina;
2. que transformação organizacional precisa ser possibilitada;
3. que problema de arquitetura será formulado e tratado;
4. que decisão o projeto deverá apoiar;
5. o que está incluído e excluído;
6. que capacidades existentes precisam ser preservadas;
7. que requisitos e limites já são conhecidos;
8. quem possui responsabilidade e autoridade;
9. quais recursos, acessos e participações são necessários;
10. que entregas são esperadas;
11. em que condições o projeto poderá prosseguir, ser revisto, suspenso ou encerrado;
12. quem autorizou sua abertura.

## 2. Posição do termo no protocolo

Este documento é produzido após o **PC-1 — Aceite da transição** e antes da elaboração do Plano de Arquitetura.

```text
Diagnóstico concluído
        ↓
Transição preparada
        ↓
PC-1 — Aceite da transição
        ↓
Termo de Abertura
        ↓
Plano de Arquitetura
        ↓
Consolidação de requisitos e critérios
        ↓
PC-2 — Prontidão para desenhar
```

A aprovação deste termo significa:

> Existe um projeto de arquitetura suficientemente identificado, delimitado, responsável e autorizado para ser planejado.

A aprovação deste termo **não significa**:

- que a arquitetura futura já foi escolhida;
- que uma ferramenta foi aprovada;
- que todos os requisitos estão consolidados;
- que o projeto já está pronto para desenhar;
- que o orçamento de implantação foi autorizado;
- que a arquitetura final foi validada;
- que o Módulo 4 pode começar.

O PC-2 somente poderá ser decidido depois que problema, decisão, escopo, requisitos, critérios e plano estiverem suficientemente claros.

## 3. Instruções de uso

1. Duplique este arquivo para cada projeto real.
2. Não preencha diretamente o template-mestre.
3. Substitua os campos entre colchetes.
4. Utilize `não aplicável` quando o campo tiver sido examinado e não se aplicar.
5. Utilize `não determinado` quando a informação ainda não puder ser estabelecida.
6. Utilize `pendente` somente quando houver responsável, prazo ou condição de resolução.
7. Mantenha referências aos documentos oficiais em vez de reproduzir grandes volumes de conteúdo.
8. Preserve divergências materiais; não as transforme artificialmente em consenso.
9. Não converta preferência, hipótese ou solução solicitada em requisito obrigatório sem justificativa.
10. Não retire itens da versão aprovada; altere o estado e registre a decisão correspondente.
11. Submeta qualquer mudança material de escopo, autoridade, prazo, risco ou finalidade ao controle de mudanças.
12. Registre a evidência da aprovação, mesmo quando a organização for composta por uma única pessoa.

### 3.1 Convenções de preenchimento

| Convenção | Significado |
| --- | --- |
| `[Preencher]` | Registro necessário. |
| `Não aplicável` | O campo foi examinado e não se aplica ao projeto. |
| `Não determinado` | Ainda não existe informação suficiente. |
| `Pendente` | A definição foi adiada com tratamento explícito. |
| `A confirmar` | Existe indicação inicial que requer validação. |
| `DEC-AAAA-NNN` | Referência a decisão formal. |
| `REQ-AAA-NNN` | Referência a requisito de arquitetura. |
| `CAP-AAA-NNN` | Referência a capacidade existente ou futura. |
| `RSK-AAA-NNN` | Referência a risco. |
| `LAC-AAA-NNN` | Referência a lacuna. |

### 3.2 Princípio de concisão rastreável

O termo deve registrar o suficiente para autorizar e delimitar o projeto. Conteúdo detalhado deve permanecer em seu artefato próprio.

Sempre que houver documento oficial:

- sintetize o elemento necessário;
- registre seu identificador;
- indique a fonte;
- preserve a versão consultada;
- não crie uma segunda fonte concorrente.

## 4. Identificação do projeto

| Campo | Registro |
| --- | --- |
| ID da arquitetura | ARQ-AAAA-NNN |
| Título | [Nome específico e compreensível] |
| Organização | [Nome] |
| Unidade, área ou processo | [Quando aplicável] |
| Cliente ou responsável contratual | [Nome] |
| Solicitante | [Nome e função] |
| Patrocinador ou responsável do cliente | [Nome e função] |
| Responsável pela arquitetura | [Nome] |
| Custodiante dos registros | [Nome] |
| Data de abertura | [DD/MM/AAAA] |
| Data de aprovação | [DD/MM/AAAA] |
| Prazo ou condição de conclusão | [Data, período ou condição] |
| Classificação preliminar | [Focal, funcional, sistêmica ou a definir] |
| Sensibilidade | [Pública, interna, confidencial ou sensível] |
| Versão | [0.1] |
| Estado atual | [Selecionar na seção 5] |

### 4.1 Regra para o título

O título deve indicar a capacidade, condição ou domínio que será desenhado.

**Evitar:**

> Projeto de melhoria interna

**Preferir:**

> Arquitetura da capacidade de receber, qualificar e acompanhar oportunidades comerciais

### 4.2 Identificadores relacionados

| Objeto | Identificador | Versão | Referência |
| --- | --- | --- | --- |
| Diagnóstico de origem | DIA-AAAA-NNN | [Versão] | [Link ou caminho] |
| Transição de origem | TRA-AAAA-NNN | [Versão] | [Link ou caminho] |
| Decisão relacionada | DEC-AAAA-NNN | [Versão] | [Link ou caminho] |
| Contrato, proposta ou autorização | [ID] | [Versão] | [Link ou caminho] |
| Iniciativa ou programa relacionado | [ID] | [Versão] | [Link ou caminho] |

## 5. Estado da abertura

Selecione um único estado vigente.

- [ ] **Em abertura** — informações e condições iniciais estão sendo consolidadas.
- [ ] **Aguardando informação** — existe lacuna necessária à decisão de abertura.
- [ ] **Aguardando aprovação de abertura** — o termo está completo e depende de autorização.
- [ ] **Aprovado para planejamento** — o projeto foi formalmente aberto.
- [ ] **Aprovado para planejamento com condições** — o projeto foi aberto com pendências controladas.
- [ ] **Devolvido à transição** — a base recebida precisa ser complementada ou corrigida.
- [ ] **Redirecionado** — a demanda pertence a outro tipo de trabalho.
- [ ] **Suspenso** — a abertura foi interrompida temporariamente.
- [ ] **Recusado** — o projeto não será aberto nas condições apresentadas.
- [ ] **Cancelado** — a demanda deixou de existir antes da abertura.
- [ ] **Substituído** — outro termo passou a constituir a referência vigente.

**Data da última mudança de estado:** [DD/MM/AAAA]  
**Responsável pelo registro:** [Nome]  
**Motivo ou referência:** [Preencher]

## 6. Origem e legitimidade da demanda

### 6.1 Como a necessidade de arquitetura surgiu?

- [ ] Encaminhamento de diagnóstico organizacional.
- [ ] Decisão formal resultante do diagnóstico.
- [ ] Continuidade de projeto anterior.
- [ ] Mudança estratégica.
- [ ] Exigência regulatória, contratual ou de segurança.
- [ ] Incidente ou risco material.
- [ ] Oportunidade de desenvolvimento organizacional.
- [ ] Solicitação direta com base equivalente ao diagnóstico.
- [ ] Outro: [Preencher].

### 6.2 Relato da demanda

Registre a necessidade utilizando, quando útil, as palavras do solicitante.

[Preencher]

### 6.3 Por que a demanda é legítima?

Indique a relação entre a necessidade, a finalidade da organização e a autoridade de quem solicita.

[Preencher]

### 6.4 Por que esta arquitetura importa agora?

[Preencher]

### 6.5 Consequência de não abrir o projeto

[Preencher]

### 6.6 Solução inicialmente imaginada ou solicitada

- [ ] Não foi apresentada solução.
- [ ] Foi apresentada como hipótese.
- [ ] Foi apresentada como preferência.
- [ ] Foi apresentada como restrição já decidida.
- [ ] Foi apresentada como resultado obrigatório.

**Solução mencionada:** [Preencher]

**Origem da proposta:** [Preencher]

**Tratamento metodológico:** [Explique se será hipótese, alternativa, restrição ou decisão anterior a ser verificada.]

> Uma solução solicitada não constitui automaticamente o problema, o requisito ou a arquitetura escolhida.

## 7. Registro do PC-1 — Aceite da transição

### 7.1 Resultado

- [ ] Aceita.
- [ ] Aceita com condições.
- [ ] Devolvida para complementação.
- [ ] Devolvida ao diagnóstico.
- [ ] Suspensa.
- [ ] Recusada.

### 7.2 Registro do aceite

| Campo | Registro |
| --- | --- |
| Data do PC-1 | [DD/MM/AAAA] |
| Responsável pela verificação | [Nome] |
| Responsável pela autorização organizacional | [Nome e função] |
| Versão da transição examinada | [Versão] |
| Registro oficial | [ID, link ou caminho] |
| Fundamentação resumida | [Preencher] |

### 7.3 Condições vinculadas ao aceite

| ID | Condição ou pendência | Origem | Responsável | Prazo ou gatilho | Impacto se não resolvida | Impede qual etapa? | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CON-001 | [Preencher] | [Fonte] | [Nome] | [Data/condição] | [Impacto] | [Planejamento, PC-2 ou outra] | Aberta |

### 7.4 Limite da aceitação condicional

Registre o que pode começar apesar das pendências e o que permanece proibido até sua resolução.

**Pode começar:** [Preencher]

**Não pode começar:** [Preencher]

**Pessoa autorizada a confirmar a resolução:** [Nome e função]

## 8. Documentos de origem e fonte oficial

| Documento | ID | Versão | Estado | Sensibilidade | Função neste termo | Referência |
| --- | --- | --- | --- | --- | --- | --- |
| Briefing do diagnóstico | [ID] | [Versão] | [Estado] | [Nível] | Contexto inicial | [Link] |
| Plano de investigação | [ID] | [Versão] | [Estado] | [Nível] | Delimitação diagnóstica | [Link] |
| Matriz de Evidências | [ID] | [Versão] | [Estado] | [Nível] | Fonte dos achados | [Link] |
| Síntese diagnóstica | [ID] | [Versão] | [Estado] | [Nível] | Síntese validada | [Link] |
| Relatório de diagnóstico | [ID] | [Versão] | [Estado] | [Nível] | Análise ampliada | [Link] |
| Transição para Arquitetura | TRA-AAAA-NNN | [Versão] | [Estado] | [Nível] | Fonte principal | [Link] |
| Registro do PC-1 | [ID] | [Versão] | [Estado] | [Nível] | Aceite da entrada | [Link] |
| Outros | [ID] | [Versão] | [Estado] | [Nível] | [Função] | [Link] |

### 8.1 Fonte oficial da abertura

**Documento principal:** [Indicar documento e versão]

**Regra em caso de divergência:** [Indicar qual registro prevalece ou quem decide.]

### 8.2 Documentos provisórios

| Documento | Elemento provisório | Efeito potencial | Tratamento |
| --- | --- | --- | --- |
| [Nome] | [Preencher] | [Preencher] | [Preencher] |

## 9. Síntese executiva da transição

### 9.1 Situação atual

[Descreva em um ou dois parágrafos a condição organizacional que originou o projeto.]

### 9.2 Questão diagnóstica respondida

> [Reproduzir a questão central do diagnóstico.]

### 9.3 Conclusão diagnóstica principal

[Preencher]

### 9.4 Transformação necessária

[Preencher]

### 9.5 Capacidade principal a preservar

[Preencher]

### 9.6 Problema prioritário

[Preencher]

### 9.7 Requisito central

[Preencher]

### 9.8 Risco ou limite principal

[Preencher]

### 9.9 Lacuna mais relevante

[Preencher ou registrar “nenhuma lacuna material conhecida”.]

## 10. Transformação organizacional necessária

### 10.1 Condição atual de referência

[O que a organização consegue ou não consegue realizar hoje?]

### 10.2 Condição futura necessária

[O que a organização precisará conseguir realizar de forma confiável, responsável e sustentável?]

### 10.3 Mudança observável

Complete:

> A organização passará de **[condição atual]** para **[condição futura]**, preservando **[capacidade, identidade ou relação]** e respeitando **[limites principais]**.

### 10.4 Valor organizacional esperado

| Beneficiário | Valor esperado | Como poderá ser observado | Horizonte |
| --- | --- | --- | --- |
| [Pessoa, grupo ou organização] | [Resultado] | [Sinal ou indicador] | [Período] |

### 10.5 Elementos que não devem ser perdidos na transformação

- [Elemento 1]
- [Elemento 2]
- [Elemento 3]

## 11. Problema de arquitetura

### 11.1 Formulação inicial

Utilize a estrutura:

> A organização precisa desenvolver a capacidade de **[realizar algo]** para **[produzir resultado]**, preservando **[capacidade ou identidade]** e respeitando **[limites, riscos ou restrições]**.

**Formulação do projeto:**

> [Preencher]

### 11.2 Relação com o problema diagnosticado

| Elemento | Registro |
| --- | --- |
| Problema diagnosticado | [Preencher] |
| Evidências ou achados de origem | [IDs] |
| Capacidade futura necessária | [Preencher] |
| Relação entre ambos | [Explique por que a capacidade futura trata o problema.] |

### 11.3 Pessoas, capacidades ou resultados afetados

- [Elemento 1]
- [Elemento 2]

### 11.4 Consequências que o desenho deverá reduzir

- [Consequência 1]
- [Consequência 2]

### 11.5 Incertezas da formulação

| Incerteza | Por que importa | Como será esclarecida | Limite temporal |
| --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Atividade ou decisão] | [Data/etapa] |

### 11.6 Verificação da formulação

- [ ] Declara capacidade futura, não apenas falha atual.
- [ ] Não pressupõe ferramenta ou fornecedor.
- [ ] Está ligada aos achados diagnósticos.
- [ ] Preserva capacidades existentes relevantes.
- [ ] Explicita limites principais.
- [ ] Pode orientar alternativas diferentes.
- [ ] Pode ser compreendida por quem decidirá.

## 12. Decisão que a arquitetura apoiará

### 12.1 Decisão principal

> [Que escolha, compromisso ou autorização o projeto deverá tornar possível?]

### 12.2 Autoridade decisória

| Campo | Registro |
| --- | --- |
| Pessoa ou instância | [Nome/fórum] |
| Função | [Função] |
| Fundamento da autoridade | [Papel, contrato, governança ou norma] |
| Prazo ou condição da decisão | [Data/condição] |
| Registro de decisão previsto | DEC-AAAA-NNN |

### 12.3 Alternativas inicialmente admissíveis

- [Alternativa ou classe de solução 1]
- [Alternativa ou classe de solução 2]
- [ ] A alternativa de não intervir será examinada.
- [ ] A alternativa de experimento limitado será examinada.
- [ ] As alternativas ainda serão formuladas no plano.

### 12.4 Decisões secundárias previstas

| ID provisório | Decisão | Autoridade | Dependência | Momento esperado |
| --- | --- | --- | --- | --- |
| DEC-P01 | [Preencher] | [Nome/função] | [Elemento] | [Etapa/marco] |

### 12.5 Decisões anteriores que limitam o projeto

| ID | Decisão vigente | Efeito sobre a arquitetura | Pode ser revista? | Autoridade para revisão |
| --- | --- | --- | --- | --- |
| DEC-AAAA-NNN | [Preencher] | [Preencher] | [Sim/Não/Condição] | [Nome/função] |

### 12.6 Decisões fora da autoridade deste projeto

- [Decisão 1]
- [Decisão 2]

### 12.7 Consequência do adiamento

[Preencher]

## 13. Objetivo e resultado esperado

### 13.1 Objetivo do projeto

> Desenhar, comparar, integrar, validar e documentar [capacidade ou configuração futura] para que [decisão ou resultado], respeitando [limites principais].

**Objetivo registrado:**

> [Preencher]

### 13.2 Resultado organizacional esperado

[O que deverá tornar-se possível após implantação e estabilização?]

### 13.3 Resultado projetual esperado

[O que o Módulo 3 deverá entregar para permitir decisão e passagem ao Módulo 4?]

### 13.4 Horizonte

| Horizonte | Expectativa |
| --- | --- |
| Ao concluir a arquitetura | [Decisão e pacote disponíveis] |
| Ao concluir a implantação inicial | [Capacidade mínima operante] |
| Após estabilização | [Resultado sustentável esperado] |

### 13.5 O que não constitui sucesso

- produzir grande volume de documentos sem decisão utilizável;
- escolher uma ferramenta sem desenhar a capacidade;
- aprovar um desenho que a organização não consiga sustentar;
- ocultar riscos ou divergências para cumprir prazo;
- transferir responsabilidade humana indevida para inteligência artificial;
- [Outro critério específico].

## 14. Classificação e proporcionalidade

### 14.1 Classificação preliminar

- [ ] **Focal** — uma capacidade, interface ou decisão delimitada.
- [ ] **Funcional** — conjunto relacionado de capacidades ou processo transversal.
- [ ] **Sistêmica** — múltiplas capacidades e dependências organizacionais.
- [ ] **A definir no planejamento** — informação ainda insuficiente.

### 14.2 Justificativa

[Explique por que a classificação é proporcional ao problema e à decisão.]

### 14.3 Complexidade inicial

| Fator | Baixa | Média | Alta | Justificativa |
| --- | :---: | :---: | :---: | --- |
| Número de capacidades | [ ] | [ ] | [ ] | [Preencher] |
| Número de áreas ou pessoas afetadas | [ ] | [ ] | [ ] | [Preencher] |
| Dependências entre processos | [ ] | [ ] | [ ] | [Preencher] |
| Sensibilidade dos dados | [ ] | [ ] | [ ] | [Preencher] |
| Impacto humano | [ ] | [ ] | [ ] | [Preencher] |
| Mudança tecnológica | [ ] | [ ] | [ ] | [Preencher] |
| Participação de IA | [ ] | [ ] | [ ] | [Preencher] |
| Requisitos regulatórios | [ ] | [ ] | [ ] | [Preencher] |
| Dificuldade de reversão | [ ] | [ ] | [ ] | [Preencher] |
| Incerteza diagnóstica | [ ] | [ ] | [ ] | [Preencher] |

### 14.4 Regra de revisão

**Condição que pode ampliar o projeto:** [Preencher]

**Condição que pode reduzi-lo:** [Preencher]

**Quem autoriza reclassificação:** [Nome e função]

## 15. Escopo preliminar

O escopo deve ser expresso por capacidades e fronteiras, não apenas por uma lista de documentos ou ferramentas.

### 15.1 Capacidades incluídas

| ID provisório | Capacidade | Resultado que deverá produzir | Estado atual | Motivo da inclusão |
| --- | --- | --- | --- | --- |
| CAP-F01 | [Preencher] | [Preencher] | [Inexistente, frágil, parcial ou existente] | [Preencher] |

### 15.2 Dimensões incluídas

| Dimensão | Incluída? | Elementos preliminares | Profundidade esperada |
| --- | --- | --- | --- |
| Processos e fluxos | [Sim/Não/A confirmar] | [Preencher] | [Essencial, parcial ou detalhada] |
| Papéis e responsabilidades | [Sim/Não/A confirmar] | [Preencher] | [Nível] |
| Decisões e autoridade | [Sim/Não/A confirmar] | [Preencher] | [Nível] |
| Informação e dados | [Sim/Não/A confirmar] | [Preencher] | [Nível] |
| Conhecimento e aprendizagem | [Sim/Não/A confirmar] | [Preencher] | [Nível] |
| Comunicação e coordenação | [Sim/Não/A confirmar] | [Preencher] | [Nível] |
| Documentação e registros | [Sim/Não/A confirmar] | [Preencher] | [Nível] |
| Tecnologia e integração | [Sim/Não/A confirmar] | [Preencher] | [Nível] |
| Inteligência artificial | [Sim/Não/A confirmar] | [Preencher] | [Nível] |
| Indicadores e controles | [Sim/Não/A confirmar] | [Preencher] | [Nível] |
| Governança e manutenção | [Sim/Não/A confirmar] | [Preencher] | [Nível] |

### 15.3 Fronteira operacional

| Elemento | Limite definido |
| --- | --- |
| Ponto de entrada | [Onde a capacidade ou fluxo começa] |
| Ponto de saída | [Onde termina] |
| Pessoas ou grupos | [Quem está incluído] |
| Unidades ou áreas | [Quais estão incluídas] |
| Localidades ou canais | [Quais estão incluídos] |
| Sistemas | [Quais relações serão examinadas] |
| Período de referência | [Intervalo histórico ou horizonte] |
| Exceções incluídas | [Quais situações excepcionais serão desenhadas] |

### 15.4 Nível de detalhe esperado

[Indique o que precisa ser decidido e o nível de precisão necessário para essa decisão.]

## 16. Não objetivos e exclusões

### 16.1 Não objetivos

O projeto não pretende:

- [Não objetivo 1]
- [Não objetivo 2]
- [Não objetivo 3]

### 16.2 Elementos excluídos

| Elemento excluído | Motivo | Relação com o projeto | Risco da exclusão | Encaminhamento |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Ignorar, monitorar, investigar ou criar outro projeto] |

### 16.3 Soluções ou promessas proibidas

- [Solução que não pode ser presumida]
- [Resultado que não pode ser prometido]
- [Uso que não será realizado]

### 16.4 Regra para questões emergentes

Questões fora do escopo serão:

1. registradas;
2. avaliadas quanto ao impacto sobre o projeto atual;
3. classificadas como impeditivas, relacionadas ou independentes;
4. encaminhadas à autoridade competente;
5. incorporadas apenas por decisão de mudança aprovada.

## 17. Fronteiras com outros projetos e sistemas

| Projeto, sistema ou iniciativa | Tipo de relação | Dependência recebida | Dependência fornecida | Responsável pela interface | Risco de sobreposição |
| --- | --- | --- | --- | --- | --- |
| [Nome/ID] | [Entrada, saída, compartilhamento ou conflito] | [Preencher] | [Preencher] | [Nome] | [Preencher] |

### 17.1 Fonte de verdade entre projetos

[Defina que projeto ou documento governa cada elemento compartilhado.]

### 17.2 Conflitos conhecidos

| Conflito | Projetos afetados | Autoridade para resolver | Prazo | Estado |
| --- | --- | --- | --- | --- |
| [Preencher] | [IDs] | [Nome/fórum] | [Data] | [Aberto] |

## 18. Capacidades existentes a preservar

| ID | Capacidade existente | Evidência de valor | Pessoas que a sustentam | Condição de preservação | Risco de perda |
| --- | --- | --- | --- | --- | --- |
| CAP-P01 | [Preencher] | [ACH/EV/registro] | [Preencher] | [Preencher] | [Preencher] |

### 18.1 Conhecimentos críticos

- [Conhecimento 1]
- [Conhecimento 2]

### 18.2 Práticas eficazes

- [Prática 1]
- [Prática 2]

### 18.3 Relações e elementos identitários

- [Relação ou elemento 1]
- [Relação ou elemento 2]

### 18.4 Soluções informais úteis

| Solução informal | Valor atual | Limite | Como deverá ser considerada |
| --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preservar, formalizar, adaptar ou substituir com cuidado] |

## 19. Capacidades futuras iniciais

Estas capacidades ainda serão detalhadas e validadas durante a arquitetura.

| ID provisório | Capacidade necessária | Beneficiário | Resultado | Origem | Prioridade inicial | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| CAP-F01 | [A organização precisa conseguir...] | [Quem] | [Resultado] | [ACH/PRB/REQ] | [Obrigatória, importante ou desejável] | Proposta |

### 19.1 Relações críticas entre capacidades

| Capacidade de origem | Relação | Capacidade de destino | Consequência da ruptura |
| --- | --- | --- | --- |
| CAP-F01 | [Fornece, depende, habilita ou controla] | CAP-F02 | [Preencher] |

### 19.2 Capacidade mínima viável

[Qual é o menor conjunto de capacidades que poderia produzir valor sem criar risco inaceitável?]

## 20. Requisitos iniciais

Os requisitos desta seção constituem entrada para o Catálogo de Requisitos. Eles podem ser detalhados, desdobrados, priorizados ou rejeitados de forma justificada durante o planejamento e a consolidação.

| ID | Requisito inicial | Tipo | Origem | Prioridade | Obrigatoriedade | Critério inicial de atendimento | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| REQ-ARQ-001 | [A arquitetura deve...] | [Funcional, humano, informacional, técnico, ético, regulatório, operacional ou manutenção] | [ID/fonte] | [Alta/Média/Baixa] | [Obrigatório, negociável ou desejável] | [Preencher] | Proposto |

### 20.1 Requisitos sem origem diagnóstica

| ID | Requisito | Origem posterior | Justificativa | Autoridade de inclusão |
| --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Norma, contrato, especialista ou decisão] | [Preencher] | [Nome/função] |

### 20.2 Conflitos iniciais entre requisitos

| Requisitos | Conflito ou compensação | Impacto | Decisão necessária |
| --- | --- | --- | --- |
| REQ-___ / REQ-___ | [Preencher] | [Preencher] | DEC-___ |

### 20.3 Lacunas de requisito

| ID | Lacuna | Informação necessária | Responsável | Limite para resolução | Impede PC-2? |
| --- | --- | --- | --- | --- | --- |
| LAC-ARQ-001 | [Preencher] | [Preencher] | [Nome] | [Data/etapa] | [Sim/Não] |

## 21. Critérios iniciais de desenho e sucesso

### 21.1 Critérios de desenho

| ID | Critério | Origem | Como orientará comparação | Obrigatoriedade |
| --- | --- | --- | --- | --- |
| CRI-001 | [Ex.: simplicidade sustentável] | [Fonte] | [Preencher] | [Obrigatório/Preferencial] |

Considere, quando aplicável:

- coerência com o propósito;
- preservação de capacidades valiosas;
- viabilidade humana;
- clareza de responsabilidade;
- segurança e privacidade;
- acessibilidade;
- proporcionalidade;
- manutenibilidade;
- reversibilidade;
- interoperabilidade;
- custo total de sustentação;
- observabilidade;
- capacidade de aprendizagem;
- autonomia responsável;
- possibilidade de evolução.

### 21.2 Critérios de sucesso do projeto de arquitetura

| Critério | Evidência esperada | Responsável por verificar | Momento |
| --- | --- | --- | --- |
| [Preencher] | [Artefato, validação ou decisão] | [Nome/papel] | [Marco] |

### 21.3 Critérios de aceite das entregas

As entregas serão consideradas aptas para decisão quando:

- [ ] possuírem finalidade e versão identificáveis;
- [ ] estiverem rastreadas a requisitos e decisões;
- [ ] representarem interfaces relevantes;
- [ ] explicitarem riscos, limites e lacunas;
- [ ] tiverem sido revisadas pelas pessoas adequadas;
- [ ] distinguirem fato, hipótese, recomendação e decisão;
- [ ] permitirem compreender condições de implantação e manutenção;
- [ ] cumprirem os critérios específicos abaixo.

| Entrega | Condição específica de aceite | Aprovador ou validador |
| --- | --- | --- |
| [Nome] | [Preencher] | [Nome/função] |

## 22. Princípios e limites aplicáveis

### 22.1 Princípios do Sistema Operacional relevantes

| Princípio | Implicação para este projeto |
| --- | --- |
| Responsabilidade humana | [Preencher] |
| Rastreabilidade | [Preencher] |
| Proporcionalidade | [Preencher] |
| Preservação de contexto | [Preencher] |
| Segurança e cuidado | [Preencher] |
| Aprendizagem contínua | [Preencher] |

### 22.2 Limites éticos, jurídicos, humanos e técnicos

| ID | Limite | Origem | Efeito sobre o desenho | Responsável por verificar |
| --- | --- | --- | --- | --- |
| LIM-001 | [Preencher] | [Política, lei, contrato, princípio ou decisão] | [Preencher] | [Nome/papel] |

### 22.3 Condições não negociáveis

- [Condição 1]
- [Condição 2]

### 22.4 Preferências negociáveis

- [Preferência 1]
- [Preferência 2]

## 23. Premissas, questões abertas e lacunas

### 23.1 Premissas

| ID | Premissa | Base atual | Consequência se falsa | Como será verificada | Limite de validade |
| --- | --- | --- | --- | --- | --- |
| PRE-001 | [Preencher] | [Fonte/razão] | [Impacto] | [Método] | [Data/etapa] |

### 23.2 Questões abertas

| ID | Questão | Por que importa | Responsável | Método de resposta | Prazo | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| QUE-001 | [Preencher] | [Preencher] | [Nome] | [Investigação, consulta ou decisão] | [Data] | Aberta |

### 23.3 Lacunas impeditivas e não impeditivas

| ID | Lacuna | Classificação | Etapa que pode prosseguir | Etapa bloqueada | Tratamento |
| --- | --- | --- | --- | --- | --- |
| LAC-001 | [Preencher] | [Impeditiva/Não impeditiva] | [Preencher] | [Preencher] | [Preencher] |

## 24. Restrições e dependências

### 24.1 Restrições

| ID | Restrição | Tipo | Origem | Efeito | Pode ser negociada? | Autoridade |
| --- | --- | --- | --- | --- | --- | --- |
| RES-001 | [Preencher] | [Prazo, recurso, técnica, jurídica, humana, contratual ou outra] | [Fonte] | [Preencher] | [Sim/Não/Condição] | [Nome/função] |

### 24.2 Dependências

| ID | Dependência | Fornecedor | Necessidade | Data ou condição | Plano se indisponível | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| DEP-001 | [Preencher] | [Pessoa, projeto ou sistema] | [Preencher] | [Data/condição] | [Alternativa] | [Estado] |

### 24.3 Restrições apresentadas como solução

| Declaração recebida | Classificação após exame | Justificativa | Tratamento |
| --- | --- | --- | --- |
| [Ex.: “precisa usar a ferramenta X”] | [Restrição, preferência, hipótese ou requisito] | [Preencher] | [Preencher] |

## 25. Governança inicial

### 25.1 Papéis

| Papel | Pessoa | Responsabilidade neste projeto | Autoridade | Substituto | Disponibilidade |
| --- | --- | --- | --- | --- | --- |
| Solicitante | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |
| Patrocinador | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |
| Responsável pela arquitetura | [Nome] | Integridade metodológica | [Preencher] | [Nome] | [Condição] |
| Arquiteta ou analista | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |
| Responsável dimensional | [Nome] | [Dimensão] | [Preencher] | [Nome] | [Condição] |
| Responsável pela validação | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |
| Responsável pela implantação | [Nome/A definir] | Consulta sobre implantabilidade | [Preencher] | [Nome] | [Condição] |
| Custodiante dos registros | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |
| Aprovador | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |

### 25.2 Ausência ou acúmulo de papéis

[Registre papéis ainda sem responsável e acúmulos que possam criar conflito, sobrecarga ou ausência de revisão independente.]

### 25.3 Instâncias de governança

| Instância | Finalidade | Participantes | Frequência ou gatilho | Registro produzido |
| --- | --- | --- | --- | --- |
| [Reunião de direção, revisão ou decisão] | [Preencher] | [Preencher] | [Preencher] | [Ata, decisão ou validação] |

## 26. Autoridade e responsabilidade decisória

Use as letras:

- **P** — propõe;
- **E** — elabora ou executa;
- **R** — recomenda;
- **V** — valida;
- **D** — decide;
- **A** — aprova;
- **C** — deve ser consultado;
- **I** — deve ser informado.

| Objeto ou decisão | Solicitante | Patrocinador | Responsável pela arquitetura | Analista | Validador | Especialista | Aprovador |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Aprovar abertura | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |
| Alterar escopo | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |
| Priorizar requisitos | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |
| Aceitar risco | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |
| Selecionar alternativa | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |
| Aprovar arquitetura | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |
| Suspender projeto | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |
| Autorizar implantação | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |

### 26.1 Verificação de autoridade

- [ ] Cada decisão material possui uma única autoridade final identificada.
- [ ] A autoridade organizacional do cliente está distinguida da autoridade metodológica do Estúdio.
- [ ] Aceitação de risco possui responsável legítimo.
- [ ] A aprovação da arquitetura está separada da autorização de implantação.
- [ ] Nenhuma IA ocupa função de responsabilidade, validação ou aprovação.

## 27. Participantes e pessoas afetadas

### 27.1 Mapa inicial

| Pessoa ou grupo | Relação com a capacidade | Como será afetado | Conhecimento que possui | Participação necessária | Momento | Risco de não participação |
| --- | --- | --- | --- | --- | --- | --- |
| [Nome/grupo] | [Executa, usa, recebe, mantém, decide ou supervisiona] | [Preencher] | [Preencher] | [Entrevista, oficina, revisão, teste ou decisão] | [Etapa] | [Preencher] |

### 27.2 Grupos cuja voz pode ser sub-representada

- [Grupo 1]
- [Grupo 2]

**Medida de inclusão:** [Preencher]

### 27.3 Impactos humanos iniciais

| Impacto potencial | Pessoas afetadas | Intensidade | Reversibilidade | Forma de escuta ou validação |
| --- | --- | --- | --- | --- |
| [Carga, autonomia, vigilância, acessibilidade, papel, aprendizagem ou outro] | [Grupo] | [Baixa/Média/Alta] | [Alta/Média/Baixa] | [Preencher] |

### 27.4 Disponibilidade confirmada

- [ ] Participantes essenciais foram identificados.
- [ ] A participação foi autorizada.
- [ ] Existe disponibilidade compatível com o prazo.
- [ ] Barreiras de idioma, acesso, tempo ou tecnologia foram consideradas.
- [ ] A não participação de alguma pessoa foi registrada e tratada.

## 28. Especialidades necessárias

| Especialidade | Questão que exige competência | Profissional ou fonte | Momento necessário | Condição de continuidade | Estado |
| --- | --- | --- | --- | --- | --- |
| [Jurídica, contábil, segurança, dados, acessibilidade, tecnologia ou outra] | [Preencher] | [Nome/A contratar] | [Etapa] | [Obrigatória antes de...] | [Estado] |

### 28.1 Limites de competência do Estúdio

[Registre questões sobre as quais o Estúdio não emitirá conclusão especializada.]

### 28.2 Tratamento da ausência de especialista

- [ ] A questão será excluída do escopo.
- [ ] O projeto poderá avançar até um limite definido.
- [ ] A decisão ficará suspensa.
- [ ] Será utilizada orientação oficial ou parecer existente.
- [ ] Outro: [Preencher].

## 29. Informação, dados e sensibilidade

### 29.1 Classificação geral

- [ ] Pública.
- [ ] Interna.
- [ ] Confidencial.
- [ ] Sensível.

**Justificativa:** [Preencher]

### 29.2 Categorias de informação previstas

| Categoria | Finalidade de uso | Fonte | Pessoas autorizadas | Local de armazenamento | Retenção | Restrição |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Papéis] | [Repositório] | [Período/regra] | [Preencher] |

### 29.3 Dados pessoais ou sensíveis

- [ ] Não são necessários.
- [ ] Podem aparecer incidentalmente.
- [ ] São necessários e possuem tratamento definido.
- [ ] A necessidade ainda será avaliada.

**Base, autorização ou política aplicável:** [Preencher]

**Minimização prevista:** [Preencher]

**Anonimização ou pseudonimização:** [Preencher]

### 29.4 Controle de acesso

| Repositório ou artefato | Quem acessa | Quem concede acesso | Revisão | Regra de retirada |
| --- | --- | --- | --- | --- |
| [Preencher] | [Papéis] | [Nome/função] | [Frequência] | [Preencher] |

### 29.5 Incidente ou uso inadequado

**Canal de comunicação:** [Preencher]

**Responsável inicial:** [Nome]

**Ação imediata:** [Preencher]

## 30. Participação preliminar da inteligência artificial

A IA pode apoiar atividades instrumentais. A responsabilidade pelo projeto, pelas decisões e pelas aprovações permanece humana.

### 30.1 Usos previstos

| Atividade | Papel da IA | Entrada permitida | Saída esperada | Revisão humana | Ferramenta aprovada? |
| --- | --- | --- | --- | --- | --- |
| [Pesquisa, síntese, classificação, modelagem, redação, revisão ou análise] | [Apoio específico] | [Tipo de dado] | [Produto] | [Nome/papel] | [Sim/Não/A definir] |

### 30.2 Usos proibidos

- aprovar o termo, o plano ou a arquitetura;
- decidir em nome do cliente ou do Estúdio;
- aceitar riscos;
- definir fato sem fonte verificável;
- utilizar dado incompatível com a ferramenta ou autorização;
- ocultar incerteza, divergência ou ausência de evidência;
- substituir consulta a pessoa afetada;
- emitir orientação especializada sem revisão competente;
- [Uso proibido específico].

### 30.3 Condições mínimas

- [ ] Finalidade de uso definida.
- [ ] Dados permitidos identificados.
- [ ] Ferramenta compatível com a sensibilidade.
- [ ] Revisão humana atribuída.
- [ ] Fonte e versão preservadas quando necessárias.
- [ ] Risco de erro, viés ou fabricação considerado.
- [ ] Saída identificada como assistida por IA quando relevante.
- [ ] Possibilidade de realizar a atividade sem IA examinada.

### 30.4 Decisão sobre uso de IA

- [ ] Autorizado nas condições registradas.
- [ ] Autorizado apenas com dados não sensíveis.
- [ ] Depende de avaliação adicional.
- [ ] Não autorizado neste projeto.

**Autoridade:** [Nome e função]  
**Data:** [DD/MM/AAAA]  
**Registro:** [ID ou referência]

## 31. Entregas esperadas

As entregas desta seção são preliminares. O Plano de Arquitetura definirá atividades, responsáveis, versões, dependências e marcos.

### 31.1 Núcleo esperado

- [ ] Termo de Abertura aprovado.
- [ ] Plano de Arquitetura.
- [ ] Catálogo de Requisitos.
- [ ] Mapa de Capacidades.
- [ ] Alternativas de arquitetura.
- [ ] Registros de decisão.
- [ ] Arquitetura integrada.
- [ ] Matriz de Rastreabilidade atualizada.
- [ ] Registro de validação.
- [ ] Pacote de transição para implantação.
- [ ] Registro de aprendizados.

### 31.2 Artefatos dimensionais condicionados ao escopo

- [ ] Arquitetura de processos e fluxos.
- [ ] Arquitetura de papéis e responsabilidades.
- [ ] Arquitetura da informação.
- [ ] Arquitetura do conhecimento.
- [ ] Arquitetura da comunicação.
- [ ] Arquitetura documental.
- [ ] Arquitetura de tecnologia e integrações.
- [ ] Arquitetura de inteligência artificial.
- [ ] Arquitetura de indicadores e controles.
- [ ] Outro: [Preencher].

### 31.3 Registro preliminar das entregas

| ID | Entrega | Finalidade | Público | Obrigatoriedade | Aprovador/validador | Critério inicial |
| --- | --- | --- | --- | --- | --- | --- |
| ENT-001 | [Preencher] | [Preencher] | [Preencher] | [Obrigatória/Condicional] | [Nome/papel] | [Preencher] |

### 31.4 Entregas explicitamente não incluídas

- cronograma detalhado de implantação, salvo contratação específica;
- execução da implantação;
- aquisição de ferramenta;
- migração integral de dados;
- treinamento operacional completo;
- operação continuada;
- [Outra exclusão].

## 32. Estratégia inicial de validação e aprovação

### 32.1 Objetos que precisarão ser validados

| Objeto | Quem conhece a realidade | Quem verifica tecnicamente | Quem decide ou aprova | Forma prevista |
| --- | --- | --- | --- | --- |
| Requisitos | [Nome/grupo] | [Nome/papel] | [Nome/função] | [Revisão/oficina/teste] |
| Capacidades futuras | [Nome/grupo] | [Nome/papel] | [Nome/função] | [Forma] |
| Processos e papéis | [Nome/grupo] | [Nome/papel] | [Nome/função] | [Forma] |
| Tecnologia e IA | [Nome/grupo] | [Nome/papel] | [Nome/função] | [Forma] |
| Arquitetura integrada | [Nome/grupo] | [Nome/papel] | [Nome/função] | [Forma] |

### 32.2 Validações independentes necessárias

[Preencher ou registrar “não identificadas nesta etapa”.]

### 32.3 Evidência de validação

- [ ] Ata ou registro de reunião.
- [ ] Comentários identificados.
- [ ] Lista de requisitos verificados.
- [ ] Cenários ou testes.
- [ ] Parecer especializado.
- [ ] Registro de divergências.
- [ ] Aprovação formal.

### 32.4 Distinção entre validação e aprovação

**Validação** verifica adequação, coerência ou correspondência com a realidade.

**Aprovação** manifesta autoridade para aceitar o resultado e permitir a passagem à etapa seguinte.

Uma pessoa pode validar sem possuir autoridade para aprovar.

## 33. Recursos, acessos e disponibilidade

### 33.1 Recursos previstos

| Recurso | Necessidade | Disponibilidade | Responsável por fornecer | Data limite | Consequência da ausência |
| --- | --- | --- | --- | --- | --- |
| Tempo de participantes | [Preencher] | [Confirmada/A confirmar] | [Nome] | [Data] | [Impacto] |
| Documentos e dados | [Preencher] | [Estado] | [Nome] | [Data] | [Impacto] |
| Ferramentas de trabalho | [Preencher] | [Estado] | [Nome] | [Data] | [Impacto] |
| Especialista | [Preencher] | [Estado] | [Nome] | [Data] | [Impacto] |
| Orçamento de arquitetura | [Preencher] | [Estado] | [Nome] | [Data] | [Impacto] |
| Ambiente de teste | [Preencher] | [Estado] | [Nome] | [Data] | [Impacto] |

### 33.2 Acessos necessários

| Acesso | Finalidade | Nível mínimo | Aprovador | Prazo | Revogação |
| --- | --- | --- | --- | --- | --- |
| [Sistema, pasta, agenda ou pessoa] | [Preencher] | [Leitura/edição/administração] | [Nome] | [Data] | [Regra] |

### 33.3 Disponibilidade do cliente

| Atividade | Pessoas necessárias | Carga estimada | Janela disponível | Confirmada? |
| --- | --- | --- | --- | --- |
| [Entrevista, oficina, revisão ou decisão] | [Nomes/papéis] | [Horas] | [Período] | [Sim/Não] |

### 33.4 Limite de esforço

[Registre limites contratuais, de horas, orçamento ou capacidade operacional que deverão orientar o plano.]

## 34. Prazo, urgência e marcos iniciais

### 34.1 Prazo ou condição de conclusão

[Preencher]

### 34.2 Origem da urgência

- [ ] Decisão estratégica.
- [ ] Obrigação externa.
- [ ] Risco ou incidente.
- [ ] Dependência de outro projeto.
- [ ] Janela comercial ou operacional.
- [ ] Preferência do solicitante.
- [ ] Não existe urgência material.
- [ ] Outro: [Preencher].

**Justificativa:** [Preencher]

### 34.3 Consequência do atraso

[Preencher]

### 34.4 Marcos iniciais

| Marco | Condição de conclusão | Data desejada | Dependência | Autoridade |
| --- | --- | --- | --- | --- |
| Abertura aprovada | Termo autorizado | [Data] | PC-1 | [Nome] |
| Plano concluído | Plano verificável | [Data] | Abertura | [Nome] |
| PC-2 | Prontidão para desenhar decidida | [Data] | Plano e requisitos | [Nome] |
| [Outro marco] | [Condição] | [Data] | [Dependência] | [Nome] |

### 34.5 Regra de proporcionalidade temporal

Se o prazo não permitir investigação, comparação, integração e validação compatíveis com o risco, o projeto deverá:

- reduzir escopo;
- produzir arquitetura provisória ou experimental claramente identificada;
- aumentar recursos;
- adiar a decisão;
- ou ser recusado nas condições propostas.

## 35. Comunicação e registro

### 35.1 Canais oficiais

| Finalidade | Canal | Participantes | Responsável | Registro oficial? |
| --- | --- | --- | --- | --- |
| Coordenação | [Preencher] | [Preencher] | [Nome] | [Sim/Não] |
| Entrega de documentos | [Preencher] | [Preencher] | [Nome] | Sim |
| Decisões | [Preencher] | [Preencher] | [Nome] | Sim |
| Incidentes ou bloqueios | [Preencher] | [Preencher] | [Nome] | Sim |

### 35.2 Ritmo inicial

| Encontro ou comunicação | Finalidade | Frequência/gatilho | Participantes | Produto |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Registro] |

### 35.3 Regra de comunicação decisória

Uma decisão somente será considerada vigente quando:

1. a pessoa ou instância competente estiver identificada;
2. o objeto decidido estiver claro;
3. condições, limites e divergências estiverem registrados;
4. a decisão possuir data e referência;
5. as pessoas afetadas forem informadas quando necessário.

### 35.4 Fonte oficial dos registros

**Repositório:** [Preencher]

**Estrutura ou pasta:** [Preencher]

**Custodiante:** [Nome]

## 36. Riscos iniciais do projeto

Registre riscos à condução da arquitetura, distinguindo-os dos riscos organizacionais que a arquitetura deverá tratar.

| ID | Evento de risco | Causa | Consequência | Probabilidade | Impacto | Tratamento inicial | Responsável | Gatilho |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RSK-ARQ-001 | [Preencher] | [Preencher] | [Preencher] | [Baixa/Média/Alta] | [Baixo/Médio/Alto/Crítico] | [Evitar, reduzir, transferir, aceitar ou investigar] | [Nome] | [Sinal] |

### 36.1 Riscos que exigem decisão antes do planejamento

| ID | Motivo | Autoridade | Decisão necessária | Prazo |
| --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Nome/função] | [Preencher] | [Data] |

### 36.2 Riscos de viés ou predeterminação

- [ ] Existe solução preferida por pessoa com poder.
- [ ] Existe pressão por confirmação de decisão anterior.
- [ ] Existe dependência comercial de ferramenta ou fornecedor.
- [ ] Existe informação controlada por uma única parte interessada.
- [ ] Existe risco de silenciar pessoas afetadas.
- [ ] Existe risco de tratar automação como objetivo em si.

**Tratamento:** [Preencher]

## 37. Controle de mudanças da abertura

### 37.1 Mudanças que exigem nova aprovação

- alteração da transformação necessária;
- alteração da decisão principal;
- ampliação ou redução material do escopo;
- inclusão de nova categoria de dado sensível;
- mudança de patrocinador, responsável ou aprovador;
- mudança relevante de prazo, orçamento ou disponibilidade;
- inclusão de uso de IA antes não autorizado;
- aceitação de risco alto ou crítico;
- alteração de requisito não negociável;
- mudança que afete outro projeto ou obrigação externa.

### 37.2 Fluxo de mudança

```text
Solicitação registrada
        ↓
Impacto analisado
        ↓
Recomendação técnica
        ↓
Decisão da autoridade
        ↓
Termo e rastreabilidade atualizados
        ↓
Pessoas afetadas informadas
```

### 37.3 Registro de solicitações

| ID | Mudança solicitada | Motivo | Impacto sobre escopo, prazo, risco e entregas | Recomendação | Decisão | Versão afetada |
| --- | --- | --- | --- | --- | --- | --- |
| MUD-001 | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [ID/estado] | [Versão] |

### 37.4 Autoridade de mudança

**Pode aprovar mudança de escopo:** [Nome/função]

**Pode aprovar mudança metodológica:** [Nome/função]

**Pode aceitar impacto financeiro ou temporal:** [Nome/função]

## 38. Suspensão, recusa, cancelamento e reabertura

### 38.1 Condições de suspensão

O projeto poderá ser suspenso quando:

- informação indispensável permanecer indisponível;
- autoridade decisória deixar de existir;
- risco ético, jurídico, humano ou técnico exigir avaliação;
- mudança de contexto invalidar a base diagnóstica;
- participantes essenciais não puderem contribuir;
- houver uso inadequado de dados;
- existir conflito material sem instância capaz de decidir;
- o cliente não cumprir condição necessária registrada;
- [Outra condição].

### 38.2 Condições de recusa ou encerramento antecipado

- finalidade incompatível com os princípios do Estúdio;
- exigência de resultado predeterminado sem possibilidade de exame;
- risco não mitigável;
- ausência de competência indispensável;
- inviabilidade reconhecida;
- retirada de autorização;
- substituição por outro projeto;
- perda da utilidade da decisão.

### 38.3 Autoridade

| Ação | Quem pode recomendar | Quem pode decidir | Quem deve ser informado |
| --- | --- | --- | --- |
| Suspender | [Preencher] | [Preencher] | [Preencher] |
| Recusar | [Preencher] | [Preencher] | [Preencher] |
| Cancelar | [Preencher] | [Preencher] | [Preencher] |
| Reabrir | [Preencher] | [Preencher] | [Preencher] |

### 38.4 Condições de retomada

[Que evidência, decisão ou recurso permitirá retomar o trabalho?]

### 38.5 Preservação dos registros

Mesmo quando o projeto não prosseguir, devem ser preservados:

- versão vigente do termo;
- motivo e autoridade da decisão;
- riscos e pendências;
- documentos recebidos;
- condições para eventual reabertura;
- aprendizados já produzidos.

## 39. Condições de abertura

### 39.1 Condições obrigatórias

- [ ] Existe diagnóstico ou base equivalente identificada.
- [ ] A transição possui resultado formal no PC-1.
- [ ] A situação atual está suficientemente compreendida para planejar.
- [ ] A transformação necessária foi registrada.
- [ ] O problema de arquitetura não pressupõe solução.
- [ ] A decisão apoiada e sua autoridade estão identificadas.
- [ ] O escopo preliminar e os não objetivos estão claros.
- [ ] Capacidades existentes a preservar foram reconhecidas.
- [ ] Requisitos iniciais, restrições e riscos materiais foram registrados.
- [ ] O patrocinador ou responsável do cliente está identificado.
- [ ] O responsável pela arquitetura está identificado.
- [ ] Existe disponibilidade mínima para elaborar o plano.
- [ ] Sensibilidade e acesso receberam tratamento inicial.
- [ ] A participação de IA foi limitada ou autorizada.
- [ ] Existe prazo ou condição de conclusão.
- [ ] As entregas esperadas são reconhecíveis.
- [ ] Pendências possuem responsável e limite de resolução.
- [ ] Existe autoridade para aprovar a abertura.

### 39.2 Verificação de coerência

- [ ] O objetivo responde à transformação necessária.
- [ ] O escopo é compatível com a decisão.
- [ ] As entregas são compatíveis com o escopo.
- [ ] O prazo é compatível com a complexidade.
- [ ] Os participantes são compatíveis com os impactos.
- [ ] A classificação é proporcional à amplitude do projeto.
- [ ] Os dados previstos são necessários à finalidade.
- [ ] Os usos de IA são compatíveis com sensibilidade e responsabilidade.
- [ ] As condições do PC-1 foram incorporadas.
- [ ] O termo não contradiz a transição aceita.

### 39.3 Pendências remanescentes

| ID | Pendência | Por que não impede a abertura | Responsável | Limite de resolução | Consequência do descumprimento |
| --- | --- | --- | --- | --- | --- |
| PEN-001 | [Preencher] | [Preencher] | [Nome] | [Data/etapa] | [Preencher] |

## 40. Decisão de abertura

### 40.1 Resultado

- [ ] **Aprovado para planejamento.**
- [ ] **Aprovado para planejamento com condições.**
- [ ] **Devolvido para ajuste do termo.**
- [ ] **Devolvido à transição.**
- [ ] **Redirecionado.**
- [ ] **Suspenso.**
- [ ] **Recusado.**
- [ ] **Cancelado.**

### 40.2 Fundamentação

[Registre por que o projeto deve ou não ser aberto nas condições apresentadas.]

### 40.3 Limites da autorização

Esta decisão autoriza:

- [ ] elaboração do Plano de Arquitetura;
- [ ] consolidação inicial de requisitos;
- [ ] organização das frentes e participantes;
- [ ] atividades exploratórias limitadas descritas abaixo;
- [ ] outro: [Preencher].

Esta decisão ainda não autoriza:

- seleção definitiva de solução;
- contratação de ferramenta ou fornecedor;
- alteração da operação vigente;
- uso de dados além das condições registradas;
- implantação;
- comunicação da arquitetura como aprovada;
- [Outro limite].

### 40.4 Condições vinculantes

| ID | Condição | Responsável | Prazo ou gatilho | Verificador | Efeito sobre o projeto |
| --- | --- | --- | --- | --- | --- |
| CON-ABR-001 | [Preencher] | [Nome] | [Data/condição] | [Nome] | [Preencher] |

## 41. Aprovações

### 41.1 Responsável pela arquitetura

**Nome:** [Preencher]  
**Manifestação:** [Recomendo / Recomendo com condições / Não recomendo]  
**Fundamentação:** [Preencher]  
**Data:** [DD/MM/AAAA]  
**Evidência:** [Assinatura, mensagem, ata ou registro]

### 41.2 Patrocinador ou responsável do cliente

**Nome:** [Preencher]  
**Manifestação:** [Aprovo / Aprovo com condições / Não aprovo]  
**Condições ou observações:** [Preencher]  
**Data:** [DD/MM/AAAA]  
**Evidência:** [Assinatura, mensagem, ata ou registro]

### 41.3 Aprovador adicional, quando aplicável

**Nome e função:** [Preencher]  
**Objeto da aprovação:** [Preencher]  
**Manifestação:** [Preencher]  
**Data:** [DD/MM/AAAA]  
**Evidência:** [Preencher]

### 41.4 Divergências preservadas

| Pessoa ou grupo | Divergência | Efeito sobre a aprovação | Tratamento | Decisão relacionada |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [ID] |

> Ausência de manifestação não deve ser registrada como concordância.

## 42. Próximo movimento autorizado

### 42.1 Documento seguinte

**Plano de Arquitetura:** `plano-de-arquitetura.md`

### 42.2 Responsável

[Nome]

### 42.3 Data ou condição de início

[Preencher]

### 42.4 Insumos que serão transferidos

- [ ] termo aprovado;
- [ ] transição aceita;
- [ ] documentos diagnósticos oficiais;
- [ ] condições do PC-1;
- [ ] requisitos iniciais;
- [ ] mapa preliminar de participantes;
- [ ] riscos, restrições e dependências;
- [ ] regras de acesso e uso de IA;
- [ ] decisões anteriores aplicáveis.

### 42.5 Questões que o plano deverá resolver

- [Questão 1]
- [Questão 2]
- [Questão 3]

### 42.6 Condição para submeter o PC-2

O projeto somente será submetido ao **PC-2 — Prontidão para desenhar** quando estiverem suficientemente definidos:

- problema de arquitetura;
- decisão apoiada;
- escopo e não objetivos;
- requisitos consolidados;
- critérios de desenho e comparação;
- frentes e dimensões;
- participantes e responsabilidades;
- atividades e marcos;
- estratégia de alternativas;
- estratégia de integração;
- estratégia de validação;
- riscos, dados e controles;
- plano de arquitetura.

## 43. Síntese executiva da abertura

Preencha esta seção ao final. Ela deve permitir leitura rápida sem substituir o restante do termo.

| Elemento | Síntese |
| --- | --- |
| Projeto | [ID e título] |
| Origem | [Diagnóstico e transição] |
| Transformação necessária | [Uma frase] |
| Problema de arquitetura | [Uma frase] |
| Decisão apoiada | [Uma frase] |
| Escopo | [Capacidades e fronteira] |
| Não objetivos | [Principais exclusões] |
| Capacidade a preservar | [Principal] |
| Requisito central | [Principal] |
| Risco principal | [Principal] |
| Prazo ou condição | [Preencher] |
| Patrocinador | [Nome] |
| Responsável pela arquitetura | [Nome] |
| Resultado da abertura | [Estado] |
| Condições pendentes | [IDs ou “nenhuma”] |
| Próximo movimento | Elaborar Plano de Arquitetura |

## 44. Controle de versões

| Versão | Data | Estado | Alteração | Responsável | Aprovação relacionada |
| --- | --- | --- | --- | --- | --- |
| 0.1 | [DD/MM/AAAA] | Em abertura | Criação inicial | [Nome] | [Não aplicável] |
| 1.0 | [DD/MM/AAAA] | Aprovado | Linha de base da abertura | [Nome] | [Registro] |

### 44.1 Linha de base

**Versão vigente aprovada:** [Versão]

**Data:** [DD/MM/AAAA]

**Local oficial:** [Link ou caminho]

**Versão substituída:** [Versão ou não aplicável]

## 45. Teste de reconstrução

Antes de concluir, uma pessoa autorizada que não participou da abertura deve tentar responder:

1. Por que este projeto existe?
2. De que diagnóstico e transição ele se origina?
3. Que transformação precisa ser possibilitada?
4. Que problema de arquitetura será tratado?
5. Que decisão será apoiada e quem pode tomá-la?
6. O que está dentro e fora do escopo?
7. Que capacidades precisam ser preservadas?
8. Que requisitos, restrições e riscos já são obrigatórios?
9. Quem responde pelo projeto?
10. Que dados e usos de IA são permitidos?
11. Que entregas são esperadas?
12. Que condições ainda estão abertas?
13. O que a aprovação deste termo autoriza?
14. O que ela ainda não autoriza?
15. Qual é o próximo movimento?

### 45.1 Resultado do teste

- [ ] Todas as respostas puderam ser reconstruídas.
- [ ] Existem lacunas não impeditivas registradas abaixo.
- [ ] Existem lacunas impeditivas; o termo deve retornar a `em abertura`.

| Questão | Lacuna encontrada | Correção necessária | Responsável |
| --- | --- | --- | --- |
| [Número] | [Preencher] | [Preencher] | [Nome] |

## 46. Versão reduzida para arquitetura focal

Esta versão pode ser utilizada quando o projeto for focal, de baixo risco e baixa complexidade. Ela não elimina controles obrigatórios; apenas concentra o registro.

### 46.1 Identificação

| Campo | Registro |
| --- | --- |
| ID e título | [Preencher] |
| Organização | [Preencher] |
| Diagnóstico e transição | [IDs] |
| Patrocinador | [Nome] |
| Responsável pela arquitetura | [Nome] |
| Prazo | [Preencher] |
| Sensibilidade | [Nível] |

### 46.2 Núcleo da abertura

| Elemento | Registro |
| --- | --- |
| Transformação necessária | [Preencher] |
| Problema de arquitetura | [Preencher] |
| Decisão apoiada e autoridade | [Preencher] |
| Capacidade incluída | [Preencher] |
| Fronteira | [Entrada, saída e pessoas] |
| Não objetivos | [Preencher] |
| Capacidade a preservar | [Preencher] |
| Requisitos obrigatórios | [IDs] |
| Risco ou restrição principal | [Preencher] |
| Entregas | [Preencher] |
| Participantes | [Preencher] |
| Dados e IA | [Condição] |
| Pendências | [IDs ou nenhuma] |

### 46.3 Condições mínimas

- [ ] PC-1 registrado.
- [ ] Problema sem solução predeterminada.
- [ ] Decisão e autoridade definidas.
- [ ] Escopo e exclusões definidos.
- [ ] Responsável e patrocinador definidos.
- [ ] Riscos e dados tratados.
- [ ] Prazo proporcional.
- [ ] Aprovação evidenciada.

### 46.4 Decisão

**Resultado:** [Aprovado / Aprovado com condições / Não aprovado]  
**Condições:** [Preencher]  
**Responsável pela arquitetura:** [Nome e data]  
**Patrocinador:** [Nome e data]  
**Evidência:** [Referência]

## 47. Regra de encerramento do termo

O termo está concluído quando:

- a versão aprovada constitui linha de base;
- o estado foi atualizado para `aprovado para planejamento` ou `aprovado para planejamento com condições`;
- as aprovações possuem evidência;
- as pendências foram transferidas para mecanismo de acompanhamento;
- o Plano de Arquitetura recebeu os insumos necessários;
- a Matriz de Rastreabilidade pode relacionar origem, requisitos, decisão e projeto;
- as pessoas responsáveis foram informadas.

O termo permanece como registro histórico durante todo o ciclo da arquitetura. Mudanças posteriores não apagam a abertura original: elas produzem nova versão, novo vínculo decisório ou novo termo quando a transformação e a finalidade tiverem sido materialmente alteradas.

---

## Registro final

**Estado do termo:** [Preencher]  
**Versão vigente:** [Preencher]  
**Data da conclusão:** [DD/MM/AAAA]  
**Responsável pelo registro:** [Nome]  
**Próximo documento:** `plano-de-arquitetura.md`  
**Observações finais:** [Preencher]
