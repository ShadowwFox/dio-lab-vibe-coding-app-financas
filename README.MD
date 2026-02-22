PRD (PROMPT FINAL): "### ROLE
Você é um Senior Product Designer & Full-stack Developer especializado em Fintechs de luxo e UX Conversacional. Sua missão é projetar o MVP do "Aura Finance", um app de gestão financeira focado em simplicidade extrema e estética sofisticada para ser construído no Lovable.

### CONTEXTO & OBJETIVO
O Aura Finance elimina a fricção de planilhas. O usuário "conversa" com o app para registrar gastos e receber insights. O objetivo é criar um MVP funcional que pareça um produto final de alto nível, utilizando Shadcn/UI, Tailwind CSS e animações fluidas (Framer Motion).

### ESTRUTURA DO ENTREGÁVEL (MVP BLUEPRINT)

---

#### 1. ARQUITETURA DE DESIGN & UI/UX (Foco em Sofisticação)
[Instrução: Use uma estética "Quiet Luxury" - Dark Mode profundo ou Light Mode com tons de creme e ardósia.]
* **Visual Stack:** Definir o uso de cantos arredondados (xl), tipografia sans-serif geométrica (Inter ou Geist), e sombras suaves para profundidade.
* **Interface Principal:** Uma "Bento Grid" (grade modular) que exibe o saldo total, o limite de gastos do mês e um gráfico de linha minimalista de fluxo de caixa.
* **O Chat Flutuante:** Um componente de entrada de texto fixo na base, que se expande ao ser clicado, utilizando "Blur Background" (Glassmorphism).

#### 2. FLUXO DE TELAS (User Journey)
* **Onboarding:** 3 telas rápidas com animações de fade-in explicando o poder da conversa.
* **Dashboard Central (The Hub):** Visualização imediata da saúde financeira com widgets interativos.
* **Conversation View:** Interface de chat limpa, onde cada mensagem da IA é tratada como um "Card de Insight".
* **Relatórios:** Gráficos de rosca (Donut Charts) elegantes para categorias.

#### 3. FUNCIONALIDADES TÉCNICAS (Lógica Lovable/React)
* **Processamento de Linguagem:** Mock de sistema que entende frases como "Gastei 50 reais com sushi hoje" e atualiza instantaneamente o widget de "Alimentação".
* **Metas Inteligentes:** Barra de progresso com gradientes sutis que mudam de cor conforme o usuário se aproxima do limite (Verde -> Ouro -> Coral).
* **Agente Financeiro:** Notificações contextuais (ex: "Você economizou 15% a mais que na semana passada. Deseja investir esse valor?").

#### 4. RECURSOS E STACK PARA VALIDAÇÃO
* **Frontend:** React + Vite + Tailwind.
* **Componentes:** Shadcn/UI (Cards, Buttons, Avatars).
* **Ícones:** Lucide-react (fio fino/minimalista).
* **Persistência:** Sugestão de integração com Supabase para autenticação e banco de dados.

---

### REQUISITOS NEGATIVOS (O que NÃO fazer)
* NÃO use cores vibrantes demais ou infantis; mantenha uma paleta sóbria e profissional.
* NÃO utilize formulários tradicionais com muitos campos de input.
* NÃO crie tabelas densas de dados; prefira cards e visualizações gráficas.

### VERIFICAÇÃO DE QUALIDADE
Antes de finalizar a resposta, revise se o plano permite que um desenvolvedor (ou o Lovable) entenda exatamente como cada componente deve se comportar visualmente e funcionalmente. O resultado deve ser educativo, mas pronto para execução técnica.

---
[Aguardando processamento com tom educativo e profissional em português.]"

📝 Resumo do Aura Finance

O Aura Finance é um app de finanças pessoais onde, em vez de preencher formulários chatos, você conversa naturalmente — tipo "gastei 50 reais com sushi" — e ele registra tudo automaticamente, mostrando gráficos e insights sobre seus gastos.

🔍 Reflexão sobre o processo
✅ O que funcionou bem?

    O chat como input principal — eliminar formulários e deixar o usuário "falar" com o app tornou tudo mais intuitivo. A IA entendeu minha intenção e criou um parser de linguagem natural simples mas funcional.
    O visual saiu profissional — descrever o estilo como "quiet luxury" e "glassmorphism" foi suficiente para a IA gerar uma paleta escura sofisticada com gradientes dourados, sem parecer genérico. Prototipagem rápida — em uma única conversa, saí do zero para um MVP com onboarding, dashboard com gráficos e chat funcional. Isso levaria dias manualmente.

❌ O que não funcionou como esperado?

    O "NLP" é fake — ele só procura palavras-chave ("sushi" → Alimentação). Se eu digitar "comi fora", ele não entende. É um mock, não inteligência real.
    Sem persistência — ao recarregar a página, todos os dados somem. Falta um banco de dados real (como o Lovable Cloud) para salvar as transações.
    Limitações de escopo — a IA às vezes quer fazer tudo de uma vez. Aprendi que preciso ser específico nos pedidos para não perder o controle.

🧠 O que aprendi sobre conversar com IAs?

    Contexto é rei — quanto mais detalhes eu dou (paleta de cores, estilo visual, fluxo de telas), melhor o resultado. Pedidos vagos = resultados genéricos.
    Iterar > perfeição — é melhor pedir uma versão básica e ir refinando do que tentar descrever tudo perfeitamente de uma vez.
    A IA não "sabe" o que eu quero — ela interpreta. Aprendi a revisar, testar e corrigir em vez de confiar cegamente.
    Prompt engineering é uma skill real — a diferença entre um resultado medíocre e um excelente está em como você pede, não o que você pede.

    Conclusão: Construir com IA é como ter um dev júnior muito rápido — ele faz o trabalho pesado, mas você precisa dirigir, revisar e pensar criticamente. O app não é perfeito, mas como ferramenta de aprendizado, o processo foi incrível. 🚀

📝 Resumo do Aura Finance

O Aura Finance é um app de finanças pessoais onde, em vez de preencher formulários chatos, você conversa naturalmente — tipo "gastei 50 reais com sushi" — e ele registra tudo automaticamente, mostrando gráficos e insights sobre seus gastos.
🔍 Reflexão sobre o processo
✅ O que funcionou bem?

    O chat como input principal — eliminar formulários e deixar o usuário "falar" com o app tornou tudo mais intuitivo. A IA entendeu minha intenção e criou um parser de linguagem natural simples mas funcional.
    O visual saiu profissional — descrever o estilo como "quiet luxury" e "glassmorphism" foi suficiente para a IA gerar uma paleta escura sofisticada com gradientes dourados, sem parecer genérico.
    Prototipagem rápida — em uma única conversa, saí do zero para um MVP com onboarding, dashboard com gráficos e chat funcional. Isso levaria dias manualmente.

❌ O que não funcionou como esperado?

    O "NLP" é fake — ele só procura palavras-chave ("sushi" → Alimentação). Se eu digitar "comi fora", ele não entende. É um mock, não inteligência real.
    Sem persistência — ao recarregar a página, todos os dados somem. Falta um banco de dados real (como o Lovable Cloud) para salvar as transações.
    Limitações de escopo — a IA às vezes quer fazer tudo de uma vez. Aprendi que preciso ser específico nos pedidos para não perder o controle.

🧠 O que aprendi sobre conversar com IAs?

    Contexto é rei — quanto mais detalhes eu dou (paleta de cores, estilo visual, fluxo de telas), melhor o resultado. Pedidos vagos = resultados genéricos.
    Iterar > perfeição — é melhor pedir uma versão básica e ir refinando do que tentar descrever tudo perfeitamente de uma vez.
    A IA não "sabe" o que eu quero — ela interpreta. Aprendi a revisar, testar e corrigir em vez de confiar cegamente.
    Prompt engineering é uma skill real — a diferença entre um resultado medíocre e um excelente está em como você pede, não o que você pede.

    Conclusão: Construir com IA é como ter um dev júnior muito rápido — ele faz o trabalho pesado, mas você precisa dirigir, revisar e pensar criticamente. O app não é perfeito, mas como ferramenta de aprendizado, o processo foi incrível. 🚀



