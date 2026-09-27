# 🚀 Portfólio Acadêmico com CI/CD (GitHub Actions + GitHub Pages)

Repositório criado para fins educacionais na disciplina de **Desenvolvimento Web**, demonstrando a construção de uma página web estática moderna e a automação completa do seu processo de deploy utilizando uma pipeline de **CI/CD** (Integração Contínua e Entrega Contínua).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico** & **CSS3** (Flexbox e design responsivo).
* **Git & GitHub** para controle de versão.
* **GitHub Actions** para automação da pipeline (YAML).
* **GitHub Pages** para hospedagem estática em nuvem.

---

## 📂 Estrutura do Repositório

O repositório está organizado da seguinte forma:

```text
.
├── .github/
│   └── workflows/
│       └── deploy.yaml   # Pipeline de CI/CD automatizada
├── portfolio-web/
│   ├── index.html        # Página principal do portfólio
│   └── style.css         # Estilização e responsividade
└── README.md             # Documentação do projeto
```

## ⚙️ Como Funciona a Pipeline de CI/CD
Sempre que um novo código é enviado (push) para a branch principal (main), o GitHub Actions executa automaticamente duas etapas principais:

Validação e Qualidade (CI):

Faz o checkout do código.

Verifica se os arquivos essenciais (index.html e style.css) estão presentes na estrutura correta.

Simula verificações de boas práticas no código estático.

Deploy Automático (CD): (Só executa se o CI passar com 100% de sucesso)

Configura o ambiente do GitHub Pages.

Empacota os arquivos estáticos da pasta portfolio-web/.

Publica a aplicação diretamente em produção.

## 🌐 Acesso Online
Você pode visualizar a aplicação rodando ao vivo através do link do GitHub Pages:

👉 https://seu-usuario.github.io/nome-do-repositorio/ (Substitua com a sua URL real)

## 👨‍💻 Como Executar Localmente
Se você deseja rodar este projeto na sua máquina para testes:

Clone o repositório:
~~~
git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
~~~
Acesse a pasta do projeto:

~~~
cd nome-do-repositorio/portfolio-web
~~~

Abra o arquivo index.html diretamente no seu navegador de preferência.