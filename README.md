# Mapeamento de Processos

O mapeamento de processos é uma forma estruturada de organizar o fluxo de trabalho no desenvolvimento de software, garantindo que cada etapa seja realizada com eficiência e controle.

</br>

## Pit Stop

Assim como em uma corrida de Fórmula 1, o Pit Stop é um momento de pausa planejada, seja para almoço, descanso ou outra interrupção. Aqui, você registra rapidamente onde parou e qual era o próximo passo planejado, facilitando a retomada com o mesmo raciocínio.

## Inicialização

Antes de começar a codificar, é essencial garantir que o ambiente está pronto, verificando se a branch main do projeto está atualizada, criar uma nova branch para a nova tarefa que vai ser realizada ou outros procesos realizados a preparação para a codificação de fato.

## Construção

Aqui acontece o desenvolvimento real do código, implementando uma funcionalidade nova ou até solucionando um bug. O objetivo é construir aquilo que a tarefa pede, respeitando boas práticas e padrões definidos pela equipe da empresa.

## Refinação

Depois de implementar as mudanças, é essencial refinar o código para garantir clareza, organização e eficiência. Isso pode ser feito por meio da refatoração, tornando o código mais limpo e otimizado, além de ajustes baseados no feedback da equipe. Também é importante realizar testes manuais e automatizados para evitar erros antes da revisão final.

## Testes Manuais

Antes de finalizar, é importantíssimo que seja testado por completo toda a solução proposta na tarefa.

## Finalização

Antes de considerar uma tarefa concluída, é essencial revisar toda a implementação e validar as mudanças. Isso inclui revisar o código para garantir qualidade, buildar e testar a aplicação, e abrir um pull request para a revisão da equipe.

</br>

## Atualmente, essa é estrutura inicial para cada tarefa:

```
# Mapeamento de Processos
## Pit Stop

- [ ]  *Definir conforme a necessidade da tarefa.*

## Inicialização

- [ ]  Atualizar branch main.
- [ ]  Criar nova branch.
- [ ]  Aplicar novas migrations no supabase se houver.
- [ ]  Fazer projeto rodar.

## Construção

- [ ]  *Definir conforme a necessidade da tarefa.*

## Refinação

- [ ]  *Definir conforme a necessidade da tarefa.*

## Testes Manuais

- [ ]  Fluxo principal (core da funcionalidade)
- [ ]  Fluxos alternativos
- [ ]  Casos extremos
- [ ]  Tratamento de erros

## Finalização

- [ ]  Revisar.
- [ ]  Buildar.
- [ ]  Gerar migrations caso tenha sido feito alterações na estrutura do banco ou adição de novas permissões.
- [ ]  Atualizar branch main e fazer merge com a branch da tarefa.
- [ ]  Fazer um supabase migration up caso no merge tenha vindo novas migrations.
- [ ]  Abrir pull request.
```
