# 📋 Documento de Requisitos - AgroVision Pro

Este documento define as capacidades (funcionais) e as restrições (não-funcionais) do sistema **AgroVision Pro**, servindo como base para o desenvolvimento do protótipo e futura implementação.

---

## 🚀 1. Requisitos Funcionais (RF)
Os requisitos funcionais descrevem as ações que o sistema deve ser capaz de executar para atender às necessidades do produtor rural.

| ID | Requisito | Descrição Detalhada | Prioridade |
| :--- | :--- | :--- | :--- |
| **RF01** | **Autenticação** | O sistema deve permitir o registro e login de usuários para salvaguarda de informações personalizadas [2]. | Essencial |
| **RF02** | **Gestão Financeira** | O sistema deve calcular o lucro líquido subtraindo custos de insumos e manutenção da receita da colheita [2]. | Essencial |
| **RF03** | **Mapa de Produtividade** | O usuário deve conseguir marcar e visualizar as áreas da fazenda que renderam maior volume de sacas [2]. | Desejável |
| **RF04** | **Histórico de Pragas** | O sistema deve manter um registro temporal de infestações passadas para consulta e análise preditiva [2]. | Importante |
| **RF05** | **Registro de Aplicações** | O sistema deve permitir o registro detalhado de defensivos utilizados, incluindo data e local da aplicação [2]. | Essencial |
| **RF06** | **Cadastro de Culturas** | O sistema deve permitir o registro de diferentes tipos de cultura (ex: Soja, Milho, Feijão, Tabaco) [5]. | Essencial |
| **RF07** | **Priorização de Manejo** | Opção para selecionar quais culturas devem receber indicações de manejo com maior frequência [5]. | Importante |
| **RF08** | **Cotação de Mercado** | Aba destinada à visualização de preços de insumos e produtos de empresas registradas na região [5]. | Importante |
| **RF09** | **Diagnóstico por IA** | Função de captura e envio de imagens para obter diagnóstico automatizado da saúde da planta [5]. | Essencial |
| **RF10** | **Monitoramento Climático** | Visualização da previsão do tempo em tempo real e previsões futuras para planejamento de campo [6]. | Essencial |

---

## 🛠️ 2. Requisitos Não-Funcionais (RNF)
Os requisitos não-funcionais definem os critérios de qualidade e as restrições operacionais do sistema.

| ID | Categoria | Descrição Detalhada |
| :--- | :--- | :--- |
| **RNF01** | **Usabilidade** | A interface deve possuir botões expandidos e tipografia de alta legibilidade para facilitar o uso por pessoas com dificuldades digitais [6]. |
| **RNF02** | **Disponibilidade** | O sistema deve permitir o registro de dados em modo offline, realizando a sincronização automática assim que houver sinal de rede [6]. |
| **RNF03** | **Desempenho** | Os cálculos de rentabilidade e lucro devem ser processados e exibidos em menos de 2 segundos [6]. |
| **RNF04** | **Atualização** | O banco de dados técnico deve ser atualizado frequentemente para garantir a precisão das recomendações de manejo [6]. |
| **RNF05** | **Sincronização Local** | Após o registro de uma cultura, o app deve baixar automaticamente o banco de dados específico para consulta offline permanente [7]. |
| **RNF06** | **Notificações** | O sistema deve enviar alertas push frequentes sobre o status do manejo e lembretes de atividades pendentes [7]. |
| **RNF07** | **Alertas Climáticos** | Notificações urgentes sobre condições climáticas adversas (geada, chuvas fortes, ondas de calor) [7]. |
| **RNF08** | **Personalização** | Coleta de padrões de uso para adequar a interface ao perfil do usuário e sugerir melhorias no fluxo [7]. |

---


**Instituição:** Centro Universitário Campo Real  
**Disciplina:** Fundamentos de Engenharia de Software
