# Plano de Comunicação e Engajamento

**Identificação técnica no repositório**

```yaml
id_plano_comunicacao_engajamento: PCE-IMP-AAAA-NNN
id_implantacao: IMP-AAAA-NNN
titulo: "[Nome claro e específico da implantação — Plano de Comunicação e Engajamento]"
organizacao:
area_ou_contexto:
id_termo_de_abertura: TER-IMP-AAAA-NNN
versao_termo_de_abertura:
id_plano_de_implantacao: PLA-IMP-AAAA-NNN
versao_plano_de_implantacao:
id_estrutura_analitica: EAI-IMP-AAAA-NNN
versao_estrutura_analitica:
id_cronograma_mestre: CRM-IMP-AAAA-NNN
versao_cronograma_mestre:
id_sistema_de_fluxo: BLG-IMP-AAAA-NNN
versao_sistema_de_fluxo:
id_matriz_de_rastreabilidade: MTR-IMP-AAAA-NNN
versao_matriz_de_rastreabilidade:
id_registro_integrado_controle: RIC-IMP-AAAA-NNN
versao_registro_integrado_controle:
id_projeto_arquitetura: ARQ-AAAA-NNN
id_linha_de_base_arquitetural: LB-ARQ-NNN
versao_linha_de_base_arquitetural:
data_de_status: AAAA-MM-DD
responsavel_pela_implantacao:
responsavel_pelo_plano:
autoridade_da_implantacao:
responsavel_pela_arquitetura:
responsavel_operacional:
custodiante_do_plano:
data_de_criacao: AAAA-MM-DD
data_da_ultima_revisao:
estado_do_plano: em_configuracao
classificacao_da_implantacao: focal | funcional | sistemica
nivel_de_sensibilidade: publica | interna | confidencial | sensivel
versao: 1.0
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 4 — Implantação  
**Tipo:** Template operacional  
**Função:** Governar comunicação, compreensão, participação, escuta, contribuição e devolutiva durante a implantação  
**Documentos de entrada:** linha de base aceita; arquitetura da comunicação aplicável; Termo de Abertura; Plano de Implantação; Estrutura Analítica; Cronograma Mestre; Backlog e Quadro Kanban; Matriz de Rastreabilidade; Registro Integrado de Controle vigentes  
**Documento anterior:** `templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md`  
**Documento seguinte na ordem de construção:** `templates/09-plano-de-treinamento-e-capacitacao.md`  
**Pontos de controle relacionados:** `PI-1` a `PI-5`, com ações e verificações durante todo o ciclo

---

## 1. Finalidade

Este template materializa o Plano de Comunicação e Engajamento da implantação.

Sua finalidade é criar condições para que pessoas, grupos, papéis, instâncias e organizações recebam contexto utilizável, compreendam o que lhes afeta, participem no grau aplicável, expressem conhecimento e contestação, conheçam a autoridade decisória e recebam retorno sobre suas contribuições.

O plano deve permitir demonstrar:

- que comunicações materiais possuem finalidade, objeto e público identificados;
- que pessoas afetadas foram reconhecidas sem serem reduzidas a destinatárias passivas;
- que o conteúdo necessário chega antes do efeito material, salvo emergência governada;
- que emissor, porta-voz e autoridade de representação são legítimos;
- que canais correspondem à urgência, sensibilidade, acessibilidade e necessidade de interação;
- que envio, recebimento, compreensão, concordância, compromisso e execução permanecem distinguíveis;
- que participação possui propósito, escopo e influência previamente declarados;
- que contribuições, dúvidas, objeções e alertas recebem triagem, tratamento, decisão e devolutiva;
- que discordância não é apagada nem classificada automaticamente como resistência;
- que comunicação sensível protege pessoas, dados, autoria, segurança e continuidade;
- que ações humanas estão integradas ao cronograma, ao trabalho, aos gates e às evidências;
- que comunicações recorrentes e responsabilidades transitam para a operação quando aplicável.

Comunicação emitida não significa compreensão. Participação realizada não significa influência efetiva. Manifestação recebida não significa tratamento. Engajamento não significa concordância.

---

## 2. Pergunta central

> Quem precisa compreender, participar, responder, decidir ou agir em relação a cada objeto material da implantação, com que contexto, influência, canal, tempo, proteção, confirmação e devolutiva, para que a mudança possa ser realizada de forma governável e humana?

O plano é suficiente quando outra pessoa autorizada consegue reconstruir:

1. que evento ou condição tornou a comunicação ou participação necessária;
2. que resultado comunicacional ou participativo era esperado;
3. quem foi afetado, incluído, representado ou legitimamente excluído;
4. que conteúdo e contexto foram utilizados;
5. quem emitiu, facilitou, respondeu e decidiu;
6. quando e por qual canal a ação ocorreu;
7. que estado foi efetivamente confirmado;
8. que contribuições materiais surgiram;
9. como foram tratadas e que decisão receberam;
10. que retorno foi dado;
11. que limitação, risco ou discordância permaneceu;
12. que efeito o resultado teve sobre trabalho, gate, configuração ou transição.

---

## 3. Posição no protocolo

Este plano é iniciado na Etapa 15 do Protocolo de Implantação, depois que o objeto, o escopo, a governança, a estratégia de realização e as unidades de trabalho já possuem definição suficiente.

Ele recebe da arquitetura a comunicação desenhada para o estado futuro e acrescenta as ações temporárias necessárias para preparar, realizar, liberar, validar, estabilizar e transferir a mudança.

```text
PI-1 — transição aceita
  → importar arquitetura da comunicação e públicos
  → mapear efeitos, direitos e lacunas de representação
  → planejar comunicação, participação e devolutiva
  → integrar ações ao trabalho e ao tempo
  → verificar condições humanas no PI-2
  → comunicar, escutar e ajustar durante a execução
  → preparar liberação e suporte no PI-3
  → validar compreensão, participação e efeitos no PI-4
  → transferir comunicações recorrentes e condições no PI-5
  → encerrar ações temporárias e destinar aprendizagem
```

O plano prepara e registra relações. Ele não decide gates, não substitui a autoridade e não converte compreensão em aceite presumido.

---

## 4. Natureza do documento

Este é um template-mestre duplicável.

Na implantação real:

1. duplique-o para o dossiê `IMP-AAAA-NNN`;
2. atribua identidade, versão e fonte oficial;
3. importe objetos e condições da linha de base sem renumerá-los;
4. registre apenas ações materiais e proporcionais;
5. relacione ações a objetos, públicos, trabalho, tempo e decisão;
6. mantenha dados pessoais e manifestações sensíveis nas fontes protegidas apropriadas;
7. atualize por evento e por cadência;
8. preserve fotografias utilizadas nos gates;
9. transfira comunicações recorrentes e encerre as temporárias.

| Camada | Conteúdo | Natureza |
| --- | --- | --- |
| Template | Campos, vocabulários, regras e verificações reutilizáveis. | Não preenchido como caso real. |
| Plano mestre | Fonte canônica das ações previstas e de seus estados independentes. | Fonte oficial do dossiê. |
| Registro de ocorrência | Fato de emissão, facilitação, confirmação, contribuição ou devolutiva. | Evidência contextualizada. |
| Fonte protegida | Conteúdo pessoal, sensível ou sujeito a acesso restrito. | Referenciada, sem cópia desnecessária. |
| Visão derivada | Recorte por público, onda, gate, canal, prazo ou estado. | Não altera a fonte. |
| Decisão | Ato humano de autoridade sobre objeto, contribuição ou avanço. | Fonte decisória apenas referenciada. |

---

## 5. Distinções fundamentais

| Elemento | Pergunta principal | Não comprova automaticamente |
| --- | --- | --- |
| Transmissão | O conteúdo foi enviado? | Recebimento. |
| Recebimento | O conteúdo chegou ou foi acessado? | Leitura atenta. |
| Compreensão | O sentido necessário foi interpretado? | Concordância. |
| Concordância | A pessoa aceita a proposição? | Compromisso. |
| Compromisso | Uma ação, responsabilidade ou decisão foi assumida? | Execução. |
| Execução | A ação ocorreu? | Qualidade ou resultado. |
| Informação | Que conteúdo contextualizado apoia ação ou compreensão? | Comunicação concluída. |
| Comunicação | Que relação torna informação utilizável entre participantes? | Adesão. |
| Consulta | Que experiência ou avaliação deve informar uma decisão? | Poder de decidir. |
| Cocriação | Que parte da solução será construída conjuntamente? | Aprovação final. |
| Validação | O objeto atende critérios e uso no âmbito verificado? | Autoridade de aceite. |
| Decisão | Que escolha foi feita por autoridade competente? | Compreensão pelas pessoas afetadas. |
| Participação | Como alguém intervém no objeto e em que grau? | Incorporação da contribuição. |
| Engajamento | Que relação sustentada permite compreender, contribuir e agir no escopo aplicável? | Entusiasmo, concordância ou disponibilidade ilimitada. |
| Devolutiva | Que destino e fundamento foram comunicados após contribuição ou decisão? | Satisfação com o resultado. |
| Adoção | A nova forma foi incorporada adequadamente ao trabalho? | Concordância pessoal com a mudança. |

### 5.1 Engajamento não é adesão produzida

Engajamento legítimo cria condições de relação, participação e resposta. Não utiliza comunicação para fabricar concordância, esconder perdas ou pressionar manifestação positiva.

### 5.2 Público não é massa homogênea

Pessoas com o mesmo cargo podem possuir contextos, acessos, riscos, turnos, idiomas, competências ou direitos diferentes. Segmentação precisa de fundamento material, não de conveniência retórica.

### 5.3 Silêncio não é confirmação

Ausência de pergunta, reclamação ou oposição pode decorrer de compreensão, falta de tempo, medo, ausência de canal, assimetria de poder, inacessibilidade, desinteresse legítimo ou desconhecimento. O plano não atribui sentido único ao silêncio.

### 5.4 Discordância não é incompreensão

Uma pessoa pode compreender plenamente e discordar. Quando o conteúdo foi compreendido, nova repetição da mesma mensagem não substitui tratamento da objeção.

### 5.5 Comunicação não substitui condição material

Mensagem não resolve falta de recurso, autoridade, competência, acesso, tempo, desenho adequado ou segurança. Quando o problema é material, registre e trate o objeto na fonte competente.

---

## 6. Fronteiras com os instrumentos relacionados

| Instrumento | Fonte oficial do quê | Relação com este plano |
| --- | --- | --- |
| Arquitetura da Comunicação — Módulo 3 | Eventos, públicos, mensagens, canais, retornos e proteções do estado autorizado. | É recebida e preservada; alteração material retorna ao Módulo 3. |
| `templates/01-termo-de-abertura-da-implantacao.md` | Delimitação inicial, pessoas afetadas, canais e condições conhecidas. | Fornece hipóteses e referências iniciais. |
| `templates/02-plano-de-implantacao.md` | Estratégia integrada e síntese dos planos humanos. | Referencia este plano como fonte especializada. |
| `templates/03-estrutura-analitica-da-implantacao.md` | Entregas, condições e pacotes de trabalho. | Contém o trabalho necessário para executar o plano. |
| `templates/04-cronograma-mestre-da-implantacao.md` | Datas, janelas, marcos, dependências e reservas. | Governa o compromisso temporal das ações. |
| `templates/05-backlog-e-quadro-kanban-da-implantacao.md` | Demanda qualificada e estado factual do trabalho. | Governa produção e execução cotidiana das ações. |
| `templates/06-matriz-de-rastreabilidade-da-implantacao.md` | Objetos, vínculos, cobertura e fotografias de gates. | Relaciona comunicação e participação à origem, evidência e decisão. |
| `templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md` | Riscos, problemas, impedimentos, dependências, condições e mudanças. | Recebe condições que não se resolvem por comunicação. |
| `templates/09-plano-de-treinamento-e-capacitacao.md` | Desenvolvimento e verificação de competência. | Recebe necessidades formativas; este plano comunica e mobiliza. |
| `templates/10-plano-de-gestao-da-mudanca-organizacional.md` | Impactos, transição humana, adoção e sustentação da mudança. | Recebe sinais e contribuições; não é substituído por campanha. |
| `templates/11-plano-de-piloto-ondas-virada-e-reversao.md` | Estratégia de exposição, suporte, contingência e reversão. | Define eventos que exigem comunicação e participação. |
| `templates/12-registro-de-ciclo-pdca.md` | Hipótese, teste, resultado, ajuste e aprendizagem do ciclo. | Recebe falhas e contribuições que exigem aprendizagem governada. |
| `templates/13-verificacao-de-prontidao.md` | Verificações de condição antes de execução e liberação. | Recebe evidências delimitadas de preparação humana. |
| `templates/14-registro-de-validacao-e-aceite.md` | Critérios, evidências, resultados e decisões de validação e aceite. | Recebe resultados de compreensão e participação aplicáveis. |
| `templates/15-registro-da-configuracao-implantada.md` | Forma efetivamente instalada e suas diferenças. | Recebe eventos, canais e retornos recorrentes que integram a configuração. |
| `templates/16-relatorio-de-implantacao.md` | Síntese final da realização, limites e resultados. | Referencia fatos e indicadores sem substituir o plano mestre. |
| `templates/17-transicao-para-operacao.md` | Transferência bilateral da configuração e das condições. | Recebe rotinas comunicacionais, fontes, acessos e responsabilidades. |
| `templates/18-retrospectiva-da-implantacao.md` | Aprendizagem sobre método, realização e relações. | Recebe o que produziu compreensão, participação, ruído ou exclusão. |

### 6.1 O plano não substitui a arquitetura da comunicação

Este documento planeja a comunicação da implantação. Ele não redesenha silenciosamente canais, autoridades, eventos recorrentes ou direitos comunicacionais do estado futuro.

### 6.2 O plano não substitui treinamento

Explicar mudança, procedimento ou ferramenta pode apoiar aprendizagem. Quando desempenho ou julgamento precisa ser demonstrado, a obrigação pertence ao plano de treinamento e capacitação.

### 6.3 O plano não substitui gestão da mudança

Comunicação e participação integram a mudança organizacional, mas não esgotam impactos sobre carga, identidade, autonomia, poder, adoção, suporte e capacidade.

---

## 7. Autoridade e limites

O plano pode organizar:

- finalidades, públicos, ações e sequências;
- conteúdos mínimos e pacotes de contexto;
- canais, formatos e contingências;
- métodos de participação e confirmação;
- triagem, tratamento e devolutiva;
- registros, indicadores e cadências;
- escalonamentos para a autoridade competente.

O plano não pode, por si:

- autorizar mudança arquitetural;
- representar opinião pessoal como decisão institucional;
- falar em nome de pessoa afetada sem autorização;
- prometer resultado, prazo, recurso ou proteção não aprovados;
- classificar discordância como resistência sem investigação;
- exigir exposição pessoal desnecessária;
- converter ausência de resposta em aceite;
- divulgar conteúdo além da finalidade e do acesso autorizados;
- usar IA para inferir estado emocional, intenção ou concordância;
- decidir `PI-1`, `PI-2`, `PI-3`, `PI-4` ou `PI-5`.

| Situação | Autoridade mínima | Registro |
| --- | --- | --- |
| Aprovar mensagem institucional material | Papel autorizado a representar o objeto. | Aprovação e versão da mensagem. |
| Delimitar participação e influência | Autoridade da implantação, com responsáveis e afetados aplicáveis. | Plano e fundamento. |
| Restringir público por sensibilidade | Autoridade da informação e responsável aplicável. | Classe, motivo, duração e acesso. |
| Decidir contribuição que altera execução | Alçada do Módulo 4. | Decisão e análise de impacto. |
| Decidir contribuição arquitetural | Autoridade do Módulo 3. | Retorno formal e nova linha de base, se aprovada. |
| Comunicar incidente | Autoridade do protocolo aplicável. | Registro de incidente e comunicação. |
| Aceitar lacuna de compreensão ou participação | Autoridade do gate correspondente. | Condição, risco e consequência. |

---

## 8. Instruções de uso

Preencha o plano progressivamente.

1. identifique implantação, fontes, versão e custodiante;
2. importe eventos, públicos, canais e proteções da linha de base;
3. identifique ações temporárias da implantação;
4. analise efeitos, direitos, acesso, poder e sub-representação;
5. defina propósito, objeto, influência e resultado de cada ação;
6. relacione conteúdo, emissor, canal, tempo e confirmação;
7. planeje participação, tratamento e devolutiva;
8. integre o trabalho à Estrutura Analítica, ao Cronograma e ao Kanban;
9. verifique riscos, dependências, acessibilidade e sensibilidade;
10. execute, registre fatos e preserve limitações;
11. sincronize a Matriz e os gates;
12. transfira rotinas vigentes e encerre ações temporárias.

### 8.1 Convenções de preenchimento

| Convenção | Uso |
| --- | --- |
| `[Preencher]` | Campo obrigatório ainda não informado. |
| `N.A.` | Campo avaliado e não aplicável, com fundamento quando material. |
| `Não determinado` | Informação ainda desconhecida e sujeita a tratamento. |
| `ID` | Referência estável à fonte oficial. |
| `Nome/papel` | Pessoa nominal e função quando necessário à responsabilidade. |
| `Data/gatilho` | Data fixa ou condição observável que aciona a ação. |
| `Fonte protegida` | Local de acesso controlado; não copiar conteúdo sensível. |

### 8.2 Qualidade mínima de uma ação

Uma ação não está pronta quando registra apenas “enviar comunicado”, “alinhar equipe”, “engajar usuários” ou “realizar reunião”.

Ela precisa indicar:

- evento ou objeto de origem;
- finalidade e resultado esperado;
- público e pessoas afetadas;
- influência e ação esperadas;
- conteúdo e contexto mínimos;
- emissor e autoridade;
- canal e acessibilidade;
- momento e prazo de resposta;
- confirmação proporcional;
- forma de retorno;
- evidência e destino.

---

## 9. Identificação do plano

| Campo | Preenchimento |
| --- | --- |
| ID do plano | `PCE-IMP-AAAA-NNN` |
| ID da implantação | `IMP-AAAA-NNN` |
| Título | [Preencher] |
| Organização | [Preencher] |
| Área ou contexto | [Preencher] |
| Escopo da comunicação e do engajamento | [Preencher] |
| Horizonte | [Projeto/onda/incremento/período] |
| Linha de base arquitetural | [ID/versão] |
| Arquitetura da comunicação recebida | [IDs/versões] |
| Fonte oficial | [Caminho/link] |
| Responsável pelo plano | [Nome/papel] |
| Custodiante | [Nome/papel] |
| Autoridade | [Nome/papel] |
| Classificação | [Focal/funcional/sistêmica] |
| Sensibilidade | [Classe] |
| Versão | [N.N] |
| Data de status | [AAAA-MM-DD] |

### 9.1 Escopo incluído e excluído

| Tipo | Objeto | Motivo | Fonte de referência | Autoridade |
| --- | --- | --- | --- | --- |
| Incluído | [Público/evento/onda/decisão] | [Preencher] | [ID] | [Nome/papel] |
| Excluído | [Público/evento/onda/decisão] | [Preencher] | [ID] | [Nome/papel] |

Exclusão de pessoa ou grupo materialmente afetado exige proteção, representação legítima ou decisão explícita. Não use baixa influência hierárquica como fundamento suficiente.

---

## 10. Estado do plano

| Estado | Significado | Condição típica de saída |
| --- | --- | --- |
| Em configuração | Fontes e ações estão sendo estruturadas. | Cobertura mínima definida. |
| Em validação | Públicos, responsáveis e autoridades verificam adequação. | Ajustes incorporados ou divergências registradas. |
| Vigente | Plano aprovado para orientar ações delimitadas. | Revisão, substituição ou encerramento. |
| Vigente com condições | Plano utilizável sob obrigações explícitas. | Condições cumpridas, aceitas ou escaladas. |
| Em revisão | Mudança material ou aprendizagem exige nova versão. | Versão aprovada ou plano suspenso. |
| Suspenso | Ações materiais não podem prosseguir. | Retomada autorizada, substituição ou cancelamento. |
| Substituído | Nova versão ou plano assumiu a função. | Preservação histórica. |
| Encerrado | Ações temporárias foram concluídas e rotinas destinadas. | Reabertura formal, se necessária. |

### 10.1 Estado do plano não é estado de cada ação

Um plano vigente pode conter ações planejadas, emitidas, em confirmação, em devolutiva, suspensas ou encerradas. Cada ação mantém estado próprio.

---

## 11. Fonte oficial, versões e precedência

| Fonte | ID/versão | Função | Custodiante | Acesso | Estado |
| --- | --- | --- | --- | --- | --- |
| Plano mestre | `PCE-IMP-AAAA-NNN` | Fonte canônica das ações. | [Nome/papel] | [Local] | [Estado] |
| Registro de ocorrências | [ID/local] | Fatos de execução e confirmação. | [Nome/papel] | [Local] | [Estado] |
| Fonte protegida de manifestações | [ID/local] | Conteúdo sensível minimizado. | [Nome/papel] | [Restrito] | [Estado] |
| Matriz de rastreabilidade | `MTR-IMP-AAAA-NNN` | Vínculos e cobertura. | [Nome/papel] | [Local] | [Estado] |
| Decisões | [Fonte] | Atos de autoridade. | [Nome/papel] | [Local] | [Estado] |

### 11.1 Regra de precedência

Em caso de divergência:

1. decisão formal vigente prevalece sobre resumo comunicacional;
2. linha de base arquitetural prevalece sobre interpretação de execução;
3. fonte especializada prevalece sobre cópia em apresentação ou mensagem;
4. registro de ocorrência prevalece sobre plano quanto ao fato realizado;
5. versão aprovada mais recente prevalece para o futuro sem reescrever o passado.

### 11.2 Exportações e cópias

| Exportação | Versão de origem | Data | Finalidade | Público | Validade | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [Painel/apresentação/lista] | [N.N] | [Data] | [Preencher] | [Grupos] | [Condição] | [Nome] |

Exportação é visão derivada. Atualização na cópia não altera o plano mestre.

---

## 12. Herança da arquitetura da comunicação

O Módulo 3 pode fornecer eventos, públicos, mensagens, canais, confirmações, retornos, reuniões, rituais, alertas, escalonamentos e autoridades identificados.

| Objeto herdado | ID/versão | Finalidade no estado futuro | Uso na implantação | Alteração necessária? | Destino |
| --- | --- | --- | --- | --- | --- |
| Comunicação | `COM-ARQ-___` | [Preencher] | [Preparar/testar/ativar] | [Não/sim] | [Usar/retornar ao M3] |
| Público | `PUB-ARQ-___` | [Preencher] | [Informar/consultar/validar] | [Não/sim] | [Preencher] |
| Canal | `CAN-ARQ-___` | [Preencher] | [Configurar/testar/usar] | [Não/sim] | [Preencher] |
| Confirmação | `CNF-ARQ-___` | [Preencher] | [Executar/verificar] | [Não/sim] | [Preencher] |
| Retorno | `RTA-ARQ-___` | [Preencher] | [Ativar/testar] | [Não/sim] | [Preencher] |
| Escalonamento | `ESC-ARQ-___` | [Preencher] | [Preparar/exercitar] | [Não/sim] | [Preencher] |

### 12.1 Comunicação temporária e comunicação permanente

| Natureza | Exemplo | Destino esperado |
| --- | --- | --- |
| Temporária da implantação | Convocação de piloto, aviso de janela, resultado de gate. | Encerrar com o evento e preservar evidência. |
| Preparatória do estado futuro | Apresentação de novo canal ou responsabilidade. | Transferir à configuração implantada. |
| Recorrente do estado futuro | Alerta, rito, decisão ou passagem de contexto. | Validar, configurar e transferir à operação. |
| Emergente não prevista | Comunicação exigida por risco, incidente ou descoberta. | Tratar no Módulo 4; retornar ao Módulo 3 se material e permanente. |

### 12.2 Gatilhos de retorno ao Módulo 3

Retorne quando a ação proposta:

- cria ou elimina comunicação recorrente material;
- redefine público com direito, impacto ou obrigação relevante;
- altera autoridade de representação ou decisão;
- muda interface crítica entre papéis, processos ou organizações;
- introduz novo canal estrutural, dependência ou exposição;
- modifica sensibilidade, acesso, registro ou retenção material;
- altera função comunicacional de IA;
- reduz possibilidade de contestação ou resposta;
- excede o envelope de implantação.

---

## 13. Governança do plano

| Elemento | Definição |
| --- | --- |
| Objeto governado | Ações materiais de comunicação e engajamento da implantação. |
| Fonte oficial | [Caminho/link] |
| Custodiante | [Nome/papel] |
| Responsável por conteúdo | [Nome/papel] |
| Responsável por participação | [Nome/papel] |
| Autoridade de aprovação | [Nome/papel] |
| Cadência ordinária | [Preencher] |
| Eventos extraordinários | [Mudança, gate, incidente, suspensão ou outro] |
| Regra de versionamento | [Preencher] |
| Regra de acesso | [Preencher] |
| Regra de retenção | [Preencher] |
| Regra de escalonamento | [Preencher] |

### 13.1 Uma fonte, múltiplas visões

Podem existir visões por público, onda, canal, gate, responsável ou estado. Todas derivam da fonte canônica e exibem versão ou data de corte.

### 13.2 Governança da interpretação

Sínteses de manifestações precisam preservar contexto, divergência e limite. Quem sintetiza não recebe autoridade para transformar opiniões diversas em consenso aparente.

---

## 14. Unidades de registro e identificadores

| Objeto | Padrão canônico | Uso |
| --- | --- | --- |
| Plano | `PCE-IMP-AAAA-NNN` | Identificar a fonte oficial. |
| Ação de comunicação | `IMP-AAAA-NNN-COM-NNN` | Planejar emissão, interação ou publicação material. |
| Ação de engajamento | `IMP-AAAA-NNN-ENG-NNN` | Planejar consulta, cocriação, validação ou participação. |
| Mensagem ou material | `IMP-AAAA-NNN-MSG-NNN` | Versionar conteúdo material quando necessário. |
| Confirmação | `IMP-AAAA-NNN-CNF-NNN` | Registrar ocorrência e estado confirmado. |
| Contribuição | `IMP-AAAA-NNN-CTR-NNN` | Dar identidade a manifestação material. |
| Devolutiva | `IMP-AAAA-NNN-DEV-NNN` | Registrar retorno sobre contribuição, decisão ou evento. |
| Público local da implantação | `IMP-AAAA-NNN-PUB-NNN` | Referenciar agrupamento temporário ainda não existente na arquitetura. |

Objetos herdados conservam IDs do Módulo 3. O padrão local não renumera `COM-ARQ`, `PUB-ARQ`, `CAN-ARQ`, `CNF-ARQ` ou outro objeto arquitetural.

### 14.1 Uso de IDs locais

Crie ID quando o objeto:

- possui ciclo ou estado próprio;
- aparece em mais de uma fonte;
- precisa ser relacionado a trabalho, gate, decisão ou evidência;
- contém versão material;
- exige histórico ou análise de impacto.

### 14.2 Não conversão

Uma contribuição que gera risco, impedimento, mudança ou diferença mantém seu ID e recebe vínculo ao novo objeto. Não converta `CTR` em `RIS`, `MUD` ou `DIF`.

### 14.3 Registro de namespaces

| Prefixo | Fonte | Responsável | Regra de unicidade | Estado |
| --- | --- | --- | --- | --- |
| `COM-ARQ` | Módulo 3 | [Nome/papel] | [Preencher] | [Ativo] |
| `IMP-...-COM` | Plano de Comunicação | [Nome/papel] | Sequencial no dossiê. | [Ativo] |
| `IMP-...-ENG` | Plano de Comunicação | [Nome/papel] | Sequencial no dossiê. | [Ativo] |
| `IMP-...-CTR` | Registro protegido ou mestre | [Nome/papel] | Sequencial no dossiê. | [Ativo] |

---

## 15. Registro mestre — fonte canônica das ações

Cada linha representa uma ação identificada. Resultados independentes não devem ser comprimidos em uma única coluna de “status”.

| ID | Tipo | Objeto/origem | Finalidade | Público | Influência | Momento | Canal | Estado da ação | Estado de entrega | Estado de compreensão | Estado de participação | Estado de devolutiva | Responsável | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [COM/ENG ID] | [Comunicação/consulta/cocriação/validação/outro] | [IDs] | [Preencher] | [IDs] | [Modo] | [Data/gatilho] | [ID/canal] | [Estado] | [Estado/N.A.] | [Estado/N.A.] | [Estado/N.A.] | [Estado/N.A.] | [Nome/papel] | [ID/link] |

### 15.1 Estados da ação

| Estado | Significado |
| --- | --- |
| Proposta | Necessidade identificada, ainda não qualificada. |
| Planejada | Objeto, público, finalidade e responsabilidade definidos. |
| Em preparação | Conteúdo, canal, acesso ou facilitação sendo preparados. |
| Pronta | Critérios de preparação atendidos. |
| Autorizada | Emissão ou realização material aprovada quando exigida. |
| Em execução | A ação está ocorrendo. |
| Em confirmação | Resultado comunicacional está sendo verificado. |
| Em tratamento | Contribuições ou efeitos exigem resposta. |
| Encerrada | Critério e destino foram atendidos no horizonte. |
| Cancelada | Ação não ocorrerá, com motivo e efeito registrados. |
| Suspensa | Ação interrompida até condição ou decisão. |
| Substituída | Outra ação ou versão assumiu a função. |

### 15.2 Estados independentes

| Dimensão | Estados possíveis |
| --- | --- |
| Entrega | N.A.; não iniciada; emitida; entregue parcialmente; entregue; falha; não verificável. |
| Compreensão | N.A.; não verificada; amostra insuficiente; parcial; demonstrada; divergente; refutada; não verificável. |
| Participação | N.A.; não iniciada; convocada; em curso; realizada; insuficiente; impedida; contestada. |
| Devolutiva | N.A.; não requerida; pendente; parcial; realizada; recusada com fundamento; vencida; não verificável. |

“Divergente” em compreensão significa interpretações materiais diferentes, não discordância com a decisão.

---

## 16. Catálogo de públicos, papéis e pessoas afetadas

| ID | Público, papel ou grupo | Relação com o objeto | Efeito recebido | Direito/interesse | Contexto necessário | Forma de contato | Fonte | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [PUB/PAP/GRP ID] | [Preencher] | [Executa/decide/sustenta/é afetado/outro] | [Preencher] | [Preencher] | [Preencher] | [Canal/condição] | [ID] | [Confirmado/a validar] |

### 16.1 Pessoa afetada não é apenas usuária

Inclua, quando material, quem:

- executa trabalho;
- recebe resultado;
- é avaliado por dado ou indicador;
- tem acesso, autoridade ou autonomia alterados;
- assume carga, risco ou responsabilidade;
- pode sofrer exclusão ou barreira;
- sustenta conhecimento crítico;
- responde por falha;
- depende de continuidade;
- possui direito de informação, revisão ou contestação.

### 16.2 Segmentação legítima

| Segmento | Fundamento material | Necessidade distinta | Risco da segmentação | Proteção | Revisão |
| --- | --- | --- | --- | --- | --- |
| [ID/grupo] | [Atividade, acesso, idioma, turno, efeito ou direito] | [Preencher] | [Exclusão/versões conflitantes/outro] | [Preencher] | [Data/gatilho] |

---

## 17. Impacto, direito, interesse e necessidade de participação

Não utilize apenas matrizes de “poder e interesse” para decidir quem merece ser ouvido. Hierarquia não elimina impacto, conhecimento situado ou direito aplicável.

| Público | Objeto afetado | Natureza do efeito | Materialidade | Conhecimento situado | Direito/obrigação | Influência necessária | Justificativa |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Atividade, carga, acesso, risco, benefício, perda] | [Baixa/média/alta/crítica] | [Preencher] | [Preencher] | [Informar/consultar/cocriar/validar/decidir] | [Preencher] |

### 17.1 Efeito desigual

| Mudança | Grupo beneficiado | Grupo que assume custo ou risco | Assimetria | Resposta | Autoridade |
| --- | --- | --- | --- | --- | --- |
| [ID/descrição] | [IDs] | [IDs] | [Preencher] | [Participação/proteção/compensação/escalonamento] | [Nome/papel] |

---

## 18. Pessoas ausentes, inacessíveis ou sub-representadas

| Grupo | Motivo da ausência | Efeito da ausência | Risco | Forma de inclusão, representação ou proteção | Limite | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID/grupo] | [Preencher] | [Preencher] | [ID/síntese] | [Preencher] | [Data/gatilho] | [Nome/papel] |

### 18.1 Representação

| Representado | Representante | Base da representação | Escopo | Limite | Forma de validação | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| [Grupo] | [Nome/papel] | [Mandato, escolha, papel ou outra] | [Preencher] | [Preencher] | [Preencher] | [Confirmada/a validar] |

Não presuma que gestor, especialista, usuário mais vocal ou participante disponível representa todas as pessoas afetadas.

---

## 19. Poder, segurança e possibilidade de manifestação

| Situação | Pessoas afetadas | Assimetria ou risco | Proteção | Canal | Confidencialidade | Não retaliação | Autoridade |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [IDs] | [Preencher] | [Anonimização, facilitação, canal independente ou outra] | [ID] | [Regra] | [Proteção] | [Nome/papel] |

### 19.1 Segurança para informar falhas

O plano deve permitir relato de erro, risco, sobrecarga, dano, exceção, desvio de finalidade e discordância sem exposição desnecessária.

### 19.2 Canal protegido não significa decisão secreta

O conteúdo pessoal pode permanecer restrito. O objeto, o tratamento, a autoridade e o destino precisam continuar governáveis no grau permitido.

---

## 20. Finalidades e resultados comunicacionais

| Finalidade | Resultado esperado | Público | Objeto | Evidência possível | Limite |
| --- | --- | --- | --- | --- | --- |
| Informar | Informação material disponível e encontrável. | [IDs] | [IDs] | [Publicação/entrega] | Não comprova compreensão. |
| Produzir compreensão | Público interpreta mudança e ação aplicável. | [IDs] | [IDs] | [Devolutiva/demonstração/pergunta aplicada] | Não comprova concordância. |
| Coordenar | Ações, dependências, tempos e responsáveis alinhados. | [IDs] | [IDs] | [Compromissos/registro] | Não comprova execução. |
| Consultar | Experiência ou avaliação informa decisão delimitada. | [IDs] | [IDs] | [Contribuições registradas] | Não transfere decisão. |
| Cocriar | Parte delimitada da solução é construída conjuntamente. | [IDs] | [IDs] | [Versões/contribuições] | Não implica aprovação final. |
| Validar | Adequação é verificada no escopo e critério definidos. | [IDs] | [IDs] | [Registro de validação] | Não equivale a aceite. |
| Mobilizar | Pessoas sabem quando e como participar ou agir. | [IDs] | [IDs] | [Confirmação/ação] | Não exige entusiasmo. |
| Alertar | Risco, incidente ou mudança exige atenção e resposta. | [IDs] | [IDs] | [Recepção/resposta] | Urgência precisa de critério. |
| Transferir | Contexto e responsabilidade chegam ao destinatário. | [IDs] | [IDs] | [Aceite bilateral] | Envio de arquivo não basta. |

---

## 21. Catálogo de eventos de comunicação

| ID | Evento/gatilho | Objeto | Finalidade | Públicos | Conteúdo mínimo | Prazo | Confirmação | Retorno | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [COM ID] | [Data, decisão, mudança, risco ou estado] | [IDs] | [Preencher] | [IDs] | [Preencher] | [Janela] | [Método/N.A.] | [Forma] | [Nome/papel] |

### 21.1 Eventos mínimos a avaliar

- abertura e mobilização;
- confirmação do objeto, escopo e limites;
- convocação e resultado de participação;
- alteração material de plano, prazo, risco, público ou estratégia;
- decisão de gate;
- bloqueio, suspensão, cancelamento ou retorno ao Módulo 3;
- janela de piloto, onda, virada ou operação paralela;
- liberação, contingência, reversão e restauração;
- incidente e atualização de resposta;
- condição de aceite ou risco residual;
- início, extensão e conclusão da estabilização;
- transferência para operação;
- encerramento e destino de pendências.

### 21.2 Evento sem ação necessária

| Evento | Motivo para não comunicar | Risco avaliado | Autoridade | Revisão |
| --- | --- | --- | --- | --- |
| [ID] | [Sem efeito, já coberto, consulta no ponto de uso ou outro] | [ID/síntese] | [Nome/papel] | [Data/gatilho] |

---

## 22. Catálogo de ações de engajamento

| ID | Objeto | Finalidade | Público | Modo de participação | Questão delimitada | Influência prometida | Momento | Facilitador | Saída | Devolutiva |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ENG ID] | [IDs] | [Preencher] | [IDs] | [Consultar/cocriar/validar/outro] | [Preencher] | [Preencher] | [Data/gatilho] | [Nome/papel] | [ID/tipo] | [DEV ID/método] |

### 22.1 Engajamento com objeto delimitado

Evite “ouvir as pessoas” sem dizer:

- sobre qual objeto;
- antes ou depois de qual decisão;
- que conhecimento é necessário;
- que parte pode mudar;
- que parte já foi decidida;
- quem decidirá;
- quando haverá retorno.

---

## 23. Matriz objeto–público–relação

| Objeto | Público | Relação | Informação necessária | Ação esperada | Influência | Proteção | Ação COM/ENG |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Executa/decide/sustenta/é afetado/recebe resultado] | [Preencher] | [Compreender/responder/agir/contribuir] | [Modo] | [Preencher] | [IDs] |

### 23.1 Muitos-para-muitos

Um objeto pode afetar vários públicos, e um público pode relacionar-se a vários objetos. Registre relações separadas quando necessidades, efeitos ou influências forem diferentes.

---

## 24. Modos de participação

| Modo | Função | Compromisso da governança | Não significa |
| --- | --- | --- | --- |
| Informar | Disponibilizar contexto necessário. | Clareza, tempo, acesso e canal de dúvida. | Consulta. |
| Consultar | Obter conhecimento, avaliação ou preferência. | Considerar e devolver destino. | Decisão compartilhada. |
| Cocriar | Construir alternativa ou execução delimitada. | Compartilhar trabalho e critérios. | Autoridade final automática. |
| Validar | Verificar adequação conforme critério. | Registrar resultado e limite. | Aceite institucional. |
| Decidir | Escolher por alçada competente. | Assumir fundamento e consequência. | Unanimidade. |
| Executar | Realizar ação ou aplicar decisão. | Fornecer condição, competência e suporte. | Concordância pessoal. |
| Sustentar | Manter funcionamento após transição. | Receber autoridade, recurso e aceite bilateral. | Depósito de pendências. |
| Contestar | Apresentar objeção, risco, dano ou desvio. | Proteger, tratar e responder. | Poder de veto universal. |

### 24.1 Mudança do modo

Se uma consulta passa a cocriação, ou uma validação passa a decisão, atualize escopo, autoridade, participantes, expectativa e registro antes de continuar.

---

## 25. Escopo de influência e autoridade decisória

| Ação ENG | Parte aberta à influência | Parte não aberta | Autoridade decisória | Critério | Como a influência será demonstrada | Limite |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Nome/papel] | [Preencher] | [Versão, decisão, justificativa ou outro] | [Preencher] |

### 25.1 Participação simbólica

Não convoque participação quando a decisão estiver integralmente fechada e nenhuma contribuição puder alterar compreensão, proteção, execução, validação ou decisão. Nessa situação, comunique com honestidade o que foi decidido e abra apenas os canais reais de esclarecimento e contestação.

---

## 26. Conteúdo e pacote de contexto

| Mensagem/material | Objeto | Finalidade | Conteúdo mínimo | Referências | Ação esperada | Prazo | Limites/incertezas | Versão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [MSG ID] | [IDs] | [Preencher] | [Preencher] | [IDs/links] | [Preencher] | [Data/condição] | [Preencher] | [N.N] |

### 26.1 Conteúdo mínimo para mudança material

Avalie incluir:

- o que muda;
- por que muda;
- o que permanece;
- quem e o que são afetados;
- quando o efeito começa;
- que ação é esperada;
- quem decide e dentro de qual limite;
- onde localizar a fonte oficial;
- onde pedir apoio;
- como perguntar, contribuir, contestar ou pedir revisão;
- que risco, condição ou incerteza existe;
- onde IA participa, quando material.

---

## 27. Mensagem mínima e chamada para ação

| Campo | Preenchimento |
| --- | --- |
| Título encontrável | [Preencher] |
| Estado do conteúdo | [Fato/decisão/proposta/hipótese/alerta] |
| Objeto e versão | [IDs] |
| Síntese | [Preencher] |
| Efeito para o público | [Preencher] |
| Ação esperada | [Preencher/N.A.] |
| Prazo ou gatilho | [Preencher/N.A.] |
| Autoridade | [Nome/papel] |
| Fonte oficial | [ID/link] |
| Canal de dúvida ou contestação | [Preencher] |
| Acessibilidade | [Formato/alternativa] |
| Vigência | [Período/condição] |

### 27.1 Chamada para ação não ambígua

Distinga `ler`, `confirmar recebimento`, `demonstrar compreensão`, `responder`, `contribuir`, `decidir`, `executar` e `escalar`. Não utilize “dar ciência” para ocultar qual estado realmente precisa ser confirmado.

---

## 28. Fato, decisão, hipótese, proposta e opinião

| Conteúdo | Classificação | Fonte | Grau de certeza | Autoridade | Tratamento na mensagem |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Fato/decisão/hipótese/proposta/opinião] | [ID] | [Preencher] | [Nome/papel/N.A.] | [Afirmar, qualificar, submeter ou distinguir] |

### 28.1 Incerteza explícita

Não apresente previsão, síntese de IA, expectativa de adoção ou interpretação de manifestação como fato confirmado.

---

## 29. Emissor, facilitador, porta-voz e autoridade

| Ação | Emissor/facilitador | Papel | Autoridade de representação | Aprovador | Limites | Substituto | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [COM/ENG ID] | [Nome] | [Papel] | [Objeto/alçada] | [Nome/papel] | [Preencher] | [Nome/papel] | [ID] |

### 29.1 Produção não é representação

Quem redige, formata, traduz ou prepara uma mensagem não adquire autoridade para falar em nome da organização, da decisão ou das pessoas afetadas.

### 29.2 Porta-voz

| Porta-voz | Objeto autorizado | Públicos | Canais | Vigência | Restrições | Autoridade concedente |
| --- | --- | --- | --- | --- | --- | --- |
| [Nome/papel] | [IDs] | [IDs] | [IDs] | [Período] | [Preencher] | [Nome/papel] |

---

## 30. Destinatário, receptor e pessoa afetada

| Ação | Destinatário direto | Receptor operacional | Pessoas afetadas | Precisa responder? | Pode contestar? | Exclusões justificadas |
| --- | --- | --- | --- | --- | --- | --- |
| [COM/ENG ID] | [IDs] | [Pessoa/papel/sistema] | [IDs] | [Sim/forma/N.A.] | [Sim/canal] | [Preencher/N.A.] |

Mensagem entregue ao gestor não demonstra que executores ou pessoas afetadas receberam o contexto necessário.

---

## 31. Linguagem e inteligibilidade

| Ação | Público | Idioma/registro | Termos críticos | Complexidade | Tom | Teste de compreensão | Revisor |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [COM/ENG ID] | [IDs] | [Preencher] | [Glossário/IDs] | [Baixa/média/alta] | [Preencher] | [Método] | [Nome/papel] |

### 31.1 Clareza com precisão

- explique siglas na primeira ocorrência;
- distinga estado vigente de estado futuro;
- apresente decisão, fundamento, ação e prazo de forma encontrável;
- declare limites e incertezas;
- evite jargão que apenas sinaliza pertencimento;
- ofereça aprofundamento sem tornar toda mensagem longa;
- utilize exemplos compatíveis com a experiência real do público.

---

## 32. Acessibilidade e inclusão comunicacional

| Público | Barreira possível | Requisito | Formato principal | Alternativa | Canal de resposta | Validação | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Visual, auditiva, cognitiva, linguística, tecnológica, temporal ou outra] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Método/ID] | [Nome] |

### 32.1 Acessibilidade desde a preparação

Considere legenda, transcrição, contraste, leitura por tecnologia assistiva, linguagem, duração, ritmo, navegação, banda, dispositivo, fuso, turno, ambiente e forma de manifestação.

### 32.2 Formato alternativo não é versão inferior

O formato alternativo deve preservar conteúdo, contexto, ação, prazo, autoridade e possibilidade de resposta.

---

## 33. Sensibilidade, confidencialidade e acesso

| Ação/material | Informação | Classe | Públicos permitidos | Canal permitido | Restrições | Expiração | Incidente |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/tipo] | [Pública/interna/restrita/confidencial/crítica] | [IDs] | [IDs] | [Cópia, gravação, encaminhamento ou outra] | [Data/condição] | [Resposta] |

### 33.1 Confidencialidade não é silêncio indevido

Restrição deve possuir finalidade, escopo, duração e autoridade. Pessoas afetadas continuam recebendo o necessário para agir, exercer direitos, pedir apoio ou contestar.

### 33.2 Gravação e imagem

| Tratamento | Pessoas/públicos | Finalidade | Base/condição | Acesso | Retenção | Recusa/alternativa | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Gravação, transcrição, imagem ou voz] | [IDs] | [Preencher] | [Referência] | [Papéis] | [Regra] | [Forma] | [Nome] |

---

## 34. Catálogo de canais

| Canal | Finalidade permitida | Públicos | Modalidade | Sensibilidade | Tempo esperado | Registro | Contingência | Custodiante |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [CAN-ARQ ID/canal temporário] | [Preencher] | [IDs] | [Síncrono/assíncrono/híbrido] | [Classes] | [Faixa] | [Fonte] | [Canal/ação] | [Nome/papel] |

### 34.1 Canal oficial e canal auxiliar

| Canal | Papel | Pode originar decisão? | Deve retornar a qual fonte? | Risco |
| --- | --- | --- | --- | --- |
| [ID] | [Oficial/auxiliar/emergencial] | [Sim/não/condicionado] | [Fonte] | [Preencher] |

Conversa em canal auxiliar pode apoiar coordenação. Decisão, mudança, risco ou compromisso material deve retornar à fonte competente.

---

## 35. Seleção de canal e formato

| Ação | Urgência | Complexidade | Sensibilidade | Interação | Persistência | Acessibilidade | Canal escolhido | Motivo | Contingência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [COM/ENG ID] | [Classe] | [Baixa/média/alta] | [Classe] | [Baixa/média/alta] | [Necessária/não] | [Requisitos] | [ID] | [Preencher] | [ID/ação] |

### 35.1 Falhas de seleção

| Falha | Exemplo | Consequência | Correção |
| --- | --- | --- | --- |
| Canal efêmero para decisão | Decisão apenas em conversa. | Ausência de referência. | Registrar na fonte oficial. |
| Canal amplo para conteúdo restrito | Grupo com acesso excessivo. | Exposição. | Restringir e registrar incidente se aplicável. |
| Canal assíncrono para risco imediato | Mensagem sem monitoramento. | Resposta tardia. | Acionar canal crítico e escalonamento. |
| Reunião para atualização simples | Leitura coletiva de status. | Carga desnecessária. | Síntese assíncrona encontrável. |
| Mensagem individual para efeito coletivo | Contexto concentrado. | Assimetria e versões diferentes. | Usar fonte e público adequados. |
| Canal inacessível | Formato incompatível. | Exclusão. | Disponibilizar alternativa equivalente. |

---

## 36. Comunicação síncrona, assíncrona e híbrida

| Modalidade | Utilizar quando | Evitar quando | Proteção |
| --- | --- | --- | --- |
| Síncrona | Construção conjunta, tensão, ambiguidade alta ou urgência real. | Conteúdo pode ser compreendido e respondido sem presença simultânea. | Agenda, facilitação, tempo e síntese. |
| Assíncrona | Reflexão, distribuição temporal, registro ou atualização. | Risco exige resposta imediata ou nuance não cabe no formato. | Prazo, contexto e canal de dúvida. |
| Híbrida | Preparação assíncrona seguida de deliberação ou prática síncrona. | Etapas apenas duplicam conteúdo. | Função distinta para cada etapa. |

### 36.1 Direito à assincronia

Assincronia pode proteger concentração, fusos, turnos, acessibilidade e autonomia. Expectativa de resposta e rota de urgência precisam permanecer explícitas.

### 36.2 Reuniões e oficinas

| ID | Finalidade | Decisão ou saída | Participantes | Preparação | Facilitação | Registro | Duração | Critério de encerramento |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ENG/COM ID] | [Preencher] | [ID/tipo] | [IDs] | [Material/ação] | [Nome/papel] | [Fonte] | [Tempo] | [Preencher] |

Reunião não é evidência de alinhamento apenas porque ocorreu.

---

## 37. Momento, antecedência, cadência e vigência

| Ação | Gatilho | Antecedência | Janela | Cadência | Fuso/turno | Vigência | Deve ocorrer antes de | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [COM/ENG ID] | [Evento] | [Tempo] | [Início/fim] | [Única/periódica/contínua] | [Condição] | [Período] | [Marco/gate/efeito] | [Nome] |

### 37.1 Tempo para compreender e responder

Comunicação anterior ao efeito precisa reservar tempo compatível com:

- complexidade do conteúdo;
- necessidade de consulta a fontes;
- diversidade de públicos;
- turnos, fusos e ausências;
- possibilidade de reunião ou apoio;
- prazo real para influenciar a decisão;
- risco e reversibilidade.

### 37.2 Cadência por necessidade

| Situação | Cadência possível | Gatilho de mudança |
| --- | --- | --- |
| Preparação estável | Síntese por marco ou consulta à fonte. | Mudança material ou bloqueio. |
| Execução com dependências | Evento e ciclo curto. | Variação crítica ou acúmulo. |
| Piloto ou onda | Antes, durante e depois da exposição. | Incidente, condição ou decisão. |
| Estabilização | Frequência ligada a sinais e suporte. | Limite, falha ou maturidade. |
| Incidente | Frequência proporcional à criticidade. | Contenção, restauração ou encerramento. |

---

## 38. Urgência, prioridade e tempo de resposta

| Classe | Consequência do atraso | Tempo de primeira resposta | Canal | Escalonamento | Autoridade |
| --- | --- | --- | --- | --- | --- |
| Crítica | Dano imediato ou continuidade ameaçada. | [Tempo] | [ID] | [ID/rota] | [Nome/papel] |
| Alta | Impacto material dentro de janela curta. | [Tempo] | [ID] | [ID/rota] | [Nome/papel] |
| Normal | Trabalho pode seguir dentro da cadência. | [Tempo] | [ID] | [Condição] | [Nome/papel] |
| Baixa | Não condiciona ação atual. | [Tempo] | [Consulta/síntese] | N.A. | [Nome/papel] |

### 38.1 Urgência não cria autoridade

Urgência pode acionar comunicação, contenção ou escalonamento. Não autoriza promessa, exposição, decisão ou mudança fora da alçada aplicável.

### 38.2 Acordos de resposta

| Canal/ação | Primeira resposta | Resposta conclusiva | Horário aplicável | Exceção | Contingência |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Tempo] | [Tempo/condição] | [Janela] | [Tipos] | [Ação/canal] |

Resposta inicial pode confirmar recebimento e informar prazo de tratamento. Não deve simular solução concluída.

---

## 39. Sequência comunicacional por objeto

| Objeto | Antes da preparação | Antes da execução | Antes da liberação | Durante uso | Após resultado | Na transição |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [COM/ENG IDs] | [COM/ENG IDs] | [COM/ENG IDs] | [COM/ENG IDs] | [COM/ENG/DEV IDs] | [COM/DEV IDs] |

### 39.1 Mudança de sequência

| Alteração | Motivo | Públicos afetados | Risco | Decisão | Atualizações necessárias |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [ID/síntese] | [IDs] | [ID] | [ID] | [Cronograma/backlog/matriz/plano] |

---

## 40. Plano integrado de ações

| Ação | Objeto | Público | Resultado | Preparação | Data/gatilho | Dependências | Responsável | Verificador | Evidência | Gate |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [COM/ENG ID] | [IDs] | [IDs] | [Preencher] | [PT/ITM IDs] | [Preencher] | [IDs] | [Nome] | [Nome/papel] | [EVD/tipo] | [PI/ocorrência] |

### 40.1 Ação planejada não é ação pronta

Antes da realização, verifique conteúdo, versão, autoridade, público, canal, acessibilidade, sensibilidade, momento, suporte e contingência.

### 40.2 Ação concluída não é resultado demonstrado

“Reunião realizada” ou “mensagem enviada” conclui uma atividade. O resultado depende da finalidade e do critério declarado.

---

## 41. Produção, revisão, validação e aprovação do conteúdo

| Material | Fonte | Autor | Revisor de conteúdo | Revisor de linguagem/acessibilidade | Autoridade de aprovação | Versão aprovada | Data |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [MSG ID] | [IDs] | [Nome/papel] | [Nome/papel] | [Nome/papel] | [Nome/papel] | [N.N] | [Data] |

### 41.1 Critérios de prontidão do material

- [ ] objeto e versão estão identificados;
- [ ] fonte vigente foi utilizada;
- [ ] finalidade e público estão explícitos;
- [ ] fato, decisão, hipótese e proposta estão distinguidos;
- [ ] ação, prazo e autoridade são encontráveis;
- [ ] linguagem é compreensível sem perder precisão;
- [ ] acessibilidade e formatos alternativos foram verificados;
- [ ] sensibilidade, acesso e retenção estão adequados;
- [ ] canal de pergunta, contribuição ou contestação existe;
- [ ] confirmação e devolutiva estão preparadas;
- [ ] aprovação aplicável foi obtida.

---

## 42. Emissão, entrega, recepção e falha

| Ocorrência | Ação | Versão | Emissão | Canal | Público esperado | Resultado técnico | Falhas/exclusões | Evidência | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/COM ID] | [COM ID] | [N.N] | [Data/hora] | [ID] | [IDs] | [Emitida/entregue/parcial/falha] | [Preencher] | [ID/link] | [Nome] |

### 42.1 Falha de entrega

| Falha | Público afetado | Efeito | Contingência | Prazo | Escalonamento | Resultado |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [IDs] | [Preencher] | [Canal/ação] | [Tempo] | [Nome/rota] | [Preencher] |

### 42.2 Log técnico possui alcance limitado

Log de envio, abertura ou acesso demonstra evento técnico delimitado. Não comprova atenção, compreensão, concordância ou ação.

---

## 43. Estados de confirmação

Toda confirmação declara o estado confirmado.

| Estado | Pergunta | Método possível | Não comprova |
| --- | --- | --- | --- |
| Emissão | O conteúdo saiu da fonte? | Log ou protocolo. | Entrega. |
| Entrega | Chegou ao destino técnico? | Log, protocolo ou retorno. | Acesso humano. |
| Recepção | O destinatário recebeu ou acessou? | Manifestação, registro ou checagem. | Compreensão. |
| Compreensão | Interpreta o sentido necessário? | Reformulação, cenário, demonstração ou resposta aplicada. | Concordância. |
| Concordância | Aceita a proposição? | Manifestação explícita. | Compromisso. |
| Compromisso | Assume ação, prazo e condição? | Aceite registrado. | Execução. |
| Execução | A ação ocorreu? | Evidência operacional. | Qualidade. |

### 43.1 Registro de confirmação

| ID | Ação | Estado confirmado | Público/amostra | Método | Critério | Resultado | Limite | Verificador | Data |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [CNF ID] | [COM/ENG ID] | [Estado] | [IDs/descrição] | [Preencher] | [Preencher] | [Atendido/parcial/não atendido/inconclusivo] | [Preencher] | [Nome/papel] | [Data] |

---

## 44. Confirmação de compreensão

Confirmação é necessária quando interpretação inadequada pode produzir erro, dano, perda de direito, falha de coordenação, decisão inválida ou risco material.

| Ação | Conteúdo que precisa ser compreendido | Públicos | Método | Amostra | Critério | Momento | Correção |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [COM ID] | [Decisão, mudança, risco, instrução ou limite] | [IDs] | [Reformular/demonstrar/responder cenário/aplicar] | [Regra] | [Condição observável] | [Antes de marco/efeito] | [Esclarecer/adaptar/treinar/escalar] |

### 44.1 Pergunta socialmente insuficiente

“Entendeu?” ou “alguma dúvida?” favorece resposta rápida e social. Quando material, peça explicação com palavras próprias, aplicação a um caso, identificação do próximo movimento ou reconhecimento de exceção.

### 44.2 Amostra

| Público | População aplicável | Amostra | Critério de seleção | Limitação | Expansão necessária? |
| --- | --- | --- | --- | --- | --- |
| [ID] | [N/descrição] | [N/descrição] | [Risco, papel, turno, diversidade ou outro] | [Preencher] | [Sim/não/gatilho] |

Amostra por conveniência não deve ser apresentada como compreensão de todo o público.

---

## 45. Incompreensão, ambiguidade e correção

| ID | Ação | Sinal observado | Tipo | Público | Efeito | Correção | Nova verificação | Destino |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/CNF ID] | [COM ID] | [Preencher] | [Lacuna/ambiguidade/interpretação conflitante/barreira] | [IDs] | [Preencher] | [Preencher] | [Método/data] | [Plano/treinamento/mudança/risco] |

### 45.1 Repetição não é correção universal

Se a causa for linguagem inadequada, contexto ausente, canal inacessível, instrução contraditória, falta de competência ou desenho inviável, repetir a mensagem original preserva a falha.

### 45.2 Incompreensão material

Quando a incompreensão afeta prontidão, liberação, segurança ou validade de uma decisão, registre risco, impedimento ou condição e avalie o gate aplicável.

---

## 46. Consulta, cocriação e validação participativa

| Ação | Modo | Questão | Material prévio | Método | Participantes | Critério de diversidade | Registro | Decisão posterior |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ENG ID] | [Consulta/cocriação/validação] | [Preencher] | [MSG/IDs] | [Entrevista/oficina/teste/outro] | [IDs] | [Preencher] | [Fonte] | [ID/fórum] |

### 46.1 Antes da decisão

Participação deve ocorrer antes da decisão quando a experiência das pessoas puder revelar requisito, exceção, inviabilidade, risco, efeito desigual ou perda de capacidade.

### 46.2 Depois da decisão

Participação posterior pode aprofundar execução, proteção, suporte e validação, mas não deve ser apresentada retroativamente como influência sobre decisão já tomada.

---

## 47. Preparação e facilitação da participação

| Ação ENG | Facilitador | Objetivo | Regras de participação | Assimetria prevista | Proteção | Forma de fala | Síntese | Validação da síntese |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Nome/papel] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Síncrona/assíncrona/protegida] | [Responsável] | [Método] |

### 47.1 Condições de facilitação

- informar escopo e autoridade;
- diferenciar exploração de deliberação;
- permitir manifestação não pública quando necessária;
- equilibrar tempo sem presumir equivalência de experiência;
- impedir humilhação, retaliação e exposição indevida;
- registrar divergência sem forçar consenso;
- declarar como a síntese será produzida e validada;
- encerrar com próximos movimentos e prazo de devolutiva.

---

## 48. Registro de contribuições

| ID | Ação de origem | Autor/grupo ou referência protegida | Objeto | Tipo | Síntese factual | Sensibilidade | Estado | Responsável | Fonte completa |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [CTR ID] | [ENG/COM ID] | [ID/referência] | [IDs] | [Dúvida/sugestão/objeção/risco/exceção/relato] | [Minimizada] | [Classe] | [Estado] | [Nome/papel] | [Fonte protegida/N.A.] |

### 48.1 Estados da contribuição

| Estado | Significado |
| --- | --- |
| Recebida | Conteúdo entrou por canal reconhecido. |
| Em triagem | Objeto, materialidade, sensibilidade e rota estão sendo avaliados. |
| Em análise | Responsável competente examina contexto e efeito. |
| Encaminhada | Outra fonte ou autoridade recebeu o objeto. |
| Incorporada | Contribuição alterou objeto dentro de alçada. |
| Incorporada parcialmente | Parte foi aplicada e parte recebeu outro destino. |
| Não incorporada | Decisão fundamentada manteve o objeto. |
| Pendente de decisão | Autoridade ou evidência ainda é necessária. |
| Em devolutiva | Retorno está sendo preparado ou realizado. |
| Encerrada | Destino e devolutiva foram concluídos no horizonte. |

### 48.2 Autoria e atribuição

Preserve autoria quando material e autorizado. Anonimização não deve ser utilizada para apropriar contribuição nem para impedir reconhecimento legítimo.

---

## 49. Triagem e tratamento de contribuições

| Contribuição | Materialidade | Objeto afetado | Classificação | Rota | Prazo | Autoridade | Ação/decisão | Devolutiva |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [CTR ID] | [Baixa/média/alta/crítica] | [IDs] | [Esclarecimento/trabalho/risco/mudança/diferença/incidente/outro] | [Fonte/fórum] | [Data] | [Nome/papel] | [IDs] | [DEV ID] |

### 49.1 Perguntas de triagem

1. O conteúdo pode ser compreendido sem expor dado desnecessário?
2. Há risco imediato que exige contenção?
3. O objeto pertence à comunicação, à execução, à arquitetura, à operação ou a protocolo especializado?
4. A contribuição contradiz fonte, premissa ou evidência?
5. A pessoa precisa de resposta individual, coletiva ou protegida?
6. Que autoridade pode decidir?
7. Que prazo corresponde ao efeito?
8. Que vínculo e devolutiva serão necessários?

### 49.2 Encaminhamento não encerra responsabilidade

Quem encaminha preserva acompanhamento até que a fonte destinatária confirme recebimento e assuma responsabilidade delimitada.

---

## 50. Devolutiva e fechamento do ciclo

| ID | Origem | Público/destinatário | Objeto | Destino da contribuição ou decisão | Fundamento | Próximo movimento | Canal | Data | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [DEV ID] | [CTR/ENG/COM/DEC ID] | [IDs] | [IDs] | [Incorporada/parcial/não incorporada/encaminhada/pendente] | [ID/síntese] | [Preencher] | [ID] | [Data] | [Nome/papel] |

### 50.1 Devolutiva suficiente

Quando aplicável, deve esclarecer:

- o que foi ouvido ou decidido;
- que parte foi incorporada;
- que parte não foi e por quê;
- que limitação permanece;
- quem decidiu;
- que fonte foi atualizada;
- que ação ou prazo segue;
- como contestar ou complementar.

### 50.2 Devolutiva coletiva e individual

Síntese coletiva pode informar padrões e decisões. Questões pessoais, sensíveis ou com efeito individual podem exigir retorno protegido. Uma forma não substitui automaticamente a outra.

---

## 51. Discordância, objeção e contestação

| ID/contribuição | Objeto | Fundamento | Evidência | Efeito alegado | Autoridade | Tratamento | Decisão | Preservação |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [CTR ID] | [IDs] | [Preencher] | [IDs/N.A.] | [Risco, injustiça, inviabilidade, perda ou outro] | [Nome/papel] | [Investigar/validar/escalar] | [ID/pendente] | [Fonte] |

### 51.1 Discordância preservada

Decisão pode prosseguir sem unanimidade quando autoridade, fundamento, participação, proteção e efeito estão governados. A discordância material permanece ligada à decisão e às condições aplicáveis.

### 51.2 Contestação como controle

Relatos sobre falha, dano, exceção, sobrecarga, discriminação, risco, desvio de finalidade ou divergência da linha de base devem alcançar a fonte e a autoridade competentes.

---

## 52. Resistência como hipótese, não rótulo final

| Sinal observado | Hipóteses a investigar | Evidência necessária | Resposta possível | Responsável |
| --- | --- | --- | --- | --- |
| [Baixa participação, uso alternativo, atraso, objeção ou outro] | [Falta de contexto, perda, sobrecarga, risco, desenho inadequado, incentivo incompatível, experiência anterior, contestação ética ou outra] | [Preencher] | [Comunicar, proteger, capacitar, redesenhar execução, escalar ou outra] | [Nome/papel] |

### 52.1 O que não registrar sem base

Evite descrições como “pessoa resistente”, “equipe negativa”, “baixo comprometimento” ou inferências emocionais sem declaração, evidência e finalidade legítima.

### 52.2 Comunicação persuasiva possui limite

Esclarecer valor e fundamento é legítimo. Ocultar custo, induzir concordância, manipular emoção ou usar assimetria de informação viola a função deste plano.

---

## 53. Comunicação de decisão

| Decisão | Objeto/versão | Autoridade | Públicos | Conteúdo mínimo | Efeito | Ação esperada | Vigência | Contestação/revisão | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [DEC/GAT ID] | [IDs] | [Nome/papel] | [IDs] | [Resultado, fundamento, condição, limite] | [Preencher] | [Preencher] | [Data/gatilho] | [Canal/condição] | [COM/CNF IDs] |

### 53.1 Decisão tomada em reunião

Decisão oral material deve retornar ao registro decisório com objeto, autoridade, fundamento, consequência e versão. A comunicação posterior referencia a decisão; não a substitui.

### 53.2 Decisão condicionada

Condição, responsável, prazo, consequência e forma de verificação precisam alcançar as pessoas que executam, verificam e respondem pelo objeto.

---

## 54. Mudanças, riscos, bloqueios e gates

| Evento | Fonte | Públicos | Informação obrigatória | Momento | Confirmação | Canal de resposta | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Mudança de plano | [MUD/DEC ID] | [IDs] | Objeto, motivo, efeito, nova referência e ação. | Antes do efeito. | [Método] | [Canal] | [Nome] |
| Mudança arquitetural | [MUD/ARQ/DEC ID] | [IDs] | Retorno, contenção, decisão e nova linha de base. | Conforme decisão. | [Método] | [Canal] | [Nome] |
| Risco crítico | [RIS ID] | [IDs] | Exposição, proteção, ação e autoridade. | Conforme gatilho. | [Método] | [Canal] | [Nome] |
| Impedimento material | [IPD ID] | [IDs] | Objeto bloqueado, efeito, rota e previsão. | Na janela definida. | [Método/N.A.] | [Canal] | [Nome] |
| Resultado de gate | [GAT/DEC ID] | [IDs] | Objeto, versão, resultado, condições, limites e próximo movimento. | Após decisão e antes do efeito. | [Método] | [Canal] | [Nome] |

### 54.1 Comunicação não encerra controle

Avisar sobre risco, impedimento ou mudança não constitui tratamento, desbloqueio, aprovação ou incorporação.

---

## 55. Piloto, onda, virada, reversão e restauração

| Evento | Antes | Durante | Critério de atualização | Canal crítico | Depois | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| Piloto | [COM/ENG IDs] | [Suporte/escuta] | [Gatilho] | [ID] | [Resultado/devolutiva] | [Nome] |
| Onda | [COM/ENG IDs] | [Suporte/escuta] | [Gatilho] | [ID] | [Resultado/devolutiva] | [Nome] |
| Virada | [COM/CNF IDs] | [Sala/canal/boletim] | [Gatilho] | [ID] | [Estabilização] | [Nome] |
| Reversão | [Aviso/condição] | [Instrução e confirmação] | [Gatilho] | [ID] | [Estado restaurado] | [Nome] |
| Restauração | [Preparação] | [Orientação] | [Gatilho] | [ID] | [Confirmação] | [Nome] |

### 55.1 Pacote mínimo antes da exposição

- o que será exposto e a quem;
- quando começa e termina;
- que comportamento é esperado;
- como obter apoio;
- como registrar falha ou efeito;
- quem pode interromper;
- que contingência ou reversão existe;
- como será comunicado o próximo estado.

---

## 56. Comunicação de incidente e crise

Este plano referencia o protocolo especializado aplicável. Não cria um protocolo de crise genérico quando obrigação legal, técnica ou contratual exige outro tratamento.

| Cenário | Gatilho | Autoridade | Públicos | Canal primário | Contingência | Conteúdo inicial | Cadência | Encerramento |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/tipo] | [Evento] | [Nome/papel] | [IDs] | [ID] | [ID] | [Fato conhecido, proteção, ação e próxima atualização] | [Tempo] | [Condição] |

### 56.1 Informação incompleta

Em incidente, comunique o que é conhecido, o que ainda não é, que proteção está ativa, que ação se espera e quando haverá nova atualização. Não preencha lacunas com certeza aparente.

### 56.2 Correção pública ou dirigida

| Comunicação incorreta | Públicos alcançados | Correção | Canal | Urgência | Referência | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [COM/MSG ID] | [IDs] | [MSG ID/ação] | [ID] | [Classe] | [Fonte vigente] | [Nome] |

---

## 57. Dúvidas, apoio e escalonamento

| Necessidade | Público | Canal | Horário/tempo | Responsável | Substituto | Escalonamento | Registro |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Esclarecimento | [IDs] | [ID] | [Preencher] | [Nome/papel] | [Nome/papel] | [Rota] | [Fonte] |
| Apoio ao uso | [IDs] | [ID] | [Preencher] | [Nome/papel] | [Nome/papel] | [Rota] | [Fonte] |
| Contestação | [IDs] | [ID] | [Preencher] | [Nome/papel] | [Nome/papel] | [Rota] | [Fonte protegida] |
| Incidente | [IDs] | [ID] | [Preencher] | [Nome/papel] | [Nome/papel] | [Rota crítica] | [Fonte] |

### 57.1 Capacidade do canal

| Canal | Volume esperado | Capacidade | Limite | Sinal de saturação | Resposta | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Faixa] | [Faixa] | [Condição] | [Preencher] | [Reforçar/priorizar/redirecionar] | [Nome] |

Abrir canal sem capacidade de tratamento cria participação aparente e risco de confiança.

---

## 58. Engajamento, uso e adoção

| Objeto | Sinal de comunicação | Sinal de participação | Sinal de uso | Sinal de adoção | Fonte oficial |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [PCE/plano de mudança/validação] |

### 58.1 Fronteira

Este plano demonstra comunicação, compreensão e participação delimitadas. Adoção apropriada pertence à validação e ao Plano de Gestão da Mudança Organizacional.

### 58.2 Uso forçado

Obrigatoriedade pode produzir uso. Não demonstra compreensão, adequação, segurança, competência ou legitimidade.

---

## 59. Integração com treinamento e capacitação

| Necessidade observada | Público | Conteúdo/atividade | É comunicação ou competência? | Destino | Critério | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [IDs] | [Preencher] | [Comunicação/treinamento/ambos] | [COM ID/Plano 09] | [Preencher] | [Nome] |

### 59.1 Gatilhos para o Plano 09

Encaminhe quando a pessoa precisar:

- executar atividade;
- aplicar procedimento;
- decidir ou julgar exceção;
- operar ferramenta ou controle;
- responder a risco;
- sustentar conhecimento;
- demonstrar competência em contexto real ou equivalente.

### 59.2 Comunicação do treinamento

Este plano pode governar convocação, contexto, pré-requisitos, acesso, suporte e devolutiva. Presença continua sendo evidência de participação, não de competência.

---

## 60. Integração com gestão da mudança organizacional

| Sinal/contribuição | Grupo | Impacto possível | Fonte | Tratamento no Plano 10 | Retorno a este plano |
| --- | --- | --- | --- | --- | --- |
| [CTR/observação ID] | [ID] | [Carga, perda, autonomia, identidade, risco ou outro] | [ID] | [Ação/hipótese/validação] | [COM/DEV ID] |

### 60.1 O que permanece no Plano 10

- análise de impacto humano;
- capacidades e práticas a preservar;
- perdas, ganhos e efeitos desiguais;
- preparação de transição;
- hipóteses e critérios de adoção;
- suporte e sustentação humana;
- tratamento integrado de mudança organizacional.

Este plano comunica e cria participação em torno desses objetos; não os substitui.

---

## 61. Sincronização com a Estrutura Analítica

| Ação do plano | Entrega/condição | Pacote de trabalho | Critério | Evidência | Estado de sincronização |
| --- | --- | --- | --- | --- | --- |
| [COM/ENG ID] | [ENT/condição ID] | [PT ID] | [Preencher] | [EVD/tipo] | [Sincronizado/divergente] |

### 61.1 Trabalho humano é trabalho material

Preparar conteúdo, adaptar acessibilidade, facilitar participação, confirmar compreensão, tratar contribuições e realizar devolutiva precisa existir como trabalho quando exige esforço, capacidade ou dependência material.

### 61.2 Novo trabalho

Necessidade emergente entra em pacote existente, novo pacote autorizado ou condição. O plano não cria escopo silencioso.

---

## 62. Sincronização com o Cronograma Mestre

| Ação | Janela no plano | Compromisso no cronograma | Deve ocorrer antes de | Dependência | Variação | Decisão |
| --- | --- | --- | --- | --- | --- | --- |
| [COM/ENG ID] | [Data/gatilho] | [JNL/MRC ID] | [Marco/gate/efeito] | [IDs] | [Tempo] | [ID/N.A.] |

### 62.1 Fonte temporal

O Cronograma Mestre é a fonte de datas, janelas, marcos e dependências temporais. Este plano preserva a necessidade comunicacional e referencia o compromisso vigente.

### 62.2 Atraso comunicacional

| Ação | Atraso | Efeito humano/operacional | Público | Resposta | Replanejamento | Autoridade |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Tempo] | [Preencher] | [IDs] | [Preencher] | [CRM/DEC ID] | [Nome/papel] |

---

## 63. Sincronização com Backlog e Quadro Kanban

| Ação/plano | Item de backlog | Estado factual | Bloqueio | Classe de serviço | Responsável | Próximo movimento |
| --- | --- | --- | --- | --- | --- | --- |
| [COM/ENG/DEV ID] | [ITM ID] | [Estado] | [IPD ID/N.A.] | [Classe] | [Nome] | [Preencher] |

### 63.1 Quadro não expõe manifestação sensível

O Kanban registra trabalho, objeto e bloqueio necessários. Conteúdo pessoal, autoria protegida ou relato sensível permanece na fonte adequada.

### 63.2 Item concluído

Conclusão do item demonstra trabalho executado conforme sua definição. Resultado de compreensão, participação ou devolutiva precisa ser verificado no registro correspondente.

---

## 64. Sincronização com a Matriz de Rastreabilidade

| Origem | Relação | Ação/resultado | Vínculo | Cobertura | Estado |
| --- | --- | --- | --- | --- | --- |
| [Objeto/condição] | [Relação controlada] | [COM/ENG/CNF/CTR/DEV ID] | [VNC ID] | [Estado] | [Confirmado/a validar] |

### 64.1 Relações úteis

- `deriva_de` para ligar ação à origem;
- `formaliza` para tornar obrigação explícita;
- `protege` para participação, acessibilidade ou contestação;
- `depende_de` e `é_condicionado_por` para condições de realização;
- `é_demonstrado_por` para evidência delimitada;
- `contradiz` para manifestação que questiona premissa ou resultado;
- `qualifica` para limite ou contexto;
- `é_autorizado_por` para emissão ou ação sujeita a autoridade;
- `gera_aprendizagem_para` para destino metodológico.

### 64.2 Vínculo não demonstra resultado

Relacionar comunicação a um público não demonstra entrega ou compreensão. Relacionar contribuição a decisão não demonstra incorporação.

---

## 65. Sincronização com o Registro Integrado de Controle

| Condição | Tipo | Objeto | Efeito comunicacional/participativo | Ação deste plano | Registro RIC | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Risco/problema/impedimento/dependência/restrição/premissa/condição/mudança] | [IDs] | [Preencher] | [COM/ENG/DEV IDs] | [ID] | [Estado] |

### 65.1 Quando abrir ou relacionar item

- incompreensão material ameaça prontidão ou segurança;
- público crítico está inacessível;
- participação exigida não pode ocorrer;
- canal ou autoridade necessários estão indisponíveis;
- contribuição revela risco, diferença ou mudança;
- devolutiva vence com efeito material;
- informação incorreta produz exposição;
- comunicação recorrente exige mudança arquitetural.

Comunicação do item não substitui seu tratamento.

---

## 66. Verificação para o `PI-1`

Pergunta oficial:

> A linha de base arquitetural, suas condições e seus critérios são suficientes para mobilizar a implantação?

| Verificação | Estado | Evidência | Lacuna/condição | Responsável |
| --- | --- | --- | --- | --- |
| Arquitetura da comunicação aplicável foi recebida com IDs e versões. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Públicos, pessoas afetadas e autoridades conhecidas são localizáveis. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Canais, confirmações, retornos e proteções materiais são compreensíveis. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Condições e lacunas transferidas foram aceitas, condicionadas ou devolvidas. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Alterações necessárias podem ser tratadas no envelope ou exigem retorno. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |

O plano pode estar inicial no `PI-1`. A decisão precisa saber o que foi recebido e que lacunas impedem ou condicionam a mobilização.

---

## 67. Verificação para o `PI-2`

Pergunta oficial:

> Escopo, entregas, recursos, responsabilidades, dependências, riscos e planos humanos estão preparados para iniciar a execução?

| Verificação | Estado | Evidência | Condição/risco | Responsável |
| --- | --- | --- | --- | --- |
| Ações materiais possuem objeto, público, finalidade e responsável. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Pessoas afetadas e ausentes possuem inclusão ou proteção proporcional. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Influência, autoridade e partes já decididas foram declaradas. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Conteúdo, canais, acessibilidade e sensibilidade estão preparados. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Confirmação de compreensão foi definida quando material. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Canais de pergunta, contribuição, contestação e apoio têm capacidade. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Devolutiva possui responsabilidade e prazo. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Trabalho e datas estão sincronizados com EAI, Cronograma e Kanban. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Riscos, impedimentos, dependências e mudanças possuem tratamento. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Participação material da IA e seus limites estão definidos. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |

Plano preenchido não demonstra prontidão. As condições precisam estar verificadas para o objeto e a ocorrência de `PI-2` aplicáveis.

---

## 68. Verificação para o `PI-3`

Pergunta oficial:

> Este incremento, piloto, onda ou virada possui condições técnicas, humanas, documentais e operacionais para ser liberado?

| Verificação | Estado | Evidência | Condição/risco | Responsável |
| --- | --- | --- | --- | --- |
| Públicos da liberação e do suporte estão atualizados. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Comunicações prévias ocorreram com antecedência suficiente. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Conteúdo material foi compreendido no grau exigido. | [Estado] | [CNF IDs] | [ID/nenhuma] | [Nome] |
| Pessoas sabem agir, pedir apoio, relatar falha e interromper quando autorizado. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Canais de suporte, incidente, contingência e reversão estão ativos. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Contribuições críticas receberam tratamento ou condição explícita. | [Estado] | [CTR/DEC IDs] | [ID/nenhuma] | [Nome] |
| Mudanças de janela, público, risco e configuração foram comunicadas. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |

Data prevista de liberação não substitui `PI-3`. Comunicação pronta também não compensa ausência de competência, controle ou reversibilidade.

---

## 69. Verificação para o `PI-4`

Pergunta oficial:

> A capacidade foi efetivamente implantada, validada e aceita dentro dos critérios autorizados?

| Verificação | Estado | Evidência | Limite | Responsável |
| --- | --- | --- | --- | --- |
| Comunicação material realizada pode ser reconstruída. | [Estado] | [COM/MSG IDs] | [Preencher] | [Nome] |
| Compreensão exigida foi demonstrada no público ou amostra válida. | [Estado] | [CNF IDs] | [Preencher] | [Nome] |
| Participação prevista ocorreu ou recebeu decisão de exceção. | [Estado] | [ENG IDs] | [Preencher] | [Nome] |
| Contribuições materiais possuem tratamento e devolutiva. | [Estado] | [CTR/DEV IDs] | [Preencher] | [Nome] |
| Discordâncias e limitações permanecem visíveis. | [Estado] | [IDs] | [Preencher] | [Nome] |
| Efeitos comunicacionais inesperados foram tratados. | [Estado] | [IDs] | [Preencher] | [Nome] |
| Resultados foram integrados à validação, à mudança e à configuração. | [Estado] | [VNC/DEC IDs] | [Preencher] | [Nome] |

Ausência de reclamação não demonstra compreensão, participação suficiente, adoção ou aceite.

---

## 70. Verificação para o `PI-5`

Pergunta oficial:

> O Módulo 5 recebeu a configuração implantada, compreendeu suas condições e possui capacidade para sustentá-la?

| Verificação | Estado | Evidência | Condição residual | Aceite operacional |
| --- | --- | --- | --- | --- |
| Comunicações temporárias foram encerradas ou destinadas. | [Estado] | [IDs] | [ID/nenhuma] | [ID] |
| Eventos, canais, mensagens e retornos recorrentes possuem responsáveis operacionais. | [Estado] | [IDs] | [ID/nenhuma] | [ID] |
| Fontes oficiais, acessos, contingências e regras de atualização foram transferidos. | [Estado] | [IDs] | [ID/nenhuma] | [ID] |
| Dúvidas, contribuições e discordâncias abertas possuem destino aceito. | [Estado] | [IDs] | [ID/nenhuma] | [ID] |
| Comunicação de transição foi compreendida pelos públicos materiais. | [Estado] | [CNF IDs] | [ID/nenhuma] | [ID] |
| Retenção, eliminação e acesso a registros foram definidos. | [Estado] | [IDs] | [ID/nenhuma] | [ID] |
| Aprendizagem recebeu destino nos módulos aplicáveis. | [Estado] | [IDs] | [ID/nenhuma] | [ID] |

Operação não recebe canal, pendência ou responsabilidade sem objeto, autoridade, recurso, condição e aceite.

---

## 71. Fotografias históricas de gates

Cada ocorrência de gate referencia uma fotografia reproduzível do plano e dos resultados aplicáveis.

| Ocorrência | Gate | Objeto/versão | Versão do plano | Ações consideradas | Confirmações | Contribuições abertas | Condições | Data de corte | Fonte |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [GAT ID] | [`PI-N`] | [IDs] | [N.N] | [COM/ENG IDs] | [CNF IDs] | [CTR IDs/nenhuma] | [IDs/nenhuma] | [Data/hora] | [Link/ID] |

### 71.1 Não reescrever o passado

Atualização posterior do plano não altera o conjunto que a autoridade examinou. Nova evidência, ação ou correção recebe data, versão e vínculo com a decisão anterior.

### 71.2 Gate reaberto

| Gate anterior | Motivo da reabertura | Nova evidência ou fato | Escopo reavaliado | Nova ocorrência | Autoridade |
| --- | --- | --- | --- | --- | --- |
| [GAT ID] | [Preencher] | [IDs] | [Objetos/públicos] | [GAT ID] | [Nome/papel] |

---

## 72. Papéis e responsabilidades

| Papel | Responsabilidade | Autoridade | Entrada | Saída | Limite | Substituto |
| --- | --- | --- | --- | --- | --- | --- |
| Responsável pela implantação | Integrar o plano à realização e aos gates. | [Alçada] | Planos e fatos. | Decisões e escalonamentos. | Não decide fora da alçada. | [Nome/papel] |
| Responsável pelo plano | Manter ações, resultados e sincronização. | [Alçada] | Fontes e ocorrências. | Plano vigente e visões. | Não representa todos os públicos. | [Nome/papel] |
| Responsável por conteúdo | Preservar precisão, fonte e versão. | [Alçada] | Objetos oficiais. | Mensagem candidata. | Não aprova sem autoridade. | [Nome/papel] |
| Emissor/porta-voz | Comunicar dentro da representação concedida. | [Alçada] | Mensagem aprovada. | Comunicação realizada. | Não amplia promessa. | [Nome/papel] |
| Facilitador | Criar condições de participação e síntese fiel. | [Alçada] | Questão e participantes. | Registro de participação. | Não decide pelo grupo. | [Nome/papel] |
| Responsável por acessibilidade | Verificar barreiras e equivalência de formatos. | [Alçada] | Materiais e públicos. | Validação e correções. | Não presume experiência alheia. | [Nome/papel] |
| Responsável por proteção | Governar sensibilidade, acesso e retenção. | [Alçada] | Classes e fontes. | Regras e decisões. | Encaminha tema especializado. | [Nome/papel] |
| Responsável pelo tratamento | Triar contribuições e coordenar destino. | [Alçada] | `CTR` e fontes. | Ação, decisão e devolutiva. | Não oculta divergência. | [Nome/papel] |
| Pessoa afetada/participante | Informar experiência, efeito, limite e contribuição. | Conforme objeto. | Contexto acessível. | Manifestação/validação. | Não assume responsabilidade decisória universal. | N.A. |
| Autoridade decisória | Decidir objeto e assumir consequência. | Registrada. | Evidências e contribuições. | Decisão governável. | Não presume compreensão. | [Nome/papel] |
| Responsável operacional | Receber rotinas recorrentes e sustentação. | Operacional. | Configuração e condições. | Aceite no `PI-5`. | Pode recusar transferência insuficiente. | [Nome/papel] |

### 72.1 Combinação de papéis

Quando a mesma pessoa redige, revisa, aprova, emite, confirma e avalia resultado material, registre a combinação e aplique verificação adicional proporcional.

### 72.2 Pessoa participante

Participar não cria obrigação de disponibilidade contínua, exposição pessoal, representação de grupo ou aceitação do resultado.

---

## 73. Matriz de autoridade

| Objeto/ação | Prepara | Revisa | Aprova | Emite/facilita | Confirma/verifica | Decide destino | Recebe escalonamento |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Mensagem material | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] |
| Consulta | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] |
| Síntese de contribuições | [Papel] | [Papel/participantes] | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] |
| Devolutiva | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] |
| Comunicação de gate | [Papel] | [Papel] | [Autoridade do gate] | [Papel] | [Papel] | [Autoridade do gate] | [Papel] |
| Comunicação de incidente | [Papel] | [Especialista] | [Autoridade] | [Porta-voz] | [Papel] | [Autoridade] | [Instância] |

### 73.1 Autoridade indisponível

| Ação | Autoridade requerida | Indisponibilidade | Substituição autorizada | Condição | Decisão |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Nome/papel] | [Preencher] | [Nome/papel/N.A.] | [Preencher] | [Aguardar/suspender/escalar] |

Ausência de autoridade não deve ser compensada por linguagem ambígua ou publicação “informal”.

---

## 74. Cadências e eventos de revisão

| Cadência/evento | Finalidade | Participantes | Entradas | Saídas | Duração | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| Revisão ordinária do plano | Atualizar ações e estados. | [Papéis] | Plano, cronograma, Kanban e ocorrências. | Plano sincronizado. | [Tempo] | [Nome] |
| Revisão de públicos | Reconhecer novos efeitos e exclusões. | [Papéis/grupos] | Mudanças e manifestações. | Catálogo atualizado. | [Tempo] | [Nome] |
| Triagem de contribuições | Qualificar e encaminhar. | [Papéis] | `CTR` recebidas. | Rotas e prazos. | [Tempo] | [Nome] |
| Preparação de gate | Produzir fotografia e lacunas. | [Papéis] | Ações e evidências. | Visão de gate. | [Tempo] | [Nome] |
| Revisão extraordinária | Responder a mudança, risco ou incidente. | [Papéis] | Evento e fontes. | Ação, decisão ou suspensão. | [Tempo] | [Nome] |
| Revisão de transição | Destinar rotinas e pendências. | [Papéis] | Configuração e condições. | Pacote para `PI-5`. | [Tempo] | [Nome] |

### 74.1 Atualização por evento

Atualize o plano quando houver:

- novo público ou efeito material;
- mudança de objeto, versão, janela ou autoridade;
- falha de canal ou acessibilidade;
- incompreensão relevante;
- contribuição material;
- decisão de gate;
- liberação, reversão ou incidente;
- alteração de suporte ou operação;
- transferência ou encerramento.

---

## 75. Indicadores do plano

Indicadores devem apoiar decisão e melhoria. Contagem de mensagens, reuniões ou participantes mede atividade, não compreensão ou influência.

| Indicador | Pergunta | Numerador | Denominador | Fonte | Frequência | Limite/gatilho | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Cobertura de públicos materiais | Públicos aplicáveis possuem ação definida? | Públicos cobertos. | Públicos materiais identificados. | Plano mestre. | [Cadência] | [Limite] | [Nome] |
| Oportunidade temporal | Ações ocorreram antes do efeito? | Ações no prazo. | Ações materiais vencidas. | Cronograma/ocorrências. | [Cadência] | [Limite] | [Nome] |
| Acessibilidade verificada | Ações aplicáveis possuem formatos validados? | Ações verificadas. | Ações com requisito. | Registros de validação. | [Cadência] | [Limite] | [Nome] |
| Compreensão demonstrada | Critérios foram atendidos? | Pessoas/amostras atendidas. | População/amostra aplicável. | `CNF`. | [Cadência] | [Limite] | [Nome] |
| Participação realizada | Ações previstas ocorreram adequadamente? | Ações realizadas. | Ações de participação devidas. | `ENG`. | [Cadência] | [Limite] | [Nome] |
| Devolutiva tempestiva | Contribuições materiais receberam retorno no prazo? | Devolutivas no prazo. | Contribuições com devolutiva vencida. | `CTR`/`DEV`. | [Cadência] | [Limite] | [Nome] |
| Contribuições sem destino | Há objetos recebidos sem responsável ou rota? | Contribuições sem destino. | Contribuições materiais. | `CTR`. | [Cadência] | [Limite] | [Nome] |
| Carga comunicacional | O volume cria interrupção ou redundância? | [Medida definida]. | [População/período]. | Canais/pesquisa delimitada. | [Cadência] | [Limite] | [Nome] |
| Falhas de entrega | Canais alcançam públicos previstos? | Falhas materiais. | Emissões aplicáveis. | Logs/ocorrências. | [Cadência] | [Limite] | [Nome] |

### 75.1 Contrato do indicador

| Campo | Preenchimento |
| --- | --- |
| Nome | [Preencher] |
| Decisão apoiada | [Preencher] |
| Definição | [Preencher] |
| Unidade e fórmula | [Preencher] |
| População e exclusões | [Preencher] |
| Fonte e qualidade | [Preencher] |
| Frequência | [Preencher] |
| Limite e ação | [Preencher] |
| Risco de manipulação | [Preencher] |
| Proteção humana | [Preencher] |
| Responsável e intérprete | [Preencher] |
| Data de revisão | [Preencher] |

### 75.2 Cobertura não é eficácia

Cem por cento de ações enviadas pode coexistir com incompreensão, exclusão, sobrecarga ou ausência de resposta. Analise indicadores em conjunto com evidência qualitativa e limites.

---

## 76. Monitoramento e proteções humanas

| Monitoramento | Finalidade | Dado mínimo | Pessoas afetadas | Acesso | Retenção | Risco | Proteção |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Entrega, resposta, dúvida, uso de canal ou outro] | [Preencher] | [Preencher] | [IDs] | [Papéis] | [Regra] | [Vigilância, exposição, incentivo adverso ou outro] | [Preencher] |

### 76.1 O plano não mede entusiasmo obrigatório

Não use taxa de reação, presença, tom, velocidade de resposta ou atividade em canal como proxy automática de comprometimento, lealdade, saúde, disposição ou concordância.

### 76.2 Métrica individual

Monitoramento individual exige finalidade material, necessidade, proporcionalidade, transparência, acesso restrito, prazo e avaliação especializada quando aplicável.

### 76.3 Feedback sobre o próprio plano

| Público | Pergunta | Método | Frequência | Proteção | Uso esperado | Devolutiva |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Clareza, carga, acesso, confiança ou outro] | [Preencher] | [Preencher] | [Preencher] | [Ajuste/decisão] | [Forma] |

---

## 77. Dados pessoais, privacidade, retenção e eliminação

| Registro | Finalidade | Dados | Sensibilidade | Base/condição | Acesso | Retenção | Eliminação/anonimização | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Plano, ocorrência, gravação, contribuição, confirmação] | [Preencher] | [Mínimos] | [Classe] | [Referência] | [Papéis] | [Regra] | [Regra] | [Nome] |

### 77.1 Minimização

O plano mestre deve registrar o necessário para governar o objeto. Relato completo, dado pessoal, conteúdo clínico, conflito individual ou informação protegida permanece em fonte adequada quando sua cópia não for necessária.

### 77.2 Anonimização e reidentificação

| Conjunto | Método | Risco de reidentificação | Acesso à chave | Finalidade | Revisão |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Baixo/médio/alto] | [Papéis/N.A.] | [Preencher] | [Data] |

### 77.3 Encerramento

Antes de encerrar, elimine cópias temporárias, revogue acessos desnecessários, preserve registros obrigatórios e transfira somente o conteúdo aceito pela operação.

---

## 78. Participação da inteligência artificial

A IA pode apoiar preparação, organização, acessibilidade, análise preliminar e verificação estrutural. Sua participação não cria autoridade, representação nem conhecimento direto da experiência humana.

| Função | Apoio possível | Entrada permitida | Saída | Verificação humana | Limite |
| --- | --- | --- | --- | --- | --- |
| Rascunho | Estruturar mensagem a partir de fontes. | Conteúdo autorizado e minimizado. | Texto candidato. | Fonte, precisão, tom e efeito. | Não publicar autonomamente. |
| Adaptação | Sugerir linguagem, resumo ou formato. | Material autorizado. | Versão candidata. | Equivalência e acessibilidade. | Não eliminar nuance material. |
| Tradução | Produzir tradução inicial. | Conteúdo autorizado. | Texto candidato. | Revisão linguística e contextual. | Não certificar exatidão especializada. |
| Organização | Classificar ações, prazos e vínculos. | Metadados permitidos. | Tabela ou alerta. | Confirmar semântica. | Não decidir prioridade ou público. |
| Síntese | Resumir contribuições. | Conteúdo permitido e protegido. | Síntese candidata. | Preservar autoria, divergência e limite. | Não fabricar consenso. |
| Verificação | Apontar lacunas, inconsistências e duplicações. | Plano e regras. | Lista de achados. | Julgar materialidade. | Não aprovar prontidão. |
| Análise | Sugerir temas em conjunto autorizado. | Dados minimizados. | Hipóteses. | Confirmar com pessoas e fontes. | Não inferir emoção ou intenção. |

### 78.1 A IA não deve

- selecionar sozinha quem merece participar;
- representar pessoa ou grupo sem autorização;
- publicar comunicação material sem revisão e autoridade;
- inventar fundamento, decisão, prazo ou consenso;
- interpretar silêncio como concordância;
- classificar pessoas como resistentes;
- inferir emoção, intenção, crença ou saúde a partir de linguagem;
- expor manifestação sensível em prompt ou saída sem base;
- decidir destino de contribuição;
- aceitar risco, mudança, liberação ou gate;
- utilizar conteúdo para finalidade diferente da autorizada.

### 78.2 Registro da participação

| ID | Função | Sistema/modelo | Versão/configuração | Entrada | Dados/sensibilidade | Saída | Revisor | Correções | Destino |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Preencher] | [IDs/síntese] | [Classe] | [ID/local] | [Nome/papel] | [Preencher] | [Usada/rejeitada/parcial] |

### 78.3 Conteúdo sintético e personificação

Uso de voz, imagem, avatar ou estilo de pessoa exige autorização, finalidade, identificação apropriada, limites e revisão. A IA não personifica liderança, cliente, participante ou pessoa afetada de forma enganosa.

---

## 79. Automação e regras processáveis

Automação pode reduzir esquecimento e inconsistência sem retirar julgamento humano.

| Regra | Gatilho | Entrada | Ação automatizada | Saída | Verificação humana | Exceção |
| --- | --- | --- | --- | --- | --- | --- |
| Ação vencida | Data ultrapassada e estado aberto. | Plano/cronograma. | Alertar responsável. | Notificação. | Confirmar efeito e prioridade. | [Regra] |
| Devolutiva vencida | `CTR` material sem `DEV` no prazo. | Registro. | Sinalizar lacuna. | Alerta. | Definir resposta e autoridade. | [Regra] |
| Público sem ação | Relação material sem `COM/ENG`. | Matriz/plano. | Criar achado. | Lista de lacunas. | Confirmar necessidade. | [Regra] |
| Mensagem desatualizada | Fonte ou versão mudou. | Repositório. | Marcar revisão. | Alerta. | Avaliar materialidade. | [Regra] |
| Gate próximo | Janela atingida. | Cronograma. | Gerar checklist preliminar. | Visão. | Verificar evidências. | [Regra] |
| Acesso expirado | Data/condição atingida. | Registro de acesso. | Solicitar revogação. | Tarefa. | Confirmar obrigação e execução. | [Regra] |

### 79.1 Limite da automação

Automação não decide compreensão, legitimidade, representatividade, resistência, materialidade, resposta a contestação, autoridade ou gate.

### 79.2 Falha da automação

| Regra | Falha possível | Detecção | Contingência | Responsável |
| --- | --- | --- | --- | --- |
| [ID/regra] | [Falso positivo, omissão, atraso, exposição ou outro] | [Método] | [Ação manual/canal] | [Nome/papel] |

---

## 80. Proporcionalidade

A profundidade do plano corresponde ao impacto, à diversidade, à sensibilidade, à recorrência, à distribuição, à urgência e à reversibilidade.

| Fator | Pergunta | Intensificação possível |
| --- | --- | --- |
| Impacto | O que acontece se não houver compreensão? | Confirmação mais forte e gate condicionado. |
| Diversidade | Públicos possuem necessidades diferentes? | Segmentação, formatos e participação ampliada. |
| Sensibilidade | Que dano decorre da exposição? | Acesso, canal protegido e revisão especializada. |
| Complexidade | Quanto contexto é necessário? | Interação, exemplos e múltiplas camadas. |
| Recorrência | A comunicação integra o estado futuro? | Teste, documentação e transferência operacional. |
| Urgência | Quanto tempo existe para agir? | Canal crítico, redundância e escalonamento. |
| Distribuição | Há fusos, turnos, localidades ou organizações? | Assincronia, responsáveis locais e contingência. |
| Assimetria de poder | Pessoas podem manifestar-se com segurança? | Facilitação, proteção e canal independente. |
| Reversibilidade | Erro comunicacional pode ser corrigido? | Validação prévia e controle de versão. |
| Obrigação | Há dever legal, contratual ou ético? | Formalidade, especialista e evidência. |

### 80.1 Implantação focal

Pode utilizar:

- uma tabela mestre de ações;
- poucos públicos e eventos;
- canais já autorizados;
- confirmação apenas para conteúdo material;
- registro simples de contribuições e devolutivas;
- integração direta com cronograma e gate.

### 80.2 Implantação funcional

Utiliza catálogo de públicos, ações separadas, participação, confirmações, fontes protegidas, indicadores, gates e integração completa com os planos humanos.

### 80.3 Implantação sistêmica

Pode exigir:

- múltiplas ondas, públicos e organizações;
- governança distribuída e porta-vozes locais;
- canais redundantes e comunicação de incidente;
- segmentação e acessibilidade ampliadas;
- amostras e validações por grupo;
- gestão formal de contribuições e discordâncias;
- fotografias repetidas de gates;
- indicadores e análise de carga;
- transição de arquitetura comunicacional completa.

### 80.4 Regra de redução

Reduza campos e visões, não as funções materiais. Mesmo a versão mínima preserva objeto, público, finalidade, responsabilidade, momento, canal, possibilidade de resposta e evidência proporcional.

---

## 81. Versão focal reduzida

Utilize esta visão somente quando a mudança for delimitada, de baixo risco e com poucas interfaces.

### 81.1 Identificação mínima

| Campo | Preenchimento |
| --- | --- |
| Implantação | `IMP-AAAA-NNN` |
| Objeto e versão | [IDs] |
| Responsável | [Nome/papel] |
| Autoridade | [Nome/papel] |
| Públicos afetados | [IDs/descrição] |
| Fonte oficial | [Link/caminho] |
| Horizonte | [Período/evento] |

### 81.2 Ações mínimas

| ID | Evento/objeto | Público | Finalidade | Conteúdo/ação | Momento | Canal | Confirmação | Retorno | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [COM/ENG ID] | [Preencher] | [IDs] | [Preencher] | [Preencher] | [Data/gatilho] | [ID] | [Método/N.A.] | [Forma] | [Nome] |

### 81.3 Verificação focal

- [ ] pessoas materialmente afetadas foram reconhecidas;
- [ ] a informação chega antes do efeito;
- [ ] emissor possui autoridade;
- [ ] o canal é acessível e adequado;
- [ ] existe possibilidade de pergunta e contestação;
- [ ] compreensão será confirmada quando o risco exigir;
- [ ] contribuições materiais terão destino e devolutiva;
- [ ] alteração estrutural retornará ao Módulo 3;
- [ ] operação receberá qualquer rotina recorrente.

### 81.4 Gatilhos de aprofundamento

Aprofunde se surgir público excluído, dado sensível, efeito desigual, conflito de autoridade, múltiplos turnos ou organizações, IA material, liberação difícil de reverter, incidente, discordância relevante ou comunicação recorrente do estado futuro.

---

## 82. Revisão consolidada e teste de reconstrução

### 82.1 Identidade e fonte

- [ ] o plano possui ID, versão, fonte e custodiante;
- [ ] linha de base e arquitetura da comunicação estão referenciadas;
- [ ] exportações indicam versão ou data de corte;
- [ ] fontes protegidas e decisórias permanecem separadas.

### 82.2 Públicos e poder

- [ ] pessoas afetadas foram reconhecidas além dos destinatários diretos;
- [ ] ausências, representação e sub-representação possuem tratamento;
- [ ] influência prometida corresponde à autoridade real;
- [ ] segurança e possibilidade de contestação são proporcionais;
- [ ] segmentação possui fundamento e não exclui direitos.

### 82.3 Ações e resultados

- [ ] cada ação possui objeto, finalidade, público e resultado;
- [ ] conteúdo, fonte, emissor, canal e momento são localizáveis;
- [ ] entrega, compreensão, participação e devolutiva têm estados independentes;
- [ ] critérios de confirmação precedem o resultado;
- [ ] ação concluída não é apresentada como efeito demonstrado.

### 82.4 Participação e devolutiva

- [ ] consulta, cocriação, validação e decisão estão distinguidas;
- [ ] contribuições materiais possuem ID, rota e prazo;
- [ ] sínteses preservam autoria, divergência e limite;
- [ ] incorporações e recusas possuem fundamento;
- [ ] devolutiva fecha o ciclo no grau aplicável.

### 82.5 Integração e gates

- [ ] EAI, Cronograma, Kanban, Matriz e RIC estão sincronizados;
- [ ] planos de treinamento e mudança recebem os objetos próprios;
- [ ] gates possuem fotografias reproduzíveis;
- [ ] alteração arquitetural possui rota formal;
- [ ] rotinas recorrentes possuem destino operacional.

### 82.6 Proteção e tecnologia

- [ ] acessibilidade foi tratada desde o desenho;
- [ ] dados e registros são minimizados;
- [ ] acesso, retenção e eliminação estão definidos;
- [ ] monitoramento não produz vigilância desproporcional;
- [ ] IA possui função, entrada, revisão e limite registrados.

### 82.7 Percurso de reconstrução

Selecione uma ação material e reconstrua:

```text
origem e objeto
  → público e efeito
  → finalidade e influência
  → conteúdo e fonte
  → autoridade, canal e momento
  → emissão ou participação
  → confirmação ou contribuição
  → tratamento e decisão
  → devolutiva
  → evidência, gate e destino
```

| Ação testada | Percurso completo? | Lacunas | Divergências | Correções | Responsável | Data |
| --- | --- | --- | --- | --- | --- | --- |
| [COM/ENG ID] | [Sim/parcial/não] | [IDs] | [Preencher] | [Ações] | [Nome] | [Data] |

---

## 83. Antipadrões e sinais de qualidade

### 83.1 Antipadrões

| Antipadrão | Manifestação | Risco |
| --- | --- | --- |
| Comunicação como envio | Considerar tarefa concluída ao publicar. | Incompreensão invisível. |
| Comunicação como campanha | Persuadir sem reconhecer custo ou risco. | Manipulação e perda de confiança. |
| Engajamento como entusiasmo | Medir reações positivas ou presença. | Pressão e indicador falso. |
| Participação decorativa | Consultar depois da decisão sem influência real. | Legitimidade aparente. |
| Público genérico | “Todos” recebem o mesmo conteúdo. | Sobrecarga e exclusão. |
| Gestor como representante universal | Apenas liderança informa efeitos. | Trabalho real invisível. |
| Silêncio como aceite | Ausência de resposta encerra o tema. | Risco e discordância apagados. |
| Resistência como culpa | Objeção é atribuída à pessoa. | Problema estrutural oculto. |
| Repetição como solução | Mensagem original é reenviada. | Barreira preservada. |
| Canal aberto sem tratamento | Manifestação não recebe responsável. | Participação aparente. |
| Devolutiva vaga | “Agradecemos o feedback”. | Destino não governável. |
| Reunião como evidência | Presença prova alinhamento. | Compreensão presumida. |
| Mensagem como decisão | Texto de divulgação cria regra. | Autoridade ambígua. |
| Urgência permanente | Tudo é crítico. | Interrupção e perda de confiança. |
| Confidencialidade excessiva | Afetados não recebem o necessário. | Assimetria e incapacidade de agir. |
| Registro total | Toda conversa e emoção são capturadas. | Vigilância e exposição. |
| Métrica individual sem necessidade | Velocidade ou reação avalia pessoa. | Incentivo adverso e dano. |
| IA como intérprete das pessoas | Modelo infere emoção ou resistência. | Falsa certeza e discriminação. |
| Síntese como consenso | Divergências desaparecem no resumo. | Decisão mal informada. |
| Comunicação sem origem | Mensagens não se ligam a objeto ou evento. | Carga e ruído. |
| Operação como destinatária final | Rotinas são entregues sem aceite. | Continuidade frágil. |

### 83.2 Sinais de qualidade

- mensagens materiais são curtas ou extensas conforme a função, sempre encontráveis;
- pessoas sabem distinguir proposta, decisão e instrução vigente;
- públicos afetados conseguem perguntar e contestar com segurança;
- participação ocorre quando ainda pode influenciar;
- contribuições recebem destino visível e devolutiva;
- discordância pode permanecer sem impedir governança;
- compreensão é verificada proporcionalmente ao risco;
- canais têm finalidade, capacidade e contingência;
- acessibilidade altera o preparo, não apenas o formato final;
- carga comunicacional diminui quando a fonte no ponto de uso é suficiente;
- mudanças de versão alcançam quem precisa agir;
- comunicação recorrente chega à operação com responsável e manutenção;
- outra pessoa reconstrói o percurso sem memória privada.

---

## 84. Exemplo aplicado — sistema editorial

### 84.1 Contexto

A implantação `IMP-2026-001` prepara um incremento piloto de sistema editorial com estados, responsabilidade, aprovação e arquivos localizáveis.

| Objeto | ID |
| --- | --- |
| Linha de base | [LB-ARQ-ID/versão] |
| Capacidade editorial | [CAP-ARQ-ID/versão] |
| Incremento piloto | `IMP-2026-001-INC-001` |
| Entrega do fluxo configurado | `IMP-2026-001-ENT-001` |
| Pacote de preparação humana | `IMP-2026-001-PT-006` |
| Item de produção do material | `IMP-2026-001-ITM-012` |

O público inclui autora, revisora, aprovadora e responsável operacional. A autora é também pessoa afetada porque o novo fluxo altera a passagem de arquivos, a visibilidade de estado e a preservação de voz autoral.

### 84.2 Ações planejadas

| ID | Tipo | Objeto | Público | Finalidade | Momento | Confirmação/devolutiva |
| --- | --- | --- | --- | --- | --- | --- |
| `IMP-2026-001-COM-001` | Comunicação | `IMP-2026-001-INC-001` | Autora e revisora | Explicar escopo, estados, fonte oficial e limites do piloto. | Antes da preparação. | Reformulação aplicada a um conteúdo. |
| `IMP-2026-001-ENG-001` | Consulta | Fluxo de devolução | Autora e revisora | Identificar exceções e perda de contexto no trabalho real. | Antes do `PI-2`. | `IMP-2026-001-DEV-001`. |
| `IMP-2026-001-COM-002` | Comunicação | Janela do piloto | Participantes e suporte | Mobilizar uso, suporte, interrupção e contingência. | Antes do `PI-3`. | Confirmação de ação e canal crítico. |
| `IMP-2026-001-ENG-002` | Validação participativa | `IMP-2026-001-INC-001` | Autora, revisora e operação | Validar clareza, exceções e capacidade de localizar próxima ação. | Após quatro conteúdos. | Registro de validação e devolutiva. |

### 84.3 Mensagem material

| Campo | Exemplo |
| --- | --- |
| ID | `IMP-2026-001-MSG-001 v1.0` |
| Objeto | `IMP-2026-001-INC-001` |
| O que muda | Cada conteúdo passa a possuir estado, responsável, arquivo e próxima ação visíveis. |
| O que permanece | Aprovação humana e preservação da voz autoral. |
| Limite | Quatro conteúdos em ambiente de piloto; não representa escala maior. |
| Ação | Utilizar o fluxo assistido e registrar exceção pelo canal definido. |
| Contingência | Retornar ao fluxo manual documentado se houver perda de arquivo ou referência. |
| Fonte oficial | [Caminho do piloto] |
| Autoridade | [Papel designado] |

### 84.4 Confirmação de compreensão

| ID | Ação | Método | Critério | Resultado de exemplo | Limite |
| --- | --- | --- | --- | --- | --- |
| `IMP-2026-001-CNF-001` | `IMP-2026-001-COM-001` | Cada participante indica o estado, a próxima ação e a rota de exceção em um caso. | Resposta correta sem consulta informal a memória privada. | [Atendido/parcial] | Não demonstra competência autônoma em escala. |

Se a participante compreende o fluxo e discorda da carga adicional, a compreensão pode estar atendida enquanto a contribuição permanece aberta.

### 84.5 Contribuição e tratamento

Durante `IMP-2026-001-ENG-001`, a revisora informa que o estado único `em revisão` não distingue leitura em curso de ajustes devolvidos à autora.

| Campo | Exemplo |
| --- | --- |
| Contribuição | `IMP-2026-001-CTR-001` |
| Objeto | Fluxo e estados do piloto. |
| Tipo | Exceção operacional e proposta. |
| Efeito | Próxima ação pode ficar ambígua. |
| Rota | Relacionar a `IMP-2026-001-MUD-003` no Registro Integrado. |
| Limite de alçada | Se redistribuir autoridade, retornar ao Módulo 3. |
| Decisão | [DEC-ID] |
| Devolutiva | `IMP-2026-001-DEV-001` |

O ID da contribuição não é convertido em ID de mudança. O vínculo preserva origem, autoria autorizada, decisão e destino.

### 84.6 Devolutiva

| ID | Destino | Fundamento | Próximo movimento | Público |
| --- | --- | --- | --- | --- |
| `IMP-2026-001-DEV-001` | Incorporar dois estados no piloto, condicionado ao teste de materialidade. | Evidência de ambiguidade na próxima ação. | Atualizar fluxo, mensagem, teste e matriz; retornar ao Módulo 3 se autoridade mudar. | Participantes da consulta e responsáveis. |

### 84.7 Relação com gates

| Gate | Evidência deste plano | O que ainda não demonstra |
| --- | --- | --- |
| `PI-2` | Públicos, ações, compreensão inicial e canais preparados. | Prontidão técnica ou competência completa. |
| `PI-3` | Comunicação da janela, suporte e contingência compreendida. | Liberação autorizada. |
| `PI-4` | Participação, contribuições, devolutiva e efeitos registrados. | Adoção ou estabilidade além do piloto. |
| `PI-5` | Rotina de comunicação recorrente atribuída e aceita. | Sustentação futura sem monitoramento operacional. |

### 84.8 Limite do exemplo

O exemplo demonstra relações e estados independentes. Não prescreve públicos, canais, critérios, autoridades ou mensagens para outra implantação.

---

## 85. Manifestações, divergências e controle de versões

### 85.1 Responsável pelo plano

| Campo | Manifestação |
| --- | --- |
| Nome e papel | [Preencher] |
| Versão considerada | [N.N] |
| Cobertura suficiente para o horizonte? | [Sim/parcial/não] |
| Limitações | [Preencher] |
| Ações abertas | [IDs/nenhuma] |
| Assinatura ou registro | [ID/data] |

### 85.2 Responsável pela implantação

| Campo | Manifestação |
| --- | --- |
| Nome e papel | [Preencher] |
| Integração com trabalho e tempo | [Suficiente/parcial/insuficiente] |
| Riscos e condições | [IDs/nenhuma] |
| Próximo gate ou movimento | [Preencher] |
| Assinatura ou registro | [ID/data] |

### 85.3 Pessoas afetadas ou representantes

| Público/grupo | Participante/representante | Objeto | Manifestação | Divergência | Limite de representação | Registro |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Nome/papel ou referência protegida] | [IDs] | [Compreendido/validado/com ressalva/outro] | [Síntese/ID] | [Preencher] | [ID/data] |

### 85.4 Responsável operacional

| Campo | Manifestação |
| --- | --- |
| Nome e papel | [Preencher] |
| Rotinas recorrentes recebidas | [IDs] |
| Capacidade de sustentação | [Demonstrada/parcial/insuficiente] |
| Condições e pendências | [IDs/nenhuma] |
| Aceite relacionado | [ID] |
| Assinatura ou registro | [ID/data] |

### 85.5 Divergências preservadas

| ID | Pessoa, papel ou grupo | Objeto | Divergência | Fundamento | Efeito | Decisão | Destino |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/CTR ID] | [ID/referência] | [IDs] | [Preencher] | [Preencher] | [Preencher] | [ID/pendente] | [Fonte/módulo] |

### 85.6 Versão vigente

| Campo | Registro |
| --- | --- |
| Versão | [N.N] |
| Estado | [Estado] |
| Data de status | [Data/hora] |
| Fonte oficial | [Caminho/link] |
| Linha de base referenciada | [ID/versão] |
| Gate mais recente | [ID/N.A.] |
| Fotografia mais recente | [ID/N.A.] |
| Decisão/aprovação | [ID/N.A.] |
| Versão substituída | [N.N/N.A.] |

### 85.7 Histórico de versões do plano preenchido

| Versão | Data | Alteração | Evento/motivo | Ações/públicos afetados | Responsável | Aprovação |
| --- | --- | --- | --- | --- | --- | --- |
| [N.N] | [Data] | [Preencher] | [ID/síntese] | [IDs] | [Nome] | [ID/N.A.] |

---

## 86. Encerramento e registro final

### 86.1 Critérios de conclusão

O plano pode ser considerado concluído para a implantação quando:

- possui identidade, versão, fonte e custodiante;
- públicos e pessoas materialmente afetadas possuem destino;
- ações materiais foram realizadas, canceladas ou transferidas com fundamento;
- resultados de entrega, compreensão, participação e devolutiva estão registrados separadamente;
- contribuições materiais possuem tratamento, decisão ou rota aceita;
- discordâncias e limitações permanecem recuperáveis;
- mensagens e fontes desatualizadas foram encerradas ou substituídas;
- canais temporários foram fechados e acessos revogados quando aplicável;
- comunicações recorrentes possuem responsável, documentação, contingência e aceite operacional;
- registros possuem retenção, eliminação e acesso definidos;
- Matriz, RIC, validações, configuração e transição estão sincronizados;
- participação material da IA está registrada;
- aprendizagem possui destino;
- outra pessoa autorizada consegue reconstruir os percursos materiais.

### 86.2 Resultado de conclusão

- [ ] Concluído para o horizonte declarado
- [ ] Concluído com ações ou condições residuais aceitas
- [ ] Requer complementação
- [ ] Requer decisão de autoridade
- [ ] Requer retorno ao Módulo 3
- [ ] Requer extensão da estabilização
- [ ] Bloqueado
- [ ] Suspenso
- [ ] Reaberto
- [ ] Substituído

| Campo | Registro |
| --- | --- |
| Horizonte | [Objetos/período] |
| Resultado | [Selecionar] |
| Ações abertas | [IDs/nenhuma] |
| Contribuições sem destino | [IDs/nenhuma] |
| Rotinas transferidas | [IDs/nenhuma] |
| Condições residuais | [IDs/nenhuma] |
| Gate/decisão | [ID] |
| Próximo movimento | [Transferir/corrigir/reabrir/encerrar/outro] |
| Responsável | [Nome/papel] |
| Autoridade | [Nome/papel] |
| Data | [Data/hora] |
| Evidência | [ID/link] |

Encerrar o plano não apaga comunicação recorrente, contribuição em tratamento ou condição aceita pela operação. O objeto continua na fonte competente com referência ao dossiê.

### 86.3 Registro final do template

| Campo | Registro |
| --- | --- |
| Identificador do template | `templates/08-plano-de-comunicacao-e-engajamento.md` |
| Módulo | 4 — Implantação |
| Tipo | Template operacional |
| Função | Governar comunicação, compreensão, participação, contribuição e devolutiva durante a implantação |
| Entrada principal | Linha de base aceita, arquitetura da comunicação e instrumentos vigentes da implantação |
| Saída principal | Fonte canônica de ações, ocorrências, resultados e destinos comunicacionais e participativos |
| Gates relacionados | `PI-1` a `PI-5` |
| Documento anterior | `templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md` |
| Documento seguinte | `templates/09-plano-de-treinamento-e-capacitacao.md` |
| Fonte oficial | Repositório do Sistema Operacional do Estúdio LICHTARA |
| Responsabilidade final | Humana |

### Histórico de versões do template

| Versão | Data | Alteração | Responsável |
| --- | --- | --- | --- |
| 1.0 | 2026-08-03 | Criação integral do Plano de Comunicação e Engajamento como instrumento de comunicação, compreensão, participação, escuta, contribuição e devolutiva da implantação. | Estúdio LICHTARA |
