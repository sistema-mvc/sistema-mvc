<!-- Banner de Boas-vindas -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=777BB4&height=250&section=header&text=Olá,%20eu%20sou%20Elias%20Antonio!&fontSize=50&animation=fadeIn&fontColor=ffffff" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/sistema-mvc" target="_blank">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=777BB4&center=true&vCenter=true&width=435&lines=Software+Engineer;PHP+Specialist;MVC+Architecture+Enthusiast;Building+Scalable+Solutions" alt="Typing SVG" />
  </a>
</p>

---

# 🚀 PHP MVC Boilerplate

Um boilerplate MVC moderno desenvolvido do zero com foco em:

- 🧱 Arquitetura escalável
- 🔒 Segurança integrada
- 🧼 Clean Code
- ⚡ Performance
- ♻ Reutilização
- 🧩 Baixo acoplamento

Inspirado na experiência de desenvolvimento de frameworks modernos como Laravel, mas mantendo total controle da aplicação sem abstrações excessivas.

---

# ✨ Principais Recursos

## 🧠 Arquitetura Moderna

✔ Estrutura organizada em camadas  
✔ Separação clara de responsabilidades  
✔ Core reutilizável  
✔ Services + Repositories  
✔ Middlewares desacoplados  
✔ MVC limpo e extensível

---

## 🔒 Segurança Integrada

✔ Proteção CSRF  
✔ Sessões seguras  
✔ Sanitização de dados  
✔ Validação centralizada  
✔ Upload seguro de arquivos  
✔ Sistema de autenticação reutilizável

---

## ⚡ Developer Experience

✔ Autoload PSR-4 com Composer  
✔ Rotas organizadas  
✔ Estrutura intuitiva  
✔ Fácil manutenção  
✔ Logs centralizados  
✔ Configuração via `.env`

---

# 🛠️ Stack

<p align="center">

<img src="https://skillicons.dev/icons?i=php,mysql,git,github,vscode,linux" />

</p>

<div align="center">

| Backend  | Database           | Architecture | Tools    |
| -------- | ------------------ | ------------ | -------- |
| PHP 8.2+ | MySQL              | MVC          | Composer |
| PDO      | SQL                | SOLID        | Git      |
| OOP      | Repository Pattern | Clean Code   | PSR-4    |

</div>

---

# 📂 Estrutura do Projeto

```bash
project/
│
├── public/              # Única pasta pública
├── app/
│   ├── Core/            # Núcleo reutilizável do framework
│   ├── Controllers/
│   ├── Models/
│   ├── Services/
│   ├── Repositories/
│   ├── Middlewares/
│   ├── Helpers/
│   └── Views/
│
├── bootstrap/           # Inicialização da aplicação
├── config/              # Configurações globais
├── routes/              # Definição de rotas
├── database/            # Migrations e seeds
├── storage/             # Logs, cache, uploads e sessões
│
├── composer.json
├── .env.example
└── README.md
```

---

# 🧩 Core do Framework

O diretório `app/Core` concentra toda a infraestrutura reutilizável da aplicação.

## Componentes Principais

| Classe        | Responsabilidade              |
| ------------- | ----------------------------- |
| `Application` | Kernel da aplicação           |
| `Router`      | Sistema de roteamento         |
| `Controller`  | Base dos controllers          |
| `Model`       | Active Record + Query Builder |
| `Database`    | Singleton PDO                 |
| `Session`     | Sessões + Flash + CSRF        |
| `Auth`        | Sistema de autenticação       |
| `Validator`   | Validação centralizada        |
| `Logger`      | Logs PSR-3                    |
| `View`        | Renderização de templates     |
| `Request`     | Encapsulamento HTTP           |

---

# 🏗️ Arquitetura

O projeto segue uma arquitetura desacoplada baseada em responsabilidades bem definidas:

```text
Request
   ↓
Router
   ↓
Middleware
   ↓
Controller
   ↓
Service
   ↓
Repository
   ↓
Model
   ↓
Database
```

---

# 🔥 Diferenciais

## ✔ Sem dependência de framework pesado

Controle total da aplicação sem “mágicas” ocultas.

## ✔ Estrutura enterprise-ready

Projetado para crescer sem virar um monólito desorganizado.

## ✔ Código reutilizável

O núcleo pode ser reaproveitado em múltiplos projetos.

## ✔ Foco em arquitetura

Mais importante que quantidade de features é a qualidade estrutural do sistema.

---

# 📈 Filosofia

> “Complexidade é inevitável. O desafio é transformá-la em simplicidade através de uma boa arquitetura.”

Este projeto foi criado para demonstrar que PHP puro, quando bem estruturado, pode oferecer uma experiência moderna, escalável e profissional.

---

# 🤝 Contribuição

Contribuições, sugestões e melhorias são sempre bem-vindas.

---

# 👨‍💻 Autor

<p align="center">
  <a href="https://github.com/sistema-mvc">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=waving&color=777BB4&height=120&section=footer"
  />
</p>
```
