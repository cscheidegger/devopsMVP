# Proteus.lab - Plataforma de Serviços de Impressão 3D

Este é o repositório principal do Proteus.lab, uma plataforma completa de serviços de impressão 3D.

## Estrutura do Projeto

O projeto Proteus.lab está organizado em três repositórios principais:

1. **[FrontMVP](https://github.com/cscheidegger/FrontMVP)** - Frontend React
2. **[APIMVP](https://github.com/cscheidegger/APIMVP)** - Backend API FastAPI
3. **[devopsMVP](https://github.com/cscheidegger/devopsMVP)** (este repositório) - Configurações DevOps

## Começando

1. Clone este repositório:
   ```bash
   git clone https://github.com/cscheidegger/devopsMVP.git
   cd devopsMVP
   ```

2. Configure as variáveis de ambiente:
   ```bash
   cp .env.example .env
   # Edite o arquivo .env com suas configurações
   ```

3. Inicie a aplicação:
   ```bash
   docker-compose up -d
   ```

4. Acesse a aplicação:
   - Frontend: http://localhost:5173
   - API: http://localhost:8000
   - Documentação da API: http://localhost:8000/docs

## Arquitetura

Consulte o arquivo [ARCHITECTURE.md](ARCHITECTURE.md) para detalhes sobre a arquitetura do sistema.

## Configuração DevOps

Este repositório contém todas as configurações necessárias para orquestrar os diferentes serviços que compõem a plataforma Proteus.lab, incluindo:

- Docker Compose para orquestração de contêineres
- Scripts de inicialização e backup
- Configurações de rede
- Volumes para persistência de dados

## Licença

[MIT](LICENSE)
