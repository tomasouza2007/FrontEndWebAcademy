# fundamentos-front-end-t10

Repositório da disciplina Fundamentos de Programação Front-end (Turma 10)

## Atualizando o repositório local

O código produzido em sala de aula, e compartilhado neste repositório, pode ser atualizado no repositório local com o comando:

```console
git pull
```

No entanto, se foram feitas alterações no repositório local, o comando acima pode gerar conflitos. Para evitar lidar com isso, é possível forçar uma atualização com o repositório remoto por meio dos comandos:

```console
git fetch origin
git reset --hard origin/main
```

O primeiro comando recebe as atualizações mais recentes do repositório remoto, e o segundo descarta todas as alterações locais e atualiza com o histórico mais recente do repositório remoto (branch main).

## Ambiente de Desenvolvimento

> [!WARNING]
> A preparação adequada do ambiente de desenvolvimento é fundamental para o bom andamento das atividades da disciplina. Dedique atenção a esse passo e certifique-se de que o ambiente está corretamente configurado.

- [Preparação do Ambiente de Desenvolvimento Front-end](https://github.com/webacademyufac/tutoriais/blob/main/ambiente-desenvolvimento-frontend.md)

## Material de Apoio

### Sites de referência

- MDN Web Docs - Aprendendo desenvolvimento web: <https://developer.mozilla.org/pt-BR/docs/Learn>
- W3Schools Online Web Tutorials: <https://www.w3schools.com/>
- W3C Standards: <https://www.w3.org/standards/>

### SGCM - Sistema de Gerenciamento de Clínica Médica

A demonstração de uso das ferramentas e tecnologias abordadas na capacitação é baseada em um projeto de exemplo, o SGCM. A documentação do projeto está disponível [em outro repositório](https://github.com/webacademyufac/sgcmdocs):

- [Principais funcionalidades](https://github.com/webacademyufac/sgcmdocs#principais-funcionalides)
- [Histórias de usuário](https://github.com/webacademyufac/sgcmdocs#histórias-de-usuário)
- [Fluxo de Atendimento](https://github.com/webacademyufac/sgcmdocs#fluxo-de-atendimento)
- [Diagrama de Classes](https://github.com/webacademyufac/sgcmdocs#diagrama-de-classes)
- [Diagrama Entidade Relacionamento](https://github.com/webacademyufac/sgcmdocs#diagrama-entidade-relacionamento)

### Conteúdo da Disciplina

O [texto de referência](./docs/README.md) reúne os fundamentos teóricos e exemplos práticos da disciplina, abordando a introdução ao desenvolvimento web e as três tecnologias base do front-end: HTML, CSS e JavaScript.
