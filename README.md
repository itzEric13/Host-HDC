# hDC Host

hDC Host é um site de apresentação para uma empresa de hospedagem. O site oferece uma interface para visualização de planos, serviços e contato com a empresa. Esta documentação fornece uma visão geral sobre como o site está estruturado e como o código é organizado.

## Estrutura do Projeto

O projeto é composto por um arquivo HTML e um arquivo CSS. O HTML define a estrutura e o conteúdo da página, enquanto o CSS é responsável pelo estilo visual.

### Arquivo `index.html`

Este é o arquivo principal do projeto e define a estrutura do site. Ele inclui:

- **Cabeçalho (`<head>`)**: Contém a configuração básica da página, incluindo o título, links para fontes externas e o arquivo de estilo CSS.
- **Corpo (`<body>`)**: Contém o conteúdo da página, organizado em várias seções:
  - **NavBar**: Menu de navegação com links para diferentes seções do site.
  - **Main Banner**: Banner principal com o título e uma breve descrição.
  - **Services Container**: Seção que destaca os serviços oferecidos pela empresa.
  - **Pricing Container**: Seção que apresenta os planos de preços disponíveis.
  - **Search Domain Container**: Seção para pesquisa de disponibilidade de domínio.
  - **Contact Container**: Formulário para envio de mensagens para a empresa.
  - **Footer**: Rodapé com informações de contato do desenvolvedor.

### Arquivo `style.css`

Este arquivo define o estilo visual do site. Os principais pontos incluem:

- **Reset de Estilos**: Remove margens e preenchimentos padrão e define a fonte e o box-sizing.
- **Navbar**: Estiliza o menu de navegação, incluindo cores, espaçamentos e comportamento de hover.
- **Main Banner**: Define o estilo do banner principal, incluindo a imagem de fundo, cores e tamanhos de texto.
- **Services Container**: Estiliza a seção de serviços, incluindo ícones, cores e layout de lista.
- **Pricing Container**: Define o estilo para a seção de preços, incluindo a disposição dos planos e estilos de botões.
- **Search Domain Container**: Estiliza a seção de pesquisa de domínio, incluindo cores e tamanhos dos inputs.
- **Contact Container**: Define o estilo para o formulário de contato, incluindo tamanhos de inputs e áreas de texto.
- **Footer**: Estiliza o rodapé da página.
- **Responsividade**: Inclui media queries para garantir que o site fique bem em diferentes tamanhos de tela (tablet e mobile).

## Dependências

O projeto utiliza a biblioteca Font Awesome para ícones, carregada a partir do CDN:

