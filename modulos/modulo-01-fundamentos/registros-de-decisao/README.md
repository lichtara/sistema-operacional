# Registros de Decisão

## Sistema Operacional do Estúdio LICHTARA

**Módulo:** 1 — Fundamentos
**Função:** Memória institucional das decisões
**Documento de referência:** `../protocolo-de-decisao.md`
**Template:** `../templates/registro-de-decisao.md`

---

## 1. Finalidade

Este diretório armazena os registros formais das decisões do Estúdio LICHTARA.

Cada registro deve permitir compreender:

* que situação originou a decisão;
* qual problema estava sendo tratado;
* quais evidências estavam disponíveis;
* quais hipóteses foram adotadas;
* quais alternativas foram consideradas;
* que escolha foi realizada;
* quem respondeu pela escolha;
* como ela foi executada;
* quais resultados foram observados;
* que aprendizado foi incorporado ao sistema.

Os registros não existem apenas para arquivamento.

Eles constituem a memória decisória do Estúdio e devem apoiar:

* continuidade;
* rastreabilidade;
* revisão;
* aprendizagem;
* prevenção de contradições;
* aperfeiçoamento do Sistema Operacional.

---

## 2. Quando criar um registro

Deve ser criado um registro quando a escolha:

* comprometer recursos;
* definir direção;
* afetar clientes;
* alterar um processo;
* introduzir uma ferramenta;
* criar uma automação;
* implantar inteligência artificial;
* alterar responsabilidades;
* produzir risco relevante;
* criar compromisso recorrente;
* estabelecer exceção;
* exigir acompanhamento posterior.

Tarefas rotineiras já autorizadas por uma decisão ou processo existente não precisam gerar um novo registro.

---

## 3. Antes de registrar

Antes de criar o arquivo, consultar:

1. `../protocolo-de-decisao.md`;
2. `../teste-de-coerencia.md`;
3. `indice-de-decisoes.md`.

O índice deve ser verificado para evitar:

* registros duplicados;
* decisões contraditórias;
* repetição de análises já realizadas;
* criação de novo registro quando uma decisão anterior deveria ser reaberta.

---

## 4. Como criar um registro

### Passo 1 — Definir o identificador

Utilizar o padrão:

```text
DEC-AAAA-NNN
```

Onde:

* `DEC` identifica um registro de decisão;
* `AAAA` representa o ano;
* `NNN` representa a sequência anual.

### Exemplos

```text
DEC-2026-001
DEC-2026-002
DEC-2027-001
```

A numeração deve ser sequencial dentro de cada ano.

Identificadores não devem ser reutilizados, mesmo quando uma decisão for cancelada, rejeitada ou excluída da execução.

---

### Passo 2 — Duplicar o template

Copiar:

```text
../templates/registro-de-decisao.md
```

para a pasta correspondente ao ano.

Não preencher ou alterar diretamente o template-mestre.

---

### Passo 3 — Nomear o arquivo

Utilizar o padrão:

```text
AAAA-MM-DD-DEC-AAAA-NNN-nome-da-decisao.md
```

### Exemplo

```text
2026-08-01-DEC-2026-001-adocao-de-ferramenta-de-gestao.md
```

Regras para o nome:

* utilizar letras minúsculas;
* não utilizar acentos;
* separar palavras por hífen;
* manter o título curto e identificável;
* incluir o mesmo ID registrado no documento.

---

### Passo 4 — Atualizar o índice

Adicionar a decisão ao arquivo:

```text
indice-de-decisoes.md
```

A decisão deve ser incluída no índice assim que for registrada, sem esperar pela aprovação ou encerramento.

---

## 5. Estrutura de diretórios

Os registros devem ser organizados por ano.

```text
registros-de-decisao/
├── README.md
├── indice-de-decisoes.md
├── 2026/
│   ├── 2026-08-01-DEC-2026-001-exemplo.md
│   └── 2026-08-15-DEC-2026-002-exemplo.md
└── 2027/
    └── 2027-01-10-DEC-2027-001-exemplo.md
```

Pastas anuais devem ser criadas conforme a necessidade.

---

## 6. Índice central

O arquivo `indice-de-decisoes.md` deve conter, no mínimo:

| ID           | Data       | Título  | Caminho | Estado     | Responsável | Revisão    | Registro                 |
| ------------ | ---------- | ------- | ------- | ---------- | ----------- | ---------- | ------------------------ |
| DEC-2026-001 | 01/08/2026 | Exemplo | Padrão  | Em análise | Nome        | 01/09/2026 | [Abrir](2026/arquivo.md) |

O índice deve ser atualizado quando houver mudança em:

* título;
* caminho;
* estado;
* responsável;
* data de revisão;
* localização do arquivo.

---

## 7. Caminhos de decisão

Cada registro deve indicar um dos caminhos definidos no Protocolo de Decisão.

### Rápido

Para decisões de:

* baixo impacto;
* baixo risco;
* fácil reversão;
* pequena abrangência.

Pode utilizar apenas as seções essenciais do template.

### Padrão

Para decisões com:

* impacto moderado;
* custo ou dependência relevante;
* efeito sobre clientes ou processos;
* necessidade de implantação estruturada.

Exige preenchimento completo das seções aplicáveis.

### Crítico

Para decisões de:

* alto impacto;
* baixa reversibilidade;
* risco elevado;
* uso de dados sensíveis;
* efeito sobre identidade ou fundamentos;
* participação relevante de IA;
* possível dano humano, ético, jurídico, financeiro ou reputacional.

Exige análise crítica, revisão adicional e plano de contingência.

---

## 8. Estados permitidos

Os estados utilizados nos registros e no índice são:

| Estado                     | Utilização                                          |
| -------------------------- | --------------------------------------------------- |
| **Registrada**             | A decisão foi aberta e possui contexto inicial.     |
| **Em triagem**             | O caminho está sendo definido.                      |
| **Em análise**             | Evidências e alternativas estão sendo estudadas.    |
| **Aguardando informação**  | Faltam informações necessárias.                     |
| **Aguardando consulta**    | Depende de contribuição externa ou especializada.   |
| **Aguardando aprovação**   | Está pronta para decisão.                           |
| **Aprovada**               | Pode seguir para execução.                          |
| **Aprovada com condições** | Pode avançar mediante condições registradas.        |
| **Em experimentação**      | Está sendo testada em escala limitada.              |
| **Adiada**                 | Não será decidida ou executada neste momento.       |
| **Em reformulação**        | A solução precisa ser redesenhada.                  |
| **Rejeitada**              | Não deve prosseguir nas condições avaliadas.        |
| **Em execução**            | Está sendo implementada.                            |
| **Em verificação**         | Os resultados estão sendo analisados.               |
| **Encerrada**              | O ciclo foi concluído e o aprendizado registrado.   |
| **Reaberta**               | Novas evidências exigem nova análise.               |
| **Substituída**            | Outra decisão passou a cumprir sua função.          |
| **Cancelada**              | A necessidade deixou de existir antes da conclusão. |

O estado registrado no arquivo deve corresponder ao estado exibido no índice.

---

## 9. Regras de preenchimento

### Registrar o que era conhecido no momento

O documento deve preservar o raciocínio disponível quando a decisão foi tomada.

Informações posteriores não devem ser apresentadas como se fossem conhecidas desde o início.

---

### Diferenciar tipos de informação

Sempre que possível, distinguir:

* fatos;
* interpretações;
* hipóteses;
* lacunas;
* incertezas aceitas.

---

### Registrar alternativas reais

Decisões dos caminhos padrão e crítico devem considerar mais de uma possibilidade, incluindo a não intervenção quando pertinente.

---

### Nomear responsáveis humanos

Toda decisão deve possuir uma responsável humana.

A inteligência artificial não pode ser registrada como:

* responsável final;
* aprovadora;
* titular do risco;
* autoridade ética;
* responsável perante cliente ou organização.

---

### Registrar condições e riscos

Decisões aprovadas com condições devem informar:

* quais condições são obrigatórias;
* quem responde por elas;
* quando precisam ser cumpridas;
* o que acontece em caso de descumprimento.

---

### Definir verificação

Toda decisão relevante deve indicar:

* resultado esperado;
* evidência de sucesso;
* responsável pela verificação;
* data ou condição de revisão.

---

## 10. Participação da inteligência artificial

Quando a IA participar materialmente da análise, decisão ou execução, registrar:

* sistema ou agente utilizado;
* função desempenhada;
* informações fornecidas;
* limitações relevantes;
* responsável humano pela revisão;
* forma de verificação das saídas.

Não devem ser reproduzidos no registro dados sensíveis desnecessários.

O registro deve descrever as categorias de dados utilizadas, preservando confidencialidade e minimização.

---

## 11. Atualização dos registros

O mesmo arquivo deve acompanhar o ciclo completo da decisão.

Ele pode ser atualizado durante:

* análise;
* aprovação;
* execução;
* verificação;
* encerramento;
* reabertura.

Cada alteração relevante deve ser incluída no histórico do próprio registro.

Não apagar:

* alternativas descartadas;
* hipóteses rejeitadas;
* riscos inicialmente identificados;
* decisões anteriores;
* resultados inesperados.

Correções factuais podem ser realizadas, desde que a mudança fique registrada quando afetar a compreensão da decisão.

---

## 12. Reabertura

Uma decisão deve ser reaberta quando:

* surgirem novas evidências;
* o contexto mudar;
* uma hipótese central se mostrar incorreta;
* o resultado deixar de se sustentar;
* uma condição obrigatória for violada;
* surgir risco relevante;
* a solução precisar de alteração substancial.

Ao reabrir:

1. alterar o estado para `Reaberta`;
2. registrar o motivo;
3. preservar a decisão anterior;
4. definir nova análise;
5. atualizar o índice;
6. decidir se o mesmo registro será continuado ou se uma nova decisão vinculada será criada.

---

## 13. Substituição

Quando uma decisão posterior substituir outra:

* o registro anterior deve permanecer preservado;
* seu estado deve ser alterado para `Substituída`;
* o ID da nova decisão deve ser informado;
* a nova decisão deve citar o registro anterior;
* o índice deve mostrar a relação entre ambas.

---

## 14. Encerramento

Uma decisão somente deve ser encerrada quando:

* [ ] foi executada ou formalmente interrompida;
* [ ] os resultados foram verificados;
* [ ] as condições foram revisadas;
* [ ] os riscos foram avaliados;
* [ ] o aprendizado foi registrado;
* [ ] os documentos afetados foram atualizados;
* [ ] o índice central foi atualizado;
* [ ] não existem pendências sem responsável.

Produzir o entregável não significa, por si só, encerrar a decisão.

---

## 15. Registros de clientes

Decisões relacionadas a clientes devem preservar:

* confidencialidade;
* minimização de dados;
* autoria;
* limites de acesso;
* responsabilidades do Estúdio;
* responsabilidades do cliente.

Quando possível, o registro interno deve utilizar descrições suficientes para a governança sem reproduzir informações pessoais ou sensíveis desnecessárias.

A aprovação do cliente deve ser vinculada ao registro quando a decisão afetar:

* identidade;
* estratégia;
* recursos;
* dados;
* operação;
* escopo;
* responsabilidade;
* investimento.

---

## 16. Registros não devem ser excluídos por conveniência

Registros de decisões rejeitadas, canceladas, substituídas ou malsucedidas continuam possuindo valor institucional.

Eles ajudam a compreender:

* caminhos já investigados;
* hipóteses rejeitadas;
* riscos observados;
* mudanças de contexto;
* evolução do pensamento;
* origem dos protocolos atuais.

Quando houver necessidade legítima de remoção por privacidade, segurança ou obrigação jurídica, a exclusão deve ser documentada de forma compatível com a situação.

---

## 17. Revisão periódica do índice

O índice deve ser revisado periodicamente para identificar:

* decisões sem responsável;
* decisões sem data de revisão;
* aprovações condicionais pendentes;
* decisões paralisadas;
* experimentos sem conclusão;
* registros prontos para encerramento;
* decisões que precisam ser reabertas;
* contradições entre decisões vigentes.

Na fase inicial do Estúdio, recomenda-se realizar essa revisão mensalmente.

---

## 18. Síntese operacional

Para registrar uma decisão:

1. verificar se já existe decisão relacionada;
2. atribuir o próximo ID disponível;
3. duplicar o template;
4. nomear o arquivo corretamente;
5. preencher a identificação e a situação;
6. classificar o caminho;
7. realizar a análise proporcional;
8. aplicar o Teste de Coerência;
9. registrar a decisão final;
10. acompanhar a execução;
11. verificar o resultado;
12. registrar o aprendizado;
13. atualizar o índice;
14. encerrar, reabrir ou substituir.

O valor deste diretório não está na quantidade de documentos produzidos.

Está na capacidade de reconstruir decisões, aprender com seus efeitos e impedir que o conhecimento organizacional desapareça.

