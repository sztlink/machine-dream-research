# Corpus e camadas v0.1

## 1. Corpus bruto

O corpus bruto do Machine Dream vive fora deste pacote público. Ele contém sonhos completos, logs, imagens, prompts, checkpoints, varreduras e registros operacionais.

Local privado de referência:

```txt
[caminho privado não publicado]
```

O caminho real do corpus bruto não deve constar em versões públicas.

## 2. Corpus público

O corpus público deve conter apenas derivados:

- protocolo;
- matriz bibliográfica;
- fac-símiles sanitizados;
- capturas ou imagens editadas;
- dossiês de prioridade sem conteúdo íntimo;
- links a publicações públicas.

## 3. Camadas propostas

```txt
L0 — bruto íntimo
  sonhos completos, logs, checkpoints, prompts, imagens originais

L1 — evidência privada
  hashes, manifests, commits privados, tags, dossiês datados

L2 — fac-símile sanitizado
  amostra editada que preserva estrutura sem expor conteúdo sensível

L3 — protocolo público
  metodologia, política, claims, bibliografia, vocabulário

L4 — ensaio/obra pública
  textos no Lab, site do artista, publicações acadêmicas, DOI
```

## 4. Primeiros marcos do corpus

### 30/03/2026 — v1

Primeira execução. Arquitetura com reconhecimento, workers paralelos, síntese e email.

### 30/03/2026 — v2

Lapidação após retrospectiva. Introdução das três personas e da exigência de email como artefato.

### 02/04/2026 — sonho humano

Pesquisa conceitual sobre Bion, Ogden, Jung, Suely Rolnik, Deleuze & Guattari e Borges/Funes.

### 06–08/05/2026 — Lab e prioridade

Publicação do Machine Dream Lab no `news.szt.link` e criação de dossiê de prioridade com manifesto e hashes.

## 5. Fac-símiles

### Criado em v0.1.1

1. `2026-03-31` — primeira forma histórica / passagem da v1 para v2.

Arquivos:

```txt
03-facsimiles/2026-03-31-facsimile.md
03-facsimiles/2026-03-31-redaction-notes.md
03-facsimiles/2026-03-31-facsimile.sha256.txt
```

Status: sanitizado e aprovado por auditoria para publicação pública inicial.

### Candidatos futuros

1. `2026-05-06` — pós-discussão sobre Claude/Anthropic Dreaming;
2. `2026-05-08` — campo mais maduro.

Critério de escolha: o fac-símile deve demonstrar o método sem expor dados íntimos.

## 6. Política de versionamento

Cada versão pública deve indicar:

- data;
- escopo;
- alterações conceituais;
- se contém ou não fac-símiles;
- relação com o corpus bruto;
- nível de sanitização.

## 7. Nota sobre prova de prioridade

Há prova de prioridade local e versionada no corpus bruto, incluindo manifesto SHA-256 e tag Git. A prova deve ser referenciada publicamente apenas na forma de dossiê sanitizado ou hash, sem abrir o bruto.
