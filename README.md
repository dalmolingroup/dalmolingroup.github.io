# dalmolingroup.github.io

Visit **[dalmolingroup.github.io](https://dalmolingroup.github.io)** 🚀

_Built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_

## Como adicionar ou editar seu perfil no site

Se você é membro do grupo (ou ex-membro/alumni), pode adicionar ou editar sua página e foto diretamente pela interface web do GitHub. Siga os passos abaixo:

### 1. Adicionando sua foto

- Navegue até a pasta `images/team/` neste repositório.
- Clique no botão **Add file** no canto superior direito e depois em **Upload files**.
- Faça o upload da sua foto (preferencialmente quadrada, ex: `seu_nome.jpg`).
- Clique em **Commit changes...** para salvar a foto.

### 2. Criando ou editando sua página de perfil

- Navegue até a pasta `_members/`.
- Para editar um perfil existente, clique no arquivo com o seu nome e depois no ícone de lápis ✏️ (**Edit this file**).
- Para criar um novo perfil, clique em **Add file** > **Create new file**.
- Nomeie o arquivo como `seu_nome.md` (use letras minúsculas e _underline_ em vez de espaços).

### 3. Preenchendo os dados

Copie o modelo abaixo e cole no seu arquivo, ajustando com suas informações:

```yaml
---
name: Seu Nome Completo
image: images/team/seu_nome.jpg
description: Resumo do que você faz (ex: PhD Student, MSc in Bioinformatics)
role: phd # Opções aceitas: undergrad, msc, phd, postdoc, pi
links:
  github: seu-usuario-github
  lattes: "1234567890123456" # Coloque o número do Lattes sempre entre aspas!
  orcid: 0000-0000-0000-0000
aliases:
  - Seu Nome
  - S. Nome
# group: alum # Remova o '#' no início desta linha se você for um ex-membro
# current_position: "Posição atual" # Apenas para alumni, mostra onde você está agora
---

Escreva sua biografia aqui embaixo. Você pode descrever sua formação, interesses de pesquisa e projetos nos quais trabalha. Aceita formatação em Markdown!
```

### 4. Salvando e enviando as alterações (Pull Request)

- Após editar o arquivo, clique no botão verde **Commit changes...** no canto superior direito.
- Selecione a opção para criar uma nova _branch_ para o seu commit (ex: `seu_nome-patch-1`) e clique em **Propose changes**.
- Por fim, clique em **Create pull request**. Um dos administradores revisará e aprovará sua alteração para ir ao ar no site!
