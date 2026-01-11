# 🎯 Desafio - Entrega do PRD e Lovable
Aqui, baseado nas aulas assistidas de IA, do Bootcamp CAIXA - Inteligência Artificial na Prática, apresento o resultado final do meu projeto de criação de um aplicativo de finanças pessoais, com uso de **Vibe Coding**, com as ferramentas **CoPilot** e **Lovable**, para colocar em prática o aprendizado até o momento.
Para facilitar a leitura do Read.me, dividir as interações entre CoPilot e Lovable, além de inserir os vídeos, com as interações feitas em cada etapa, para verificar o funcionamento e como foram feitas.

## Usando o CoPilot, para aperfeiçoar o PRD desenvolvido:
>
#### 1. Prompt inicial utilizado com o CoPilot

```
Boa tarde, Copilot.

Criei o seguinte PRD (Product Requirements Document), para ser utilizado com a plataforma **Lovable**, para a criação de um aplicativo de controle de finanças, onde o usuário irá interagir por meio de conversas naturais, visando ter maior controle sobre suas finanças, hábitos de consumo e como guardar dinheiro, para projetos futuros.  
Baseado nas premissas acima, necessito que me ajude na revisão desse PRD, verificando a clareza dos itens; pensando em design UX limpo, claro e acessível para todos os usuários; além de que a conversa com o aplicativo flua de forma natural e tom amigável.  
Me apresente o PRD com sua análise, e no final, coloque um resumo sintético de tudo que foi analisado, as mudanças efetuadas e explicação dos pontos fortes e o que foi melhorado do PRD original, conforme sua análise.

---

### Contexto
Quero criar um aplicativo de **Organização de Finanças Pessoais** que funcione por meio de conversas com o usuário, em linguagem natural e tom amigável, para estimular o uso do aplicativo no dia-a-dia, para controle de todos os gastos e entradas de dinheiro.  
A ideia é facilitar o controle financeiro — de forma simples e natural — sem a necessidade de usar formulários manuais ou planilhas complexas, otimizando a inserção dos dados por meio das conversas.

---

### Problema
Muitas pessoas desistem de controlar seus gastos, pois os apps atuais:
- Exigem muita entrada manual, com diversas telas e opções.
- Oferecem pouca personalização para as necessidades do usuário.
**Objetivo:** Resolver isso com uma experiência de conversa e recomendações automáticas de economia, estimulando o usuário a atingir seus objetivos e desenvolver hábitos poupadores.

---

### Público-Alvo
- Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação.  
- Iniciantes e pessoas com pouca experiência em aplicativos ou sobre o tema de finanças.

---

### Funcionalidades-Chave
- Registrar gastos via chat, em linguagem natural e tom amigável.  
- Classificar automaticamente as transações (categorias, tipos e datas).  
- Definir e acompanhar metas financeiras (ex.: guardar R$500 até o fim do mês).  
- Receber dicas de economia validadas e aprovadas no mercado financeiro, por meio do **Agente Financeiro**.  
- Visualizar relatórios simples e personalizados, com filtros por categorias, tipos, datas e entradas/saídas.  
- Identificar gastos anormais, com valores fora do habitual.  
- Avisar ao usuário em caso de desequilíbrio financeiro (ex.: recebeu R$500, mas gastou R$600).
```
---

#### 1.1. PRD revisado pelo Copilot, após o prompt inicial acima
```
### 📱 PRD Revisado – Aplicativo de Organização de Finanças Pessoais Conversacional

---

### Contexto
O aplicativo será um **assistente financeiro pessoal**, que interage com o usuário por meio de conversas naturais e amigáveis, facilitando o controle de gastos e entradas de dinheiro sem burocracia.  
A proposta é substituir formulários e planilhas complexas por uma experiência fluida de diálogo, tornando o processo de organização financeira mais simples, acessível e motivador.

---

### Problema
Usuários frequentemente abandonam aplicativos de finanças porque:
- Exigem entrada manual extensa e pouco intuitiva.
- Possuem interfaces complexas, com muitas telas e opções.
- Oferecem baixa personalização, não se adaptando às necessidades individuais.

**Solução proposta:**
- Interação conversacional simplificada.  
- Recomendações automáticas de economia e hábitos financeiros saudáveis.  
- Estímulo ao comportamento poupador, com feedback positivo e motivador.

---

### Público-Alvo
- Pessoas iniciantes no controle financeiro.  
- Usuários com pouca experiência em aplicativos ou em gestão de finanças.  
- Pessoas que desejam praticidade e clareza, sem lidar com termos técnicos ou interfaces complexas.  

👉 **Foco em acessibilidade e inclusão, garantindo que qualquer pessoa consiga usar sem barreiras.**

---

### Funcionalidades-Chave

#### Registro de gastos via chat
- Usuário informa: *“Gastei 50 reais em supermercado”* → sistema registra automaticamente.  
- Tom amigável e educativo, sem jargões técnicos.

#### Classificação automática de transações
- Categorias: alimentação, transporte, lazer, contas fixas etc.  
- Possibilidade de correção pelo usuário, com aprendizado contínuo.

#### Metas financeiras personalizadas
- Exemplo: *“Quero guardar 500 reais até o fim do mês.”*  
- Sistema acompanha progresso e envia lembretes motivacionais.

#### Dicas de economia pelo “Agente Financeiro”
- Conteúdo validado e confiável.  
- Linguagem acessível, com exemplos práticos.

#### Relatórios simples e visuais
- Gráficos e resumos claros.  
- Filtros por categoria, tipo de transação, período e entradas/saídas.

#### Detecção de gastos fora do padrão
- Exemplo: alerta quando gasto em *“lazer”* ultrapassa média habitual.

#### Avisos de desequilíbrio financeiro
- Exemplo: *“Você gastou 600 reais, mas sua entrada foi de 500 reais. Atenção para não entrar no vermelho.”*

---

### Entregável da IA
#### Plano de MVP

**Principais telas:**
- Tela inicial (chat conversacional).  
- Tela de metas financeiras.  
- Tela de relatórios simples.  
- Tela de dicas do Agente Financeiro.  

**Recursos necessários:**
- Motor de NLP (processamento de linguagem natural).  
- Classificação automática de transações.  
- Sistema de alertas e notificações.  
- Visualização de relatórios simples e acessíveis.  

**Esboço de validação inicial:**
- Testes com usuários iniciantes.  
- Avaliação da clareza da conversa.  
- Feedback sobre relatórios e dicas.  
```

---

#### 1.2. GIF mostrando a interação entre usuário e CoPilot.
![prompt_inicial_e_resultado_final_PRD](https://github.com/user-attachments/assets/341329e4-6502-406e-8bb5-617eed1cb86d)
>
