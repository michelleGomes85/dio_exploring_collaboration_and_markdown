# Explorando Colaboração e Markdown

Este projeto foi desenvolvido como parte do desafio da Formação Github Certification da DIO (Digital Innovation One). O objetivo principal foi aprimorar o conhecimento e as habilidades no uso do GitHub, com foco específico no uso de Markdown para arquivos README e na colaboração entre desenvolvedores.

# Objetivos do Estudo

O projeto se concentrou em:

- **Aprender e aplicar Markdown**: Explorar as melhores práticas para criar arquivos README informativos e bem estruturados, utilizando o Markdown.
- **Colaboração no GitHub**: Compreender como usar as funcionalidades do GitHub para colaborar com outros desenvolvedores, como branches, pull requests e issues.

-------

# Tutorial Básico sobre Markdown

O Markdown é uma linguagem de marcação simples que permite formatar textos de forma legível e converter para HTML. É muito utilizado em documentação de projetos, especialmente em arquivos README no GitHub.

## 1. Estrutura Básica do Markdown

**Títulos**

Use # para criar títulos, com o número de # indicando o nível do título. Exemplo:

```bash
# Título de Nível 1
## Título de Nível 2
### Título de Nível 3
#### Título de Nível 4
```

**Parágrafos**

Para criar parágrafos, basta escrever o texto normalmente. Apenas separe parágrafos com uma linha em branco.

```bash
Este é um parágrafo.

Este é outro parágrafo.
```

**Negrito** e *Itálico*

```bash
**Texto em Negrito**

*Texto em Itálico*
```

**Listas**

- Listas não ordenadas: Use -, + ou * para itens da lista.

```bash
- Item 1
- Item 2
- Item 3
```

- Listas ordenadas: Use números seguidos de ponto.

```bash
1. Item 1
2. Item 2
3. Item 3
```

**Links e Imagens**

- Links: Coloque o texto entre colchetes e a URL entre parênteses.

```bash
[Google](https://www.google.com)
```

- Imagens: A mesma sintaxe do link, mas com um ! antes.

```bash
![Imagem de exemplo](url_da_imagem)
```

**Códigos**

Código em linha: Use crase ` para envolver o código.

```bash
Use o comando `git status` para ver as alterações.
```

Blocos de código: Use 3 crases ``` para blocos de código.

```markdown
```

2. Outros Elementos Comuns


- Citações: Use o sinal de maior > para criar citações.

```bash
> Este é um exemplo de citação.
```

- Tabelas: Use | para separar colunas e - para separar os cabeçalhos das linhas.

```bash
| Nome  | Idade |
|-------|-------|
| João  | 30    |
| Maria | 25    |
```

------------------------------------------

# Como Funciona a Contribuição no GitHub

Agora, vou te explicar como funciona o processo de contribuição para projetos no GitHub, usando o fluxo básico de `fork`, `branch`, `commit` e `pull request`.

1. Fork
   
O primeiro passo é fazer um fork do repositório de um projeto para ter sua própria cópia do repositório. No GitHub:

- Acesse o repositório original.
- Clique em Fork (no canto superior direito).
- Isso cria uma cópia do repositório na sua conta.

2. Clone
   
Agora, você precisa clonar o repositório que foi "forkado" para a sua máquina local para começar a trabalhar:  

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

3. Criar um Branch

Sempre crie um branch novo para a sua contribuição. Isso garante que você não vai modificar diretamente a branch principal (main ou master).

```bash
git checkout -b nome-do-branch
```

4. Fazer Alterações e Commits

Agora, faça as alterações no código ou na documentação. Após editar, faça o commit das alterações:

```bash
git add .
git commit -m "Descrição das alterações"
```

5. Subir as Alterações (Push)

Depois de fazer o commit, envie (push) as alterações para o repositório remoto.

```bash
git push origin nome-do-branch
```

6. Criar um Pull Request

Agora que você enviou suas alterações para o seu fork no GitHub, o próximo passo é criar um Pull Request (PR) para sugerir as mudanças no repositório original.

- Acesse o repositório do seu fork no GitHub.
- Você verá uma opção para criar um Pull Request.
- Clique em "New Pull Request", escolha o branch correto e adicione uma descrição.

7. Revisão e Merge
   
O mantenedor do repositório original revisará seu Pull Request. Se as alterações forem aprovadas, ele será mergeado (integrado) ao repositório original.

## Fluxo Completo de Contribuição
1. Fork o repositório.
2. Clone o repositório para a sua máquina local.
3. Crie um branch.
4. Faça as alterações e faça o commit.
5. Envie suas alterações com git push.
6. Crie um Pull Request no GitHub.
7. O mantenedor revisa e mergeia.
