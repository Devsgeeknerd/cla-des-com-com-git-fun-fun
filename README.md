<!-- Título -->
# Desfazendo Commits

***Conteúdo da Aula:***

## :memo: Explicação do Processo

**O que este conteúdo faz?**

Ensina como reverter (desfazer) commits específicos no Git, sem apagar o histórico de mudanças.

**Vocabulário Básico:**

- `git log` &#8594; Comando que mostra o histórico de commits (como um diário de mudanças).
- `hash` &#8594; Código único de identificação de cada commit (como um número de série).
- `git revert` &#8594; Comando para desfazer um commit específico, criando um novo commit que anula as mudanças anteriores.

**Explicação Passo a Passo:**

1. `git log` &#8594; É como folhear um álbum de fotos dos seus projetos
   - Mostra todos os commits já feitos.
   - Cada commit tem um hash único (número de identificação).
   - Permite ver quem fez a mudança, quando e o que foi alterado.

2. `git revert hash` &#8594; É como dar um "ctrl+z" em um commit específico
   - Você escolhe o commit que quer desfazer.
   - O Git cria um novo commit que cancela as mudanças daquele commit.
   - Importante: NÃO apaga o histórico, apenas cria um novo commit que desfaz as alterações.

**Cuidado!**

- Sempre verifique o hash correto antes de reverter.
- Reverter pode causar conflitos se outras pessoas já tiverem baixado as mudanças.
- Use com cuidado em projetos compartilhados.

**Exemplo Prático:**

```bash
# Ver o histórico de commits
git log

# Reverter um commit específico
git revert [hash-do-commit]
```

**Analogia do Mundo Real:**

Imagine que o Git é como um caderno de anotações. `git revert` é como riscar uma página inteira que você escreveu errado, mas mantendo o registro de que você a riscou. Assim, todo mundo ainda pode ver o que foi escrito originalmente e que você decidiu cancelar.

**Exercício Mental:**

- Pense em um desenho que você fez e depois decidiu apagar parcialmente
- Como você faria isso sem sujar ou rasgar o papel?
- É exatamente assim que o `git revert` funciona no código!

> [!IMPORTANT]\
> **Boas práticas**:
>
> - **Revert vs Reset**:
>   - `git revert`: Recomendado para repositórios compartilhados.
>   - `git reset`: Uso mais cauteloso, pode reescrever histórico.
>
> - **Fluxo Recomendado**:
>   - Verificar histórico com `git log`.
>   - Identificar hash do commit.
>   - Executar `git revert [hash]`.

---

<!-- > [!WARNING]\
> **Recomendações**:
>

--- -->

> [!NOTE]\
> **Observações**:
>
> - Sempre comunique a equipe antes de reverter commits.
> - Verifique impactos em branches compartilhadas.
> - Tenha backup antes de operações destrutivas.

---

## :clipboard: Próximos Passos

- Estudar estratégias avançadas de gerenciamento de commits.
- Praticar comandos em repositórios de teste.
- Entender merge e rebase.

## :bookmark: Tags

`#Git` `#ControleDeVersão` `#DevOps` `#Desenvolvimento` `#Programação`

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-des-com-com-git-fun-fun&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-des-com-com-git-fun-fun?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-des-com-com-git-fun-fun?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-des-com-com-git-fun-fun?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-des-com-com-git-fun-fun?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-des-com-com-git-fun-fun?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
