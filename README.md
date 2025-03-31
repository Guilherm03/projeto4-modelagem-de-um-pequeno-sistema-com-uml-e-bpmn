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

🔵  [INÍCIO] <br>
   │ <br>
   ▼ <br>
👤  [Usuário acessa o sistema] <br>
   │ <br>
   ▼ <br>
📅  [Seleciona sala e horário] <br>
   │ <br>
   ▼ <br>
🔎  [Verifica disponibilidade] <br>
   │ <br>
   ▼ <br>
❓  {Sala disponível?} <br>
   ├──► ✅ [SIM] →      [Reserva confirmada] →     🔴 [FIM] <br>
   └──► ❌ [NÃO] →   [Exibe salas alternativas] →  🔴 [FIM] <br>
