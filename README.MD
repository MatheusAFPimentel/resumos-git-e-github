
# DIO | Resumos Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub do curso Versionamento de Código com Git e GitHub da [Digital Innovation One](https://www.dio.me/)

## Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com)

### Gravando Alterações no Repositório Local
```
git init: inicia repositório
git log: estado dos commits
git reflog: estado dos commits mais detalhados
git reset: retorna para um commit anterior e desfaz os commits comitados anteriormente
```
### Trabalhando com Branches
```
git checkout -b teste: cria e troca a branch atual para a teste
git checkout nomedabranch: aponta para a branch que vc deseja atualmente
git branch -v: lista o último commit de cada branch
git merge teste: mescla a branch teste com main
git branch: lista todas as branches do rep
git branch -d teste: exclui a branch teste
git fetch origin main: baixa as atualizações da branch main sem mesclar.
git diff main origin/main: retorna a diferença entre a branch main com a origin/main.
git clone urldorep --branch teste --single-branch: clona uma branch específica de um repositorio 
```
### Conflitos de merge
```
git pull: para atualizar seu repositorio local com o remoto
Em caso de conflito no momento do push, definir qual o código mais atualizado e se adequar a essa informação.
```

