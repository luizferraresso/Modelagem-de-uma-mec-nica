Sistema de Controle de Oficina Mecânica
Este projeto consiste na modelagem de um banco de dados relacional para o gerenciamento de Ordens de Serviço (OS) em uma oficina mecânica. A estrutura foi projetada para garantir que todo o fluxo, desde a entrada do veículo até a execução pela equipe técnica, seja registrado de forma íntegra e organizada.

Funcionalidades e Regras de Negócio
O sistema foi estruturado para atender aos seguintes requisitos:

Gestão de Clientes e Veículos: Cadastro de clientes e seus respectivos veículos (Relacionamento 1:N).
Equipes de Trabalho: Organização de mecânicos em equipes para execução dos serviços.
Fluxo de Ordem de Serviço (OS): * Registro de data de emissão, valor total, status e data de conclusão.
Vínculo direto com a Equipe responsável e o Veículo atendido.
Catálogo de Serviços e Peças: * Tabela de referência para preços de mão-de-obra.
Gestão de peças utilizadas em cada manutenção (Relacionamentos N:N).
Autorização e Execução: Controle de status para garantir que o serviço só seja executado após a autorização do cliente.
