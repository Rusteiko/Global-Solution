# 🎥 SCRIPT OFICIAL – GLOBAL SOLUTION 2025  
## Unidade Robótica de Resgate em Áreas Isoladas  
### Cinemática e Robótica Industrial – 1º Semestre

---

## 🎬 **CENA 1 — ABERTURA**

Quando a natureza se impõe, cada segundo pode significar a diferença entre vida e morte. Terremotos, avalanches e nevascas severas deixam regiões inteiras inacessíveis — isolando comunidades e equipes de exploração.  

Para esses cenários extremos, a tecnologia se torna um aliado indispensável.  
A **Global Solution 2025 – 1º Semestre** desafia os estudantes a projetar soluções robóticas inspiradas em iniciativas reais da **Boston Dynamics**, **Cruz Vermelha** e operações humanitárias internacionais.

---

## 🌨️ **CENA 2 — O AMBIENTE DO DESAFIO**

A FIAP construiu no CoppeliaSim um ambiente hostil e imponente:  

```
HIMALAIA FIAP — A Simulação de Montanhas Nevadas
```

Uma região desértica, congelada e completamente inadequada à sobrevivência humana.  
Entre montanhas estreitas e vales profundos, dois grupos de exploradores partiram em direções opostas para mapear a área.

---

## 🧭 **CENA 3 — AS EQUIPES DE EXPLORAÇÃO**

O primeiro grupo, identificado pelas **jaquetas amarelas**, saiu pela rota oeste.  
O segundo grupo, com **jaquetas vermelhas**, seguiu rumo leste.

Ambas as equipes mantiveram comunicação…  
Até que uma nevasca inesperada tomou toda a região, interrompendo sinais e apagando trilhas.

As duas equipes ficaram **perdidas**, incapazes de retornar para a base de apoio.

---

## 🚁 **CENA 4 — O DRONE DE RESGATE**

Como reforço, a FIAP disponibilizou um **robô drone autônomo**, posicionado ao lado da cabana de controle e pronto para decolar assim que receber o algoritmo de busca.

A missão:  
Localizar os dois grupos perdidos e guiá-los de volta ao conhecimento da equipe de resgate.

---

## 🧊 **CENA 5 — CRITÉRIOS DA MISSÃO**

A região montanhosa cria um corredor natural de fendas.  
Por isso, o drone deve seguir regras específicas de navegação:

- Voo entre fendas para não ultrapassar a altura máxima.  
- Não voar muito baixo para evitar colisão com a neve.  
- Manter a altitude operacional entre:
  ```
  Min: 1.1  
  Max: 1.5  
  ```
- Altitude especial em caso de colisão:
  ```
  Z = 2.0
  ```

Ao encontrar cada grupo, o drone deve:

```
1. Subir à altura determinada.
2. Realizar uma trajetória circular ao redor do grupo.
3. Permitir que a equipe de resgate visualize a posição.
4. Seguir imediatamente em busca do próximo grupo.
```

---

## 🗺️ **CENA 6 — POSIÇÃO INICIAL E FINAL**

O drone deve iniciar e finalizar seu percurso na mesma coordenada:

```
X = +1.0732e+01  
Y = +1.0696e+01  
Z = +5.9700e-01
```

A missão só é concluída quando ambos os grupos forem encontrados **e** o drone retornar à base com segurança.

---

## 🧠 **CENA 7 — ESTRATÉGIA SUGERIDA**

O professor recomenda o uso de **4 Paths**:

- 2 paths de trajetória (para a busca da equipe amarela e vermelha)  
- 2 paths circulares abertos (para orbitar cada grupo encontrado)

Um vídeo demonstrativo foi disponibilizado no Teams para referência.

---

## 💻 **CENA 8 — O DESAFIO DE PROGRAMAÇÃO**

O estudante deve programar em **LUA**:

- O percurso do drone pelas fendas  
- A mudança de altitude conforme a região  
- A busca e reconhecimento visual dos grupos  
- A trajetória circular ao redor de cada equipe  
- O retorno seguro à base

A atividade é **individual** — cada estudante precisa desenvolver sua própria solução.

---

## 📦 **CENA 9 — O QUE ENTREGAR**

O aluno deve enviar:

- 🎞️ **Vídeo explicando a programação em LUA**
- 🗂️ **Arquivo do CoppeliaSim (.ttt)** com seu nome no arquivo
- 📌 O drone funcionando do início ao fim, encontrando os dois grupos

---

## 🏁 **CENA 10 — ENCERRAMENTO**

Na Global Solution, tecnologia e propósito caminham juntos.  
Este desafio conecta robótica, autonomia, cinemática e impacto humano.  

É um exercício de engenharia, mas também um lembrete:  
Quando tudo desmorona, é a inovação que abre novos caminhos de esperança.

**WE ARE TOGETHER!**  

---

## 👤 **CRÉDITOS**

**Orientação:**  
Prof. MSc. Adilson Cunha Rusteiko 


