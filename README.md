
---

# 💸 App de Organização de Finanças Pessoais  
**Jessé Alves com Vibe Coding**

Este projeto foi desenvolvido como um desafio de Vibe Coding utilizando o Lovable e o Copilot Web. A proposta é criar um aplicativo de organização financeira pessoal baseado em interações em linguagem natural.

---

## 📄 PRD Refinado no Copilot Web

```markdown
# PRD - App de Organização Financeira com Conversa Natural

## Visão Geral
Criar um aplicativo de organização de finanças pessoais que funcione por meio de conversas em linguagem natural.  
O objetivo é tornar o controle financeiro mais intuitivo, acessível e livre de burocracias como planilhas ou formulários complexos.

## Problema a Resolver
Muitas pessoas abandonam o controle financeiro por acharem os aplicativos atuais complicados, exigindo entradas manuais e oferecendo pouca personalização.  
Queremos resolver isso com uma experiência conversacional fluida e recomendações automáticas que se adaptam ao perfil do usuário.

## Público-Alvo
Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicações — especialmente iniciantes que não têm familiaridade com apps financeiros tradicionais.

## Funcionalidades-Chave
1. Registro de gastos via chat: O usuário descreve seus gastos em linguagem natural, como “gastei R$ 30 no mercado”.
2. Classificação automática de transações: O app identifica e categoriza os gastos com base no texto.
3. Definição e acompanhamento de metas financeiras: O usuário pode criar metas como “economizar R$ 500 até o fim do mês”.
4. Dicas personalizadas do Agente Financeiro: Um assistente virtual que sugere formas de economizar com base nos hábitos do usuário.
5. Relatórios simples e personalizados: Visualizações claras dos gastos, metas e progresso, adaptadas ao estilo do usuário.

## Princípio de Design Universal
A solução será construída com base em Design Universal, garantindo que o aplicativo ofereça uma experiência acessível, intuitiva e inclusiva para o maior número possível de pessoas — independentemente de idade, nível de alfabetização digital, limitações físicas ou cognitivas.  
Isso inclui:
- Interface clara e legível
- Navegação simples e sem sobrecarga de informações
- Compatibilidade com leitores de tela e comandos por voz
- Feedbacks visuais e auditivos para facilitar o uso
- O usuário terá que acessar o app por meio de login e senha

## Entregável da IA
Gerar um plano de MVP contendo:
- As principais telas (chat, metas, relatórios)
- Recursos técnicos necessários (NLP, categorização automática, motor de recomendações)
- Estratégia de validação inicial com usuários reais
- Linguagem acessível e tom educativo, em português
- Aplicação dos princípios de Design Universal desde o protótipo
```

---

## 🎬 Interações com o Lovable

> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}  
> Não está registrando as informações de gastos e benefícios recebidos. E no campo perfil não tem como editar as informações dos usuários ou acessar os campos de configurações. O modo escuro não ativa.  
> Corrija o valor das variáveis lançadas. EX: Eu digito que recebi a quantia de 5.000 e ele contabiliza apenas 5,00. Quero que zere todos os valores para a partir de agora eu efetuar todos os lançamentos tanto de crédito quanto de débitos.  
> Corrija o campo metas. Habilitando os campos para edição de valores, ou exclusão do campo metas, e habilite o campo criar novas metas. No chat não fica salvo os lançamentos quando eu saio da tela chat e retorno para ela não tem os últimos lançamentos que eu digitei. Não está contabilizando os lançamentos que estão realizando, isso precisa ser corrigido. O saldo está zerado toda vez que eu digitar um valor de crédito tem que atualizar meu saldo, toda vez que eu digitar um valor referente a gasto, tem que abater do saldo.  

### Correções solicitadas:
- Habilitar a função: Alterar senha  
- Não deixar o valor estipulado da meta (o usuário é quem define)  
- Transferências para metas devem ser abatidas do saldo atual  
- Criar relatórios de gastos por categoria e transações recentes  
- Informar saídas de metas com ícone específico  
- No campo editar meta: apenas informar o valor desejado, sem obrigatoriedade de valor atual  
- Ajustar tela de login: manter frase “Organize suas finanças com conversas simples” com menos ênfase e adicionar nome fixo do app  
- Nome do App: **MetaCash**  
- Criar campo mostrando valor total aplicado (saldo + metas)  
- Criar aba de entradas e saídas: semanal, mensal e anual  

📌 **Resultado final no Lovable:**  
👉 [fala-dinheiro-facil.lovable.app](https://fala-dinheiro-facil.lovable.app)

<img width="1911" height="917" alt="image" src="https://github.com/user-attachments/assets/4698d91b-5f29-4269-8f6c-aacf510c6029" />  
<img width="1313" height="850" alt="image" src="https://github.com/user-attachments/assets/a9c286ea-dde5-4500-bff1-099e1d5a9051" />

---

# 📱 App de Organização Financeira com Conversa Natural

## Visão Geral
Um aplicativo de finanças pessoais que funciona por meio de conversas em linguagem natural.  
O objetivo é tornar o controle financeiro mais intuitivo, acessível e livre de burocracias como planilhas ou formulários complexos.

---

## 🎯 Problema a Resolver
Muitas pessoas abandonam o controle financeiro por acharem os aplicativos atuais complicados, exigindo entradas manuais e oferecendo pouca personalização.  
Este app resolve isso com uma experiência conversacional fluida e recomendações automáticas adaptadas ao perfil do usuário.

---

## 👥 Público-Alvo
- Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicações.  
- Especialmente iniciantes sem familiaridade com apps financeiros tradicionais.

---

## 🔑 Funcionalidades-Chave
1. **Registro de gastos via chat**  
   - O usuário descreve seus gastos em linguagem natural, como “gastei R$ 30 no mercado”.

2. **Classificação automática de transações**  
   - O app identifica e categoriza os gastos com base no texto.

3. **Definição e acompanhamento de metas financeiras**  
   - Exemplo: “economizar R$ 500 até o fim do mês”.

4. **Dicas personalizadas do Agente Financeiro**  
   - Sugestões de economia com base nos hábitos do usuário.  
   - Mensagens motivacionais diárias.

5. **Relatórios simples e personalizados**  
   - Visualizações claras dos gastos, metas e progresso.

---

## 🧭 Estrutura de Navegação
- **Resumo**: visão geral das finanças (saldo, entradas, saídas)  
- **Chat**: registro de gastos e interação com o assistente  
- **Metas**: definição e acompanhamento de objetivos financeiros  
- **Relatórios**: análises detalhadas e personalizadas  
- **Perfil**: dados do usuário e configurações  

---

## 🧠 Recursos Técnicos
- Processamento de Linguagem Natural (NLP)  
- Motor de categorização automática de transações  
- Sistema de recomendações personalizadas  
- Autenticação segura com login e senha  

---

## 📝 Reflexão

### O que funcionou bem?  
O refinamento do PRD previamente elaborado no Copilot ajudou muito, pois os créditos para usufruir gratuitamente acabam em poucas interações.  

### O que não funcionou como o esperado?  
Esperava poder interagir bem mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender Vibe Coding.  

### O que aprendeu sobre conversar com IAs?  
Quanto mais detalhes você fornece à IA, ela dá a sensação de estar na mesma linha de raciocínio e executa a tarefa com maestria, trazendo resultados melhores do que o esperado. A interação é idêntica à humana.  

---
