# 💸 App de Organização de Finanças Pessoais do Matheus com Vibe Coding

PRD refinado no Copilot:
```
# PRD - Assistente de Finanças Pessoais Conversacional

## 1. Visão Geral

Criar um aplicativo de organização financeira pessoal baseado em conversação em linguagem natural.

O usuário deve conseguir registrar receitas, despesas e metas financeiras através de mensagens simples, sem necessidade de preencher formulários complexos ou utilizar planilhas.

O sistema interpreta as mensagens, classifica automaticamente as transações, gera insights financeiros e acompanha a evolução dos objetivos do usuário.

O produto deve priorizar simplicidade, inclusão, acessibilidade e facilidade de uso para iniciantes.

---

## 2. Problema

Muitas pessoas abandonam aplicativos financeiros porque:

- Exigem preenchimento manual excessivo.
- Possuem interfaces complexas.
- Não oferecem orientações personalizadas.
- Exigem conhecimento prévio sobre finanças.
- Possuem excesso de funcionalidades para usuários iniciantes.

Como consequência, os usuários deixam de acompanhar seus gastos e perdem oportunidades de melhorar sua saúde financeira.

---

## 3. Objetivo do Produto

Criar uma experiência simples, intuitiva e acessível para que qualquer pessoa possa controlar suas finanças por meio de uma conversa.

O usuário deve sentir que está conversando com um assistente financeiro pessoal.

### Indicadores de Sucesso

- O usuário registra sua primeira despesa em menos de 2 minutos.
- O usuário consegue visualizar um resumo financeiro após 5 lançamentos.
- Pelo menos 70% das transações são classificadas corretamente de forma automática.
- O usuário recebe recomendações personalizadas com base no seu comportamento financeiro.
- Pelo menos 50% dos usuários retornam ao aplicativo na segunda semana.

---

## 4. Público-Alvo

Pessoas entre 18 e 45 anos que:

- Nunca utilizaram aplicativos financeiros.
- Possuem pouca experiência com controle financeiro.
- Consideram planilhas complicadas.
- Utilizam aplicativos de mensagens diariamente.
- Procuram uma solução simples e prática para organizar gastos.

### Principais Necessidades

- Entender para onde o dinheiro está indo.
- Criar hábitos financeiros saudáveis.
- Economizar dinheiro.
- Acompanhar metas financeiras.
- Controlar receitas e despesas sem esforço.

---

## 5. Proposta de Valor

"Controle suas finanças conversando com um assistente, como se estivesse enviando mensagens para um amigo."

Exemplos de interação:

- Gastei R$ 45 no almoço.
- Recebi R$ 3.500 de salário.
- Quero juntar R$ 5.000 para viajar.
- Quanto gastei com transporte este mês?
- Estou economizando o suficiente para minha meta?

---

## 6. Funcionalidades do MVP

### 6.1 Registro de Transações por Chat

O usuário poderá registrar movimentações financeiras através de linguagem natural.

Exemplos:

- Gastei R$ 25 em café.
- Comprei um curso por R$ 150.
- Recebi R$ 4.000 de salário.

O sistema deverá:

- Identificar valor.
- Identificar tipo da movimentação.
- Classificar automaticamente.
- Confirmar o registro para o usuário.
- Atualizar os resumos financeiros.

---

### 6.2 Classificação Automática

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Salário
- Investimentos
- Outros

O usuário poderá editar categorias quando necessário.

---

### 6.3 Metas Financeiras

Permitir a criação e acompanhamento de objetivos financeiros.

Exemplos:

- Quero economizar R$ 10.000.
- Quero guardar R$ 5.000 para viajar.

Cada meta deverá possuir:

- Nome da meta.
- Valor alvo.
- Prazo opcional.
- Valor acumulado.
- Percentual de progresso.

---

### 6.4 Agente Financeiro

O sistema deverá atuar como um assistente financeiro educacional.

Exemplos de insights:

- Seus gastos com alimentação aumentaram 15% este mês.
- Você economizou R$ 120 em comparação com o mês anterior.
- Mantendo o ritmo atual, você alcançará sua meta em 6 meses.

As recomendações devem ser educativas, simples e não invasivas.

---

### 6.5 Dashboard Financeiro

Apresentar uma visão simplificada da situação financeira.

Informações exibidas:

- Saldo atual.
- Total de receitas.
- Total de despesas.
- Categorias com maiores gastos.
- Evolução mensal.
- Metas financeiras.
- Recomendações do assistente.

---

## 7. Principais Telas

### Tela 1 - Onboarding

Objetivo:

Apresentar o produto e explicar o funcionamento.

Elementos:

- Mensagem de boas-vindas.
- Benefícios do aplicativo.
- Explicação simples da proposta.
- Botão "Começar".

---

### Tela 2 - Chat Principal

Objetivo:

Permitir interação com o assistente financeiro.

Elementos:

- Histórico de conversas.
- Campo de mensagem.
- Sugestões rápidas.
- Confirmações automáticas.
- Recomendações contextuais.

---

### Tela 3 - Dashboard

Objetivo:

Apresentar um resumo financeiro visual.

Elementos:

- Saldo.
- Receitas.
- Despesas.
- Gráficos simples.
- Categorias.
- Metas.

---

### Tela 4 - Metas Financeiras

Objetivo:

Criar e acompanhar objetivos financeiros.

Elementos:

- Lista de metas.
- Barra de progresso.
- Valor acumulado.
- Valor restante.

---

### Tela 5 - Perfil e Configurações

Elementos:

- Nome.
- Preferências.
- Configurações de notificações.
- Categorias personalizadas.
- Configurações de acessibilidade.

---

## 8. Fluxo Principal do Usuário

1. Usuário cria conta.
2. Usuário conclui o onboarding.
3. Usuário acessa o chat.
4. Usuário registra uma despesa.
5. Sistema interpreta e classifica a transação.
6. Dashboard é atualizado.
7. Usuário cria uma meta financeira.
8. Sistema acompanha o progresso.
9. Usuário recebe recomendações personalizadas.

---

## 9. Design Universal e Acessibilidade

O produto deve seguir os princípios de Design Universal para garantir que o maior número possível de pessoas consiga utilizar a aplicação com facilidade.

### Objetivos

- Simplicidade acima da complexidade.
- Inclusão acima da personalização excessiva.
- Clareza acima de elementos decorativos.
- Aprendizado intuitivo.
- Baixa carga cognitiva.

### Requisitos de Acessibilidade

- Seguir as diretrizes WCAG 2.2 Nível AA.
- Alto contraste entre texto e fundo.
- Tipografia legível.
- Compatibilidade com leitores de tela.
- Navegação por teclado.
- Componentes acessíveis.
- Feedback visual e textual.
- Não depender apenas de cores para transmitir informações.
- Suporte para diferentes tamanhos de tela.

### Diretrizes de UX

- Mobile First.
- Linguagem simples.
- Fluxos curtos.
- Poucas ações por tela.
- Feedback imediato após cada ação.
- Experiência intuitiva para usuários com pouca familiaridade tecnológica.

---

## 10. Requisitos Não Funcionais

- Aplicação responsiva.
- Tempo de carregamento inferior a 3 segundos.
- Interface otimizada para dispositivos móveis.
- Arquitetura preparada para futuras integrações.
- Estrutura escalável.
- Boas práticas de segurança e privacidade dos dados.

---

## 11. Escopo Futuro

Funcionalidades fora do MVP:

- Integração com Open Finance.
- Integração com bancos.
- Importação de extratos.
- Registro por voz.
- Integração com WhatsApp.
- Planejamento automático de orçamento.
- Sistema avançado de IA financeira.
- Gamificação financeira.
- Alertas inteligentes de consumo.

---

## 12. Critérios de Validação

O MVP será considerado validado quando:

- Usuários conseguirem registrar despesas sem treinamento.
- O chat for o principal meio de interação.
- Os usuários compreenderem seus gastos por categoria.
- Houver percepção de simplicidade e facilidade de uso.
- O produto demonstrar potencial de retenção e recorrência.

---

## Prompt para Lovable

Crie uma aplicação web responsiva de gestão financeira pessoal baseada em conversação por linguagem natural.

O usuário deve conseguir registrar receitas, despesas e metas financeiras através de um chat semelhante a aplicativos de mensagens.

O sistema deve interpretar mensagens como:

- "gastei R$50 em almoço"
- "recebi R$3000 de salário"
- "quero economizar R$10000"

As transações devem ser classificadas automaticamente e refletidas em tempo real no dashboard financeiro.

A aplicação deve possuir:

- Onboarding
- Chat principal
- Dashboard financeiro
- Gestão de metas
- Perfil e configurações

Utilize dados mockados.

Priorize simplicidade, experiência conversacional, acessibilidade e Design Universal.

Siga as diretrizes WCAG 2.2 nível AA.

Adote uma abordagem Mobile First.

Inspire-se na simplicidade de produtos como Nubank, Cora, Inter, Google Material Design e Apple Human Interface Guidelines.

O usuário deve conseguir registrar sua primeira despesa sem treinamento ou documentação.

A experiência deve minimizar esforço, reduzir carga cognitiva e ser acessível ao maior número possível de usuários.
```

interações com o LOVABLE:
crie um app de finanças pessoais com base no seguinte PRD (Product Requirements Document):

Resultado do LOVABLE: https://meu-bolso-em-equilibrio.lovable.app
<img width="691" height="631" alt="image" src="https://github.com/user-attachments/assets/ae491ef9-b408-4cb0-a605-8e400ac9f99b" />

<img width="525" height="2268" alt="image" src="https://github.com/user-attachments/assets/180e537f-063a-415b-ba6e-1277fdec7f1a" />
 
O fato de o primeiro resultado já apresentar uma interface coerente não significa que o produto está pronto. O maior valor obtido foi a capacidade de validar rapidamente hipóteses de UX e produto, reduzindo o custo de experimentação e aprendizado.
