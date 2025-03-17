# Store Context API

**Store Context API** é um projeto desenvolvido para demonstrar o uso da Context API do React. A aplicação simula um sistema de loja online, onde o estado global da aplicação é gerenciado através da Context API, permitindo o controle de funcionalidades como o carrinho de compras, preferências do usuário, e mais.

## Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **Context API**: Gerenciamento de estado global da aplicação.
- **JavaScript**: Linguagem de programação utilizada.
- **CSS**: Estilização da aplicação.
- **Material-UI**: Biblioteca de componentes UI para React.
- **Styled Components**: Biblioteca para estilização de componentes.

## Funcionalidades

- **Gerenciamento global do estado**: Utilização da Context API para gerenciar o estado da aplicação, como carrinho de compras, informações do usuário e formas de pagamento.
- **Carrinho de compras**: Adição e remoção de produtos, cálculo do valor total e finalização da compra.
- **Formas de pagamento**: Seleção de diferentes métodos de pagamento com cálculos de juros aplicados.
- **Autenticação simples**: Captura do nome e saldo do usuário para simular uma experiência de compra.
- **Design responsivo**: Interface adaptável para diferentes dispositivos.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **public/**: Contém os arquivos estáticos, como imagens e o arquivo `index.html`.
- **src/**: Contém todo o código-fonte do projeto.
  - **assets/**: Armazena recursos estáticos, como a logo da aplicação.
  - **common/context/**: Contextos globais da aplicação (Carrinho, Pagamento e Usuário).
  - **components/**: Componentes reutilizáveis, como o componente `Produto`.
  - **pages/**: Páginas da aplicação (Login, Feira e Carrinho).
  - **Routes.js**: Configuração das rotas da aplicação.

## Como Rodar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/store-context-api.git
   ```

2. Navegue até a pasta do projeto:
   ```bash
   cd store-context-api
   ```

3. Instale as dependências:
   ```bash
   yarn install
   ```

4. Execute o projeto:
   ```bash
   yarn start
   ```

   A aplicação estará disponível em `http://localhost:3000`.

## Scripts Disponíveis

- **`yarn start`**: Inicia o projeto no modo de desenvolvimento.
- **`yarn test`**: Executa os testes.
- **`yarn build`**: Cria uma versão otimizada para produção.
- **`yarn eject`**: Ejetar a configuração do build (avançado).

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo LICENSE para mais detalhes.

## Contato

Se você tiver alguma dúvida ou quiser entrar em contato, sinta-se à vontade para me enviar um e-mail ou me encontrar nas redes sociais.

- **E-mail**: dev.roumillac@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/diogo-roumillac-95245766

---

**Nota**: Este projeto foi desenvolvido como parte do meu aprendizado em React e está em constante evolução. Novas funcionalidades e melhorias serão adicionadas ao longo do tempo. Fique à vontade para contribuir ou sugerir melhorias!
