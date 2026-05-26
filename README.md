## Projeto Web: Cafeitoria ☕

Este projeto foi desenvolvido para a AP2 de Desenvolvimento Web. O objetivo principal é aplicar os conceitos de layout responsivo, semântica HTML e principalmente componentes do Bootstrap.

# 🔗 Link do Projeto
https://nicolas-sant.github.io/AP2-Front/

# 📋 Tema Escolhido
O tema escolhido foi uma Cafeteria, focada em um design limpo e funcional que apresenta o cardápio dos produtos (cafés, doces e salgados), destaques da semana e um sistema de reserva de mesas.

# 🏗️ Estrutura do Projeto
O site é composto por três páginas interligadas:

index.html (Home): Apresenta o conceito da cafeteria através de um carrossel com imagens e texto evidenciando a qualidade da cafeteria, além de produtos destaques da semana.

cardapio.html (Menu): Catálogo completo de produtos organizado em uma grade de cards responsivos com preços.

reservas.html (Reserva): Formulário completo para agendamento de mesas com validação nativa e confirmação.

# 🚀 Componentes Bootstrap Utilizados
Para a construção da interface, foram utilizados os seguintes componentes:

Navbar: Com suporte a menu colapse (hambúrguer) para telas mobile.

Dropdown: Implementado no menu de navegação para categorizar os produtos do cardápio.

Carousel: Galeria dinâmica na Home com 3 imagens e controles de navegação.

Cards: Utilizados para exibir produtos de forma padronizada.

Modal: Utilizado como componente avançado para exibir confirmação de formulário.

Grid System: Uso de container, row e col para garantir a responsividade em Mobile, Tablet e Desktop.

# 📐 Decisões de Layout e Design
Responsividade: O site foi construído seguindo o padrão mobile-first, garantindo que os cards se empilhem em telas pequenas e se organizem em colunas (3 por linha) em telas grandes (exceto na home onde os destques da semana são 4 colunas dedicadas para os 4 produtos).

Cores: Utilização de tons escuros (bg-dark) e neutros para passar a ideia de um ambiente sofisticado de café, mantendo o foco nas imagens dos produtos.

Navegação: Mantida no topo para fácil acesso entre as páginas do projeto.

# 🦾 Utilização do Flexbox (d-flex)
O Flexbox foi essencial para a organização fina do layout, sendo aplicado principalmente em:

Alinhamento de Cards: Na seção de destaques, para garantir que todos os cards tivessem a mesma altura e que o botão "Ver Preço" ficasse sempre fixo na base, independentemente do tamanho do texto descritivo (usando mt-auto).

Cabeçalho dos Cards: Alinhamento horizontal entre o título do produto e a etiqueta de preço (usando justify-content-between).

Footer: Centralização do conteúdo no rodapé.

# 📝 Observações de Desenvolvimento
Semântica: O código prioriza tags como <header>, <main>, <section>, <article> e <footer>.

Interatividade nativa: O site foi totalmente estruturado apenas com HTML e Bootstrap, incluindo validações de formulário, comportamentos, etc., ajudando a criar uma boa base sobre as classes do bootstrap e propriedades nativas do HTML.

Integração Form-Modal: Para permitir a confirmação de envio sem JS, o botão de submissão real foi colocado dentro de um Modal e conectado ao formulário via atributo form="id_do_form".