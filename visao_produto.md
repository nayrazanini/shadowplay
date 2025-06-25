# 📘 Documento de Visão do Produto – ShadowPlay

## 1. Nome do Sistema
**ShadowPlay** – Plataforma colaborativa para prática de inglês com técnica de shadowing

---

## 2. Visão Geral

### 2.1 Objetivo do Sistema
Oferecer um ambiente digital acessível, ético e personalizado para estudantes de inglês praticarem speaking com a técnica de *shadowing*, utilizando vídeos do YouTube classificados por nível, tema e tempo. O sistema oferece transcrição, tradução (para iniciantes) e apoio com inteligência artificial para personalização e análise da prática.


---

## 2.2 Como surgiu a ideia

A ideia do ShadowPlay surgiu a partir da minha própria experiência pessoal como estudante de inglês. Durante minhas tentativas de praticar com a técnica de *shadowing*, percebi como era difícil encontrar vídeos apropriados ao meu nível de proficiência.

Muitos conteúdos disponíveis no YouTube não ofereciam:
- Legendagem em inglês de forma clara
- Trechos curtos com linguagem cotidiana
- Uma maneira fácil de repetir frases para praticar
- Classificação por nível ou tema

Notei que mesmo vídeos educativos às vezes eram longos, avançados ou sem transcrição adequada. Isso dificultava a constância na prática, principalmente quando o tempo era curto e a organização dependia apenas de mim.

Com isso, percebi que **faltava uma ferramenta centralizada, simples e personalizada para praticar shadowing**. O ShadowPlay nasce como uma solução para preencher essa lacuna, unindo experiência real, análise técnica e proposta educacional.

---


## 3. Problema que o Sistema Resolve

Muitos estudantes de inglês, especialmente autodidatas ou sem acompanhamento pedagógico, enfrentam dificuldades como:

- Encontrar vídeos adequados ao seu nível de proficiência
- Praticar speaking com repetição eficiente sem ferramentas manuais
- Ter acesso a transcrição sincronizada com o áudio
- Receber feedback ou recomendações personalizadas
- Manter regularidade e constância nos estudos

**ShadowPlay** centraliza essas funcionalidades em um só lugar, com foco em experiência do usuário e acessibilidade.

---

## 4. Stakeholders

| Stakeholder                 | Papel no projeto                                         |
|----------------------------|----------------------------------------------------------|
| Estudantes de inglês       | Usuários finais do sistema                               |
| Professores de idiomas     | Potenciais promotores e avaliadores do sistema           |
| Criadores de conteúdo      | Autores dos vídeos utilizados de forma legal (YouTube)   |
| Desenvolvedora (Náyra)     | Idealizadora, projetista e responsável técnica           |
| Plataformas de ensino (futuro) | Parceiros educacionais para expansão do sistema      |

---

## 5. Justificativa do Projeto

- Crescimento da técnica de shadowing no ensino de idiomas
- Popularização do aprendizado autodidata com vídeos
- Demanda crescente por sistemas educacionais personalizados com IA
- Projeto educativo e ético, com grande potencial de portfólio e impacto social

---

## 6. Diferenciais Estratégicos

- IA para seleção inteligente de vídeos e análise de pronúncia
- Interface simples, responsiva e voltada para fluência real
- Curadoria colaborativa e participação ativa da comunidade
- Expansível para outros métodos de estudo (Pomodoro, flashcards, etc)
- Respeito aos direitos autorais dos criadores de conteúdo

---

## 7. Versão Inicial (MVP)

- Página com vídeos embedados e transcrição manual
- Filtros por nível, tempo e tema
- Modo shadowing com repetição de frases
- Formulário de sugestão de vídeos
- Primeira análise IA simulada (sem integração real)

---

## 8. Tecnologias e Ferramentas Envolvidas

- HTML, CSS, JavaScript
- GitHub Pages
- Figma (protótipos)
- YouTube Data API
- OpenAI Whisper (futuro)
- Markdown para documentação

---

## 9. Status do Projeto
Em desenvolvimento. Primeira versão publicada como MVP no GitHub Pages para validação e portfólio.

---


## 10. Expansão Futura: Integração com Criadores de Conteúdo e Plataformas como TikTok

### 10.1 Divulgação de Vídeos Educativos
O ShadowPlay poderá se tornar um espaço de apoio à divulgação de vídeos educativos sobre inglês e técnicas como *shadowing*, produzidos por criadores de conteúdo em plataformas como TikTok, YouTube Shorts e Instagram.

- Criadores poderão submeter seus vídeos via formulário no site
- A curadoria será feita com apoio de inteligência artificial e validação da comunidade
- O sistema poderá destacar vídeos por tema, clareza, método aplicado e nível de ensino

> Objetivo: **dar visibilidade a quem ensina com qualidade** e facilitar a descoberta de bons vídeos por quem está aprendendo.

### 10.2 Templates para Produção de Conteúdo Educativo
Para apoiar novos educadores, o site oferecerá **templates prontos para download**, com estrutura de vídeo e áudio pensados para facilitar a criação de conteúdo didático.

- Disponibilizados mediante login básico gratuito
- Permitirão a criação de vídeos mesmo **sem necessidade de aparecer**
- Incluirão sugestões de roteiro, legendas automáticas, estrutura de slide animado etc.

> Objetivo: democratizar a criação de conteúdo educacional, ajudando quem tem conhecimento a compartilhar de forma acessível e profissional.

---



---

## 11. Modelo de Sustentabilidade e Monetização

O ShadowPlay poderá, futuramente, oferecer um modelo de negócio ético, com foco em criadores de conteúdo e usuários engajados. A ideia é equilibrar **acesso livre à prática de inglês** com **vantagens e conteúdos exclusivos mediante assinatura**.

### 11.1 Assinatura para Criadores de Conteúdo
- Criadores de vídeos educativos poderão assinar uma modalidade premium com acesso a:
  - Templates exclusivos para produção de vídeos (formato vertical, roteiros, overlays)
  - Destaque na plataforma com curadoria e ranqueamento por engajamento
  - Ferramentas de IA para análise de voz e feedback dos vídeos enviados
  - Painel com métricas de visualização e engajamento no ShadowPlay

### 11.2 Restrição Inteligente por Volume de Acesso
- Usuários iniciantes poderão acessar vídeos normalmente
- A IA monitorará o número de vezes que um vídeo foi acessado por IP ou login
- Após certo limite, a facilidade de acesso poderá ser reduzida:
  - Ex: trechos embaralhados, limite diário de vídeos ou prática sem transcrição
  - A versão completa permanecerá disponível para quem assina o plano premium

> A proposta é incentivar o apoio à plataforma sem bloquear o aprendizado, respeitando os diferentes perfis de usuários.

---

## 12. Próximos Passos
- Modelagem dos requisitos funcionais e não funcionais
- Definição dos principais fluxos de usuário (casos de uso e jornada)
- Protótipo inicial no Figma com base nas funcionalidades do MVP
- Elaboração de roadmap para possíveis integrações com APIs e IA

---

**Última atualização:** Junho/2025  

