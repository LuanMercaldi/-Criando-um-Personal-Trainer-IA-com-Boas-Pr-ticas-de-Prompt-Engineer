<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://www.dio.me/users/luanwp" title="Curriculum"><img src="https://img.shields.io/badge/DIO-Curriculum-FED564"></a>
<a href="https://www.linkedin.com/in/luan-mercaldi-88080890/" title="Profile"><img src="https://img.shields.io/badge/LinkedIn-Profile-FED564?"></a>
<a href="https://chatgpt.com/" title="Powered by ChatGpt">
  <img src="https://img.shields.io/badge/Powered%20by-ChatGPT-FED564?">
</a>
</p>

<p align="center">
  <h3 align="center">🤖 Personal Trainer Virtual</h3>
    
Bem-vindo ao **Personal Trainer Virtual!** Esse bot foi desenvolvido como parte de um **desafio de Prompt Engineer** e vai ajudar você a criar treinos personalizados com base nas suas respostas a algumas perguntas rápidas e simples. Vamos nessa? 💪
</p>

---

## 📋 Índice

- [📋 Índice](#-índice)
- [🚀 O que o Bot Faz?](#-O-que-o-Bot-Faz)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [💡 Como Funciona?](#-Como-Funciona)
- [🔄 Como Atualizar as Preferências?](#-Como-Atualizar-as-Preferências)
- [📊 Benefícios](#-Benefícios)
- [📸 Exemplos Visuais](#-Exemplos-Visuais)
- [⚠️ Importante](#-Importante:-Procure-um-Profissional-Qualificado!)
- [📖 Material de Apoio](#-material-de-apoio)
- [👨‍💻 Expert](#-Expert)

---

## 🚀 O que o Bot Faz?

O **Personal Trainer Virtual** gera um plano de treino totalmente customizado para você, considerando seu biotipo, preferências de exercício e quantos dias por semana você pode treinar. Tudo isso em poucos passos! 🏋️‍♂️

Este projeto tem como objetivo criar um **prompt que auxilia a montar o treino ideal** para cada combinação de fatores, como:

- **Biotipo Corporal**: Ectomorfo, Mesomorfo, Endomorfo, ou indefinido.
- **Disponibilidade de Tempo**: Quantos dias por semana você pode treinar.
- **Tipo de Exercícios Preferidos**: Funcional, Maquinário, Peso Livre, Cardio, HIIT.

O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário, utilizando as **melhores práticas de Prompt Engineering**.


Combinando tecnologia e conhecimento em fitness, esse bot vai facilitar a criação do **treino ideal** para cada usuário, ajudando-o a atingir seus objetivos de forma eficaz e personalizada.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/Interrogacao.png" width="50%" height="50%">
    </td>
    <td><strong>Não sei, me ajude!</strong></td>
    <td>Não tem problema, dá uma olhada neste vídeo [aqui](www.youtube.com/watch?v=UTHHEOqJIaU) que vai te ajudar a entender melhor. 🎥
</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 🏋️ Tipos de Exercícios

A Segunda regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Treinos com movimentos naturais, que trabalham o corpo todo de forma equilibrada.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Você curte aparelhos de academia? Então essa é a opção ideal.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Se você prefere treinar com halteres e barras, essa é a escolha. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Gosta de correr, pedalar ou fazer exercícios de resistência? Cardio é para você!                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Quer treinos curtos e intensos para queimar gordura? O HIIT vai te desafiar! 🔥                                      |

---

## 📅 Dias Disponíveis para Treino

A Terceira regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: O bot vai sugerir um treino Full Body, ou seja, para o corpo inteiro em uma única sessão.
- **ABC**: Você vai receber um treino ABC, que divide os grupos musculares em três dias.
- **ABCDE**: Aqui o treino é mais avançado, com um plano ABCDE, onde cada dia tem um foco específico.

---

## 💡 Como Funciona?

1. **Você Responde Algumas Perguntas:**

   - O bot vai perguntar sobre o seu tipo de corpo, o tipo de treino que você prefere e quantos dias você tem disponível para treinar.
   - Exemplo de perguntas:
     - Qual é o seu biotipo corporal?
     - Você prefere treinar com pesos livres, máquinas, ou prefere cardio?
     - Quantos dias por semana você pode treinar?
    
2. **Lembre-se de Incluir Sua Base de Conhecimento:**

   - Antes de iniciar o processo, certifique-se de que o bot tenha acesso ao arquivo (abra [AQUI!](https://github.com/LuanMercaldi/-Criando-um-Personal-Trainer-IA-com-Boas-Praticas-de-Prompt-Engineer/raw/main/.github/assets/Base_de_Conhecimento.txt)) que contém todas as informações para definir qual será a melhor opção de treino para você.
   - Clique com o botão direito, em seguinda "salvar página como", escolha o local desejado para salvar o arquivo e clique em salvar.
   - Anexe o arquivo baixado no seu LLM favorito
   - Insira também o seguinte prompt para guiar o bot no seu treino:

   ```plaintext
   Baseado nessa base de conhecimento, quero que você aja como o personal trainer, não quero que dê sugestões de respostas, quero que use as perguntas pra me avaliar e em seguida defina qual o melhor treino.

3. **O Bot Gera um Treino Personalizado:**

   - Com base nas suas respostas, o bot monta um plano de treino, com dicas sobre séries, repetições e intensidade. Tudo feito sob medida! 🎯

5. **Você Treina e Acompanha seu Progresso:**

   - Agora é só seguir o plano, marcar os dias de treino, e ver os resultados! 🔥

---

## 🔄 Como Atualizar as Preferências

Se você quiser mudar o tipo de treino ou a quantidade de dias disponíveis, é só resetar o bot e responder novamente às perguntas. Ele ajusta tudo rapidinho para você. 😉

Para entender como o bot toma decisões, consulte a **[Base de Conhecimento](https://github.com/LuanMercaldi/-Criando-um-Personal-Trainer-IA-com-Boas-Praticas-de-Prompt-Engineer/raw/main/.github/assets/Base_de_Conhecimento.txt)**. Se quiser alterar a base, basta baixar o arquivo de texto, fazer as mudanças necessárias e subir o arquivo atualizado no ChatGPT. Pronto, seu bot estará com as novas informações personalizadas! 🛠️


---

## 📊 Benefícios

- **Personalização Total**: Seu treino vai ser 100% baseado nas suas respostas.
- **Simples e Rápido**: Sem complicações, você define tudo em poucos minutos.
- **Adapta-se ao seu Tempo**: Quer treinar 1, 3, 5 dias? O bot se ajusta à sua agenda.

---

## 📸 Exemplos Visuais

Aqui está um exemplo de como você verá as perguntas na interface do bot:

![image](https://github.com/user-attachments/assets/b51e977a-5f55-4d35-b2c9-7500a9ccb491)


*Na tela acima, você pode escolher o seu biotipo corporal.*

![image](https://github.com/user-attachments/assets/f3b66a4d-b4f0-4722-b7f2-b1b1166fc734)

*Nessa tela, você pode selecionar o seu exercício favorito.*

![image](https://github.com/user-attachments/assets/cb766e98-9a79-41bd-8971-48d78dc18cd9)

*Aqui, você pode definir quantos dias na semana pode treinar.*

![image](https://github.com/user-attachments/assets/4911d39f-1ff8-411b-bc82-1ed9bc065377)


*Então o BOT define o melhor treino pra você.*

---

## ⚠️ Importante: Procure um Profissional Qualificado!

Embora o **Personal Trainer Virtual** ofereça planos de treino personalizados, ele não substitui a orientação de um profissional qualificado. Cada pessoa tem necessidades e limitações específicas que devem ser acompanhadas por um especialista. 💡

Sempre que possível, **consulte um educador físico ou personal trainer** para garantir que os exercícios e as cargas estão adequados ao seu corpo e seus objetivos. O uso de Inteligência Artificial pode ser um grande suporte, mas a supervisão de um profissional é essencial para evitar lesões e maximizar resultados! 🏋️‍♂️

---

Esperamos que você aproveite o máximo desse bot e que ele te ajude a alcançar seus objetivos de treino! Se precisar de alguma coisa, estamos por aqui. 😄👊

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 👨‍💻 Expert

<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="https://github.com/user-attachments/assets/445d5b33-1db7-4cb4-a54b-a11a691de257"
    />
    <p>&nbsp&nbsp&nbspLuan Mercaldi<br>
    &nbsp&nbsp&nbsp
    <a href="https://www.dio.me/users/luanwp">
    DIO</a>&nbsp;|&nbsp;
    <a href="https://www.linkedin.com/in/luan-mercaldi-88080890/">LinkedIn</a>
</p>
<br/><br/>
<p>

---

⌨️ com 💜 por [Luan Mercaldi](https://github.com/LuanMercaldi)

