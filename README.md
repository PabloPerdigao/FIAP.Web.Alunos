# Projeto Web ALunos FIAP

Aplicação desenvolvida durante o **Capítulo 4 – Desenvolvimento Web com ASP.NET** no curso de ADS da FIAP. O objetivo foi praticar os fundamentos do **ASP.NET Core MVC**, criando uma aplicação web simples com estrutura organizada e funcional.

## 🚀 Tecnologias Utilizadas
- ASP.NET Core MVC
- Razor (Views dinâmicas)
- Tag Helpers
- Bootstrap
- Docker

## 📁 Estrutura MVC
- **Model:** classes de domínio (Cliente, Representante).
- **View:** páginas Razor estruturadas com layout compartilhado.
- **Controller:** ações responsáveis por receber requisições e enviar dados às Views.

## 🧩 Funcionalidades
- CRUD básico para Clientes:
  - Criar
  - Listar
  - Editar
  - Detalhar
  - Excluir
- Model Binding
- Uso de ViewBag e TempData

## 📚 Conhecimento Aplicado
- Estrutura MVC
- Controllers e Actions
- Views com Razor
- Tag Helpers
- Layout compartilhado
- CRUD completo

## 🐳 Execução com Docker
O projeto possui suporte a Docker para execução em container.

```bash
docker build -t fiap-web-alunos .
docker run -d -p 8080:80 fiap-web-alunos

http://localhost:8080

