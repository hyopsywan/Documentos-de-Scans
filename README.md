# Relatórios de Scans de Vulnerabilidades Web

Este repositório contém os documentos em PDF com os resultados de diferentes scans de vulnerabilidades realizados em ambientes web. Os testes foram conduzidos utilizando ferramentas reconhecidas de segurança, com o objetivo de análise prática de falhas e aprendizado em pentest.

## Conteúdo dos Scans

1. **OWASP ZAP (Ativo)**  
   - **Scan no Docker:** Teste de vulnerabilidades em um ambiente local usando uma aplicação web dentro de um container Docker.  
   - **Scan em Site PHP Vulnerável:** Teste ativo realizado em um site vulnerável hospedado externamente.  

2. **HostedScan (Passivo)**  
   - Análise de vulnerabilidades passiva realizada diretamente no site, sem interferir no servidor.  

3. **Nessus (Ativo)**  
   - Scan ativo com foco em vulnerabilidades detalhadas do sistema alvo, incluindo falhas de configuração e exposições conhecidas.  

## Estrutura do Repositório

/pdfs
├── zap_docker_scan.pdf
├── zap_site_php_scan.pdf
├── hostedscan_passivo.pdf
└── nessus_ativo.pdf

Cada PDF contém:  
- Metodologia do scan  
- Resultados encontrados  
- Observações e recomendações de mitigação  

## Observações

- Estes documentos foram gerados apenas para fins de aprendizado e testes éticos.  
- Não devem ser utilizados para exploração de sistemas sem autorização.  

