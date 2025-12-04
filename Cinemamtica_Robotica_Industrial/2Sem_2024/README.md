# 🎥 GLOBAL SOLUTION 2024  
## Energia Renovável e Automação para Comunidades Isoladas  
### Robótica Aplicada – 2º Semestre

---

## 🎬 **CENA 1 — ABERTURA**

Em muitas regiões distantes do mundo, ainda existem comunidades inteiras sem acesso à rede elétrica convencional.  
Para elas, a energia renovável é mais que uma alternativa: é a única forma de garantir qualidade de vida, segurança e desenvolvimento econômico.

A **Global Solution 2024 – 2º Semestre** coloca os estudantes diante de um desafio real:  
Criar um sistema inteligente, seguro e eficiente para fornecer energia renovável a comunidades remotas.

---

## ⚡ **CENA 2 — DESCRIÇÃO DO DESAFIO**
 
O objetivo é desenvolver uma solução que integre:

- ☀️ Energia solar  
- 🌬️ Energia eólica  
- 💧 Energia hídrica  
- 🔋 Sistema de armazenamento  
- 🧠 Gerenciamento inteligente de energia  
- 🔐 Medidas de cibersegurança  

Tudo isso formando um sistema confiável, sustentável e adaptável às condições locais.

---

## 🌄 **CENA 3 — A SITUAÇÃO DA COMUNIDADE**

Imagine uma pequena comunidade isolada.  
Sem rede elétrica convencional, ela encontrou uma saída: instalar quatro placas solares para alimentar suas baterias estacionárias.

Mas surge um novo problema:  
Se todas as placas ficarem ligadas o tempo todo, as baterias podem ser sobrecarregadas.  
É necessário automatizar o processo de ligar e desligar as placas.

---

## 🖥️ **CENA 4 — A ENTRADA DO PLC**

Para controlar o sistema, foi adquirido um PLC simples. Porém, ele possui limitações importantes:

- 8 entradas/saídas (I/O)  
- Aceita apenas duas linguagens:  
  - **Grafcet**  
  - **Blocos Lógicos**

Com essas limitações, os estudantes precisam criar uma lógica de controle capaz de proteger as baterias e otimizar o uso das placas solares.

---

## 🎯 **CENA 5 — AS REGRAS DO DESAFIO**

A bateria possui **4 sensores de nível**, identificados como:

```
S1 – Nível baixo  
S2 – Nível médio  
S3 – Nível alto  
S4 – Carregada totalmente
```

Cada sensor ativado representa um nível maior de carga.

As placas são representadas como:

```
P1, P2, P3 e P4
```

A lógica funciona assim:

- Quando **nenhum sensor** está acionado → ligar as 4 placas (P1–P4).  
- Quando **S1** está acionado → ligar apenas 3 placas (P1, P2, P3).  
- Quando **S1 + S2** → ligar apenas 2 placas (P1, P2).  
- Quando **S1 + S2 + S3** → ligar apenas 1 placa (P1).  
- Quando **todos os sensores** (S1–S4) estão acionados → **todas as placas devem ser desligadas**.  
- Caso **qualquer sensor falhe** → desligar todas as placas imediatamente.

---

## 🧩 **CENA 6 — FERRAMENTAS FORNECIDAS**

Para facilitar o desenvolvimento, foram disponibilizados dois arquivos no FluidSim:

```
Blocos.ct   – Para programação em Blocos Lógicos  
Graf.ct     – Para programação em Grafcet
```

Além disso, uma versão portable do FluidSim está disponível para download.

Cada equipe pode escolher a linguagem com que deseja trabalhar.

---

## 🖼️ **CENA 7 — INTERFACE DE PROGRAMAÇÃO**

Os estudantes terão acesso a:

- O módulo de sensores (S1–S4)  
- O módulo das placas solares (P1–P4)  
- A torre de carga representando a bateria  

Para programar:

- Em Blocos Lógicos → clique duas vezes no PLC  
- Em Grafcet → programe ao lado do circuito  

Um vídeo explicativo está disponível no Teams.

---

## 📦 **CENA 8 — ENTREGA DO TRABALHO**

A atividade deve ser realizada em grupo de até **3 integrantes**.  
Cada aluno deve enviar sua própria cópia do arquivo **.ct**, renomeado no formato:

```
SeuNome_RA.ct
```

---

## 🧠 **CENA 9 — DICAS DO PROFESSOR**

Para facilitar o desenvolvimento da solução:

- Monte um **mapeamento de I/O** antes de programar.  
- Crie uma **tabela verdade** para visualizar a lógica que controla as placas.  
- Teste cada função separadamente antes de integrar todas.  
- Priorize segurança: qualquer comportamento inesperado deve desligar o sistema.

---

## 🏁 **CENA 10 — ENCERRAMENTO**

Este desafio une energia renovável, automação industrial, lógica de programação e responsabilidade social.

Através dele, os estudantes compreendem como a tecnologia pode transformar realidades, levando energia limpa e segura para lugares onde ela nunca chegou.

**WE ARE TOGETHER!:**  

---

## 👤 **CRÉDITOS**

**Orientação:**  
Prof. MSc. Adilson Cunha Rusteiko


