# GoTrip.Solutions

Landing page para apresentação da consultora de viagens **Ana Souza** com foco em viagens personalizadas, seguras e econômicas.

## 👩‍💼 Sobre o Projeto

Este projeto é uma página HTML simples com estilo CSS e imagens, servida via NGINX com Docker. Ele permite que visitantes conheçam o trabalho da consultora e acessem seus canais de atendimento e formulários.

## 🌐 Link de Produção

Você pode acessar a página em produção (caso esteja hospedada) por meio do seu domínio NGINX ou subdomínio configurado.

## 📁 Estrutura de Pastas

```
gotrip.solutions/
├── html/
│   ├── css/
│   │   └── main.css
│   ├── img/
│   │   ├── trip1.png
│   │   ├── trip2.png
│   │   ├── trip3.png
│   └── index.html
├── nginx/
│   ├── conf.d/
│   │   └── gotrip.solutions.conf
│   └── nginx.conf
├── .env
├── .gitignore
├── docker-compose.yml
└── README.md
```

## 🧪 Tecnologias Utilizadas

* HTML5
* CSS3
* Docker + Docker Compose
* NGINX (proxy reverso)

## 🚀 Como Rodar Localmente

```bash
# 1. Clone o repositório
$ git clone <repo_url>
$ cd GOTRIP.SOLUTIONS

# 2. Suba os containers
$ docker-compose up --build

# 3. Acesse em seu navegador
http://localhost
```

## ⚙️ Variáveis de Ambiente

É necessário definir as variáveis de ambiente asism como em `.env.example`, exemplo:

```env
PORT_DEFAULT=80
```

## 🔗 Contatos da Consultora Ana Souza

* [Formulário para montar roteiro](https://forms.gle/1S1ZPZFRQRosB1K49)
* [Instagram @anacarolinasilvatur](https://instagram.com/anacarolinasilvatur)
* [Instagram @apoenaporanacarolina](https://instagram.com/apoenaporanacarolina)
* [LinkedIn](https://www.linkedin.com/in/anaconsultoria)

## 📦 Deploy

Para produção, configure seu domínio no arquivo `nginx/conf.d/gotrip.solutions.conf` e utilize HTTPS com Certbot caso deseje SSL.

## ✨ Agradecimentos

Projeto desenvolvido como parte da iniciativa **GoTrip.Solutions** para oferecer uma experiência de planejamento de viagem personalizada e acolhedora.
