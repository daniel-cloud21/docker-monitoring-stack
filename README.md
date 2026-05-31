# Docker Monitoring Stack 🚀

Stack de monitoramento estruturada com Docker, Prometheus e Grafana para coleta de métricas, visualização em dashboards e observabilidade de containers e serviços em tempo real.

## 🛠️ Tecnologias Utilizadas
* **Docker & Docker Compose**: Para orquestração e isolamento dos serviços em containers.
* **Prometheus**: Banco de dados de séries temporais utilizado para a coleta de métricas.
* **Grafana**: Ferramenta analítica para visualização de dados e criação de dashboards.
* **Node Exporter**: Agente coletor de métricas de infraestrutura a nível de sistema operacional (CPU, Memória, Disco).

## 🚀 Como Rodar o Projeto

1. Certifique-se de ter o **Docker** e o **Docker Compose** instalados na sua máquina.
2. Clone este repositório:
   ```bash
   git clone https://github.com
   ```
3. Acesse a pasta do projeto:
   ```bash
   cd docker-monitoring-stack
   ```
4. Suba a stack com o comando:
   ```bash
   docker compose up -d
   ```

## 🌐 Portas dos Serviços
* **Grafana:** [http://localhost:3000](http://localhost:3000) (User/Pass padrão: `admin` / `admin`)
* **Prometheus:** [http://localhost:9090](http://localhost:9090)
* **Node Exporter:** [http://localhost:9100](http://localhost:9100)
