# Manual-GIT

_Manual de Sobrevivência Git/GitHub_

_Capacidades_
1. Múltiplos Branches
O Git permite criar e gerenciar múltiplos branches, possibilitando o desenvolvimento de diferentes funcionalidades ou correções em paralelo.

-**Criar um branch:**
```git branch nome-do-branch```

-**Listar branches:**
```git branch```

-**Deletar um branch:**
```git branch -d nome-do-branch```

2. Navegar Entre Branches
Navegar entre branches é essencial para alternar entre diferentes linhas de desenvolvimento.

-**Trocar para um branch existente:**
```git checkout nome-do-branch```

-**Criar e trocar para um novo branch:**
```git checkout -b novo-branch```

3. Um Local de Manutenção e Um Remoto de Produção
É comum ter um repositório local para desenvolvimento e um repositório remoto para produção.

-**Adicionar um repositório remoto:**
```git remote add origin url-do-repositorio```

-**Enviar alterações para o repositório remoto:**
```git push origin nome-do-branch```

-**Puxar alterações do repositório remoto:**
```git pull origin nome-do-branch```


_Manual de Sobrevivência Git/GitHub_

_Capacidades_
1. Múltiplos Branches
O Git permite criar e gerenciar múltiplos branches, possibilitando o desenvolvimento de diferentes funcionalidades ou correções em paralelo.

-**Criar um branch:**
```git branch nome-do-branch```

-**Listar branches:**
```git branch```

-**Deletar um branch:**
```git branch -d nome-do-branch```

2. Navegar Entre Branches
Navegar entre branches é essencial para alternar entre diferentes linhas de desenvolvimento.

-**Trocar para um branch existente:**
```git checkout nome-do-branch```

-**Criar e trocar para um novo branch:**
```git checkout -b novo-branch```

3. Um Local de Manutenção e Um Remoto de Produção
É comum ter um repositório local para desenvolvimento e um repositório remoto para produção.

-**Adicionar um repositório remoto:**
```git remote add origin url-do-repositorio```

-**Enviar alterações para o repositório remoto:**
```git push origin nome-do-branch```

-**Puxar alterações do repositório remoto:**
```git pull origin nome-do-branch ```

4. Integrar em VSCode, Eclipse e Android Studio
VSCode

Instale a extensão do GitLens no VSCode.
Utilize o terminal integrado para executar comandos Git.
Eclipse
Instale o plugin EGit através do Eclipse Marketplace.
Configurar repositórios Git em: Window > Preferences > Team > Git.
Android Studio
Configurar VCS (Version Control System):
File > Settings > Version Control > Git

Utilize o terminal integrado ou a interface VCS para operações Git.

5. Tag de Versão
Tags são usadas para marcar pontos específicos na história do projeto, como releases.

-**Criar uma tag:**
git tag -a v1.0 -m "Versão 1.0"

-**Enviar tags para o repositório remoto:**
git push origin --tags

6. Commits Intermediários Só da Versão de Desenvolvimento
Realizar commits frequentes durante o desenvolvimento para manter o histórico detalhado.

-**Fazer commit:**
git add .
git commit -m "Descrição do commit"

Commits em branches de desenvolvimento podem ser feitos sem enviar ao repositório remoto até a finalização.

7. Branch Separada para Feature
Cada nova funcionalidade deve ser desenvolvida em um branch separado para facilitar o controle e a revisão.

-**Criar um branch para a feature:**
```git checkout -b feature-nova```

-**Mesclar o branch de feature na main após conclusão e revisão:**
```git checkout main```
```git merge feature-nova```


# Manual de Sobrevivência Git/GitHub

## Índice
1. [Múltiplos Branches](#múltiplos-branches)
2. [Navegar Entre Branches](#navegar-entre-branches)
3. [Um Local de Manutenção e Um Remoto de Produção](#um-local-de-manutenção-e-um-remoto-de-produção)
4. [Integrar em VSCode, Eclipse e Android Studio](#integrar-em-vscode-eclipse-e-android-studio)
5. [Tag de Versão](#tag-de-versão)
6. [Commits Intermediários Só da Versão de Desenvolvimento](#commits-intermediários-só-da-versão-de-desenvolvimento)
7. [Branch Separada para Feature](#branch-separada-para-feature)


## Múltiplos Branches
- **Criar um branch:**
  ```
  git branch nome-do-branch

Listar branch:
git branch

Este formato de documentação facilita a navegação e o entendimento das práticas recomendadas no uso do Git e GitHub.

