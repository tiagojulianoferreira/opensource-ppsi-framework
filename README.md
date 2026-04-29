Tecnologias abertas para uso com o Framework de Privacidade e Segurança da Informação - PPSI Framework

# O framework PPSI
Conforme o disposto no art. 8º, da PORTARIA SGD/MGI Nº 852, os órgãos e as entidades deverão adotar o Framework de Privacidade e Segurança da Informação. Ele é composto por um conjunto de controles, metodologias e ferramentas de apoio. [ler mais](https://www.gov.br/governodigital/pt-br/privacidade-e-seguranca/framework).

Guia do Framework de Privacidade e Segurança da Informação ([Ler em PDF](https://www.gov.br/governodigital/pt-br/privacidade-e-seguranca/ppsi/guia_framework_psi.pdf)) | [Guia de Gerenciamento de Vulnerabilidade](https://www.gov.br/governodigital/pt-br/privacidade-e-seguranca/ppsi/guia_gerenciamento_vulnerabilidades.pdf)

---

## 🧩 Articulação com os Pilares PPSI

Para uma implementação eficaz, as ferramentas abaixo são categorizadas conforme os quatro pilares fundamentais do framework:

* **Pessoas (P):** Foco em conscientização, treinamento e cultura de segurança.
* **Processos (P):** Metodologias, fluxos de trabalho, automação e governança.
* **Sistemas (S):** Tecnologias de proteção de dados, aplicações e gestão de identidades.
* **Infraestrutura (I):** Segurança de rede, monitoramento físico/lógico e ativos institucionais.

---

# 🛡️ Controles de Cibersegurança

### [Snort IDS/IPS](https://www.snort.org) | [Suricata IDS/IPS](https://suricata.io/)
**PPSI:** 🏗️ **Infraestrutura** (Detecção e Prevenção de Intrusão).
⚖️ GPL-2
> Realizam análise de tráfego em tempo real e detecção de ameaças de alto desempenho.

### [Technitium DNS](https://technitium.com/dns/)
**PPSI:** 🏗️ **Infraestrutura** (Serviços de Rede Seguros).
⚖️ GPLv3
> Servidor DNS autoritativo e recursivo para privacidade e segurança.

---

## Controle 1: Inventário e Controle de Ativos Institucionais
### [GLPI Agent](https://github.com/glpi-project/glpi-agent)
**PPSI:** 🏗️ **Infraestrutura / Processos**.
⚖️ GPL-2
> Agente de gerenciamento para execução de tarefas em nome de um servidor GLPI.

## Controle 2: Inventário e Controle de Ativos de Software
### [OCS inventory](https://ocsinventory-ng.org/?lang=en)
**PPSI:** 🏗️ **Infraestrutura / Sistemas**.
⚖️ GPLv3
> Escaneamento e inventário de hardware e software para implantação de pacotes seguros.

## Controle 3: Proteção de Dados
### [Anubis (Anti-Scraper)](https://anubis.techaro.lol/)
**PPSI:** 🖥️ **Sistemas**.
⚖️ MIT
> Interrupção de rastreadores de IA usando prova de trabalho.

### [Minarca Backup](https://minarca.org/en_CA/features)
**PPSI:** 🔄 **Processos / Sistemas**.
> Solução de backup centralizada com agente dedicado.

## Controle 4: Configuração Segura de Ativos Institucionais e Software
### [BunkerWeb (WAF)](https://www.bunkerweb.io/)
**PPSI:** 🖥️ **Sistemas**.
⚖️ AGPL-3
> Web Application Firewall (WAF) de próxima geração.

### [CrowdSec](https://crowdsec.net/)
**PPSI:** 🖥️ **Sistemas / Infraestrutura**.
⚖️ MIT
> Proteção participativa contra IPs maliciosos e acesso a CTI.

### [fail2ban](https://github.com/fail2ban/fail2ban)
**PPSI:** 🖥️ **Sistemas**.
⚖️ GPL-2
> Bane endereços IP baseando-se em falhas de login em arquivos de log.

## Controle 5: Gestão de Contas
### [OpenLDAP](https://www.openldap.org/)
**PPSI:** 🖥️ **Sistemas**.
> Implementação aberta do protocolo LDAP para diretórios.

### [GovBR - Unifi Captive Portal](https://github.com/dcc6fvo/unifi-govbr)
**PPSI:** 🏗️ **Infraestrutura / Pessoas**.
⚖️ MIT
> Portal captivo para login único federal compatível com Unifi.

## Controle 6: Gestão do Controle de Acesso
### [Authelia](https://www.authelia.com/) | [Authentik](https://goauthentik.io/) | [Keycloak](https://www.keycloak.org/) | [Zitadel](https://zitadel.com/)
**PPSI:** 🖥️ **Sistemas** (IAM/SSO).
> Provedores de identidade, autenticação multifator (MFA) e logon único.

### [Kanidm](https://kanidm.com)
**PPSI:** 🖥️ **Sistemas**.
⚖️ MPL-2.0
> Gerenciamento de identidade simples e seguro.

### [Kong Api Gateway](https://docs.konghq.com/gateway/latest/install/#kong-community)
**PPSI:** 🏗️ **Infraestrutura / Sistemas**.
⚖️ Apache-2
> Orquestração de tráfego de API, autenticação e balanceamento de carga.

## Controle 7: Gestão Contínua de Vulnerabilidades
### [DefectDojo](https://defectdojo.com/) | [OpenVas](https://www.openvas.org/)
**PPSI:** 🔄 **Processos**.
> Gestão de vulnerabilidades, DevSecOps e scanners completos.

### [DNSDiag](https://dnsdiag.org/)
**PPSI:** 🏗️ **Infraestrutura**.
⚖️ BSD2-Clause
> Auditoria de segurança e solução de problemas de DNS.

### [Shuffle (SOAR)](https://github.com/shuffle/shuffle)
**PPSI:** 🔄 **Processos**.
⚖️ AGPL-3
> Automação e resposta a incidentes de segurança.

### [Wireshark](https://github.com/wireshark/wireshark)
**PPSI:** 🏗️ **Infraestrutura / Processos**.
⚖️ GPL-2
> Analisador de protocolos de rede para análise forense e diagnósticos.

## Controle 8: Gestão de Registros de Auditoria
### [Graylog](https://graylog.org/) | [Loki](https://grafana.com/loki) | [Wazuh (SIEM)](https://wazuh.com/)
**PPSI:** 🏗️ **Infraestrutura / Processos**.
> Agregação de logs, SIEM e XDR para visibilidade total.

## Controle 9: Proteções de E-mail e Navegador Web
### [Apache SpamAssassin](https://spamassassin.apache.org/) | [MailScanner](https://www.mailscanner.info/) | [Proxmox Mail Gateway](https://www.proxmox.com/en/proxmox-mail-gateway/overview)
**PPSI:** 🖥️ **Sistemas**.
> Filtragem de spam, antivírus e proteção contra phishing em e-mails.

### [PacketStreamer](https://github.com/deepfence/PacketStreamer) | [SecretScanner](https://github.com/deepfence/SecretScanner)
**PPSI:** 🖥️ **Sistemas / Infraestrutura**.
> Captura remota de pacotes e busca por segredos (tokens/senhas) expostos.

## Controle 10: Defesas Contra Malware
### [Clamav Antivírus](https://www.clamav.net/)
**PPSI:** 🖥️ **Sistemas**.
⚖️ GPL-2
> Detecção de cavalos de Troia, vírus e malwares.

## Controle 11: Recuperação de Dados
### [Bacula](https://www.bacula.org/)
**PPSI:** 🔄 **Processos**.
⚖️ AGPLv3
> Gerenciamento de backup, recuperação e verificação de dados em rede.

## Controle 12 & 13: Gestão de Infraestrutura e Monitoramento
### [phpIPAM](https://phpipam.net/) | [Netbox](https://github.com/netbox-community/netbox)
**PPSI:** 🏗️ **Infraestrutura**.
> Gestão de endereços IP e "fonte única de verdade" para automação de rede.

### [Cacti](https://www.cacti.net/) | [Prometheus](https://prometheus.io/) | [Zabbix](https://github.com/zabbix/zabbix) | [Ntop-NG](https://www.ntop.org/)
**PPSI:** 🏗️ **Infraestrutura**.
> Monitoramento de performance, tráfego e disponibilidade em tempo real.

### [MyIP DNS Check](https://ipcheck.ing/#/)
**PPSI:** 🏗️ **Infraestrutura**.
⚖️ MIT
> Diagnóstico de conectividade, vazamentos de DNS e geolocalização.

## Controle 14: Conscientização e Treinamento
### [SRE - Site Reliability Engineering (livro)](https://sre.google/sre-book/table-of-contents/)
**PPSI:** 👤 **Pessoas**.
⚖️ AGPL-3
> Cultura e disciplina focada no ciclo de vida e confiabilidade de sistemas.

## Controle 16: Segurança de Aplicações
### [Caddy](https://caddyserver.com/) | [Zoraxy](https://zoraxy.aroz.org/index.html)
**PPSI:** 🖥️ **Sistemas / Infraestrutura**.
> Servidores web e proxies reversos com foco em HTTPS automático e facilidade.

### [HAProxy API](https://www.haproxy.com/documentation/haproxy-data-plane-api/) | [Maglev](https://github.com/kkdai/maglev)
**PPSI:** 🏗️ **Infraestrutura**.
> Balanceamento de carga e APIs para configurações dinâmicas.

### [mitmproxy](https://github.com/mitmproxy/mitmproxy) | [OWASP ZAP](https://www.zaproxy.org/)
**PPSI:** 🔄 **Processos / Sistemas**.
> Ferramentas para testes de penetração e descoberta de vulnerabilidades web.

---

## 🤝 Colabore com este Inventário!

Este repositório é um esforço contínuo para mapear tecnologias que auxiliem a administração pública a cumprir os controles do PPSI. 

**Encontrou uma ferramenta aberta que atende a um dos controles?**
**Tem uma sugestão de melhoria na articulação dos pilares?**

📢 **[Abra uma Issue aqui](https://github.com/seu-usuario/opensource-ppsi-framework/issues)** e contribua com a governança digital brasileira!

---
*Controles 15 (Gestão de Provedores), 17 (Resposta a Incidentes), 18 (Testes de Invasão) e a seção de Controles de Privacidade (19 a 31) estão em fase de mapeamento.*
