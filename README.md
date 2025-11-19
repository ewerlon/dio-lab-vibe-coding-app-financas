# 💸 App FinanceAI

Este projeto foi desenvolvido em vibe coding, uma abordagem leve, criativa e colaborativa que transforma código em expressão. Utilizei o poder das ferramentas Copilot e Lovable para acelerar o desenvolvimento, estimular ideias e garantir uma experiência fluida do início ao fim.
Com Copilot, tive suporte inteligente em tempo real, otimizando cada linha de código. Já com Lovable, trouxe personalidade e empatia à interface, criando uma conexão mais humana entre tecnologia e usuário.
O resultado? Um projeto que une eficiência técnica com sensibilidade criativa, refletindo o melhor da nova geração de desenvolvimento digital.

**Para a elaboração do PRD (Product Requirements Document), utilizamos o seguinte prompt como base de direcionamento estratégico e criativo:**
```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```
**Aqui estão interações com "Lovable"**
>Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário. A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas, permitindo também fazer lançamentos por meio de imagens (como notas fiscais, recibos, etc.) e por voz.

> Preciso que verifique um lançamento no valor de 1.518. No saldo atual e nas receitas está aparecendo apenas 1,51. Pode me ajudar a corrigir isso?

>Vou investigar o bug do valor.

>Identifiquei o problema! A regex não está lidando corretamente com o formato brasileiro (1.518,00). Vou corrigir o parsing.

**Resultado final Lovable:** https://project-financeai.lovable.app/auth

<img width="1920" height="951" alt="image" src="https://github.com/user-attachments/assets/6279570d-d12f-4065-a651-e8fd8f5f1382" />

<img width="1920" height="951" alt="image" src="https://github.com/user-attachments/assets/129747a1-9ed4-4b57-a5ef-a9cd88b78342" />

**Um resumo do que App de Finanças Pessoais faz:**
```txt
### 1. Visão Geral em Tempo Real
- Exibe o saldo atual disponível após gastos fixos.
- Mostra receitas e despesas de forma clara e atualizada.

### 2. Registro de Gastos por Conversa
- Usuário informa gastos em linguagem natural via chat.
- O sistema interpreta e registra automaticamente.

### 3. Classificação Inteligente de Transações
- Categoriza despesas com base em palavras-chave e histórico.
- Exemplo: “Uber” → Transporte.

### 4. Gestão de Gastos Fixos
- Permite adicionar despesas mensais recorrentes.
- Ajuda a calcular o saldo real disponível.

### 5. Definição e Acompanhamento de Metas
- Usuário pode criar metas como “economizar R$300 este mês”.
- O app acompanha o progresso e envia alertas.

### 6. Agente Financeiro (Lovable)
- Personagem simpático que envia dicas personalizadas.
- Motiva o usuário com mensagens educativas e afetivas.

### 7. Relatórios Simples e Personalizados
- Gráficos de pizza e barras mostram os gastos por categoria.
- Relatórios semanais e mensais com insights e sugestões.

### 8. Dica do Dia
- Sugestões rápidas para melhorar o controle financeiro.
- Exemplo: “Registre seus recebimentos e gastos para manter seu controle atualizado.”

### 9. Navegação Intuitiva
- Menu com acesso rápido a: Início, Chat, Transações, Metas e Configurações.
```

Uma breve reflexão sobre o processo:

✅ O que funcionou bem
- Clareza na comunicação: A troca por linguagem natural facilitou o desenvolvimento das ideias e funcionalidades.
- Agilidade nas respostas: A IA ajudou a organizar rapidamente conceitos, estruturar textos e gerar conteúdo em Markdown.
- Estímulo à criatividade: As sugestões do agente financeiro “Lovable” trouxeram um toque humano e empático ao projeto.
  
⚠️ O que não funcionou como o esperado
- Limitações de contexto visual: A IA não interpreta imagens diretamente sem descrição, o que exige mais detalhamento por parte do usuário.
- Dependência de instruções claras: Quando o pedido é vago, a IA precisa de mais contexto para entregar algo útil — isso pode interromper o fluxo criativo.
  
💬 O que aprendi sobre conversar com IAs
- Quanto mais específico, melhor: A IA responde com mais precisão quando recebe instruções claras e completas.
- É uma parceria, não uma ferramenta passiva: A conversa com a IA funciona como uma troca de ideias — ela propõe, ajusta e refina junto com você.
- Ela aprende com você no momento: Mesmo sem memória ativa, a IA adapta suas respostas com base no que você compartilha durante a conversa.
