# Desafio Criativo: Simplificando Tarefas e Ganhando Foco com IA

## Passo 1: Intenção

Quero que a IA gere uma triagem seca de prioridades diárias para um dono de comércio físico que atende no balcão e cuida da gestão da loja, com o objetivo de filtrar o que realmente coloca dinheiro no caixa ou destrava a operação hoje e jogar o resto para depois.

---

## Passo 2: Contexto e Restrições

Considere o seguinte contexto: o gestor trabalha em loja física com interrupções constantes no balcão, telefone e WhatsApp, e só consegue separar no máximo 2 horas reais de foco no dia para resolver pendências de gestão, compras ou financeiro. O conteúdo deve ter formato de lista numerada com no máximo 3 ações obrigatórias para o dia, uma fila curta de espera para o que foi cortado hoje e um bloco final com o primeiro passo de 10 minutos de cada ação. Evite frases motivacionais, elogios artificiais, teorias de produtividade ou listas gigantes que não cabem no relógio.

---

## Passo 3: Prompt Final Unificado

```text
Quero que você gere uma triagem seca de prioridades diárias para um dono de comércio físico que atende no balcão e cuida da gestão da loja, com o objetivo de filtrar o que realmente coloca dinheiro no caixa ou destrava a operação hoje e jogar o resto para depois.

Considere o seguinte contexto: eu trabalho em loja física com interrupções constantes no balcão, telefone e WhatsApp, e só consigo separar no máximo 2 horas reais de foco no dia para resolver pendências de gestão, compras ou financeiro.

A resposta deve seguir exatamente este formato:
1. No máximo 3 ações obrigatórias para hoje (escolhidas pelo impacto direto em caixa, margem ou operação travada), já com o tempo estimado de cada uma somando no máximo 2 horas.
2. Para cada uma das 3 ações, qual é o primeiro passo prático de 10 minutos para começar sem pensar demais.
3. Lista de corte: tudo o que eu mandei e não entrou nas 3 prioridades de hoje, com o motivo seco do corte.

Evite frases motivacionais, elogios artificiais, jargão de consultor ou listas gigantes que não cabem no relógio real.

Aqui estão minhas pendências de hoje para você filtrar:
[COLE SUA LISTA BRUTA AQUI]
```
