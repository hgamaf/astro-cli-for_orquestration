# Astro CLI for Orchestration

Este projeto usa **Apache Airflow** via Astronomer Astro para orquestração de pipelines de dados.

## 🚀 Quick Start

### Pré-requisitos
- Docker e Docker Compose instalados
- Astro CLI instalado ([guia de instalação](https://docs.astronomer.io/astro/cli/install-cli))

### Iniciar Airflow (Astro)
```bash
astro dev start
```

## 🌐 Acessos

- **Airflow UI**: http://localhost:8080
  - Username: `admin`
  - Password: `admin`

## 📁 Estrutura do Projeto

```
├── dags/                    # DAGs do Airflow
│   └── exampledag.py       # DAG de exemplo
├── include/                 # Módulos Python customizados
├── plugins/                 # Plugins do Airflow
├── tests/                   # Testes
├── .env                     # Variáveis de ambiente
├── Dockerfile              # Imagem customizada do Airflow
└── requirements.txt        # Dependências Python
```

## 🛑 Parar Serviços

```bash
astro dev stop
```
