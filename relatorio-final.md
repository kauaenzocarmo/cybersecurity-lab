# Relatório Final — Cybersecurity Lab

## 1. Objetivo

Realizar uma avaliação de segurança em um sistema Linux Mint, identificando serviços ativos, portas abertas, configurações de rede e mecanismos de proteção existentes.

## 2. Ambiente

- Sistema operacional: Linux Mint 22.3
- Base: Ubuntu 24.04 LTS
- Arquitetura: x86_64
- Firewall: UFW
- Ferramenta de análise: Nmap

## 3. Metodologia

Foram realizadas verificações locais utilizando ferramentas nativas do Linux e o Nmap.

As atividades incluíram:

- identificação da configuração de rede;
- levantamento de portas e serviços;
- análise dos serviços em execução;
- verificação do firewall;
- análise do CUPS;
- análise do Avahi;
- verificação do Bluetooth;
- verificação de atualizações;
- comparação das informações antes e depois das atualizações.

## 4. Resultados

O UFW encontra-se ativo e utiliza uma política padrão de bloqueio para conexões de entrada.

A análise local com Nmap identificou a porta TCP 631 associada ao CUPS.

A análise dos sockets confirmou que o CUPS está associado ao localhost, reduzindo sua exposição à rede.

O Avahi foi identificado como serviço responsável pela descoberta de dispositivos e serviços na rede local.

Também foram registradas as configurações de rede, serviços ativos, kernel e atualizações do sistema.

## 5. Conclusão

O projeto permitiu realizar uma avaliação prática da superfície de exposição do sistema Linux e documentar seus principais mecanismos de segurança.

As evidências coletadas foram organizadas em diretórios separados para configurações, varreduras e relatório.

O projeto demonstra conhecimentos práticos de administração Linux, análise de serviços, redes, firewall e fundamentos de segurança cibernética.

