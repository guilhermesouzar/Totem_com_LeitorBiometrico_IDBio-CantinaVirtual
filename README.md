Totem de Autoatendimento - Cantina Virtual

Visão Geral

Este projeto tem como objetivo desenvolver uma interface baseada na biblioteca de exemplo da ControlID (C#) para a criação de um programa executável destinado a totens de autoatendimento no Cantina Virtual. O sistema permitirá que os alunos realizem login por biometria e efetuem pedidos de forma autônoma, reduzindo filas e otimizando o atendimento nas cantinas escolares.

Funcionalidades Principais

Leitura e identificação biométrica: Utiliza a biblioteca ControlID para capturar e autenticar digitais.

Integração com WebView: Os dados biométricos são enviados via HTTP/API para autenticar os alunos.

Impressão automática de pedidos: A confirmação do pedido aciona uma impressora térmica via WebSocket.

Eliminação da necessidade de atendentes: O processo automatizado permite que os alunos realizem pedidos de forma rápida e eficiente.

Stacks Utilizadas

Linguagem: C#

Biblioteca de Biometria: ControlID SDK

Comunicação entre WebView e API: HTTP/API

Protocolo para Impressão: WebSocket

Dispositivos Suportados: Totens de autoatendimento com leitor biométrico e impressora térmica

Benefícios

Redução no tempo de espera: Os alunos acessam rapidamente o sistema, realizam o login e fazem seus pedidos sem precisar de interação humana.

Experiência fluida e integrada: A interface responsiva e a comunicação rápida entre os componentes garantem um processo ágil.

Automatização e redução de custos: Menos necessidade de atendentes e maior eficiência no atendimento.
