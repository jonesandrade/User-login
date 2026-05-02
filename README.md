Sistema de Login Simples com Flask

Este projeto é um sistema de autenticação web básico e funcional, desenvolvido com Flask, focado em login, registro de usuários e controle de sessão.

Ele simula uma estrutura real de aplicação web, com segurança básica e fluxo completo de autenticação.
Funcionalidades
Registro de novos usuários
Login com verificação de senha
Senhas criptografadas (hash seguro)
Sessão de usuário ativa com Flask-Login
Logout seguro
Proteção de rotas (dashboard protegido)
Estrutura do sistema
Banco de dados SQLite local (usuarios.db)
ORM com SQLAlchemy
Sistema de autenticação com Flask-Login
Templates HTML para interface (login, registro e dashboard)
Segurança
Senhas armazenadas com generate_password_hash
Verificação com check_password_hash
Controle de sessão por usuário logado
Rotas protegidas com @login_required
Páginas do sistema
/login → Tela de autenticação
/register → Cadastro de usuário
/dashboard → Área protegida (após login)
/logout → Encerrar sessão
Objetivo

Criar uma base simples de autenticação web usando Flask, servindo como estrutura inicial para projetos maiores como:

Sistemas administrativos
Dashboards
Portais internos
Aplicações web completas
Tecnologias utilizadas
Python
Flask
Flask-Login
Flask-SQLAlchemy
SQLite
Werkzeug Security
HTML (templates)
Possíveis melhorias futuras
Interface moderna com CSS/Bootstrap/Tailwind
Recuperação de senha por e-mail
Login com Google/GitHub
Painel administrativo com níveis de acesso
API REST para integração com frontend moderno (React/Vue)
