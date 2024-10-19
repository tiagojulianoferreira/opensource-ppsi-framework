# opensource-ppsi-framework
Tecnologias abertas para uso com o Framework de Privacidade e Segurança da Informação, sendo de responsabilidade da Estrutura de Governança de cada órgão e entidade

# O framework PPSI
Conforme o disposto no art. 8º, da PORTARIA SGD/MGI Nº 852, os órgãos e as entidades deverão adotar o Framework de Privacidade e Segurança da Informação, sendo de responsabilidade da Estrutura de Governança de cada órgão e entidade. A decisão de não implementação de medidas consideradas obrigatórias pelo framework deverá ser precedida de adequada motivação com base em análise de riscos. Ele é composto por um conjunto de controles, metodologias e ferramentas de apoio. [ler mais](https://www.gov.br/governodigital/pt-br/privacidade-e-seguranca/framework).

Guia do Framework de Privacidade e Segurança da Informação ([Ler em PDF](https://www.gov.br/governodigital/pt-br/privacidade-e-seguranca/ppsi/guia_framework_psi.pdf))

# Controles de Cibersegurança

## Controle 1: Inventário e Controle de Ativos Institucionais
# [GLPI Agent](https://github.com/glpi-project/glpi-agent)
⚖️ GPL-2
> O GLPI Agent é um agente de gerenciamento genérico. Ele pode executar um certo número de tarefas, de acordo com seu próprio plano de execução, ou em nome de um servidor GLPI agindo como um ponto de controle.

# [Netbox](https://github.com/netbox-community/netbox)
⚖️ Apache License 2.0 by DigitalOcean, LLC.
> 

## Controle 2: Inventário e Controle de Ativos de Software
# [OCS inventory](https://ocsinventory-ng.org/?lang=en)
⚖️ GPLv3
> É um software de código aberto. Ele permite que você escaneie e inventariie todos os seus dispositivos em seu departamento de TI. Depois de saber tudo sobre suas máquinas, tanto em termos de hardware quanto de software, você poderá implantar pacotes para manter seu ambiente seguro.

## Controle 3: Proteção de Dados
## Controle 4: Configuração Segura de Ativos Institucionais e Software
# [BunkerWeb (WAF)](https://www.bunkerweb.io/)
⚖️ AGPL-3

<!--![image](https://github.com/user-attachments/assets/86e7e654-bbc5-44b4-a334-e938a7ea7ba6)-->
> BunkerWeb is a next-generation and open-source Web Application Firewall (WAF).

## Controle 5: Gestão de Contas

# [OpenLDAP](https://www.openldap.org/)
> O software OpenLDAP é uma implementação de código aberto do Lightweight Directory Access Protocol .

## Controle 6: Gestão do Controle de Acesso


# [Authentik](https://goauthentik.io/)
⚖️ ????
4.6
<!--! [image](https://github.com/user-attachments/assets/594c1758-a33e-4b54-bb71-02785c8120b9)-->
> authentik é um IdP (Provedor de Identidade) e SSO (logon único) desenvolvido com a segurança em primeiro plano em cada pedaço de código e em cada recurso, com ênfase na flexibilidade e versatilidade.

# [Keycloak](https://www.keycloak.org/)
⚖️ Apache-2
> Gerenciamento de Identidade e Acesso de Código Aberto para Aplicações e Serviços Modernos

# [Zitadel](https://zitadel.com/)
⚖️ Apache-2

<!--![image](https://github.com/user-attachments/assets/156c2c3f-8f3a-4572-b6b6-b7c8613674e6)-->
> Gerenciamento de autenticação segura para seu aplicativo. Personalize conforme você cresce, com APIs fáceis e fluxos de trabalho programáveis. Foque no crescimento, seu login está em boas mãos.

# [Authelia](https://www.authelia.com/))
⚖️ Apache License, Version 2.0 
> Authelia é um servidor e portal de autenticação e autorização de código aberto que cumpre a função de gerenciamento de identidade e acesso (IAM) de segurança, fornecer autenticação multifator e logon único (SSO) para seus aplicativos por meio de um portal da web.

## Controle 7: Gestão Contínua de Vulnerabilidades
# [DefectDojo](https://defectdojo.com/)
⚖️ BSD-3-Clause
> DevSecOps, ASPM, Vulnerability Management. Tudo em uma plataforma.
# [OpenVas](https://www.openvas.org/)
⚖️ GPL-2
<!--![image](https://github.com/user-attachments/assets/91118b72-ecc9-4ec9-8a7c-5df5f1e175ea)-->
> O OpenVAS é um scanner de vulnerabilidades completo. Seus recursos incluem testes autenticados e não autenticados, vários protocolos industriais e de internet de alto e baixo nível, ajuste de desempenho para varreduras em larga escala e uma poderosa linguagem de programação interna para implementar qualquer tipo de teste de vulnerabilidade. O scanner obtém os testes para detectar vulnerabilidades de um feed que tem um longo histórico e atualizações diárias.

# [Shuffle (SOAR)](https://github.com/shuffle/shuffle)
⚖️ AGPL-3
> Shuffle: Uma plataforma de Orquestração, Automação e Resposta - SOAR de segurança de propósito geral. Nosso foco é colaboração e compartilhamento de recursos.
# Controle 8: Gestão de Registros de Auditoria
# [Graylog](https://graylog.org/)
> Plataforma de gerenciamento de logs gratuita e aberta.
# [Loki](https://grafana.com/loki)
⚖️ AGPL-3
> Loki é um sistema de agregação de logs multi-tenant, altamente disponível e escalável horizontalmente, inspirado no Prometheus . Ele foi projetado para ser muito econômico e fácil de operar. Ele não indexa o conteúdo dos logs, mas sim um conjunto de rótulos para cada fluxo de logs.
# [Wazuh (SIEM)](https://wazuh.com/)
⚖️ GPL-2 e AGPL-3
> Wazuh - A plataforma de segurança de código aberto. Proteção XDR e SIEM unificada para endpoints e cargas de trabalho em nuvem.
# Controle 9: Proteções de E-mail e Navegador Web
# Controle 10: Defesas Contra Malware
# Controle 11: Recuperação de Dados
[Bacula](https://www.bacula.org/)
⚖️ AGPLv3
> Bacula é um conjunto de programas de computador que permite ao administrador do sistema gerenciar backup, recuperação e verificação de dados de computador em uma rede de computadores de diferentes tipos. Bacula também pode ser executado inteiramente em um único computador e pode bac
# Controle 12: Gestão da Infraestrutura de Rede
# Controle 13: Monitoramento e Defesa da Rede
# [Zabbix](https://github.com/zabbix/zabbix)
⚖️ AGPL-3
> Monitoramento em tempo real de componentes e serviços de TI, como redes, servidores, VMs, aplicativos e nuvem.
# Controle 14: Conscientização e Treinamento de Competências sobre Segurança
# Controle 15: Gestão de Provedor de Serviços
# Controle 16: Segurança de Aplicações

# [OWASP ZAP](https://www.zaproxy.org/)
⚖️ Apache-2
>  Uma ferramenta de código aberto para encontrar vulnerabilidades de segurança em aplicações web automaticamente enquanto elas são sendo desenvolvidas.
# Controle 17: Gestão de Resposta a Incidentes
# Controle 18: Testes de Invasão

# Controles de Privacidade
## Controle 19: Inventário e Mapeamento

...

## Controle 31: Segurança Aplicada à Privacidade
