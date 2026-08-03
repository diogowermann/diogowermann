# Olá, eu sou Diogo Wermann

[English](README.md) | [Português](README.pt-BR.md)

**Analista de TI com foco em automação de infraestrutura, gerenciamento de endpoints, identidade híbrida e cibersegurança.**

Desenvolvo ferramentas orientadas a ambientes reais de produção, principalmente para o ecossistema Microsoft, com ênfase em automação segura, menor privilégio, observabilidade e implantações reversíveis. Minha atuação envolve Windows Server, Active Directory, Microsoft Entra ID, Intune, PowerShell, Python, infraestrutura Linux, APIs, monitoramento e sistemas corporativos internos.

Atualmente curso **Análise e Desenvolvimento de Sistemas** e estou aprofundando meus conhecimentos em **cibersegurança, identidade em nuvem e segurança de endpoints**.

## Áreas de atuação

- Microsoft Intune e gerenciamento corporativo de endpoints
- Active Directory e identidade híbrida com Microsoft Entra
- Automação com PowerShell e administração Windows
- APIs em Python, dashboards operacionais e monitoramento
- Servidores Linux, virtualização, backup e observabilidade
- Engenharia de segurança, menor privilégio e implantações controladas

## Projetos em destaque

| Projeto | Descrição | Foco de engenharia |
|---|---|---|
| [DeviceLifecycle](https://github.com/diogowermann/DeviceLifecycle) | Automação em PowerShell para identificar, reportar, colocar em quarentena e remover dispositivos obsoletos no Active Directory, Microsoft Entra ID e Intune. | Correlação de identidades, transições seguras, limites de ações, auditoria e recuperação |
| [DeviceLifecycle-API](https://github.com/diogowermann/DeviceLifecycle-API) | Extensão somente leitura em FastAPI para publicar de forma controlada relatórios, logs, metadados e informações de saúde do DeviceLifecycle. | Design de API, autenticação, leitura estável de arquivos, restrição de rede e integração operacional |
| [Windows-Unattended-Provisioning](https://github.com/diogowermann/Windows-Unattended-Provisioning) | Pipeline de provisionamento seguro do Windows que gera uma mídia de instalação automatizada, ingressa endpoints em uma OU definida do Active Directory on-premises, conclui o registro híbrido no Microsoft Entra e prepara o dispositivo para o Windows LAPS gerenciado pelo Intune. | Instalação automatizada, injeção de segredos durante o build, Domain Join, identidade híbrida e limpeza de artefatos sensíveis |
| [WallpaperAgent](https://github.com/diogowermann/WallpaperAgent) | Agente Windows que consome um manifesto versionado, valida assets com SHA-256 e aplica imagens de desktop e tela de bloqueio por meio de implantação gerenciada pelo Intune. | Separação de privilégios, integridade de conteúdo, promoção atômica, empacotamento e rollback |
| [RustDeskIntuneDeployment](https://github.com/diogowermann/RustDeskIntuneDeployment) | Fluxo em PowerShell para implantar e configurar RustDesk pelo Microsoft Intune em ambientes self-hosted. | Aplicativos Win32, configuração de múltiplos perfis, detecção, confiança no servidor e governança do rollout |

## Tecnologias

### Automação e desenvolvimento

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)

### Infraestrutura e plataformas

![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?logo=microsoftazure&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)

## Como trabalho com engenharia

- **Falhar com segurança:** dados ausentes ou ambíguos não devem provocar ações destrutivas.
- **Automatizar com limites:** operações privilegiadas exigem escopo explícito, thresholds e limites por execução.
- **Projetar para recuperação:** quarentena, rollback, diagnóstico e trilhas de auditoria fazem parte da solução.
- **Separar responsabilidades:** máquina, usuário, publicador e consumidores recebem somente os acessos necessários.
- **Documentar a realidade operacional:** arquitetura, implantação, segurança e modos de falha são parte do produto.

## Direção profissional

Estou ampliando minha atuação em infraestrutura e automação para a área de cibersegurança, com interesse especial em:

- segurança de identidade e acesso;
- proteção e hardening de endpoints;
- monitoramento de segurança e resposta a incidentes;
- automação segura e engenharia de infraestrutura;
- segurança em ambientes híbridos e de nuvem.

## Idiomas

- Português: nativo
- Inglês: avançado

---

A maior parte dos projetos deste perfil surgiu de problemas operacionais reais. Identificadores corporativos, credenciais, endereços, certificados e outras informações sensíveis são removidos ou substituídos antes da publicação.