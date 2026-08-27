# Dashboard Vision One — Faturamento Bradesco

## 📊 Visão Geral

Dashboard interativo de análise de faturamento para a Cadeia de Faturamento Vision One. Apresenta análise consolidada de **27.484 guias** do período mai–jul/2026, com foco em operações, convênios, glosas e responsáveis.

## ✨ Características

- **🚀 100% Offline** — Funciona completamente offline, sem dependência de internet ou CDN
- **📦 Autocontido** — Um único arquivo `.html` com todos os recursos embutidos
- **📈 Interativo** — Gráficos responsivos com Chart.js, tabelas e filtros dinâmicos
- **🎨 Design Moderno** — Interface dark-mode premium com animações suaves
- **📱 Responsivo** — Adapta-se a desktops, tablets e dispositivos móveis
- **⚡ Rápido** — Sem dependências externas, carrega instantaneamente

## 📋 Conteúdo

### Seções do Dashboard

1. **Visão Financeira**
   - Evolução mensal: Faturamento Bruto vs. Líquido + Taxa de Glosa
   - Faturamento por Convênio/Plano Bradesco (9 variantes)

2. **Operação por Unidade e Serviço**
   - Faturamento por Unidade Hospitalar (10 unidades)
   - Top 10 Procedimentos Faturados

3. **Glosas e Recebimento**
   - Glosas por Estágio do Recurso
   - Taxa de Glosa ao Longo do Tempo
   - Status de Recebimento das Guias

4. **Responsáveis pelo Faturamento**
   - Top 5 Responsáveis por Volume Faturado

5. **Resumo Mensal Detalhado**
   - Tabela com dados consolidados por mês

## 📊 Dados

Todos os dados estão embutidos no arquivo e extraídos da base **Cadeia de Faturamento Vision One**:

- **Período**: Maio – Julho 2026
- **Total de Guias**: 27.484
- **Faturamento Bruto**: R$ 4.772.875,81
- **Faturamento Líquido**: R$ 4.763.723,99
- **Total de Glosas**: R$ 9.151,82 (0,19% do bruto)

## 🚀 Como Usar

1. **Baixe** o arquivo `Dashboard_Faturamento_Vision_One.html`
2. **Abra** em qualquer navegador (Chrome, Firefox, Safari, Edge, etc.)
3. **Explore** os dados com os filtros e gráficos interativos

### Funcionalidades Interativas

- **Filtro de Período**: Visualize dados de "Trimestre", "Maio", "Junho" ou "Julho"
- **Gráficos Interativos**: Passe o mouse para ver valores detalhados
- **Tooltips**: Clique nos elementos para mais informações

## 🔧 Estrutura Técnica

### Tecnologias

- **HTML5** — Estrutura semântica
- **CSS3** — Estilos com variáveis CSS (dark-mode por padrão)
- **Chart.js v4.4.4** — Gráficos embutidos (minificado)
- **Vanilla JavaScript** — Sem dependências externas

### Validações

✅ Nenhuma chamada HTTP externa  
✅ Nenhuma dependência de CDN  
✅ Nenhuma font externa (usa system fonts)  
✅ Arquivo único e autocontido  
✅ Tags HTML/CSS/JS balanceadas  
✅ Tamanho: ~70 KB  

## 📂 Arquivo

- **Nome**: `Dashboard_Faturamento_Vision_One.html`
- **Tamanho**: ~70 KB
- **Formato**: HTML5 (single file)
- **Compatibilidade**: Todos os navegadores modernos

## 🧰 DataHub Pro Offline

O arquivo `DataHub_Pro_Offline.html` é uma ferramenta genérica para trabalhar com novas bases localmente:

- Importação de arquivos `.csv`, `.xlsx` e `.xls`
- Filtros dinâmicos por coluna
- Geração de gráficos de barras, linhas e pizza
- Exportação dos dados filtrados em CSV, JSON ou HTML
- Execução 100% offline, sem CDN ou chamadas externas

Para usar, abra o arquivo no navegador, carregue a planilha e selecione as colunas e filtros desejados.

## 📊 Dashboard Vision One

O arquivo `Dashboard_Brad (1).html` reproduz o dashboard executivo encaminhado, com KPIs, gráficos financeiros, operação por unidade, glosas, recebimento, responsáveis e resumo mensal. O Chart.js está embutido no próprio arquivo e os dados são os agregados da base Vision One.

## 📝 Dados Consolidados

### Faturamento por Mês

| Mês | Guias | Bruto | Glosa | Líquido | Taxa |
|-----|-------|-------|-------|---------|------|
| Mai/26 | 8.777 | R$ 1.527.034,57 | R$ 9.151,82 | R$ 1.517.882,75 | 0,60% |
| Jun/26 | 8.066 | R$ 1.413.523,51 | R$ 0,00 | R$ 1.413.523,51 | 0,00% |
| Jul/26 | 10.639 | R$ 1.832.317,73 | R$ 0,00 | R$ 1.832.317,73 | 0,00% |
| **Total** | **27.484** | **R$ 4.772.875,81** | **R$ 9.151,82** | **R$ 4.763.723,99** | **0,19%** |

### Top Convênios

1. BRADESCO SAÚDE (SP) — R$ 3.507.539,51 (73,5%)
2. BRADESCO OPERADORA (SP) — R$ 608.243,75 (12,7%)
3. BRADESCO SAÚDE (LASER) — R$ 309.225,00 (6,5%)

### Top Unidades

1. HPAUL — R$ 1.914.244,33 (40,1%)
2. HABC — R$ 1.101.705,73 (23,1%)
3. SAMARO — R$ 662.885,99 (13,9%)

### Top Procedimentos

1. Consulta Eletiva — R$ 1.892.893,55
2. Consulta Médica Especializada — R$ 1.161.192,19
3. Consulta de Urgência — R$ 663.143,74

## 📧 Contato

Para dúvidas ou sugestões sobre o dashboard, entre em contato.

---

**Gerado em**: 26/08/2026  
**Base**: Cadeia de Faturamento Vision One  
**Status**: ✅ 100% Offline | 🚀 Autocontido | 📊 Em Produção
