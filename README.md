
#**Aprendendo Git e GitHub com NotebookLM**

---

## OBJETIVO

Escolhi estudar Git e GitHub por serem ferramentas fundamentais para qualquer programador. Elas permitem realizar o controle de versão dos projetos, organizar o desenvolvimento do código, acompanhar alterações ao longo do tempo e facilitar o trabalho colaborativo entre desenvolvedores.

Além dos benefícios técnicos, o domínio dessas ferramentas é considerado um requisito básico para quem está iniciando na área de tecnologia. O GitHub também funciona como um portfólio, permitindo compartilhar projetos e demonstrar conhecimentos para recrutadores e empresas, aumentando as oportunidades de estágio e emprego.

O objetivo deste caderno temático é consolidar os principais conceitos de Git e GitHub utilizando o NotebookLM como ferramenta de apoio aos estudos, reunindo resumos, definições e materiais que possam servir como referência para futuras revisões.

---

## FONTES

- Pro Git (2ª Edição)
- Curso em Vídeo – Git e GitHub
- Slides em PDF do curso **Git e GitHub** – Curso em Vídeo (Gustavo Guanabara).

---

## PROMPTS UTILIZADOS

### PROMPT 1

**Pergunta**
> Explique Git.

**Resposta obtida:**
O modelo destacou que o Git é um sistema de versionamento distribuído, abordando conceitos como : snapshot, SHA-1, Working Tree, Staging Area.

 ### PROMPT 2(Refinado)

**Pergunta**
> Explique o que é Git de uma forma bem simples e de fácil entendimento, utilizando exemplos simples do dia a dia.

**Resposta obtida:**
O Git é um sistema de controle de versão que funciona como uma máquina do tempo para seus arquivos, salvando "fotos" (snapshots) do estado do seu projeto em diferentes momentos. Ele permite que você organize o histórico de alterações, trabalhe em equipe e teste novas ideias através de ramificações (branches) sem o risco de perder o que já está pronto.
- Exemplo prático: Em vez de você ter uma pasta bagunçada com arquivos chamados trabalho-v1.doc, trabalho-v2-final.doc e trabalho-final-mesmo.doc, o Git mantém apenas um arquivo visível e armazena todas as versões passadas internamente. Se você apagar algo importante por erro, pode simplesmente pedir ao Git para "voltar no tempo" e restaurar a versão exata de ontem ou de uma semana atrás

### PROMPT 3

**Pergunta**
> Explique o que é Markdown.

**Resposta obtida:**
O modelo destacou que Markdown é uma linguagem de marcação que permite escrever em texto simples, mas que é processada para ser exibida como texto rico (formatado) Em vez de usar editores visuais complexos, você utiliza símbolos simples para estruturar o conteúdo.

### PROMPT 4

**Pergunta**
> Explique o que é Issues.

**Resposta obtida:**
O NotebookLM explicou que  No contexto do GitHub e de plataformas similares como o GitLab, Issues (problemas ou questões) são as unidades básicas de discussão e organização de um projeto. Elas funcionam como um sistema de rastreamento onde a equipe e a comunidade podem relatar bugs, sugerir novas funcionalidades ou discutir tarefas pendentes.

### PROMPT 5

**Pergunta**
> Explique o que são Branches.

**Resposta obtida:**
No contexto do Git, branches (ou ramificações) são um dos recursos mais poderosos da ferramenta, sendo frequentemente descritos como sua "killer feature" por serem extremamente leves e rápidos.

### PROMPT 6(Refinado)

**Pergunta**
>explique o que são Branches de forma uma simples e sem termos complexos, e de exemplos do mundo real para ajudar.

**Resposta obtida:**
As Branches (ou ramificações) são como caminhos paralelos no seu projeto. Elas permitem que você saia da linha principal de desenvolvimento para testar novas ideias, criar funcionalidades ou corrigir erros sem "sujar" ou estragar o código que já está funcionando e estável.
- Exemplo Prático: Pense na branch principal como a sua casa pronta. Se você quiser testar uma cor de tinta nova na sala, você cria um "ambiente virtual" (branch) para ver como fica. Você pode pintar e mudar tudo lá sem que as visitas na sua "casa real" vejam a bagunça até que você decida que a reforma ficou perfeita e a aplique definitivamente.

---

## DIFICULDADES ENCONTRADAS (CICATRIZES)

- O primeiro prompt ("explique Git.") o modelo respondeu corretamente, porém foi utilizado muitos conceitos técnicos para um iniciante como snapshot, SHA-1 e Staging Area sem uma explicação simplificada.
- Ao reformular melhor o prompt utilizando a engenharia de prompts o modelo retornou a resposta em uma linguagem mais simples e exemplos do cotidiano , o NotebookLM forneceu uma resposta mais didatica de facil de compreendimento.
- O mesmo ocorreu ao estudar Branches. A primeira resposta utilizou o termo "killer feature", que não era familiar. Após pedir uma explicação sem termos complexos, a resposta ficou mais clara.

---

## MINIGUIA DE ESTUDO

### Resumo

O Git é um sistema de controle de versão distribuído que permite registrar, organizar e recuperar alterações realizadas em um projeto. Com ele, é possível trabalhar em equipe, criar diferentes versões do código e restaurar estados anteriores quando necessário.

Já o GitHub é uma plataforma que hospeda repositórios Git na nuvem, facilitando o compartilhamento de projetos, o trabalho colaborativo e a criação de um portfólio para desenvolvedores.

Entre os principais conceitos estudados estão commits, branches, merge, clone, push, pull e issues, que fazem parte do fluxo de trabalho de desenvolvimento utilizando Git e GitHub.

**Fluxo básico:**

`git init → git add → git commit → git push`

---

### Glossário

| Termo | Definição |
|-------|-----------|
| Git | Sistema de controle de versão distribuído. |
| GitHub | Plataforma para hospedagem de repositórios Git. |
| Repositório | Local onde o projeto e seu histórico são armazenados. |
| Commit | Registro permanente das alterações realizadas. |
| Branch | Ramificação utilizada para desenvolver novas funcionalidades sem afetar a principal. |
| Merge | Une alterações de uma branch em outra. |
| Clone | Cria uma cópia local de um repositório remoto. |
| Push | Envia alterações do computador para o repositório remoto. |
| Pull | Atualiza o repositório local com alterações do remoto. |
| Issues | Ferramenta para registrar bugs, tarefas e sugestões de melhoria. |
| Markdown | Linguagem de marcação simples utilizada para formatar arquivos README. |

---

### Prompts Reutilizáveis

- Explique este conceito para um iniciante utilizando linguagem simples.
- Apresente exemplos práticos do dia a dia para facilitar o entendimento.
- Faça um resumo estruturado do conteúdo em tópicos.
- Crie um glossário com os principais termos estudados.
- Elabore um quiz com 10 perguntas sobre o tema.
- Compare dois conceitos utilizando uma tabela.
- Explique quando utilizar determinado recurso na prática.


