Cybersecurity Lab — Linux Security

Sobre o projeto

Laboratório prático desenvolvido em Linux Mint para aplicar fundamentos de Cybersecurity, administração de sistemas e redes.

O projeto aborda a identificação de portas e serviços, análise de configurações, firewall, atualização do sistema e documentação de evidências técnicas.

Objetivo

Avaliar a superfície de exposição do sistema Linux e aplicar boas práticas básicas de segurança, mantendo um registro das análises realizadas.

Ambiente

- Linux Mint 22.3
- Ubuntu 24.04 LTS
- Arquitetura x86_64
- Firewall UFW
- Nmap
- Git/GitHub

Ferramentas

- Nmap
- UFW
- "ss"
- "systemctl"
- CUPS
- Avahi/mDNS
- Git

Atividades realizadas

- Inventário da rede local
- Análise de portas e serviços
- Verificação do firewall UFW
- Análise do CUPS
- Análise do Avahi/mDNS
- Verificação de serviços ativos
- Verificação do Bluetooth
- Atualização dos pacotes do sistema
- Comparação das configurações antes e depois
- Organização das evidências técnicas

Estrutura

cybersecurity-lab/
├── configuracoes/
├── relatorio/
├── scans/
├── .gitignore
└── README.md

Resultado

O sistema foi analisado e documentado. O UFW estava ativo com política padrão de bloqueio de conexões de entrada, enquanto o CUPS estava limitado ao localhost.

As análises e evidências foram organizadas no repositório para demonstrar o processo realizado durante o laboratório.

Escopo

Todas as análises foram realizadas no próprio sistema Linux utilizado no laboratório, com finalidade educacional e defensiva.

Competências desenvolvidas

- Linux
- Redes de computadores
- Análise de portas e serviços
- Firewall
- Nmap
- Administração de sistemas
- Fundamentos de Cybersecurity
- Documentação técnica
