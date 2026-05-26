# AWS & Nagios SOC Monitoring Lab

### Versão em Português
**Resumo do Projeto:**
Implementação de uma infraestrutura de monitoramento de segurança e disponibilidade na nuvem AWS. O objetivo foi simular um ambiente de operações (SOC) para monitorar ativos críticos (Linux e Windows) utilizando Nagios Core.

**Principais Atividades Técnicas:**
* **Infraestrutura AWS:** Provisionamento de 4 instâncias EC2 e configuração de VPC/Security Groups (Firewall) para segmentação de rede.
* **Monitoramento Linux (NRPE):** Configuração de agentes seguros com restrição de IP (`allowed_hosts`) para evitar conexões não autorizadas.
* **Monitoramento Windows (NSClient++):** Integração via protocolo criptografado e monitoramento de serviços críticos (RDP, CPU, Disco).
* **Segurança:** Implementação de autenticação no painel web e restrição de portas (5666, 12489) apenas para o servidor de monitoramento.

**Tecnologias:** AWS EC2, Nagios Core 4.5, Ubuntu Server, NRPE, NSClient++, Bash Scripting.

---

### English Version
**Project Summary:**
Deployment of a security and availability monitoring infrastructure on AWS cloud. The goal was to simulate a Security Operations Center (SOC) environment to monitor critical assets (Linux and Windows) using Nagios Core.

**Key Technical Activities:**
* **AWS Infrastructure:** Provisioned 4 EC2 instances and configured VPC/Security Groups (Firewall) for network segmentation.
* **Linux Monitoring (NRPE):** Configured secure agents with IP restriction (`allowed_hosts`) to prevent unauthorized connections.
* **Windows Monitoring (NSClient++):** Integration via encrypted protocol and monitoring of critical services (RDP, CPU, Disk).
* **Security Hardening:** Implemented web panel authentication and restricted ports (5666, 12489) strictly to the monitoring server.

**Tech Stack:** AWS EC2, Nagios Core 4.5, Ubuntu Server, NRPE, NSClient++, Bash Scripting.

---
**Check the configuration files above (`.cfg`) to see the security implementation details.**
