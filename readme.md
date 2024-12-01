# **🌐 Tradutor de Artigos Técnicos com AzureAI**

Um projeto que utiliza o poder da inteligência artificial do **Azure OpenAI** para traduzir artigos técnicos de maneira rápida, eficiente e preservando a formatação Markdown, incluindo imagens e links. Ideal para desenvolvedores e profissionais que desejam consumir conteúdos em sua língua nativa, sem perder a essência técnica.

---

## **📝 Descrição**

O **Tradutor de Artigos Técnicos com AzureAI** automatiza o processo de tradução de artigos de sites, mantendo a formatação original e facilitando a leitura.  
Este projeto utiliza modelos avançados da família GPT para traduzir textos técnicos para **Português do Brasil (pt-br)**, preservando a estrutura de Markdown, imagens e vídeos.

---

## **💻 Tecnologias Utilizadas**

As seguintes tecnologias e ferramentas foram empregadas no desenvolvimento deste projeto:

- **Linguagem:** Python 3.x
- **APIs:** Azure OpenAI
- **Bibliotecas:** 
  - `openai` (para integração com Azure OpenAI)
  - `requests` (para buscar conteúdo de URLs)
  - `BeautifulSoup` (para parsing de HTML)
- **Formatos de Saída:** Markdown (`.md`)

---

## **⚙️ Processo de Criação**

1. **Planejamento**:
   - Definir o objetivo do projeto: traduzir artigos técnicos para `pt-br` com preservação de formatação.
   - Escolher tecnologias compatíveis com a API Azure OpenAI.

2. **Integração com Azure OpenAI**:
   - Configurar um recurso de Azure OpenAI.
   - Criar e configurar um deployment do modelo GPT (`gpt-4o-mini`).

3. **Desenvolvimento**:
   - **Extração de Conteúdo**:
     - Usar a biblioteca `requests` para acessar o HTML da URL fornecida.
     - Utilizar o `BeautifulSoup` para extrair título, texto e imagens.
   - **Tradução**:
     - Enviar o conteúdo extraído para a API do Azure OpenAI.
     - Configurar prompts para tradução precisa e preservação de formatação.
   - **Formatar em Markdown**:
     - Combinar título, conteúdo traduzido e imagens em um documento Markdown bem estruturado.

4. **Testes**:
   - Validar com diferentes URLs e formatos de artigos.
   - Verificar se todas as traduções preservam a semântica e a estrutura original.

---

## **📊 Resultados**

- **🚀 Eficiência:** A API traduz com precisão textos técnicos para `pt-br`, reduzindo o tempo necessário para consumo de conteúdos estrangeiros.
- **🎨 Preservação de Formatação:** Imagens, links e estrutura Markdown são mantidos.
- **🌍 Aplicação Ampla:** Pode ser utilizado por desenvolvedores, equipes técnicas e estudantes para aprendizado e documentação.

---

## **🤔 Reflexão**

Este projeto demonstra a capacidade das tecnologias de IA para lidar com tarefas desafiadoras, como tradução técnica e preservação de formatação. Durante o desenvolvimento:

- Foi interessante explorar a integração com o **Azure OpenAI**.
- Aprendemos sobre a importância de prompts bem definidos para obter resultados consistentes.
- Desafios encontrados:
  - Lidar com URLs com estrutura HTML incomum.
  - Garantir a preservação exata de imagens e links.

No futuro, o projeto pode ser expandido para suportar mais idiomas, formatos de entrada e saídas personalizadas, como PDF ou apresentações.

---
