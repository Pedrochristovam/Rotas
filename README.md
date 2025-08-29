# Rotas
Sistema de Gerenciamento de Rotas e Seleção de Empresas para Vistorias Técnicas
Descrição do Projeto

Este projeto é uma aplicação web tipo dashboard para o gerenciamento de rotas e a seleção eficiente de empresas credenciadas para a realização de vistorias técnicas.

O sistema centraliza o cadastro das empresas credenciadas, que já possuem todas as informações necessárias armazenadas no banco de dados, e permite aos usuários aplicar diversos filtros para encontrar as empresas mais adequadas para cada vistoria, facilitando a tomada de decisão e otimizando o processo logístico.

Funcionalidades Principais

Filtros de Pesquisa Avançados:

Seleção do destino da vistoria (cidade ou endereço).

Filtros multiselect para tipos de serviços prestados (A, B, C, D, E, F).

Filtros com checkboxes para municípios atendidos (I a X).

Filtros para regiões ou estados atendidos.

Opções para filtrar empresas por número de chamados anteriores, incluindo intervalos personalizados e ordenação por mais ou menos chamados.

Cálculo de Rotas Integrado:

Cálculo automático da rota entre a localização de origem da empresa e o destino da vistoria.

Exibição da distância em quilômetros e do tempo estimado de deslocamento.

Botão para visualização da rota no mapa via Google Maps Embed API ou OpenRouteService.

Exibição de Resultados em Tabela Dinâmica:

Colunas detalhadas incluindo ordem de prioridade, nome da empresa, número do contrato, quadro de atividades, municípios atendidos, região/estado, total de chamados, distância e tempo de deslocamento, além de contato (e-mail e telefone).

Botão para seleção da empresa desejada para a vistoria.

Extras e Usabilidade:

Interface responsiva, clara e de fácil usabilidade para garantir eficiência no uso em diferentes dispositivos.

Sistema rápido, focado em busca e filtros, sem necessidade de upload de planilhas ou outras importações.

Tecnologias Utilizadas

Framework Front-end: React.js (ou Vue.js, conforme implementação)

APIs de Roteamento: Google Maps Embed API ou OpenRouteService

Backend e banco de dados já configurados para armazenamento das informações das empresas

Público-alvo

Empresas e gestores responsáveis por coordenação de vistorias técnicas, que necessitam otimizar o processo de seleção e deslocamento das equipes de campo.
