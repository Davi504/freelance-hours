# Projeto Freelance-Hours

## Descrição

FreelanceHours é uma aplicação desenvolvida em PHP, Laravel e Livewire, com Tailwind CSS e SQLite. Nela, freelancers podem enviar propostas de horas para contribuir em determinados projetos

## Video da aplicação rodando

[Link](https://youtu.be/bfkUYMv5oCs)

## objetivo

O objetivo do FreelanceHours é facilitar a comunicação entre freelancers e gerentes de projetos, permitindo que freelancers enviem suas propostas de horas para diferentes projetos.

## publico alvo

Freelancers e gerentes de projetos que buscam uma plataforma simples e eficiente para gerenciar propostas de trabalho e contribuição de horas

## futuras melhorias

- Integração com sistemas de pagamento: Permitir que freelancers sejam pagos diretamente pela plataforma.
- Notificações: Implementar notificações para manter os usuários informados sobre novas propostas e atualizações de projetos.

## desenvolvimento


### Backend
O backend utiliza PHP com o framework Laravel. SQLite é usado como banco de dados devido à sua leveza e simplicidade. Laravel gerencia rotas, controle de bancos de dados e lógica de negócios

### frontend
O frontend é desenvolvido com Tailwind CSS e Livewire. Tailwind CSS oferece uma estilização moderna e responsiva, enquanto Livewire facilita a criação de interfaces dinâmicas e reativas.

## problemas e soluções
Problema: Exibir informações dinâmicamente de forma agradável.

Solução: Utilização do Livewire para gerenciar componentes dinâmicos de forma eficiente.

## funcionalidades principais

- Listar projetos para que desenvolvedores possam contribuir com horas.

- Permitir que freelancers enviem suas propostas de horas.

## tecnologias utilizadas

[![My Skills](https://skillicons.dev/icons?i=php,laravel,html,tailwindcss,sqlite)](https://skillicons.dev)

## como rodar o projeto na sua maquina

1. Clone o Repositório:
```Sh
    git clone https://github.com/Davi504/freelance-hours.git
```
2. Navegue até o diretório do projeto:
```Sh
    cd freelance-hours
```
3. Instale as dependências:
```sh
    composer install
    npm install && npm run build
```
4. Configure o arquivo .env com as credenciais do banco de dados e outras configurações necessárias.

5. Rode as migrations para criar as tabelas no banco de dados:
```sh
    php artisan migrate --seed
```

6. Inicie o servidor de desenvolvimento:
   ```sh
        php artisan serve
   ```

7. Acesse a aplicação em http://localhost:8000.

## Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo LICENSE para mais detalhes.
