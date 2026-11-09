# 🎵 Sistema Musical

Sistema web em PHP + MySQL para gerenciamento de artistas, músicas e biblioteca musical, com autenticação de usuários, upload de imagens e sessão de login.

## Visão geral

Este projeto foi desenvolvido para cadastrar artistas e músicas, organizar uma biblioteca musical e permitir o acesso por meio de login com autenticação de sessão. A interface foi estruturada em páginas PHP com CSS próprio e banco de dados relacional.

## Funcionalidades

- Login e logout com sessão
- Cadastro de artistas
- Cadastro de músicas
- Upload de imagens para artistas e capas de álbum
- Biblioteca musical com filtros e visualização

## Tecnologias

- PHP
- HTML/CSS

## Requisitos

- PHP 7 ou superior
- MySQL
- Apache/Nginx
- Extensão GD habilitada no PHP
- phpMyAdmin (opcional, mas recomendado)

## Configuração do banco de dados

1. Inicie o Apache e o MySQL no seu ambiente local.
2. Acesse o phpMyAdmin.
3. Crie o banco de dados e importe o arquivo `bd.sql`.
4. Verifique se a tabela `usuarios` foi criada corretamente.
5. Ajuste as credenciais no arquivo `conexao.php` caso necessário.

## Observações importantes

- A pasta `img` é criada automaticamente pelo arquivo `conexao.php`.
- Certifique-se de que a extensão GD do PHP esteja habilitada para trabalhar com upload e redimensionamento de imagens.
- Em produção, evite expor detalhes técnicos de conexão e erro no navegador.

## Autor

Projeto desenvolvido para fins de estudo e gerenciamento musical em PHP/MySQL por Arthur Franco.

## Licença

Este projeto não possui uma licença formal definida no repositório. Caso deseje reutilizar ou distribuir, verifique antes com o responsável pelo projeto.
