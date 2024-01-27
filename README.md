# Getting Started: K1-T1

Neste repositório vou testar e praticar meus conhecimentos obtidos no curso "Git Completo: do Básico ao Avançado". Algumas anotações seram listadas neste README.md apenas para fins de demonstração. Para mais informações sobre como utilizar a ferramenta git integrada com github acesse https://git-scm.com/book/en/v2.

# Introdução ao Git e GitHub

O Git e o GitHub são ferramentas de controle de versão importantíssimas para o desenvolvimento colaborativo de softwares. Aqui explorarei alguns conceitos básicos da ferramenta Git e como ela se integra ao GitHub.

# Git

O Git é um sistema de controle de versão distribuído que permite o rastreamento de alterações em arquivos ao longo do tempo. É amplamente utilizado para gerenciar o código-fonte de projetos de software.

## Conceitos:

### Repositório

Um repositório Git (ou "repo") é um local onde todos os arquivos e histórico de um projeto são armazenados. Você pode criar um repositório local ou hospedá-lo remotamente em serviços no GitHub. Para iniciar um repo utiliza-se:

```bash
git init
```
### Ciclo de vida de arquivos

Um arquivo salvo em um repositório git passa por alguns estados antes de ser enviado para o servidor do github. Em ordem, as etapas são:
- Untracked (Detectado pelo git mas não incluído no repo)
- Unmodified (Ignorado pelo git por já ter sido salvo e não possuir modificações)
- Modified (Já incluído no repo mas possuindo alterações ainda não incluídas)
- Staged (Prestes a ser salvo no repositório git)

### Staged

É a zona de preparação para salvar alterações e novos arquivos no repositório Git. Arquivos nesse estágio ainda não estão salvos no Git, ainda precisam ser "commitados". Para adicionar arquivos ou modificações de arquivos ao Staged, utilizamos:

```bash
git add <file>
```

### Commit

Um commit é uma ação que salva as alterações em seus arquivos no Git, passando do estágio Staged para o histórico do Git. Cada commit tem uma mensagem descritiva que explica o que foi alterado.

```bash
# Exemplo de criação de um commit
git commit -m "Adicionado novo recurso de login"
```


Claro, aqui está um arquivo em formato markdown que introduz conceitos básicos sobre Git e GitHub:

markdown
Copy code
# Introdução ao Git e GitHub

O Git e o GitHub são ferramentas fundamentais para o desenvolvimento colaborativo de software. Neste guia, exploraremos os conceitos básicos do Git e como o GitHub complementa essa tecnologia.

## Git

O Git é um sistema de controle de versão distribuído que permite o rastreamento de alterações em arquivos ao longo do tempo. É amplamente utilizado para gerenciar o código-fonte de projetos de software. Aqui estão alguns conceitos-chave do Git:

### Repositório

Um repositório Git (ou "repo") é um local onde todos os arquivos e histórico de um projeto são armazenados. Você pode criar um repositório local ou hospedá-lo remotamente em serviços como o GitHub.

### Commit

Um commit é uma ação que salva as alterações em seus arquivos no Git. Cada commit tem uma mensagem descritiva que explica o que foi alterado.

### Branch

Uma branch é uma linha de desenvolvimento independente no Git. Ela permite que você trabalhe em novos recursos ou correções de bugs sem afetar o código principal.

```bash
# Exemplo de criação de uma nova branch
git branch minha-nova-feature
```
### Merge

O merge é o processo de combinar as alterações de uma branch em outra. Isso é usado para incorporar novos recursos ou correções de bugs no código principal.

```bash
# Exemplo de merge de uma branch
git merge minha-nova-feature
```

## GitHub

O GitHub é uma plataforma de hospedagem de repositórios Git na nuvem que facilita o trabalho colaborativo. Além dos recursos do Git, o GitHub oferece recursos adicionais:

### Repositórios Remotos

Você pode hospedar seus repositórios Git no GitHub, tornando-os acessíveis a outros colaboradores. Isso permite que várias pessoas trabalhem juntas em um projeto.

### Pull Request

Um pull request é uma solicitação para mesclar as alterações de uma branch em outra no GitHub. Isso facilita a revisão e a colaboração de código entre os membros da equipe.

### Issues

As issues são usadas para rastrear tarefas, bugs e melhorias no GitHub. Elas podem ser atribuídas a membros da equipe e são uma maneira eficaz de gerenciar o trabalho em equipe.

### Wiki e Documentação

O GitHub permite criar wikis e documentação para projetos, facilitando o compartilhamento de informações importantes com a equipe e a comunidade.

---

Os conceitos explicados acima são bem introdutórios e rasos. Esse repositório não é uma tentativa de guia ou um local para consulta de comandos Git. Para esses fins, consulte o livro recomendado ou a documentação oficial do git:

- https://git-scm.com/book/en/v2
- https://git-scm.com/docs/git/pt_BR
