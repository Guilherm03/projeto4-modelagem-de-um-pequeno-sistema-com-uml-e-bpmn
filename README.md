# Sistema de Reserva de Salas

## Equipe
- Antonio Helder Batista Lima Marreiro
- João Guilherme Lins Almeida 

## Descrição do Projeto
Este projeto tem como objetivo desenvolver um sistema para **reserva de salas**, permitindo que usuários agendem espaços disponíveis.

# Diagramas do Sistema

## Diagrama de Classes UML
+--------------+------+--------------+------+--------------+<br>
|   Usuário    |------|   Reserva    |------|    Sala      |<br>
+--------------+------+--------------+------+--------------+<br>
| - nome       | 1 ───| - idReserva   |── 1 | - idSala     |<br>
| - email      |------| - data        |-----| - número     |<br>
| - telefone   |------| - horário     |-----| - capacidade |<br>
+--------------+------+--------------+------+--------------+<br>

## Fluxo BPMN

[INÍCIO] ---> [Usuário acessa o sistema] ---> [Seleciona sala e horário] ---> [Verifica disponibilidade] ---> <br>
{Sala disponível?} <br>
   ├──► [SIM] →    [Reserva confirmada] → [FIM] <br>
   └──► [NÃO] →   [Exibe salas alternativas] → [FIM] <br>
