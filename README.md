# Sistema de Reserva de Salas

## Equipe
- Antonio Helder Batista Lima Marreiro
- João Guilherme Lins Almeida 

## Descrição do Projeto
Este projeto tem como objetivo desenvolver um sistema para **reserva de salas**, permitindo que usuários agendem espaços disponíveis.

## Sistemas Utilizados
- **UML** para modelagem do sistema.
- **BPMN** para modelagem do fluxo de reservas.

## Diagramas do Sistema

## Diagrama de Classes UML
![Diagrama de Classes](link_da_imagem)

## Fluxo BPMN

### FLUXO DE RESERVA DE SALA

[INÍCIO]
   │
   ▼
[Usuário acessa o sistema]
   │
   ▼
[Seleciona sala e horário]
   │
   ▼
[Verifica disponibilidade]
   │
   ▼
{Sala disponível?}
   ├──► [SIM] → [Reserva confirmada] → [FIM]
   └──► [NÃO] → [Exibe salas alternativas] → [FIM]
