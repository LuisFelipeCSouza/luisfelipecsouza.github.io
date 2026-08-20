---
title: "TSRE-DER OpenTES"
excerpt: "Simulação de recursos energéticos distribuídos usando co-simulação com Mosaik e OpenDSS<br/><img src='https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png' width='100'>"
collection: portfolio
---

## TSRE-DER OpenTES

**Repositório de código para armazenar as soluções desenvolvidas de simulação de recursos energéticos distribuídos.**

### Sobre o Projeto

O TSRE-DER OpenTES é um projeto desenvolvido no **Grupo de Redes Elétricas Inteligentes (GREI)** da Universidade Federal do Ceará (UFC), focado em **co-simulação de redes elétricas inteligentes** com recursos energéticos distribuídos (DER).

### Funcionalidades Principais

- **Co-simulação** usando o framework Mosaik
- **Simulação de sistemas de potência** com OpenDSS
- **Containerização** com Docker para facilitar a execução
- **Cenários de simulação** para redes com geração fotovoltaica distribuída

### Tecnologias Utilizadas

- **Python** - Linguagem principal
- **Docker** - Containerização e orquestração
- **Mosaik** - Framework de co-simulação
- **OpenDSS** - Simulador de sistemas de potência
- **py-dss-interface** - Interface Python para OpenDSS

### Como Executar

```bash
# Construir a imagem Docker
docker build -t opentes-simulador .

# Subir os serviços
docker compose up -d

# Executar o cenário
uv run --no-sync python src/scenarios/cenariodocker.py
```

### Acesse o Repositório

[GitHub: grei-ufc/tsre-der-opentes](https://github.com/grei-ufc/tsre-der-opentes)

### Meu Papel

**Principal contribuidor** do projeto, responsável pelo desenvolvimento das soluções de co-simulação e integração dos simuladores.
