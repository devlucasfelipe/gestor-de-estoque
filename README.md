📦 Gestão de Estoque (SPA)
Uma SPA (Single Page Application) desenvolvida com React, React Router DOM e Vite para o gerenciamento de estoque de produtos. A aplicação permite gerenciar itens de estoque com funcionalidades completas de criação, atualização e exclusão, além de exibir relatórios detalhados para facilitar a visualização e o controle do inventário.

🚀 Tecnologias utilizadas:
React + Vite ⚡ (para desenvolvimento rápido e otimizado)
React Router DOM 🛤️ (para navegação dinâmica sem recarregar a página)
localStorage 💾 (para persistir dados no navegador)
useState 🔄 (para gerenciamento de estados locais)
useRef 🏷️ (para manipulação de referências e otimização de renderizações)
createContext 🌍 (para gerenciamento de estado global)
useNavigate ⏩ (para navegação programática)
useParams 🔢 (para capturar parâmetros dinâmicos da URL)
Hooks personalizados 🔧 (para encapsular lógica reutilizável e melhorar a organização do código)
Componentes reutilizáveis 🏗️ (inputs, botões, cards, listas, etc.)
📌 Principais funcionalidades:
Página Inicial (Dashboard):
✅ Exibe a quantidade total de itens diferentes no estoque (ex.: 2 tipos de itens)
✅ Mostra a quantidade total de itens no estoque (ex.: 4 itens ao todo)
✅ Exibe a quantidade de itens adicionados nos últimos 10 dias e uma lista com esses itens
✅ Mostra itens com menos de 10 unidades em estoque e lista esses itens

Página de Itens em Estoque:
✅ Lista todos os itens com informações resumidas (nome, quantidade, preço)
✅ Oferece 3 botões para cada item: Ver mais detalhes, Atualizar e Excluir

Página de Detalhes do Item:
✅ Exibe informações completas de um item, incluindo nome, quantidade, preço, categoria e descrição
✅ Botões para atualizar e excluir o item

Tela de Criação de Itens:
✅ Formulário para adicionar novos itens com campos como nome, quantidade, preço, categoria e descrição

Tela de Atualização de Itens:
✅ Formulário para editar os dados de um item já existente

Navegação Cliente-Side:
✅ Toda a navegação é feita sem recarregar a página, utilizando React Router para navegação dinâmica

Persistência de Dados:
✅ Todos os dados são salvos no localStorage para serem preservados entre atualizações e após o fechamento da janela do navegador
