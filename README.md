# Projeto-A3---Golpes

## Descrição do Projeto
Escolhemos esse tema devido ao aumento dos golpes em que criminosos se passam por atendentes de centrais bancárias, buscando enganar os clientes e obter dados pessoais e financeiros. Esse tipo de golpe é um dos mais comuns atualmente e afeta diretamente a confiança dos usuários que atendem essa ligação.

Nossa proposta se inspira no novo sistema do iOS, que atende as ligações automaticamente, solicita a identificação do contato e o motivo da ligação, permitindo que o usuário decida se deseja atender. Também consideramos as soluções presentes em alguns modelos da Samsung, que identificam chamadas suspeitas como spam ou golpe e encerram automaticamente a ligação, emitindo um alerta ao usuário.

---

## Integrantes do Grupo
- Maria Fernanda
- Luanna Correia

---

## Arquitetura do Projeto
O projeto segue a arquitetura *MVC (Model-View-Controller)*, que separa as responsabilidades da aplicação em três camadas:  
- *Model:* Responsável pelo gerenciamento dos dados e integração com o banco de dados.  
- *View:* Páginas web que interagem com o usuário (HTML, CSS, JavaScript).  
- *Controller:* Controla o fluxo da aplicação, recebe requisições e envia respostas para a View.  

---

## Tecnologias Utilizadas
- *Java* – Backend  
- *HTML, CSS e JavaScript* – Frontend  
- *MySQL* – Banco de dados  

---

## Arquitetura
ProjetoFacul/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── app.js
│
└── backend/
    ├── server/app.js     (ou server.js)  
    ├── routes/           (rotas da API)
    ├── controllers/      (lógica que liga rota → model)
    ├── models/           (dados, lógica de negócio, banco)
    └── node_modules/     (dependências)
