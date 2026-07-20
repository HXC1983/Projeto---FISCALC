## FISCALC — Calculadora de Física ##

> Aplicação web para cálculos e visualizações de Física construída com ASP.NET MVC, C# e SQL Server.

---

**1. Sobre o Projeto**

O **FISCALC** é uma aplicação web desenvolvida com ASP.NET MVC (.NET 8) que permite realizar cálculos de Física de forma interativa. O projeto nasceu como ferramenta de estudo durante a graduação em Análise e Desenvolvimento de Sistemas na PUC Minas, unindo a experiência docente em Física com o aprendizado de desenvolvimento de software.

**Desenvolvido por:** Hugo Xavier de Castro

**Curso:** Tecnólogo em Análise e Desenvolvimento de Sistemas/PUC Minas

---

**2. Tecnologias Aplicadas**

O **FISCALC** foi construído aplicando as seguintes tecnologias e práticas de desenvolvimento:

- Arquitetura MVC com ASP.NET Core
- Autenticação e autorização com banco de dados próprio
- Integração com SQL Server via Entity Framework Core
- Criação de interfaces responsivas com Razor Views
- Visualização de dados com gráficos (Chart.js)


---

**3. Módulos**

Nesta seção estão descritas as *áreas* ou *módulos* da Física que serão contempladas na aplicação.

| # | Módulo | Status |
|---|--------|--------|
| 1 | **Cinemática** — MRU e MRUV |  Em desenvolvimento |
| 2 | **Dinâmica** — Leis de Newton |  Em desenvolvimento |
| 3 | **Termodinâmica** | Em desenvolvimento |
| 4 | **Eletricidade** |  Em desenvolvimento |

---

**4. Stack Tecnológica**

| Camada | Tecnologia |
|--------|-----------|
| Frontend | HTML5, CSS3, JavaScript, Razor Views |
| Backend | C# · ASP.NET MVC (.NET 8) |
| Banco de Dados | SQL Server (LocalDB) |
| ORM | Entity Framework Core |
| Gráficos | Chart.js |
| Versionamento | Git · GitHub |
| IDE | Visual Studio 2022 |

---

**5. Estrutura do Projeto**

```
FISCALC/
├── Controllers/
│   ├── HomeController.cs
│   ├── CinematicaController.cs
│   └── AuthController.cs
├── Models/
│   ├── CinematicaModel.cs
│   └── UsuarioModel.cs
├── Views/
│   ├── Shared/
│   │   └── _Layout.cshtml
│   ├── Cinematica/
│   │   └── Index.cshtml
│   └── Auth/
│       ├── Login.cshtml
│       └── Registro.cshtml
├── Data/
│   └── AppDbContext.cs
└── wwwroot/
    ├── css/
    ├── js/
    └── lib/
```

---

**6. Autenticação**

O sistema de autenticação foi implementado sem o ASP.NET Identity, com o objetivo de compreender o fluxo completo de autenticação — desde a criptografia de senha até o gerenciamento de sessão. Inclui:

- Cadastro de usuário com senha criptografada (BCrypt)
- Login com validação contra banco de dados
- Sessão de usuário autenticado
- Proteção de rotas para usuários não autenticados

---


**7. Evolução do Projeto**

### Fase 1 — Base da aplicação
- [ ] Criação de projeto ASP.NET MVC do zero
- [ ] Arquitetura MVC na prática — Models, Views e Controllers
- [ ] Razor Views e Tag Helpers
- [ ] Integração com SQL Server via Entity Framework Core
- [ ] Autenticação manual com banco de dados

### Fase 2 — Funcionalidades avançadas
- [ ] APIs RESTful básicas
- [ ] Integração com Chart.js para gráficos
- [ ] Animações com HTML5 Canvas
- [ ] Testes unitários básicos

---

**8. Documentação**
- [Especificação do Projeto](documentos/Especificacao-do-Projeto.md)
- [Projeto de Interface](documentos/Especificacao-do-Projeto.md)

## Licença

Este projeto está sob a licença MIT.

---

> *"Física e código — duas linguagens para descrever o mesmo universo."*

