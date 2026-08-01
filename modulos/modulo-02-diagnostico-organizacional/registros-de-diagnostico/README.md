# Registros de Diagnóstico

## Sistema Operacional do Estúdio LICHTARA

**Módulo:** 2 — Diagnóstico Organizacional
**Tipo:** Governança de registros operacionais
**Função:** Organização, controle, proteção e preservação dos diagnósticos reais
**Versão:** 0.1
**Data de criação:** 01/08/2026

---

# 1. Finalidade

Esta pasta reúne os registros dos diagnósticos organizacionais realizados pelo Estúdio LICHTARA.

Cada diagnóstico deve possuir um diretório próprio, no qual serão preservados:

* demanda inicial;
* escopo;
* plano de investigação;
* fontes;
* evidências;
* análises;
* achados;
* validações;
* decisões;
* entregas;
* transição para arquitetura;
* retrospectiva;
* histórico de alterações.

A finalidade desta estrutura é permitir que o trabalho possa ser:

* localizado;
* compreendido;
* continuado;
* revisado;
* auditado;
* protegido;
* encerrado;
* arquivado;
* utilizado como fonte de aprendizagem metodológica.

A pasta não deve funcionar apenas como armazenamento de arquivos.

Ela representa a memória operacional de cada investigação.

---

# 2. Princípios de governança

## 2.1 Um diagnóstico, um registro principal

Todo diagnóstico formal deve possuir:

* um identificador;
* uma pasta;
* um responsável;
* um estado;
* um registro no índice;
* uma fonte oficial de documentos.

Materiais distribuídos em mensagens, computadores pessoais ou plataformas externas não substituem o registro principal.

---

## 2.2 O registro começa antes da coleta

A pasta do diagnóstico deve ser criada quando a demanda for aceita para qualificação formal.

Não é necessário esperar:

* o plano estar aprovado;
* as entrevistas começarem;
* o escopo estar completamente definido.

O início do registro preserva a origem e a evolução da investigação.

---

## 2.3 O diretório oficial deve ser identificável

Deve existir um local definido como fonte oficial.

Cópias utilizadas para:

* revisão;
* exportação;
* apresentação;
* compartilhamento;

devem ser reconhecidas como derivadas.

---

## 2.4 O histórico relevante não deve ser apagado

Correções podem substituir informações incorretas nos documentos vigentes, mas mudanças relevantes devem permanecer registradas por meio de:

* histórico de versões;
* registro de validação;
* registro de decisão;
* arquivo substituído;
* nota de correção.

---

## 2.5 Acesso deve ser proporcional

Nem toda pessoa participante do diagnóstico precisa acessar:

* todas as entrevistas;
* todos os dados;
* documentos sensíveis;
* avaliações internas;
* registros de outras pessoas.

O acesso deve corresponder à:

* finalidade;
* responsabilidade;
* necessidade;
* sensibilidade.

---

## 2.6 O registro deve ser suficiente, sem se tornar excessivo

Devem ser preservados os materiais necessários para:

* reconstruir o trabalho;
* sustentar achados;
* compreender decisões;
* proteger a organização;
* produzir aprendizagem.

Não devem ser acumulados materiais sem finalidade clara.

---

## 2.7 A estrutura pode ser proporcional

Diagnósticos focais podem utilizar estrutura reduzida.

Diagnósticos funcionais ou sistêmicos podem exigir:

* mais subpastas;
* controle de acesso separado;
* arquivos específicos por frente;
* maior detalhamento das fontes.

---

# 3. Estrutura geral da pasta

```text
registros-de-diagnostico/
├── README.md
├── indice-de-diagnosticos.md
└── AAAA/
    └── DIA-AAAA-NNN-nome-do-diagnostico/
```

## Ano

Os diagnósticos devem ser agrupados pelo ano de abertura.

### Exemplo

```text
registros-de-diagnostico/
└── 2026/
```

Se um diagnóstico atravessar mais de um ano, permanece na pasta correspondente ao ano em que foi formalmente aberto.

---

# 4. Identificador do diagnóstico

Utilizar o padrão:

```text
DIA-AAAA-NNN
```

## Componentes

* `DIA`: tipo de registro;
* `AAAA`: ano de abertura;
* `NNN`: número sequencial com três dígitos.

### Exemplos

```text
DIA-2026-001
DIA-2026-002
DIA-2027-001
```

A sequência reinicia a cada ano.

O número não deve ser reutilizado, mesmo quando o diagnóstico for:

* cancelado;
* recusado após qualificação;
* suspenso;
* invalidado;
* encerrado antecipadamente.

---

# 5. Nome da pasta

Utilizar:

```text
DIA-AAAA-NNN-nome-curto-do-diagnostico
```

## Regras

O nome deve:

* começar pelo ID;
* utilizar letras minúsculas;
* utilizar hífens;
* evitar acentos;
* evitar caracteres especiais;
* ser curto;
* representar a questão ou o objeto investigado;
* não expor dados sensíveis desnecessários.

### Exemplos adequados

```text
DIA-2026-001-acompanhamento-comercial
DIA-2026-002-fluxo-de-conteudo
DIA-2026-003-organizacao-do-conhecimento
```

### Exemplos inadequados

```text
diagnostico-novo
problemas-da-empresa
cliente-carol-com-dificuldades
avaliacao-completa-final-agora-v2
```

O nome da pasta não deve conter:

* julgamento;
* hipótese apresentada como fato;
* informação clínica;
* conflito;
* nome de pessoa quando não for necessário;
* conclusão diagnóstica.

---

# 6. Estrutura padrão de um diagnóstico

```text
DIA-AAAA-NNN-nome-do-diagnostico/
├── README.md
├── briefing.md
├── plano-de-investigacao.md
├── matriz-de-evidencias.md
├── fontes/
│   ├── README.md
│   ├── entrevistas/
│   ├── observacoes/
│   ├── documentos/
│   ├── dados/
│   ├── sistemas/
│   └── externas/
├── analises/
│   ├── README.md
│   ├── mapas/
│   ├── ferramentas/
│   └── notas-de-analise/
├── sintese-diagnostica.md
├── registro-de-validacao.md
├── relatorio-final.md
├── transicao-para-arquitetura.md
├── decisoes/
│   └── README.md
├── entregas/
│   └── README.md
├── retrospectiva.md
└── historico.md
```

A estrutura deve ser adaptada conforme a complexidade.

Pastas vazias que não serão utilizadas podem ser omitidas.

---

# 7. Estrutura reduzida para diagnóstico focal

```text
DIA-AAAA-NNN-nome-do-diagnostico/
├── README.md
├── briefing.md
├── plano-de-investigacao.md
├── registros-de-coleta.md
├── matriz-de-evidencias.md
├── sintese-diagnostica.md
├── registro-de-validacao.md
├── transicao-para-arquitetura.md
└── retrospectiva.md
```

A estrutura reduzida pode ser utilizada quando:

* a questão é delimitada;
* existem poucas fontes;
* o risco é baixo;
* a duração é curta;
* não há grande volume de dados;
* a síntese é suficiente como entrega.

Mesmo em estrutura reduzida, devem permanecer:

* identificação;
* escopo;
* evidências;
* validação;
* resultado;
* aprendizagem.

---

# 8. Estrutura ampliada

Diagnósticos sistêmicos podem utilizar:

```text
DIA-AAAA-NNN-nome-do-diagnostico/
├── frentes/
│   ├── FRT-001-identidade-e-direcao/
│   ├── FRT-002-processos-e-operacao/
│   ├── FRT-003-conhecimento-e-informacao/
│   └── FRT-004-tecnologia-e-ia/
├── fontes-restritas/
├── dados-processados/
├── validacoes/
├── relatorios/
└── anexos/
```

A ampliação deve ocorrer quando melhorar:

* clareza;
* controle de acesso;
* rastreabilidade;
* divisão de responsabilidades;
* manutenção.

Não deve ser utilizada apenas para aumentar formalidade.

---

# 9. `README.md` do diagnóstico

Cada pasta deve possuir um `README.md` próprio.

Esse documento funciona como página inicial e mapa do registro.

## Conteúdo mínimo

* ID;
* título;
* organização;
* responsável;
* responsável do cliente;
* data de abertura;
* estado;
* tipo de diagnóstico;
* questão central;
* escopo resumido;
* decisão apoiada;
* nível de sensibilidade;
* documentos principais;
* pendências;
* próxima ação;
* localização de entregas;
* data da última atualização.

## Modelo resumido

```markdown
# DIA-AAAA-NNN — Nome do Diagnóstico

## Identificação

- **Organização:**
- **Responsável pelo diagnóstico:**
- **Responsável do cliente:**
- **Data de abertura:**
- **Estado:**
- **Tipo:**
- **Sensibilidade:**

## Questão central

> [Pergunta]

## Decisão apoiada

[Preencher]

## Escopo

[Preencher]

## Documentos principais

- [Briefing](briefing.md)
- [Plano](plano-de-investigacao.md)
- [Matriz](matriz-de-evidencias.md)
- [Síntese](sintese-diagnostica.md)
- [Validação](registro-de-validacao.md)
- [Relatório](relatorio-final.md)
- [Transição](transicao-para-arquitetura.md)
- [Retrospectiva](retrospectiva.md)

## Estado atual

[Preencher]

## Próxima ação

[Preencher]
```

---

# 10. Arquivos principais

## `briefing.md`

Registra:

* origem da demanda;
* questão preliminar;
* decisão apoiada;
* escopo;
* condições de viabilidade;
* autorização inicial.

## `plano-de-investigacao.md`

Registra:

* perguntas;
* hipóteses;
* fontes;
* métodos;
* cronograma;
* responsabilidades;
* critérios de conclusão.

## `matriz-de-evidencias.md`

Registra:

* fontes;
* evidências;
* interpretações;
* divergências;
* lacunas;
* confiança;
* achados.

## `sintese-diagnostica.md`

Apresenta a compreensão integrada essencial.

## `registro-de-validacao.md`

Registra:

* confirmações;
* correções;
* novas evidências;
* divergências;
* reformulações.

## `relatorio-final.md`

Apresenta o diagnóstico completo, quando necessário.

## `transicao-para-arquitetura.md`

Transfere:

* capacidades;
* problemas;
* riscos;
* restrições;
* requisitos;
* questões abertas.

## `retrospectiva.md`

Registra a aprendizagem produzida pelo trabalho.

---

# 11. Pasta `fontes/`

A pasta `fontes/` preserva os materiais que originaram evidências.

## Estrutura

```text
fontes/
├── README.md
├── entrevistas/
├── observacoes/
├── documentos/
├── dados/
├── sistemas/
└── externas/
```

## `fontes/README.md`

Deve registrar:

* categorias utilizadas;
* regras de identificação;
* restrições de acesso;
* localização de materiais não armazenados no repositório;
* regras de retenção;
* arquivos sensíveis mantidos em ambiente separado.

---

# 12. Entrevistas

## Estrutura sugerida

```text
fontes/entrevistas/
├── ENT-001-funcao-ou-identificador/
│   ├── roteiro.md
│   ├── notas.md
│   ├── sintese.md
│   ├── autorizacao.md
│   └── transcricao.txt
└── ENT-002-funcao-ou-identificador/
```

Nem todos os arquivos são obrigatórios.

## Nomenclatura

```text
ENT-NNN-funcao-ou-identificador
```

Evitar nome completo quando:

* a identificação não for necessária;
* houver risco de exposição;
* o relatório utilizar anonimização.

## Gravações

Gravações não devem ser armazenadas no repositório quando ele não oferecer proteção adequada.

Nesse caso, registrar:

* localização segura;
* responsável;
* prazo de retenção;
* data prevista de exclusão.

---

# 13. Observações

## Estrutura sugerida

```text
fontes/observacoes/
├── OBS-001-processo-observado/
│   ├── ficha.md
│   ├── notas.md
│   └── materiais/
└── OBS-002-reuniao-de-planejamento/
```

## Nomenclatura

```text
OBS-NNN-nome-curto
```

O registro deve preservar:

* data;
* contexto;
* duração;
* participantes;
* limites;
* interferência da observadora;
* relação com questões diagnósticas.

---

# 14. Documentos analisados

## Estrutura sugerida

```text
fontes/documentos/
├── inventario-documental.md
├── DOC-001-referencia-ou-copia/
├── DOC-002-referencia-ou-copia/
└── documentos-restritos.md
```

Quando o documento original estiver em sistema externo, não é necessário duplicá-lo.

Pode ser registrado:

* link;
* caminho;
* proprietário;
* versão;
* data de acesso;
* restrição.

Não devem ser criadas cópias desnecessárias de:

* contratos;
* dados pessoais;
* documentos financeiros;
* materiais confidenciais;
* propriedade intelectual.

---

# 15. Dados

## Estrutura sugerida

```text
fontes/dados/
├── README.md
├── dados-originais/
├── dados-processados/
├── dicionario-de-dados.md
└── analise.md
```

## Separação obrigatória

Quando houver processamento, manter distinção entre:

* dados originais;
* dados limpos;
* dados transformados;
* resultados analíticos.

Os dados originais não devem ser sobrescritos.

## Registro mínimo

* origem;
* período;
* definição;
* campos;
* limitações;
* alterações;
* responsável;
* sensibilidade.

---

# 16. Sistemas

A pasta `fontes/sistemas/` pode registrar:

* capturas autorizadas;
* exportações;
* descrições de configuração;
* logs;
* inventário de ferramentas;
* fluxos;
* permissões;
* limitações.

Credenciais, senhas e chaves não devem ser armazenadas.

---

# 17. Fontes externas

A pasta `fontes/externas/` pode registrar:

* legislação;
* normas;
* estudos;
* pesquisas;
* referências setoriais;
* documentação técnica;
* benchmarks.

Cada fonte deve preservar:

* título;
* autoria ou instituição;
* data;
* link;
* data de acesso;
* finalidade;
* limite de utilização.

---

# 18. Pasta `analises/`

A pasta `analises/` reúne materiais intermediários.

## Pode conter

* mapas;
* comparações;
* análises temáticas;
* agrupamentos;
* avaliações de maturidade;
* SWOT;
* Canvas;
* jornadas;
* mapas de processos;
* notas interpretativas.

## Estrutura

```text
analises/
├── README.md
├── mapas/
├── ferramentas/
└── notas-de-analise/
```

Materiais intermediários não devem ser confundidos com conclusões validadas.

---

# 19. Notas de análise

Notas exploratórias devem ser claramente identificadas.

## Nomenclatura

```text
AAAA-MM-DD-tema-da-nota.md
```

### Exemplo

```text
2026-08-12-padroes-de-transferencia.md
```

A nota deve indicar seu estado:

* exploratória;
* em revisão;
* incorporada;
* descartada;
* substituída.

Interpretações abandonadas podem ser preservadas quando forem relevantes para a aprendizagem ou para reconstruir o raciocínio.

---

# 20. Pasta `decisoes/`

A pasta `decisoes/` reúne registros de decisões relacionadas ao diagnóstico.

## Exemplos

* mudança de escopo;
* aceitação de lacuna;
* suspensão;
* alteração de prazo;
* inclusão de nova fonte;
* autorização de uso de IA;
* aceite de risco;
* passagem para arquitetura.

## Estrutura

```text
decisoes/
├── README.md
├── DEC-AAAA-NNN-titulo.md
└── DEC-AAAA-NNN-titulo.md
```

Os registros devem seguir o Protocolo de Decisão do Módulo 1.

---

# 21. Pasta `entregas/`

Reúne versões enviadas ao cliente ou a outras pessoas autorizadas.

## Estrutura sugerida

```text
entregas/
├── README.md
├── internas/
├── cliente/
├── executivas/
└── anonimizadas/
```

## `entregas/README.md`

Deve registrar:

| Data | Arquivo | Versão | Destinatário | Meio de envio | Sensibilidade |
| ---- | ------- | ------ | ------------ | ------------- | ------------- |
|      |         |        |              |               |               |

A pasta deve preservar o que foi efetivamente entregue, não apenas a versão atualmente editável.

---

# 22. Nomenclatura dos arquivos

Utilizar:

* letras minúsculas;
* hífens;
* nomes claros;
* extensões adequadas;
* identificadores quando houver múltiplos registros.

### Exemplos

```text
briefing.md
plano-de-investigacao.md
ENT-001-roteiro.md
OBS-002-ficha.md
DEC-2026-014-ampliacao-de-escopo.md
2026-08-12-mapa-do-fluxo-atual.png
```

Evitar:

```text
final.md
final-agora.md
novo-final-v2.md
documento-certo.pdf
analise-geral-finalissima.docx
```

---

# 23. Versionamento

## Documentos vivos

Arquivos como:

* briefing;
* plano;
* matriz;
* síntese;
* relatório;
* transição;

podem ser atualizados no mesmo caminho enquanto estiverem em elaboração.

O histórico interno deve registrar alterações relevantes.

## Versões entregues

Versões enviadas devem ser preservadas com identificação.

### Exemplo

```text
entregas/cliente/
├── DIA-2026-001-sintese-v1.0.pdf
└── DIA-2026-001-relatorio-v1.1.pdf
```

## Escala sugerida

* `0.x`: elaboração;
* `1.0`: primeira versão aprovada ou entregue;
* `1.x`: ajustes sem mudança estrutural;
* `2.0`: revisão material ou reabertura relevante.

---

# 24. Fonte oficial

Para cada documento deve existir uma fonte oficial editável.

### Exemplo

```text
sintese-diagnostica.md
```

Exportações em PDF ou outros formatos são versões derivadas.

Quando houver divergência, a fonte oficial deve ser identificada no `README.md` do diagnóstico.

---

# 25. Estados do diagnóstico

## Recebido

Demanda registrada, ainda não qualificada.

## Em qualificação

Briefing em elaboração.

## Aguardando aprovação de escopo

Questão e condições submetidas ao responsável.

## Planejado

Plano de investigação aprovado.

## Em coleta

Fontes estão sendo consultadas.

## Em organização

Registros e evidências estão sendo consolidados.

## Em análise

Hipóteses e relações estão sendo examinadas.

## Aguardando informação

A continuidade depende de fonte ou acesso.

## Em síntese

Achados estão sendo integrados.

## Em validação

Resultados estão sendo confrontados.

## Em revisão

Correções estão sendo incorporadas.

## Entregue

A entrega principal foi realizada.

## Em transição

Requisitos estão sendo transferidos ao Módulo 3.

## Concluído

Critérios de encerramento foram atendidos.

## Concluído com limitações

O diagnóstico foi encerrado com lacunas explícitas.

## Suspenso

A investigação foi interrompida temporariamente.

## Cancelado

A investigação foi encerrada sem conclusão por decisão formal.

## Reaberto

Nova evidência ou mudança relevante exige revisão.

## Arquivado

O registro foi encerrado e transferido para preservação.

---

# 26. Estado oficial

O estado oficial deve ser atualizado em:

1. `README.md` do diagnóstico;
2. `indice-de-diagnosticos.md`.

Quando necessário, também deve aparecer:

* no briefing;
* no plano;
* no registro de validação;
* no histórico.

---

# 27. Abertura de um diagnóstico

## Procedimento

1. verificar o próximo número disponível;
2. criar a pasta do ano, se necessário;
3. criar a pasta do diagnóstico;
4. criar o `README.md`;
5. duplicar o briefing;
6. registrar no índice;
7. definir responsável;
8. classificar sensibilidade inicial;
9. registrar a primeira ação.

## Verificação

* [ ] ID único;
* [ ] nome adequado;
* [ ] ano correto;
* [ ] responsável definido;
* [ ] estado registrado;
* [ ] índice atualizado;
* [ ] acesso inicial configurado.

---

# 28. Diagnósticos recusados após qualificação

Quando uma demanda formalmente registrada for recusada, o registro deve preservar:

* briefing parcial;
* motivo;
* data;
* responsável;
* encaminhamento;
* decisão, quando relevante.

O diagnóstico pode receber estado:

```text
Cancelado — não iniciado
```

ou:

```text
Encerrado após qualificação
```

O ID não deve ser apagado ou reutilizado.

---

# 29. Suspensão

Quando um diagnóstico for suspenso, registrar:

* motivo;
* data;
* condição para retomada;
* riscos;
* pendências;
* responsáveis;
* estado dos dados;
* comunicação realizada.

## Arquivo sugerido

```text
decisoes/DEC-AAAA-NNN-suspensao-do-diagnostico.md
```

---

# 30. Reabertura

Um diagnóstico pode ser reaberto quando:

* surgir nova evidência material;
* o contexto mudar;
* uma decisão exigir aprofundamento;
* uma validação reabrir questão crítica;
* o Módulo 3 devolver a transição;
* for identificado erro relevante.

## Procedimento

1. registrar motivo;
2. atualizar estado;
3. definir novo escopo;
4. revisar plano;
5. preservar versões anteriores;
6. atualizar índice;
7. definir nova data de revisão.

---

# 31. Encerramento

O diagnóstico pode ser encerrado quando:

* as questões essenciais foram tratadas;
* os achados possuem evidências;
* as limitações estão explícitas;
* a validação foi realizada no grau possível;
* as entregas foram registradas;
* a transição foi concluída ou descartada;
* a retrospectiva foi realizada;
* as pendências possuem encaminhamento;
* os dados receberam destinação definida;
* o índice foi atualizado.

## Checklist

* [ ] estado final registrado;
* [ ] síntese concluída;
* [ ] validação registrada;
* [ ] relatório concluído, quando aplicável;
* [ ] entrega preservada;
* [ ] transição concluída, quando aplicável;
* [ ] retrospectiva concluída;
* [ ] decisões relacionadas localizadas;
* [ ] dados sensíveis revisados;
* [ ] retenção definida;
* [ ] `README.md` atualizado;
* [ ] índice atualizado.

---

# 32. Arquivamento

Arquivar não significa apagar.

O arquivamento deve:

* preservar a memória;
* restringir alterações;
* reduzir acessos;
* manter referências;
* registrar localização;
* garantir possibilidade de recuperação.

## Data de arquivamento

Registrar no:

* `README.md`;
* índice;
* histórico.

## Pasta opcional

Quando necessário:

```text
registros-de-diagnostico/
└── arquivo/
```

A movimentação deve preservar o caminho ou atualizar todas as referências.

---

# 33. Retenção

O prazo de retenção deve considerar:

* finalidade;
* contrato;
* obrigação jurídica;
* sensibilidade;
* utilidade metodológica;
* necessidade de continuidade;
* minimização de dados.

## Categorias possíveis

### Registros metodológicos

Podem permanecer por prazo prolongado quando:

* anonimizados;
* úteis para aprendizagem;
* desvinculados de dados desnecessários.

### Dados pessoais e sensíveis

Devem possuir:

* finalidade;
* acesso restrito;
* prazo;
* regra de exclusão;
* responsável.

### Gravações

Devem ser excluídas quando:

* a finalidade for cumprida;
* a transcrição ou síntese tiver sido validada;
* não existir obrigação de preservação.

---

# 34. Exclusão e descarte

Nenhum material deve ser excluído sem verificar:

* se sustenta achado;
* se registra decisão;
* se possui obrigação de retenção;
* se integra entrega;
* se precisa ser preservado para histórico.

## Registro de descarte

| Data | Material | Motivo | Autorização | Responsável |
| ---- | -------- | ------ | ----------- | ----------- |
|      |          |        |             |             |

Quando possível, preservar metadados mínimos do material descartado.

---

# 35. Confidencialidade

Cada diagnóstico deve possuir classificação geral:

* pública;
* interna;
* confidencial;
* sensível.

Arquivos individuais podem possuir classificação mais restrita que a pasta geral.

## Exemplos

* síntese: interna;
* entrevistas: confidenciais;
* dados de saúde: sensíveis;
* apresentação pública: pública.

A classificação mais elevada não precisa bloquear todo o diretório quando for possível separar acessos.

---

# 36. Controle de acesso

## Princípio

Acesso deve ser concedido por necessidade.

## Papéis possíveis

### Responsável pelo diagnóstico

Acesso ao conjunto necessário para condução.

### Responsável do cliente

Acesso aos documentos acordados.

### Participante

Acesso apenas ao que lhe compete revisar ou validar.

### Especialista

Acesso ao material necessário para sua análise.

### Responsável pela arquitetura

Acesso ao pacote de transição, sem necessidade automática de acessar fontes pessoais.

### Administrador de registros

Acesso para organização, não necessariamente para interpretação.

## Matriz

| Pessoa ou função | Pasta ou documento | Tipo de acesso                   | Justificativa |
| ---------------- | ------------------ | -------------------------------- | ------------- |
|                  |                    | Leitura / edição / administração |               |
|                  |                    |                                  |               |

---

# 37. Proteção de identidades

Quando necessário, utilizar:

* função;
* código;
* pseudônimo;
* grupo;
* identificação parcial.

### Exemplos

```text
ENT-001 — fundadora
ENT-002 — responsável operacional
ENT-003 — cliente entrevistada
```

A chave de identificação, quando necessária, deve permanecer em ambiente restrito.

---

# 38. Materiais fora do repositório

Alguns materiais podem permanecer em:

* Google Drive;
* Notion;
* sistema do cliente;
* ferramenta de pesquisa;
* armazenamento protegido;
* ambiente local autorizado.

Nesse caso, o registro deve indicar:

* localização;
* responsável;
* acesso;
* versão;
* data;
* sensibilidade;
* condição de retenção.

Não se deve registrar credenciais.

---

# 39. Uso de inteligência artificial

Quando IA for utilizada no diagnóstico, preservar registros proporcionais de:

* sistema;
* data;
* função;
* fontes fornecidas;
* medidas de proteção;
* saída utilizada;
* revisão humana;
* erros ou limitações.

## Local sugerido

* no documento em que a IA participou;
* em registro consolidado dentro do diagnóstico;
* em anexo restrito, quando necessário.

## Proibição

Saídas de IA não devem ser armazenadas como fontes organizacionais sem identificação de sua natureza.

---

# 40. Histórico do diagnóstico

O arquivo `historico.md` pode registrar os principais eventos.

## Estrutura

| Data | Evento          | Estado anterior | Novo estado     | Responsável |
| ---- | --------------- | --------------- | --------------- | ----------- |
|      | Abertura        | —               | Em qualificação |             |
|      | Plano aprovado  | Em qualificação | Planejado       |             |
|      | Coleta iniciada | Planejado       | Em coleta       |             |

## Eventos relevantes

* abertura;
* aprovação;
* mudança de escopo;
* suspensão;
* retomada;
* validação;
* entrega;
* transição;
* encerramento;
* reabertura;
* arquivamento.

---

# 41. Atualização do índice

O arquivo `indice-de-diagnosticos.md` deve ser atualizado quando houver:

* abertura;
* mudança de título;
* mudança de responsável;
* mudança de estado;
* suspensão;
* cancelamento;
* conclusão;
* reabertura;
* arquivamento.

O índice não deve conter informações sensíveis além do necessário para localização e governança.

---

# 42. Conteúdo mínimo do índice

Cada diagnóstico deve possuir:

* ID;
* título;
* organização ou identificador;
* tipo;
* responsável;
* data de abertura;
* estado;
* sensibilidade;
* próxima ação ou data;
* link para o diretório.

Em registros com maior confidencialidade, a organização pode ser substituída por código.

---

# 43. Verificação periódica

Os registros em andamento devem ser revisados periodicamente.

## Verificar

* estado atualizado;
* próxima ação;
* pendências;
* acessos;
* documentos principais;
* arquivos sem classificação;
* gravações vencidas;
* entregas não registradas;
* diagnósticos parados sem decisão.

## Frequência sugerida

* semanal para diagnósticos ativos;
* mensal para suspensos;
* anual para arquivo, quando necessário.

---

# 44. Diagnóstico sem atividade

Um diagnóstico sem atualização deve ser revisado quando ultrapassar o período definido no plano.

## Encaminhamentos

* retomar;
* solicitar informação;
* suspender;
* cancelar;
* encerrar com limitações.

Não deve permanecer indefinidamente como “em andamento”.

---

# 45. Qualidade do registro

Um registro é considerado adequado quando:

* pode ser localizado;
* possui responsável;
* possui estado;
* contém pergunta e escopo;
* preserva fontes;
* permite rastrear achados;
* registra validação;
* diferencia versões;
* protege dados;
* possui encerramento claro;
* deixa aprendizagem.

---

# 46. Antipadrões

## Pasta sem ID

Dificulta governança e localização.

## Nome baseado em julgamento

Expõe conclusões prematuras.

## Arquivos com “final” no nome

Cria ambiguidade de versão.

## Fontes espalhadas sem referência

Impede rastreabilidade.

## Cópias excessivas

Aumenta risco de divergência e exposição.

## Registros sensíveis no mesmo nível de acesso

Amplia risco desnecessário.

## Exclusão de versões relevantes

Apaga a história da investigação.

## Diagnóstico encerrado sem retrospectiva

Perde aprendizagem metodológica.

## Índice desatualizado

Torna o sistema pouco confiável.

## Pasta ativa sem próxima ação

Oculta paralisação.

---

# 47. Perguntas de controle

Antes de considerar o registro adequadamente organizado, verificar:

1. O diagnóstico possui ID único?
2. A pasta está no ano correto?
3. O nome evita exposição desnecessária?
4. Existe `README.md`?
5. O estado está atualizado?
6. O responsável está definido?
7. A próxima ação está registrada?
8. As fontes podem ser localizadas?
9. Os achados podem ser relacionados às evidências?
10. As versões entregues estão preservadas?
11. Os dados sensíveis estão separados?
12. Os acessos são proporcionais?
13. Existe histórico de decisões relevantes?
14. A validação está registrada?
15. A retenção está definida?
16. O índice está atualizado?
17. O encerramento está claro?
18. A retrospectiva foi realizada?

---

# 48. Invariantes

## Invariante 1

Nenhum diagnóstico formal deve existir sem ID.

## Invariante 2

Nenhum ID deve ser reutilizado.

## Invariante 3

Nenhum diagnóstico ativo deve existir sem responsável.

## Invariante 4

Nenhum diagnóstico deve ser considerado concluído sem estado final registrado.

## Invariante 5

Nenhum achado relevante deve perder sua relação com as fontes.

## Invariante 6

Nenhuma entrega deve substituir silenciosamente a versão anteriormente enviada.

## Invariante 7

Nenhum dado sensível deve permanecer acessível sem necessidade.

## Invariante 8

Nenhuma gravação deve ser preservada indefinidamente sem finalidade.

## Invariante 9

Nenhuma nova evidência material deve ser incorporada sem retornar à matriz.

## Invariante 10

Nenhuma alteração metodológica relevante deve ser incorporada sem registro.

---

# 49. Checklist de abertura

* [ ] Próximo ID verificado
* [ ] Pasta anual existente
* [ ] Pasta do diagnóstico criada
* [ ] Nome revisado
* [ ] `README.md` criado
* [ ] Briefing duplicado
* [ ] Responsável definido
* [ ] Sensibilidade classificada
* [ ] Acessos configurados
* [ ] Índice atualizado
* [ ] Primeira ação registrada

---

# 50. Checklist de encerramento

* [ ] Estado final definido
* [ ] Questão central respondida no grau possível
* [ ] Matriz consolidada
* [ ] Síntese concluída
* [ ] Validação registrada
* [ ] Relatório concluído, quando aplicável
* [ ] Entrega preservada
* [ ] Transição concluída ou descartada
* [ ] Retrospectiva realizada
* [ ] Decisões localizadas
* [ ] Dados revisados
* [ ] Retenção definida
* [ ] Gravações tratadas
* [ ] Acessos revisados
* [ ] Histórico atualizado
* [ ] Índice atualizado
* [ ] Arquivamento definido

---

# 51. Exemplo de estrutura real

```text
registros-de-diagnostico/
└── 2026/
    └── DIA-2026-001-fluxo-de-conteudo/
        ├── README.md
        ├── briefing.md
        ├── plano-de-investigacao.md
        ├── matriz-de-evidencias.md
        ├── fontes/
        │   ├── README.md
        │   ├── entrevistas/
        │   │   ├── ENT-001-fundadora/
        │   │   │   ├── roteiro.md
        │   │   │   ├── notas.md
        │   │   │   └── sintese.md
        │   │   └── ENT-002-responsavel-operacional/
        │   ├── observacoes/
        │   │   └── OBS-001-planejamento-semanal/
        │   ├── documentos/
        │   │   ├── inventario-documental.md
        │   │   └── referencias.md
        │   └── dados/
        ├── analises/
        │   ├── README.md
        │   ├── mapas/
        │   │   ├── fluxo-atual.md
        │   │   └── fluxo-de-informacao.md
        │   └── notas-de-analise/
        ├── sintese-diagnostica.md
        ├── registro-de-validacao.md
        ├── relatorio-final.md
        ├── transicao-para-arquitetura.md
        ├── decisoes/
        │   ├── README.md
        │   └── DEC-2026-014-ampliacao-de-escopo.md
        ├── entregas/
        │   ├── README.md
        │   └── cliente/
        │       └── DIA-2026-001-sintese-v1.0.pdf
        ├── retrospectiva.md
        └── historico.md
```

---

# 52. Princípio de encerramento

Os registros de diagnóstico existem para preservar mais do que arquivos.

Eles preservam:

* a origem de uma pergunta;
* as condições de uma investigação;
* a proveniência das evidências;
* a evolução das hipóteses;
* os limites das conclusões;
* as decisões tomadas;
* as versões entregues;
* a aprendizagem produzida.

Um diagnóstico pode terminar.

A capacidade de compreender como ele foi construído deve permanecer.

C
