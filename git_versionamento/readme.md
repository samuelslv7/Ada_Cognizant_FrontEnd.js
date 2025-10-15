# Sobre a trilha de estudo
Nesta trilha, preparamos uma introdução para você, que deseja alcançar o cargo de desenvolvedor front-end na Cognizant. Para essa função, é importante ter domínio de HTML, CSS e JavaScript, conhecimento prático do funcionamento do DOM e uma boa base de lógica de programação. Nesta trilha, você terá uma introdução a todos esses assuntos. Bons estudos! 📚

# Git e Versionamento - 10 aulas - Bruno Feitosa
Neste curso, você aprenderá as melhores práticas para o versionamento de código através do Git. As aulas contam com os principais comandos e configurações utilizados no sistema. Para uma experiência de aprendizado completa, é fundamental que você, aluno, possua uma conta no GitHub, acesso ao Git e ao VSCode. Bons estudos!

## O que é o Git?
Git é um sistema de versionamento de código, que guarda os registros de versão como _snapshots_(fotos) do estado do projeto, alem da referencia/caminho para essa foto.

## Comandos básicos do Git

- **Configurar usuário**
  ```bash
  git config --global user.name "Seu Nome"
  git config --global user.email "seu@email.com"
  ```

- **Inicialize um repositório git**
  ```bash
  git init
  ```

- **Clonar um repositório**
  ```bash
  git clone https://github.com/usuario/repositorio.git
  ```

- **Vincule o repositório local ao GitHub**
  ```bash
  git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git
  ```

- **Visualizar o que tem no remoto**
  ```bash
  git remote
  ```

- **Verificar o status dos arquivos**
  ```bash
  git status
  ```

- **Adicionar arquivos para staging**
  ```bash
  git add .
  ```

- **Fazer um commit**
  ```bash
  git commit -m "Mensagem do commit"
  ```

- **Enviar alterações para o repositório remoto**
  ```bash
  git push origin main
  ```

- **Atualizar seu repositório, mas visualizar antes da mudança**
  ```bash
  git fetch
  git diff
  ```

- **Atualizar seu repositório local**
  ```bash
  git pull origin main
  ```

- **Ver histórico de commits**
  ```bash
  git log
  ```
  
- **Ver histórico de commits de forma resumida**
  ```bash
  git log --oneline
  ```

- **Criar e trocar de branch**
  ```bash
  git checkout -b nome-da-branch
  ```

- **Trocar para uma branch existente**
  ```bash
  git checkout nome-da-branch
  ```

- **Listar todas as branches**
  ```bash
  git branch
  ```

- **Criar uma branch**
  ```bash
  git branch nome-da-branch
  ```

- **Mesclar uma branch na branch atual**
  ```bash
  git merge nome-da-branch
  ```

- **Remover arquivos do staging**
  ```bash
  git reset HEAD nome-do-arquivo
  ```

- **Desfazer alterações em um arquivo**
  ```bash
  git checkout -- nome-do-arquivo
  ```

- **Remover um arquivo do repositório**
  ```bash
  git rm nome-do-arquivo
  ```

- **Ver diferenças entre arquivos modificados**
  ```bash
  git diff
  ```
  usar 'q' para sair


- **Desfazer mudanças nos arquivos modificados que foram para o staged**
  ```bash
  git restore --staged nome-do-arquivo
  ```