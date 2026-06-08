# 💸 Caixa Azul - App de Organização de Finanças Pessoais com Vibe Coding

Este repositório contém a entrega do meu Desafio de Projeto na plataforma DIO. Utilizando o conceito de **Vibe Coding** e focado em um **MVP (Produto Mínimo Viável)**, desenvolvi o conceito e a interface funcional de um aplicativo de finanças inclusivo, acessível e inteligente chamado **Caixa Azul**.

O grande diferencial deste projeto foi guiar a IA através de princípios de **Design Universal** e conceitos de **Cibersegurança** (como o protocolo OAuth 2.0 e separação de camadas em nuvem).

---

## 🎯 O Conceito do App: Caixa Azul
O **Caixa Azul** resolve o maior problema das ferramentas financeiras tradicionais: a entrada manual de dados entediante. Através de um assistente de IA conversacional integrado e uma divisão visual baseada em "Caixas Financeiras", o usuário gerencia seu dinheiro de forma extremamente simples e visual.

---

## 🪄 Meu Prompt Final (PRD Aplicado)

Este foi o briefing exato estruturado e inserido na plataforma **Lovable** para dar vida ao projeto:

```txt
# PRD: Aplicativo de Organização de Finanças Pessoais via Chat IA

## 1. Visão Geral do Produto
Um aplicativo web responsivo voltado para iniciantes em finanças. O controle financeiro é feito exclusivamente por meio de conversas em linguagem natural com um assistente virtual, eliminando planilhas e formulários complexos. O produto segue rigorosamente os conceitos de Design Universal.

## 2. Requisitos de Design Universal e Acessibilidade
* Contraste e Legibilidade: Fontes legíveis (mínimo 16px) e alto contraste entre texto e fundo.
* Navegação Clara: Layout limpo e espaçado. Botões e elementos clicáveis com área mínima de 48x48 pixels.
* Simplicidade Cognitiva: Interface direta, sem jargões econômicos ou excesso de elementos visuais.
* Suporte a Leitores de Tela: Código estruturado de forma semântica (tags HTML5 corretas).

## 3. Público-Target e Tom de Voz
* Usuário: Iniciantes em controle financeiro, pessoas que buscam praticidade e usuários que sofrem com compras por impulso.
* Tom de Voz: Educativo, acolhedor, empático, firme (quando necessário para compras por impulso) e simples.

## 4. Arquitetura de Telas (Escopo do MVP)

### Tela 1: Dashboard Principal (Visão Geral)
* Componente Topo: Card com o "Saldo Atual", "Total de Receitas do Mês" e "Total de Despesas".
* Componente Central (As Caixas Financeiras): Divisão visual em 3 grandes caixas ou abas:
  1. Custos Fixos: Gastos essenciais de sobrevivência (Aluguel, Luz, Internet).
  2. Lazer / Variáveis: Gastos com estilo de vida (Restaurantes, Cinema, Compras).
  3. Investimentos com Metas: Dinheiro guardado para o futuro, dividido por objetivos claros (Reserva de Emergência, Viagem dos Sonhos, Minha Casa Própria).
* Componente Inferior: Barra de progresso para a "Meta de Economia Geral do Mês".
* Botão Flutuante (CTA): Botão fixo no canto inferior direito escrito "Falar com Assistente".
* Botão de Pânico (SOS Compra por Impulso): Botão vermelho visível no dashboard para ativar o fluxo de contenção de gastos imediato.
```

---

## 📸 Demonstração do MVP

O aplicativo foi publicado com sucesso e a interface responsiva adaptou-se perfeitamente aos requisitos do PRD:

* **Link para testar o Aplicativo:** `https://chat-your-riches.lovable.app/`
* *(Insira aqui abaixo o print que você tirou da tela do seu aplicativo rodando)*

---

## 🧠 Reflexão sobre o Processo (Vibe Coding)

* **O que funcionou bem?**
  A IA entendeu perfeitamente a ideia do layout limpo e acessível. Consegui criar as divisões de gastos e os objetivos de economia de forma muito rápida. O botão de emergência `SOS Impulso` ficou ótimo e foi gerado de primeira.
  
* **O que não funcionou como o esperado?**
  Logo no início, a tela de login quebrou com um aviso de erro preto. Descobri que foi uma falha ao carregar os códigos internos de validação de e-mail e senha. Precisei usar o botão de correção automática do próprio site para consertar o código e fazer o sistema voltar a funcionar.

* **O que aprendi sobre conversar com IAs?**
  Aprendi que não adianta só pedir "um app de finanças". O resultado fica muito melhor quando explicamos as regras antes, como o tamanho dos botões, o tom de voz do chat e os tipos de investimentos que o app deve ter. Isso economiza tempo e evita erros.

* **Visão de Cibersegurança:**
  Como estou estudando para entrar na área de Segurança da Informação, achei incrível ver na prática como funciona o botão de "Continuar com o Google". Entendi que o aplicativo não rouba nossa senha, ele usa uma conexão segura direta com o Google para autorizar o usuário. É um ótimo exemplo de como os sistemas reais protegem nossos dados financeiros.
Use o código com cuidado.Prontinho! Agora é só salvar no seu repositório e enviar o link do GitHub na DIO.Avise-me quando concluir o envio na DIO para comemorarmos o encerramento das suas tarefas de IA de hoje!
