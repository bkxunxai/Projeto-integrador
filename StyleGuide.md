
--------------------------------------------------------------------------------
# 🎨 Style Guide - AgroVision Pro

Este guia define os padrões visuais e componentes de interface para garantir a consistência do ecossistema AgroVision Pro. O design foi projetado sob os princípios do **Design Thinking**, focando na acessibilidade para o produtor rural.

---

## 1. Identidade Visual
O conceito visual baseia-se na **confiança, tecnologia e simplicidade**. A interface utiliza uma hierarquia clara para evitar a "bagunça" visual relatada pelo usuário final.

---

## 2. Paleta de Cores
As cores foram selecionadas para fornecer feedback semântico imediato sobre a saúde da lavoura e a situação financeira.

### 🟢 Cores Primárias e de Marca
| Cor | Hex | Aplicação |
| :--- | :--- | :--- |
| **Verde Floresta** | `#2E7D32` | Botões de ação principal, ícones de marca e estados saudáveis. |
| **Branco Puro** | `#FFFFFF` | Fundos de tela e cards para garantir layout limpo. |
| **Cinza Neve** | `#F5F5F5` | Fundos secundários e separadores sutis. |

### ⚠️ Cores Semânticas (Status)
| Cor | Hex | Significado |
| :--- | :--- | :--- |
| **Vermelho Alerta** | `#D32F2F` | Pragas críticas, risco de geada ou prejuízo financeiro. |
| **Amarelo Atenção** | `#FBC02D` | Pragas em nível moderado ou alertas de clima médio. |
| **Verde Sucesso** | `#4CAF50` | Tarefa concluída, lucro acima da meta ou planta saudável. |

---

## 3. Tipografia
Prioriza a **alta legibilidade (RNF01)** em dispositivos móveis sob luz solar.

*   **Família:** Sans-serif (ex: Inter, Roboto ou Open Sans).
*   **Títulos:** 24px - 32px | Peso: **Bold (700)** | Cor: `#1A1A1A`.
*   **Subtítulos:** 18px - 20px | Peso: **SemiBold (600)** | Cor: `#4D4D4D`.
*   **Corpo de Texto:** 14px - 16px | Peso: **Regular (400)** | Cor: `#333333`.

---

## 4. Componentes de Interface (UI)

### 🔘 Botões
Conforme o requisito **RNF01**, todos os botões devem ser **expandidos** para facilitar o toque no campo.

*   **Botão Primário:**
    *   Fundo: Verde Floresta.
    *   Texto: Branco (Bold).
    *   Raio da Borda (Corner Radius): `12px`.
    *   Altura Mínima: `56px` (Touch Target otimizado).
*   **Botão de Filtro/Secundário:**
    *   Fundo: Cinza Neve ou transparente com borda.
    *   Texto: Verde Floresta.
    *   Raio da Borda: `24px` (Estilo Pill).

### 🗂️ Cards e Dashboards
Utilizados para agrupar informações relacionadas (Clima, Financeiro, Pragas).
*   **Borda:** `1px` sólido ou sombra suave (*Soft Shadow*).
*   **Raio da Borda:** `16px`.
*   **Padding Interno:** `16px` a `24px` para evitar poluição visual.

### 📍 Iconografia
*   **Estilo:** Figurativo e linear.
*   **Navegação:** Trator (Culturas), Gráfico (Financeiro), Estetoscópio (Diagnóstico), Nuvem (Clima).

---

## 5. Elementos Gráficos
*   **Gráficos Financeiros (RF02):** Uso de gráficos de rosca para distribuição de custos e barras para receitas vs despesas.
*   **Diagnóstico por IA (RF09):** Overlay de escaneamento visual sobre a imagem da planta com indicador de porcentagem de confiança.

---

## 6. Regras de Layout
1.  **Regra de Poucos Cliques:** Toda funcionalidade essencial deve ser acessível em no máximo 3 toques a partir do Dashboard.
2.  **Espaçamento Negativo:** Uso generoso de espaços em branco para manter o layout limpo e facilitar a digitalização visual.
3.  **Modo Offline (RNF02):** Indicador visual discreto deve aparecer quando o sistema estiver operando sem internet.

---
**Nota:** Este documento refere-se ao protótipo visual desenvolvido no Figma e serve como especificação para futuras implementações funcionais.
