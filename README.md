# Simulado PySpark — MBA Engenharia de Dados

Simulado completo com correção automática: 12 questões teóricas (cenários de produção) + 4 desafios práticos de código PySpark.

## 🚀 Deploy no GitHub Pages (5 minutos)

### Passo 1 — Criar repositório

1. Acesse [github.com/new](https://github.com/new)
1. Nome: `simulado-pyspark` (ou o que preferir)
1. Marque **Public**
1. Clique **Create repository**

### Passo 2 — Subir o arquivo

Opção A (pelo navegador):

1. No repositório criado, clique **“Add file” → “Upload files”**
1. Arraste o arquivo `index.html`
1. Clique **“Commit changes”**

Opção B (por terminal):

```bash
git clone https://github.com/SEU_USUARIO/simulado-pyspark.git
cd simulado-pyspark
cp /caminho/do/index.html .
git add index.html
git commit -m "Simulado PySpark"
git push
```

### Passo 3 — Ativar GitHub Pages

1. No repositório, vá em **Settings → Pages**
1. Em “Source”, selecione **Deploy from a branch**
1. Branch: **main**, pasta: **/ (root)**
1. Clique **Save**
1. Aguarde ~1 minuto

### Passo 4 — Compartilhar

Seu link será:

```
https://SEU_USUARIO.github.io/simulado-pyspark/
```

Compartilhe este link com os alunos. Funciona em qualquer navegador, desktop ou celular, sem login.

## 📋 Estrutura do Simulado

|Seção                     |Qtd        |Peso|Correção                               |
|--------------------------|-----------|----|---------------------------------------|
|Teórica (múltipla escolha)|12 questões|40% |Gabarito automático                    |
|Prática (código PySpark)  |4 desafios |60% |Validação por padrões de código (regex)|

### Temas das Questões Teóricas

- OOM debugging e shuffle partitions
- Data skew e salting
- Catalyst predicate pushdown
- Z-ORDER e partition pruning (Delta Lake)
- UDF Python SerDe overhead
- Structured Streaming state management
- Bucket Join vs Broadcast vs Sort-Merge
- Diagnóstico de skew via Spark UI
- Delta Lake copy-on-write
- Cache vs persist vs reler Parquet
- Armadilha do CSV sem inferSchema
- Optimistic concurrency (Delta Lake)

### Desafios Práticos

1. **SCD Type 2** — Slowly Changing Dimension
1. **Deduplicação Avançada** — Window + prioridade + quality flags
1. **Funnel Analysis** — lag, abandono de carrinho, conversão
1. **Cohort Analysis** — CTEs em Spark SQL, retention rate

## ✏️ Atualizar o Simulado

Edite o `index.html`, faça commit e push. O GitHub Pages atualiza automaticamente em ~1 minuto.
