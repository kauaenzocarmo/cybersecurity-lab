# Cybersecurity Lab — Linux Security

## Objetivo
Projeto prático de segurança realizado em um sistema Linux Mint, com foco em análise de serviços, portas, firewall, atualizações e configurações de segurança.

## Ambiente
- Sistema: Linux Mint 22.3
- Base: Ubuntu 24.04 LTS
- Arquitetura: x86_64
- Firewall: UFW
- Ferramenta de análise: Nmap
- Monitoramento de serviços: ss / systemctl

## Atividades realizadas
- Inventário da rede local
- Análise de portas e serviços
- Verificação do firewall UFW
- Análise do CUPS
- Análise do Avahi/mDNS
- Verificação de serviços ativos
- Verificação do Bluetooth
- Atualização dos pacotes do sistema
- Comparação das configurações antes e depois
- Registro das evidências e resultados

## Resultado
O sistema foi analisado e documentado, com o firewall configurado para negar conexões de entrada por padrão. O serviço CUPS permanece limitado ao localhost, enquanto o Avahi foi identificado como serviço de descoberta de dispositivos na rede local.

## Ferramentas
- Linux Mint
- Nmap
- UFW
- ss
- systemctl
- Avahi
- CUPS
