# 💸 App de Organização de Finanças Pessoais Jessé Alves com Vibe Coding

 PRD refinado no Copilot Web:

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
- O usuario tera que acessar o app por meio de logim e senha

## Entregável da IA
Gerar um plano de MVP contendo:
- As principais telas (chat, metas, relatórios)
- Recursos técnicos necessários (NLP, categorização automática, motor de recomendações)
- Estratégia de validação inicial com usuários reais
- Linguagem acessível e tom educativo, em português
- Aplicação dos princípios de Design Universal desde o protótipo

 ```
Interações com o Lovable:

> Crie um App de Finaças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

> Não esta registrando as informações de gastos e benefícios recebidos. E no campo perfil não tem como editar as informações dos usuários ou acessar os campos de configurações. O modo escuro não ativa

> Corrija o valor das variáveis ​​lançadas. EX: Eu dígito que recebi a quantia de 5.000 e ele contabiliza apenas 5,00. Quero que zere todos os valores para a partir de agora eu efetuar todos os lançamentos tanto de crédito quanto de débitos.

> Corrija o campo metas. Habilitando os campos para edição de valores, ou exclusão do campo metas, e habilite o campo criar novas metas. No chat não fica salvo os lançamentos quando eu saio da tela chat e retorna para ela não tem os últimos lançamentos que eu digitei. Não esta contabilizando os lançamentos que estão realizando isso precisa ser corrigido. O saldo está zerado toda vez que eu digitar um valor de crédito tem que atualizar meu saldo, toda vez que eu digitar um valor referente a gasto, tem que abater do saldo.

> -preciso que realize algumas correções no app:
- habilite a função: Alterar senha
- Não deixe o valor estipulado da meta. (o usuário é quem vai estipular o valor de cada meta)
- O valor que o usuário vai transferir para o campo minhas metas deve ser abatido do salto atual quando ele fizer a transação para a meta que ele escolher transferir.
- Criar um campo de relatórios mostrando gastos por categoria e um mostrando as transações recentes.
- Quando um valor for abatido de qualquer meta informe no campo metas um ícone com o valor de saida e o ícone tera que ter o nome de Saídas Metas.
- No campo editar meta: Não obrigue o usuário a já informar um valor atual, O usuário vai apenas informar o valor que deseja alcançar para a meta seja ela qual for.
- Na tela de login e senha contém um nome Organize suas finanças com conversas simples. Quero mantê-lo mas de menos enfase nele. Acima dele cria um nome fixo para o app.
- O nome do App será MetaCash
- crie um campo mostrando o valor total aplicado no app, EX: O valor total transferido para cada meta somado com o valor do saldo atual.
- crie uma aba onde mostrar o valor de entrada e saidas: semanalmente, mensalmente e anualmente

Resultado final no Lovable: https://fala-dinheiro-facil.lovable.app

<img width="1911" height="917" alt="image" src="https://github.com/user-attachments/assets/4698d91b-5f29-4269-8f6c-aacf510c6029" />
<img width="1313" height="850" alt="image" src="https://github.com/user-attachments/assets/a9c286ea-dde5-4500-bff1-099e1d5a9051" />

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
- **Resumo**: visão geral das finanças (saldo, entradas, saídas).  
- **Chat**: registro de gastos e interação com o assistente.  
- **Metas**: definição e acompanhamento de objetivos financeiros.  
- **Relatórios**: análises detalhadas e personalizadas.  
- **Perfil**: dados do usuário e configurações.

---

## 🧠 Recursos Técnicos
- Processamento de Linguagem Natural (NLP).  
- Motor de categorização automática de transações.  
- Sistema de recomendações personalizadas.  
- Autenticação segura com login e senha.

--- 
## Reflexão


 ### O que funcionou bem?  
 O refinamento do PRD previamente elaborado no Copilot ajudou muito, pois os creditos para usufluir gratuitamente acaba em poucas interações

 ### O que não funcionou como o esperado?  
 Esperava poder intetarir bem mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender Vibe Coding.
 
 ###O que aprendeu sobre conversar com IAs?
 Quanto mais detalhes você fornece a IA, ela te da a sensação de estar na mesma linha de raciocinio e executa a tarefa com maestria trazendo o resultado melhor do que é esperado. A interação é identica a humana.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
