# 🐳 Aprendendo Docker com apoio de IA

Este repositório contém o Caderno Temático criado para o desafio da DIO, explorando o uso de Inteligência Artificial (NotebookLM) como ferramenta de aprendizagem ativa para entender o universo do **Docker**.

---

## 🎯 1. Contexto e Objetivos

**Tema Escolhido:** Docker e a "mágica" dos Containers.

Eu escolhi estudar o Docker porque ouço falar muito que ele é essencial para quem quer trabalhar com tecnologia hoje em dia, mas o conceito parecia muito confuso. Meu objetivo com esse caderno temático é sair do zero absoluto e entender:
1. O que é o Docker de um jeito simples (sem aquele monte de termo técnico difícil).
2. Qual a diferença entre usar Docker e usar uma Máquina Virtual normal.
3. Entender o que significam os termos básicos (Imagem, Container, Dockerfile).

---

## 📚 2. Curadoria de Fontes

Para alimentar o meu NotebookLM e garantir que a IA não inventasse coisas da cabeça dela, eu selecionei e fiz o upload dos seguintes materiais (fontes confiáveis):

1. **Documentação Oficial do Docker (Guia de Introdução):** [Link para o Docker Docs](https://docs.docker.com/get-started/) - *Salvei em PDF e subi no Notebook.*
2. **Artigo "O que é Docker?" da Red Hat:** [Link para a Red Hat](https://www.redhat.com/pt-br/topics/containers/what-is-docker) - *Excelente para entender o conceito de mercado.*
3. **Artigo "Docker para Iniciantes":** [Link de algum blog tech como Dev.to ou Medium] - *Usei para pegar exemplos mais práticos e de fácil leitura.*

*(Nota: Forneci esses textos para o NotebookLM ler e basear todas as respostas neles).*

---

## 🧠 3. Engenharia de Prompts e "Cicatrizes"

Aqui eu mostro como foi a minha "conversa" com a IA e como fui melhorando minhas perguntas (prompts) para conseguir respostas melhores.

**Tentativa 1 (O erro de ser muito genérico):**
* **Meu Prompt:** *"O que é Docker?"*
* **A Resposta da IA:** A IA me deu uma resposta super técnica falando sobre "virtualização de nível de sistema operacional" e "kernel".
* **Minha Cicatriz (Troubleshooting):** Eu percebi que se eu não der um contexto para a IA, ela me responde como se eu fosse um engenheiro sênior. Fiquei mais confuso do que antes!

**Tentativa 2 (Ajustando o alvo - Muito melhor!):**
* **Meu Prompt:** *"Com base nos documentos, explique o que é Docker e qual a diferença dele para uma Máquina Virtual. Use uma analogia com coisas do dia a dia, como se estivesse explicando para um jovem de 17 anos que não sabe nada de programação."*
* **A Resposta da IA:** A IA usou a analogia de "Containers de Navio" e explicou que as máquinas virtuais são como construir casas inteiras separadas, enquanto o Docker é como alugar quartos em um mesmo hotel, dividindo a estrutura (o sistema operacional) e economizando muito espaço e recursos.

**Tentativa 3 (Focando no vocabulário):**
* **Meu Prompt:** *"Liste os 4 termos mais importantes do Docker mencionados nos textos e crie um mini-dicionário simples de 1 linha para cada um."*
* **A Resposta da IA:** *(Ela gerou o glossário que coloquei na seção abaixo).*

---

## 📖 4. Miniguia de Estudo

Com base nas minhas interações com o NotebookLM, este é o resumo do que aprendi:

### 📝 Resumo Estruturado: O que é Docker?
O Docker é uma plataforma que empacota, entrega e roda aplicações (programas) em "caixas" isoladas chamadas de **Containers**. 
* **O problema que ele resolve:** Sabe quando um jogo ou programa funciona no computador do seu amigo, mas no seu dá erro porque falta algum arquivo? O Docker resolve isso. Ele coloca o programa e **TUDO** que ele precisa para funcionar dentro de um container. Assim, se roda no computador do criador, vai rodar exatamente igual em qualquer outro lugar.
* **Docker vs Máquina Virtual:** Uma Máquina Virtual instala um sistema operacional inteiro (como um Windows gigante) só para rodar um app, gastando muita memória. O Docker é mais inteligente: ele usa o sistema operacional que já está lá e só isola os programas. É muito mais leve e rápido!

### 🔡 Glossário (Conceitos Principais)
* **Container:** É a "caixa" rodando. É o seu programa funcionando de forma isolada e leve.
* **Imagem (Image):** É a "receita de bolo" ou o molde. É o arquivo que diz como o Container deve ser criado (não roda, só serve de base).
* **Dockerfile:** É um arquivo de texto com as instruções passo a passo para criar uma Imagem.
* **Docker Hub:** É como se fosse a "App Store" ou o "GitHub" do Docker, onde as pessoas guardam e baixam Imagens prontas da internet.

### ♻️ Prompts Reutilizáveis (Para Revisão Futura)
Se eu precisar relembrar esse assunto daqui a alguns meses, posso jogar esses prompts na IA de novo:
1. *"Resuma os comandos
