# Índice de Diagnósticos

```yaml
titulo: Índice de Diagnósticos
modulo: 02-diagnostico-organizacional
responsavel_pelo_indice:
data_de_criacao: AAAA-MM-DD
data_da_ultima_atualizacao:
frequencia_de_revisao: semanal
estado: ativo
nivel_sensibilidade: interna
versao: 0.1
```

---

## Sistema Operacional do Estúdio LICHTARA

**Módulo:** 2 — Diagnóstico Organizacional
**Tipo:** Índice operacional e painel de governança
**Função:** Localização, acompanhamento e controle dos diagnósticos registrados
**Documento de referência:** `README.md`

---

# 1. Finalidade

Este índice reúne os diagnósticos organizacionais formalmente registrados pelo Estúdio LICHTARA.

Sua função é oferecer uma visão central sobre:

* diagnósticos existentes;
* identificadores utilizados;
* ano de abertura;
* organização ou código relacionado;
* objeto da investigação;
* tipo de diagnóstico;
* responsável;
* estado atual;
* nível de sensibilidade;
* próxima ação;
* prazo ou data de revisão;
* localização do registro;
* condição de encerramento ou arquivamento.

O índice deve permitir responder rapidamente:

1. Quais diagnósticos estão ativos?
2. Quem responde por cada um?
3. Em que etapa se encontram?
4. Qual é a próxima ação?
5. Quais estão aguardando informação ou decisão?
6. Quais permanecem parados?
7. Quais foram concluídos, cancelados ou arquivados?
8. Onde está o registro oficial de cada diagnóstico?

---

# 2. Natureza do índice

Este arquivo não substitui:

* o `README.md` de cada diagnóstico;
* o briefing;
* o plano de investigação;
* a Matriz de Evidências;
* a síntese;
* o relatório;
* o histórico do diagnóstico.

O índice apresenta apenas os metadados necessários para governança e localização.

Informações detalhadas devem permanecer dentro do respectivo diretório.

---

# 3. Princípios

## 3.1 Todo diagnóstico formal deve aparecer no índice

A criação de uma pasta de diagnóstico somente é considerada concluída quando o registro correspondente tiver sido incluído neste arquivo.

---

## 3.2 IDs não devem ser apagados

Diagnósticos:

* cancelados;
* recusados após qualificação;
* suspensos;
* invalidados;
* encerrados antecipadamente;

devem continuar registrados.

O ID nunca deve ser removido ou reutilizado.

---

## 3.3 O índice deve refletir o estado real

O estado registrado deve corresponder à condição atual do diagnóstico.

Não devem permanecer diagnósticos classificados como “em andamento” quando estiverem:

* aguardando informação;
* sem responsável;
* suspensos;
* sem atividade;
* concluídos;
* cancelados.

---

## 3.4 Toda atividade em andamento deve possuir próxima ação

Um diagnóstico ativo sem próxima ação visível apresenta risco de paralisação silenciosa.

A próxima ação deve indicar:

* o que será feito;
* quem fará;
* quando ocorrerá ou será revisada.

---

## 3.5 O índice deve minimizar exposição

Não devem ser inseridos no índice:

* relatos pessoais;
* dados clínicos;
* conteúdo de entrevistas;
* conflitos;
* hipóteses sensíveis;
* conclusões diagnósticas;
* informações contratuais detalhadas;
* dados financeiros específicos;
* nomes de pessoas sem necessidade.

Quando necessário, utilizar:

* código da organização;
* nome reduzido;
* função;
* descrição neutra do objeto.

---

# 4. Responsabilidade pelo índice

## Responsável principal

`[Nome ou função]`

## Responsabilidades

* verificar o próximo ID;
* registrar novos diagnósticos;
* atualizar estados;
* verificar diagnósticos sem atividade;
* registrar conclusões e arquivamentos;
* preservar a coerência dos links;
* revisar exposição de informações;
* manter o histórico de atualizações.

## Responsáveis pelos diagnósticos

Cada responsável deve informar mudanças relevantes de:

* estado;
* prazo;
* próxima ação;
* escopo;
* suspensão;
* conclusão;
* cancelamento;
* reabertura.

---

# 5. Convenção de identificadores

Utilizar:

```text
DIA-AAAA-NNN
```

## Exemplo

```text
DIA-2026-001
DIA-2026-002
DIA-2027-001
```

## Próximo ID disponível

| Ano  | Último ID utilizado | Próximo ID     |
| ---- | ------------------- | -------------- |
| 2026 | `DIA-2026-___`      | `DIA-2026-___` |
| 2027 | `DIA-2027-___`      | `DIA-2027-___` |

A tabela deve ser atualizada sempre que um novo diagnóstico for aberto.

---

# 6. Tipos de diagnóstico

## Focal

Investiga uma questão claramente delimitada.

### Exemplos

* etapa específica de um processo;
* dificuldade de acompanhamento;
* uso de uma ferramenta;
* ponto da jornada;
* decisão localizada.

---

## Funcional

Investiga uma função ou área organizacional.

### Exemplos

* comercial;
* comunicação;
* operações;
* conhecimento;
* tecnologia;
* gestão de projetos.

---

## Sistêmico

Investiga relações entre múltiplas dimensões organizacionais.

### Exemplos

* estrutura;
* processos;
* decisões;
* conhecimento;
* tecnologia;
* identidade;
* governança.

---

# 7. Estados oficiais

Utilizar exclusivamente os estados definidos abaixo.

| Estado                             | Significado                                              |
| ---------------------------------- | -------------------------------------------------------- |
| **Recebido**                       | Demanda registrada, ainda não qualificada.               |
| **Em qualificação**                | Briefing e formulação inicial em andamento.              |
| **Aguardando aprovação de escopo** | Questão, escopo ou condições aguardam aprovação.         |
| **Planejado**                      | Plano de investigação aprovado.                          |
| **Em coleta**                      | Fontes e evidências estão sendo produzidas.              |
| **Em organização**                 | Registros estão sendo consolidados.                      |
| **Em análise**                     | Evidências, hipóteses e relações estão sendo examinadas. |
| **Aguardando informação**          | A continuidade depende de fonte, acesso ou resposta.     |
| **Em síntese**                     | Achados estão sendo integrados.                          |
| **Em validação**                   | Resultados estão sendo confrontados com participantes.   |
| **Em revisão**                     | Correções e ajustes estão sendo incorporados.            |
| **Entregue**                       | A entrega principal foi realizada.                       |
| **Em transição**                   | Requisitos estão sendo transferidos ao Módulo 3.         |
| **Concluído**                      | Critérios de encerramento foram atendidos.               |
| **Concluído com limitações**       | Encerrado com lacunas explícitas.                        |
| **Suspenso**                       | Interrompido temporariamente por decisão formal.         |
| **Cancelado**                      | Encerrado sem conclusão diagnóstica.                     |
| **Reaberto**                       | Nova evidência ou mudança material exige revisão.        |
| **Arquivado**                      | Registro encerrado e preservado.                         |

Não utilizar variações livres como:

* quase concluído;
* parado;
* em espera;
* aguardando cliente;
* finalizado;
* ativo;
* travado.

Essas condições devem ser traduzidas para um estado oficial e explicadas na coluna de próxima ação ou observação.

---

# 8. Classificação de sensibilidade

| Classificação    | Uso                                                                                                           |
| ---------------- | ------------------------------------------------------------------------------------------------------------- |
| **Pública**      | O registro pode ser divulgado sem risco relevante.                                                            |
| **Interna**      | Destinado ao funcionamento do Estúdio e do projeto.                                                           |
| **Confidencial** | A divulgação pode gerar risco organizacional, contratual ou reputacional.                                     |
| **Sensível**     | Contém ou se relaciona a dados pessoais, estratégicos, jurídicos, financeiros, clínicos ou de alta restrição. |

O índice deve registrar a classificação geral do diagnóstico.

Arquivos internos podem possuir classificação mais elevada.

---

# 9. Painel geral

Esta é a tabela principal do índice.

| ID             | Título ou objeto | Organização ou código | Tipo                          | Responsável | Abertura | Estado | Sensibilidade | Próxima ação | Responsável pela ação | Data de revisão | Diretório                          |
| -------------- | ---------------- | --------------------- | ----------------------------- | ----------- | -------- | ------ | ------------- | ------------ | --------------------- | --------------- | ---------------------------------- |
| `DIA-AAAA-NNN` |                  |                       | Focal / Funcional / Sistêmico |             |          |        |               |              |                       |                 | `[Abrir](AAAA/DIA-AAAA-NNN-nome/)` |

## Instruções por coluna

### ID

Identificador único e permanente.

### Título ou objeto

Descrição curta e neutra da investigação.

### Organização ou código

Nome da organização ou identificador protegido.

### Tipo

Focal, funcional ou sistêmico.

### Responsável

Pessoa responsável pela condução.

### Abertura

Data de abertura formal.

### Estado

Um dos estados oficiais.

### Sensibilidade

Pública, interna, confidencial ou sensível.

### Próxima ação

Movimento concreto necessário para avanço ou encerramento.

### Responsável pela ação

Pessoa que deverá executar ou provocar a ação.

### Data de revisão

Data em que a condição deverá ser verificada.

Não precisa ser a data de conclusão.

### Diretório

Link para a pasta oficial do diagnóstico.

---

# 10. Diagnósticos ativos

Consideram-se ativos os diagnósticos nos estados:

* Recebido;
* Em qualificação;
* Aguardando aprovação de escopo;
* Planejado;
* Em coleta;
* Em organização;
* Em análise;
* Aguardando informação;
* Em síntese;
* Em validação;
* Em revisão;
* Entregue;
* Em transição;
* Reaberto.

| ID | Objeto | Estado | Responsável | Próxima ação | Data de revisão | Sinal de atenção |
| -- | ------ | ------ | ----------- | ------------ | --------------- | ---------------- |
|    |        |        |             |              |                 |                  |

## Sinais de atenção

* prazo vencido;
* sem próxima ação;
* aguardando informação;
* sem atualização recente;
* sem responsável;
* escopo não aprovado;
* acesso pendente;
* validação pendente;
* risco de cancelamento;
* outro: `[Preencher]`.

---

# 11. Diagnósticos aguardando informação ou decisão

| ID | Dependência | Pessoa ou fonte | Data da solicitação | Data de revisão | Impacto |
| -- | ----------- | --------------- | ------------------- | --------------- | ------- |
|    |             |                 |                     |                 |         |

## Ações possíveis

* reiterar solicitação;
* substituir fonte;
* aceitar lacuna;
* reduzir escopo;
* suspender;
* cancelar;
* encerrar com limitações.

Um diagnóstico não deve permanecer indefinidamente aguardando informação sem decisão explícita.

---

# 12. Diagnósticos suspensos

| ID | Motivo da suspensão | Data | Condição para retomada | Responsável | Próxima revisão |
| -- | ------------------- | ---- | ---------------------- | ----------- | --------------- |
|    |                     |      |                        |             |                 |

## Verificação

* [ ] suspensão formalmente registrada;
* [ ] cliente informado;
* [ ] dados protegidos;
* [ ] pendências registradas;
* [ ] condição de retomada definida;
* [ ] próxima revisão agendada.

---

# 13. Diagnósticos entregues ou em transição

| ID | Entrega realizada | Data | Validação | Transição | Próxima ação |
| -- | ----------------- | ---- | --------- | --------- | ------------ |
|    |                   |      |           |           |              |

## Atenção

O estado **Entregue** não equivale automaticamente a **Concluído**.

Ainda podem permanecer:

* validação;
* correções;
* transição;
* retrospectiva;
* tratamento de dados;
* atualização do índice;
* arquivamento.

---

# 14. Diagnósticos concluídos

| ID | Objeto | Data de conclusão | Resultado                  | Entrega principal | Transição | Retrospectiva | Diretório |
| -- | ------ | ----------------- | -------------------------- | ----------------- | --------- | ------------- | --------- |
|    |        |                   | Concluído / Com limitações |                   |           |               |           |

## Resultado

### Concluído

A questão foi respondida no grau necessário e os critérios de encerramento foram atendidos.

### Concluído com limitações

O diagnóstico produziu resultado utilizável, mas preserva lacunas relevantes.

As limitações devem estar registradas no diretório.

---

# 15. Diagnósticos cancelados

| ID | Objeto | Data | Etapa de cancelamento | Motivo resumido | Registro de decisão | Diretório |
| -- | ------ | ---- | --------------------- | --------------- | ------------------- | --------- |
|    |        |      |                       |                 |                     |           |

## Motivos possíveis

* demanda não viável;
* ausência de autorização;
* falta de acesso;
* mudança de prioridade;
* cancelamento contratual;
* conflito de interesse;
* risco incompatível;
* diagnóstico substituído;
* decisão de não continuidade.

O motivo deve ser descrito de forma neutra.

---

# 16. Diagnósticos arquivados

| ID | Objeto | Ano | Data de arquivamento | Localização | Retenção | Observação |
| -- | ------ | --- | -------------------- | ----------- | -------- | ---------- |
|    |        |     |                      |             |          |            |

O arquivamento deve ocorrer após:

* encerramento;
* revisão de acessos;
* tratamento de gravações;
* definição de retenção;
* conclusão da retrospectiva;
* atualização do histórico.

---

# 17. Diagnósticos reabertos

| ID | Data da reabertura | Motivo | Versão anterior | Novo escopo | Responsável |
| -- | ------------------ | ------ | --------------- | ----------- | ----------- |
|    |                    |        |                 |             |             |

## Motivos possíveis

* nova evidência material;
* erro identificado;
* mudança de contexto;
* devolução pelo Módulo 3;
* nova decisão;
* validação inconclusiva;
* ampliação formal de escopo.

A reabertura não cria automaticamente um novo ID.

Um novo ID deve ser utilizado quando houver:

* nova questão central;
* novo objeto;
* nova decisão;
* ruptura material com o diagnóstico anterior.

---

# 18. Visão por ano

## 2026

| ID             | Objeto | Tipo | Estado | Responsável | Diretório |
| -------------- | ------ | ---- | ------ | ----------- | --------- |
| `DIA-2026-001` |        |      |        |             |           |

## 2027

| ID             | Objeto | Tipo | Estado | Responsável | Diretório |
| -------------- | ------ | ---- | ------ | ----------- | --------- |
| `DIA-2027-001` |        |      |        |             |           |

Adicionar uma nova seção para cada ano com registros.

---

# 19. Visão por organização

Esta seção é opcional e deve ser utilizada apenas quando não ampliar exposição.

| Organização ou código | Diagnósticos relacionados | Diagnósticos ativos | Último diagnóstico | Observação |
| --------------------- | ------------------------- | ------------------- | ------------------ | ---------- |
|                       |                           |                     |                    |            |

## Regra

Não utilizar essa visão quando a associação entre organização e diagnóstico for sensível.

---

# 20. Visão por tipo

## Diagnósticos focais

| ID | Objeto | Estado | Responsável |
| -- | ------ | ------ | ----------- |
|    |        |        |             |

## Diagnósticos funcionais

| ID | Objeto | Estado | Responsável |
| -- | ------ | ------ | ----------- |
|    |        |        |             |

## Diagnósticos sistêmicos

| ID | Objeto | Estado | Responsável |
| -- | ------ | ------ | ----------- |
|    |        |        |             |

---

# 21. Visão por responsável

| Responsável | Diagnósticos ativos | Aguardando ação | Em validação | Em transição | Total |
| ----------- | ------------------- | --------------- | ------------ | ------------ | ----- |
|             |                     |                 |              |              |       |

## Finalidade

Esta visão ajuda a observar:

* concentração de responsabilidade;
* carga operacional;
* diagnósticos sem responsável;
* necessidade de redistribuição;
* risco de continuidade.

Não deve ser utilizada isoladamente para avaliação de desempenho.

---

# 22. Diagnósticos sem atualização recente

## Critério

Considera-se sem atualização recente o diagnóstico que ultrapassou:

`[Número de dias ou condição definida.]`

sem alteração de:

* estado;
* próxima ação;
* histórico;
* documento principal;
* data de revisão.

| ID | Estado | Última atualização | Dias sem atualização | Responsável | Encaminhamento |
| -- | ------ | ------------------ | -------------------- | ----------- | -------------- |
|    |        |                    |                      |             |                |

## Encaminhamentos possíveis

* manter ativo com justificativa;
* solicitar atualização;
* alterar para aguardando informação;
* suspender;
* cancelar;
* encerrar com limitações.

---

# 23. Pendências críticas do portfólio

| ID do diagnóstico | Pendência | Impacto | Responsável | Prazo | Estado |
| ----------------- | --------- | ------- | ----------- | ----- | ------ |
|                   |           |         |             |       |        |

## Exemplos

* ausência de autorização;
* risco de exposição;
* fonte essencial indisponível;
* entrega vencida;
* validação não realizada;
* dado sensível sem destinação;
* transição sem aceite;
* diagnóstico parado;
* acesso excessivo.

---

# 24. Próximas ações consolidadas

| Data ou período | Diagnóstico | Ação | Responsável | Dependência |
| --------------- | ----------- | ---- | ----------- | ----------- |
|                 |             |      |             |             |
|                 |             |      |             |             |

Esta seção pode ser utilizada para reuniões operacionais ou revisão semanal.

---

# 25. Indicadores do portfólio

Utilizar apenas quando houver volume suficiente para que os indicadores sejam úteis.

| Indicador                 | Valor atual | Período | Observação |
| ------------------------- | ----------- | ------- | ---------- |
| Diagnósticos ativos       |             |         |            |
| Em qualificação           |             |         |            |
| Em coleta                 |             |         |            |
| Em análise                |             |         |            |
| Aguardando informação     |             |         |            |
| Em validação              |             |         |            |
| Em transição              |             |         |            |
| Concluídos                |             |         |            |
| Concluídos com limitações |             |         |            |
| Suspensos                 |             |         |            |
| Cancelados                |             |         |            |
| Sem atualização recente   |             |         |            |

## Atenção

Indicadores não devem substituir a leitura contextual dos diagnósticos.

Um número reduzido de diagnósticos pode exigir maior cuidado que um volume elevado de investigações simples.

---

# 26. Capacidade operacional

| Responsável | Capacidade estimada | Diagnósticos ativos | Condição                     | Ação |
| ----------- | ------------------- | ------------------- | ---------------------------- | ---- |
|             |                     |                     | Adequada / elevada / crítica |      |

## Perguntas

* Existem diagnósticos demais para a capacidade atual?
* Há concentração em uma única pessoa?
* As validações estão acumuladas?
* Existem investigações que deveriam ser suspensas?
* O volume de coleta é compatível com a análise disponível?
* A abertura de novos diagnósticos é responsável?

---

# 27. Revisão semanal

## Data

`[DD/MM/AAAA]`

## Responsável

`[Nome]`

## Verificações

* [ ] novos diagnósticos registrados;
* [ ] IDs conferidos;
* [ ] estados atualizados;
* [ ] próximas ações preenchidas;
* [ ] datas de revisão atualizadas;
* [ ] diagnósticos sem atividade examinados;
* [ ] suspensões revisadas;
* [ ] entregas registradas;
* [ ] conclusões registradas;
* [ ] links verificados;
* [ ] exposição de informações revisada.

## Diagnósticos que exigem atenção

* `DIA-AAAA-NNN — [Motivo]`

## Decisões necessárias

* `[Decisão 1]`
* `[Decisão 2]`

## Próxima revisão

`[DD/MM/AAAA]`

---

# 28. Revisão mensal

## Período

`[Mês e ano]`

## Questões

1. Quantos diagnósticos foram abertos?
2. Quantos foram concluídos?
3. Quantos permanecem aguardando informação?
4. Existem diagnósticos sem próxima ação?
5. Existem diagnósticos sem responsável?
6. A capacidade está adequada?
7. Existem dados ou gravações que precisam ser tratados?
8. Quais aprendizados das retrospectivas devem alterar o método?
9. Existem padrões recorrentes nas demandas?
10. Algum diagnóstico deve ser arquivado?

## Síntese

`[Preencher]`

## Ações

| Ação | Responsável | Prazo |
| ---- | ----------- | ----- |
|      |             |       |

---

# 29. Atualização do registro

O índice deve ser atualizado quando ocorrer:

* abertura;
* mudança de título;
* mudança de organização ou código;
* mudança de responsável;
* mudança de estado;
* mudança de próxima ação;
* suspensão;
* retomada;
* entrega;
* validação;
* conclusão;
* cancelamento;
* reabertura;
* arquivamento.

---

# 30. Procedimento de inclusão

1. verificar o próximo ID;
2. confirmar a pasta anual;
3. criar o diretório;
4. criar o `README.md` do diagnóstico;
5. preencher o briefing inicial;
6. inserir uma linha no painel geral;
7. inserir na visão anual;
8. inserir em seções específicas, quando necessário;
9. registrar responsável;
10. registrar próxima ação.

## Checklist

* [ ] ID válido;
* [ ] ID não utilizado;
* [ ] título neutro;
* [ ] organização ou código adequado;
* [ ] responsável definido;
* [ ] estado inicial correto;
* [ ] sensibilidade classificada;
* [ ] próxima ação definida;
* [ ] data de revisão definida;
* [ ] link funcional.

---

# 31. Procedimento de atualização

Ao alterar o estado:

1. atualizar o painel geral;
2. atualizar a seção correspondente;
3. remover da seção anterior, quando necessário;
4. atualizar o `README.md` do diagnóstico;
5. registrar no histórico do diagnóstico;
6. revisar a próxima ação;
7. revisar a data de acompanhamento.

## Regra

O mesmo diagnóstico pode aparecer:

* no painel geral;
* na visão anual;
* em uma seção operacional específica.

Essas ocorrências devem permanecer coerentes.

---

# 32. Procedimento de encerramento

Ao concluir um diagnóstico:

1. alterar o estado;
2. registrar a data de conclusão;
3. confirmar a entrega;
4. confirmar a validação;
5. confirmar a transição ou decisão de não transição;
6. confirmar a retrospectiva;
7. revisar dados e acessos;
8. mover o registro para a seção de concluídos;
9. atualizar a visão anual;
10. definir condição de arquivamento.

---

# 33. Procedimento de cancelamento

Ao cancelar:

1. registrar a decisão;
2. alterar o estado;
3. registrar a data;
4. inserir motivo resumido;
5. proteger ou descartar dados conforme finalidade;
6. atualizar o diretório;
7. mover para a seção de cancelados;
8. preservar o ID.

---

# 34. Procedimento de arquivamento

Ao arquivar:

1. confirmar encerramento;
2. revisar retenção;
3. revisar acessos;
4. registrar localização;
5. atualizar estado;
6. inserir na seção de arquivados;
7. verificar links;
8. registrar data de arquivamento.

---

# 35. Controle de coerência

## Verificar

* o estado do índice corresponde ao `README.md`;
* o responsável é o mesmo em todos os registros;
* a data de abertura está correta;
* a pasta está no ano correto;
* o link funciona;
* a sensibilidade está atualizada;
* a próxima ação corresponde ao estado;
* diagnósticos concluídos não permanecem como ativos;
* diagnósticos suspensos possuem revisão;
* diagnósticos cancelados preservam o ID.

---

# 36. Controle de exposição

Antes de atualizar o índice, verificar:

* o título expõe informação sensível?
* o nome da organização precisa aparecer?
* o objeto contém julgamento?
* a próxima ação revela conteúdo confidencial?
* a observação identifica uma pessoa?
* o link concede acesso além do necessário?

## Formulações adequadas

```text
Organização do fluxo de atendimento
Avaliação do acompanhamento comercial
Diagnóstico da gestão de conhecimento
```

## Formulações inadequadas

```text
Problemas causados pela fundadora
Cliente desorganizada
Equipe resistente à mudança
Falhas graves no atendimento
```

---

# 37. Diagnósticos confidenciais

Quando a própria existência do diagnóstico for confidencial, utilizar:

* código;
* título genérico;
* link restrito;
* acesso limitado ao índice completo.

### Exemplo

| ID             | Título                       | Organização |
| -------------- | ---------------------------- | ----------- |
| `DIA-2026-014` | Avaliação funcional restrita | `ORG-004`   |

A chave entre código e organização deve permanecer em ambiente protegido.

---

# 38. Índices derivados

Quando necessário, podem ser produzidas versões derivadas:

* índice operacional interno;
* índice executivo;
* índice anonimizado;
* índice de diagnósticos ativos;
* índice de arquivo.

A versão derivada deve indicar:

* data;
* fonte;
* finalidade;
* responsável;
* restrições.

---

# 39. Exportações

Exportações para:

* planilha;
* PDF;
* painel;
* ferramenta de gestão;

devem ser consideradas versões derivadas.

A fonte oficial permanece este índice ou o sistema formalmente definido como substituto.

## Registro de exportação

| Data | Formato | Finalidade | Responsável |
| ---- | ------- | ---------- | ----------- |
|      |         |            |             |

---

# 40. Automação e inteligência artificial

A atualização do índice pode ser apoiada por automação ou IA para:

* verificar campos vazios;
* localizar estados inconsistentes;
* identificar prazos vencidos;
* agrupar diagnósticos;
* gerar resumos operacionais;
* verificar links;
* sinalizar falta de atualização.

## A IA não deve

* alterar estados sem revisão;
* criar diagnósticos;
* atribuir responsáveis;
* inferir sensibilidade;
* cancelar ou concluir registros;
* expor informações restritas;
* decidir prioridades.

## Registro

| Sistema ou agente | Função | Data | Saída revisada por |
| ----------------- | ------ | ---- | ------------------ |
|                   |        |      |                    |

---

# 41. Antipadrões

## Índice tratado como arquivo histórico estático

Produz estados desatualizados e perda de confiança.

## Diagnóstico sem próxima ação

Oculta paralisação.

## Uso de estados livres

Impede comparação e governança.

## Exclusão de diagnósticos cancelados

Permite reutilização indevida de IDs e apaga histórico.

## Exposição de conteúdo sensível

Transforma um instrumento de localização em risco informacional.

## Duplicidade de ID

Compromete toda a rastreabilidade.

## Link sem acesso ou quebrado

Impede localização do registro oficial.

## Manutenção de diagnóstico concluído entre ativos

Distorce capacidade e carga.

## Índice atualizado sem atualizar a pasta

Cria fontes conflitantes.

---

# 42. Invariantes

## Invariante 1

Todo diagnóstico formal possui uma linha no painel geral.

## Invariante 2

Todo diagnóstico possui ID único.

## Invariante 3

Nenhum ID é apagado ou reutilizado.

## Invariante 4

Todo diagnóstico ativo possui responsável.

## Invariante 5

Todo diagnóstico ativo possui próxima ação ou condição de espera explícita.

## Invariante 6

Todo diagnóstico possui data de revisão.

## Invariante 7

O estado do índice corresponde ao estado do diretório.

## Invariante 8

O índice não expõe conteúdo além do necessário.

## Invariante 9

Todo diagnóstico concluído possui resultado registrado.

## Invariante 10

Todo diagnóstico arquivado permanece localizável.

---

# 43. Checklist de atualização

* [ ] O novo estado é oficial?
* [ ] A próxima ação foi atualizada?
* [ ] O responsável pela ação está definido?
* [ ] A data de revisão está preenchida?
* [ ] A seção operacional correspondente foi atualizada?
* [ ] O `README.md` do diagnóstico foi atualizado?
* [ ] O histórico foi atualizado?
* [ ] O link funciona?
* [ ] A sensibilidade foi revista?
* [ ] Nenhuma informação excessiva foi incluída?

---

# 44. Histórico do índice

| Data | Versão | Alteração         | Responsável |
| ---- | ------ | ----------------- | ----------- |
|      | 0.1    | Criação do índice |             |
|      |        |                   |             |

---

# 45. Modelo inicial preenchível

## Próximo ID

| Ano  | Último ID | Próximo ID     |
| ---- | --------- | -------------- |
| 2026 | —         | `DIA-2026-001` |

## Painel geral

| ID | Título ou objeto | Organização ou código | Tipo | Responsável | Abertura | Estado | Sensibilidade | Próxima ação | Responsável pela ação | Data de revisão | Diretório |
| -- | ---------------- | --------------------- | ---- | ----------- | -------- | ------ | ------------- | ------------ | --------------------- | --------------- | --------- |
|    |                  |                       |      |             |          |        |               |              |                       |                 |           |

## Diagnósticos que exigem atenção

| ID | Motivo | Responsável | Ação |
| -- | ------ | ----------- | ---- |
|    |        |             |      |

## Próximas ações

| Data | Diagnóstico | Ação | Responsável |
| ---- | ----------- | ---- | ----------- |
|      |             |      |             |

## Última revisão

* **Data:** `[DD/MM/AAAA]`
* **Responsável:** `[Nome]`
* **Próxima revisão:** `[DD/MM/AAAA]`

---

# 46. Princípio de encerramento

O índice não existe apenas para contar diagnósticos.

Ele deve tornar visível:

* onde cada investigação está;
* quem responde por sua continuidade;
* que movimento precisa acontecer;
* que dependência está impedindo avanço;
* quais trabalhos foram concluídos;
* quais registros precisam ser protegidos;
* quanto trabalho o Estúdio consegue sustentar.

Quando o índice está atualizado, o portfólio diagnóstico pode ser governado.

Quando deixa de representar a realidade, torna-se apenas outra camada de documentação.

Com este arquivo, a estrutura de `registros-de-diagnostico/` está estabelecida. O próximo bloco do Módulo 2 é a pasta `ferramentas/`, começando pelo seu `README.md`, que deverá orientar **como escolher uma ferramenta a partir da pergunta diagnóstica, e não por hábito ou preferência**.
