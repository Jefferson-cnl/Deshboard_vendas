# 🎮 Dashboard de Vendas - Assinaturas de Game Pass

Este projeto consiste em um dashboard construído no Excel para visualização e análise de dados de **assinaturas de serviços de jogos**, incluindo planos como EA Play e Minecraft Season Pass. É voltado ao acompanhamento do desempenho comercial de diferentes tipos de assinatura em diversos períodos.

## 📁 Estrutura do Arquivo

O arquivo contém as seguintes abas:

### 1. `B̳ases`
Contém os dados brutos com informações de assinantes e suas assinaturas. As principais colunas incluem:

- `Subscriber ID`: Identificador único do assinante
- `Name`: Nome do assinante
- `Plan`: Nome e tipo do plano (Essencial, Final, Padrão)
- `Start Date`: Data de início da assinatura
- `Mês`: Mês de referência
- `Auto Renewal`: Indica se a renovação automática está ativada
- `Subscription Price`: Valor da assinatura
- `Subscription Type`: Frequência do plano (Mensal, Anual, Trimestral)
- `EA Play Season Pass`: Indica se o assinante tem acesso ao EA Play
- `EA Play Season Pass Price`: Valor adicional do EA Play
- `Minecraft Season Pass`: Indica se o assinante tem acesso ao Minecraft
- `Minecraft Season Pass Price`: Valor adicional do Minecraft
- `Coupon Value`: Desconto aplicado via cupom
- `Total Value`: Valor total pago pelo assinante

### 2. `D̳ashboard`
Painel visual com o título **"VENDAS DE ASSINATURAS DE GAMES PASS"**. Contém gráficos e indicadores gerados a partir dos dados da aba `B̳ases`.

### 3. `cálculos`
Contém cálculos auxiliares para análise de assinaturas, como somatórios por tipo de plano, especialmente relacionados ao **Minecraft Season Pass.**

### 4. `A̳ssets`
Paleta de cores e elementos visuais usados no design do dashboard (por exemplo: cores temáticas, zonas negativas, etc).

---

## 📊 Funcionalidades

- Cálculo do total de vendas por tipo de assinatura
- Comparação entre planos e frequência (Mensal, Anual, Trimestral)
- Análise da adesão a complementos (EA Play, Minecraft)
- Segmentação por mês de início da assinatura
- Visual interativo com suporte a filtros

---

## 🧩 Requisitos

- Microsoft Excel 2016 ou superior (para suportar tabelas dinâmicas e segmentações)
- Permissões habilitadas para macros e gráficos dinâmicos (se aplicável)

---

## ▶️ Como Usar

1. Abra o arquivo `Deshboard_Vendas.xlsx` no Excel.
2. Para atualizar os dados, edite ou adicione novas linhas na aba **B̳ases**.
3. Vá até a aba **D̳ashboard** para visualizar os resultados atualizados automaticamente.
4. Use os filtros e segmentações (se existirem) para aprofundar a análise.

---

## 📬 Contato

Para dúvidas, sugestões ou customização do dashboard, entre em contato com o criador do projeto.

