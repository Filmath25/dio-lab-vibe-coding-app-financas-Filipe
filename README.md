# 💸 App de Organização de Finanças Pessoais com Vibe Coding e liguagem natural.

PRD REFINADO:

```markdown
===========================================
# PRD - APLICATIVO DE ORGANIZAÇÃO FINANCEIRA
FORMATO: CMD / LINHA DE COMANDO
===========================================

## 1. CONTEXTO
O aplicativo tem como objetivo permitir que o usuário organize suas finanças por meio de uma experiência baseada em conversa. O usuário registra gastos, define metas e recebe orientações de forma simples e acessível. O foco é reduzir complexidade e manter uma interface direta.

-------------------------------------------

## 2. PROBLEMA
Usuários deixam aplicativos financeiros tradicionais porque:
- São complexos.
- Exigem entrada manual detalhada.
- Não atendem iniciantes.
- Não são acessíveis.

Solução proposta:
- Interação por chat.
- Automação básica.
- Interface simples.
- Acessibilidade universal.

-------------------------------------------

## 3. PUBLICO-ALVO
- Usuários iniciantes no controle financeiro.
- Pessoas com pouca experiência em tecnologia.
- Usuários com necessidades especiais (design universal).
- Pessoas que buscam simplicidade e orientação direta.

-------------------------------------------

 ## 4. FUNCIONALIDADES BASICAS (MVP)

### 4.1 LOGIN E AUTENTICACAO
- Cadastro com email e senha.
- Login seguro.
- Recuperação de senha.
- Sessão persistente.
- Armazenamento seguro (Supabase ou Firebase).

### 4.2 REGISTRO CONVERSACIONAL DE GASTOS
- Entrada de gastos em linguagem natural.
- Identificação automática de valor, categoria e data.
- Entrada por texto e opção de voz.
- Botões rápidos para ações comuns.

### 4.3 CLASSIFICACAO AUTOMATICA
- Categorização por regras simples.
- Ajuste manual disponível.

### 4.4 METAS FINANCEIRAS
- Criação de metas.
- Acompanhamento.
- Alertas simples e diretos.

### 4.5 AGENTE FINANCEIRO
- Recomendações baseadas em padrões do usuário.
- Destaques sobre gastos e possíveis economias.
- Linguagem clara e objetiva.

### 4.6 RELATORIOS
- Relatório por categoria.
- Relatório mensal.
- Visualização simples e acessível.
- Suporte a alto contraste e leitores de tela.

### 4.7 ACESSIBILIDADE (DESIGN UNIVERSAL)
- Interface simples.
- Compatível com leitores de tela.
- Fonte clara.
- Modo claro, escuro e alto contraste.

-------------------------------------------

## 5. DISTRIBUICAO
- Geração de APK/AAB.
- Publicação inicial em Beta Fechada na Google Play Store.
- Distribuição para testers via Play Console.
- Lançamento público após validação do MVP.

-------------------------------------------

 ## 6. ENTREGAVEIS DA IA (LOVABLE)

### 6.1 TELAS
- Tela de Login.
- Tela de Cadastro.
- Tela de Chat Financeiro.
- Tela de Metas.
- Tela de Relatórios.
- Tela de Configurações/Perfil.

### 6.2 BACKEND
- CRUD de usuários.
- CRUD de gastos.
- CRUD de metas.
- Serviço de categorização simples.
- Serviço de recomendações baseado em regras.

### 6.3 VALIDACAO
Testes com:
- Usuários iniciantes.
- Usuários com baixa visão.
- Usuários com pouco hábito de planejamento financeiro.

Objetivos:
- Avaliar clareza do chat.
- Verificar facilidade de registrar gastos.
- Garantir compreensão dos relatórios.
- Testar usabilidade do login.

-------------------------------------------

## 7. ROADMAP SIMPLIFICADO

FASE 1 - MVP
- Login.
- Chat.
- Gastos.
- Metas.
- Relatórios básicos.
- Publicação Beta Fechada.

FASE 2 - MELHORIAS
- Login com Google.
- Notificações.
- Melhorias na categorização.

FASE 3 - EXPANSAO
- Sincronização bancária.
- Comunidade.
- Recursos avançados de educação financeira.

===========================================
FIM DO DOCUMENTO

```
```
MARKDOWN 2( MAIS ROBUSTO E COMPLETO)
# 💰 Assistente Financeiro Filmath

O **Filmath** é um ecossistema de organização financeira pessoal projetado para simplificar o controle de gastos através de uma interface conversacional (Chat) e acessibilidade universal. O foco é transformar a tarefa complexa de anotar despesas em uma conversa natural.

---

## 🚀 Resumo do Projeto
O aplicativo permite que o usuário registre despesas por texto ou voz, categorizando-as automaticamente e gerando relatórios visuais instantâneos. Como um **PWA (Progressive Web App)**, ele oferece a experiência de um app nativo (instalação direta no celular) sem a necessidade de lojas de aplicativos tradicionais.

---

## 📋 PRD - Product Requirement Document (Refinado)

### 1. Problema & Solução
*   **Problema:** Apps financeiros são burocráticos, exigem muitos cliques e não entendem datas retroativas de forma simples.
*   **Solução:** Registro via Linguagem Natural (NLP) e gestão de dados com foco em correção rápida de erros (Exclusão/Edição).

### 2. Funcionalidades Principais (MVP+)
*   **Chat Inteligente:** Reconhece frases como *"Gastei 30 reais de sushi ontem"* ou *"50 reais de gasolina dia 15/02"*.
*   **Lógica de Data Retroativa:** Diferencia a data de criação do registro da data real do gasto informada pelo usuário.
*   **Categorização Automática:** Motor de regras para classificar gastos (Alimentação, Transporte, Moradia, Lazer, Saúde).
*   **Gestão de Erros (CRUD):** Botões de exclusão individual (lixeira) e Reset total de dados nas configurações.
*   **Relatórios Dinâmicos:** Gráficos de pizza e listas agrupadas por mês e categoria.

### 3. Especificações Técnicas
*   **Frontend:** React + Tailwind CSS (Vite).
*   **Ícones:** Lucide React.
*   **Persistência:** Lovable Cloud / Supabase Integration.
*   **Distribuição:** PWA (Progressive Web App) com Manifest e Service Workers para suporte offline.

### 4. Experiência do Usuário (UX)
*   **Acessibilidade:** Alto contraste, fontes escaláveis e navegação simplificada.
*   **Mobile First:** Teclados numéricos automáticos e interface otimizada para uso com uma mão.

---

## 🛠️ Como Instalar (PWA)
1. Acesse a URL do projeto pelo navegador do celular.
2. No **Android**: Clique nos três pontos ⋮ e selecione **"Instalar Aplicativo"**.
3. No **iOS**: Clique no botão de compartilhar 📤 e selecione **"Adicionar à Tela de Início"**.

---

## 📅 Roadmap de Evolução
- [x] Fase 1: Registro Conversacional e Relatórios Básicos.
- [x] Fase 2: Lógica de Datas Retroativas e Botão de Excluir.
- [ ] Fase 3: Metas de Economia Mensal e Notificações de Limite.
- [ ] Fase 4: Exportação de dados para CSV/Excel.

---
**Desenvolvido com foco em simplicidade e controle financeiro real.**
```

## Prints ou pequenos vídeos das interações com a IA:
 <img width="1359" height="617" alt="Captura de tela 2026-02-21 160618" src="https://github.com/user-attachments/assets/55d89f35-6fdb-49ee-a870-3e43b1e5d445" />
 <img width="1241" height="611" alt="Captura de tela 2026-02-21 160630" src="https://github.com/user-attachments/assets/67631f15-def1-4427-b885-2104d4b127b1" />
 
## link do APP:
Para instalar no celular como app:

Acesse o link publicado no navegador do celular: https://steer-your-app.lovable.app
Android (Chrome): Toque no menu ⋮ → "Adicionar à tela inicial"
iPhone (Safari): Toque no botão compartilhar ↑ → "Adicionar à Tela de Início"
 

## Uma breve **reflexão sobre o processo**:
### O que funcionou bem? Usar o Gemini como suporte para criação do Prd para o Lovable.
### O que não funcionou como o esperado? Precisa de várias interações para finalizar o projeto
### O que aprendeu sobre conversar com IAs? Aprendi que precisamos dar detalhes, de forma mais clanra possível.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.

