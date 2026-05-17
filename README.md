# 🛡️ Awesome CyberSec OS & Distros (The Ultimate List)

Um repositório curado e exaustivo de Sistemas Operacionais e Distribuições (Linux, Windows PE, BSD e Mobile) focados em Cibersegurança, Hacking Ético, Forense Digital (DFIR), Hardening, OPSEC e Privacidade.

---

## 📑 Índice
1. [⚔️ Teste de Invasão (Pentest) e Ofensiva](#-teste-de-invasão-pentest-e-ofensiva)
2. [🕵️‍♂️ Forense Digital e Resposta a Incidentes (DFIR)](#-forense-digital-e-resposta-a-incidentes-dfir)
3. [🦠 Análise de Malware e Engenharia Reversa](#-análise-de-malware-e-engenharia-reversa)
4. [🛡️ Defesa, Monitoramento e Hardening (Blue Team)](#-defesa-monitoramento-e-hardening-blue-team)
5. [🥷 Privacidade, OPSEC e Anonimato](#-privacidade-opsec-e-anonimato)
6. [📱 Segurança e Privacidade Móvel (Mobile)](#-segurança-e-privacidade-móvel-mobile)
7. [🛠️ Diagnóstico, Recuperação e Sanitização](#-diagnóstico-recuperação-e-sanitização)
8. [🏛️ Distros Históricas (Legado)](#-distros-históricas-legado)

---

## ⚔️ Teste de Invasão (Pentest) e Ofensiva

| Nome do Sistema | Base | Citações e Propósito |
| :--- | :--- | :--- |
| **Kali Linux** | Debian | Testes de intrusão, auditorias de rede e simulações ofensivas baseadas em uma suíte com mais de 600 ferramentas especializadas. A rainha do mercado. |
| **Parrot Security OS** | Debian | Híbrida. Hacking ético, forense digital e proteção da privacidade online com utilitários de criptografia e ambiente de desktop leve. |
| **BlackArch Linux** | Arch Linux | Repositório de alta densidade contendo milhares de ferramentas ofensivas (mais de 2.800) mantidas sob um modelo rolling release de alta estabilidade. |
| **BackBox Linux** | Ubuntu | Avaliação de segurança de rede com modo forense nativo que impede rigorosamente a montagem de mídias de armazenamento físicas. |
| **Athena OS** | Arch / NixOS | Distribuição modular baseada em perfis, permitindo configurar o sistema sob funções como Red Teamer e Web Pentester. Integração com plataformas como Hack The Box. |
| **Pentoo Linux** | Gentoo | Distribuição otimizada para testes de intrusão em redes Wi-Fi e quebra de senhas por meio de aceleração gráfica por GPU. Geralmente executada via Live USB. |
| **Wifislax** | Slackware | Distribuição com drivers de rede injetáveis modificados de fábrica para testes intensivos de segurança em adaptadores sem fio. |
| **Fedora Security Spin** | Fedora | Conjunto selecionado de ferramentas estáveis para análise de vulnerabilidades de rede e testes iniciais de segurança. |
| **DracOS Linux** | LFS | Sistema compilado do zero para máxima otimização e execução de explorações sem a sobrecarga de pacotes e serviços desnecessários. |
| **ArchStrike** | Arch Linux | Otimização de repositórios Arch com ferramentas modulares para exploração de vulnerabilidades e engenharia social. |
| **Cyborg Hawk Linux** | Ubuntu | Testes de penetração focados em segurança de redes móveis, infraestruturas sem fio corporativas e testes de estresse. |
| **Samurai WTF** | Ubuntu | (Web Testing Framework). Ambiente pré-configurado exclusivamente para testes de intrusão em aplicações web e descoberta de vulnerabilidades complexas. |
| **Garuda BlackArch** | Garuda (Arch) | Otimização estética e operacional do Arch Linux com repositórios ofensivos integrados, kernel de alto desempenho e snapshots nativos. |
| **NodeZero** | Ubuntu | Distribuição para testes de invasão com ferramentas para auditoria de segurança de rede e testes em ambientes IPv6. Atua bem como sistema duplo (servidor diário e pentest). |
| **Demon Linux** | Debian | Sistema de hacking ético minimalista e leve, ideal para execuções rápidas de prova de conceito. |
| **Bugtraq** | Debian/Ubuntu | Arsenal gigantesco para pentest e análise de malwares. |
| **Commando VM** | Windows | Script da Mandiant que transforma uma máquina Windows limpa em uma suíte ofensiva robusta. |

---

## 🕵️‍♂️ Forense Digital e Resposta a Incidentes (DFIR)

| Nome do Sistema | Base | Citações e Propósito |
| :--- | :--- | :--- |
| **CAINE** | Ubuntu | (Computer Aided Investigative Environment). Extração automatizada de evidências digitais e análise detalhada de discos rígidos com write-blocking rigoroso (conformidade jurídica). |
| **SIFT Workstation** | Ubuntu | Kit de ferramentas avançadas mantido pelo SANS Institute, projetado para investigações de incidentes cibernéticos complexos. |
| **Tsurugi Linux** | Ubuntu | Uma distro focada em investigações forenses profundas, OSINT (investigação com fontes abertas) e visão computacional forense. |
| **CSI Linux** | Ubuntu | Sistema unificado para computação forense criminal, investigações na Dark Web e inteligência de fontes abertas (OSINT), com assistente de IA Navi. |
| **DEFT Linux** | Ubuntu | Perícias forenses digitais especializadas com foco em recuperação de arquivos corrompidos, análise de disco, geração de relatórios e resposta a incidentes. |
| **Santoku Linux** | Ubuntu | O foco exclusivo deste sistema é a perícia de dispositivos móveis, extração de dados e análise de malware em mobile. |
| **Paladin Edge / Paladin** | Ubuntu | Clonagem automatizada rápida de evidências digitais e geração de somas de verificação hash (mantida pela SUMURI) sem alteração da mídia de origem. |
| **SMART Linux** | Slackware | Preservação jurídica de dados, gravação de imagens lógicas e análise de integridade física de discos corrompidos. |
| **Helix (Helix 3)** | Ubuntu | Investigação de mídias ativas, análise de memória RAM e preservação imediata de evidências digitais em tempo de execução. |
| **WinFE** | Windows PE | (Windows Forensic Environment). Ambiente live para peritos não alterarem os dados do HD do suspeito durante a extração. |

---

## 🦠 Análise de Malware e Engenharia Reversa

| Nome do Sistema | Base | Citações e Propósito |
| :--- | :--- | :--- |
| **REMnux** | Ubuntu | A referência absoluta para engenharia reversa de softwares maliciosos, inspeção de cabeçalhos binários e emulação de serviços de rede em sandbox seguro (dissecação de ransomware/trojans). |
| **Flare VM** | Windows | Script da Mandiant voltado para análise de malware avançada em sistemas operacionais Microsoft. |

---

## 🛡️ Defesa, Monitoramento e Hardening (Blue Team)

| Nome do Sistema | Base | Citações e Propósito |
| :--- | :--- | :--- |
| **Security Onion** | Oracle/CentOS| É uma maravilha do Blue Team para detecção de intrusão, unindo Suricata, Zeek e Wazuh em uma única interface (SOC). |
| **Kali Purple** | Debian | Solução para equipes de segurança defensiva estruturada de acordo com o NIST CSF, incorporando Elastic, Malcolm, Suricata e TheHive. |
| **Malcolm** | N/A | Suíte focada primariamente na captura de tráfego avançado e visualização de ameaças. |
| **Network Security Toolkit (NST)**| Fedora | Diagnóstico avançado de tráfego de rede, geolocalização de hosts e monitoramento visual corporativo com interface web integrada. |
| **OpenBSD** | BSD | Sistema focado em criptografia nativa integrada, auditoria de código constante para correções proativas e integridade total de rede. |
| **Alpine Linux** | Musl/BusyBox | Sistema focado em segurança com footprint mínimo, ideal para servidores corporativos e contêineres hardened. |
| **Owl (Openwall)** | Linux | Distribuição focada no endurecimento de segurança de servidores por meio de restrições profundas de kernel. |
| **Secureblue** | Fedora Atomic | Distribuição atômica imutável que utiliza kernels modificados, alocadores de memória blindados e navegador hardened. |
| **Kicksecure** | Debian | Distribuição hardened que limita de forma severa as permissões de administrador e aplica isolamento estrito de contas. |
| **CLIP OS** | Gentoo Hardened| Sistema de segurança multinível governamental francês que isola processos em "cages" e restringe acessos. |
| **Astra Linux (Special Ed.)**| Debian | Hardening Militar. Proteção de dados confidenciais com níveis graduais de segurança (Smolensk, Voronezh e Oryol) e checagem ELF. |
| **Devil-Linux** | Linux | Firewall corporativo executado a partir de mídia somente leitura. |
| **EnGarde Secure Linux** | Linux | Servidores blindados nativamente de fábrica contra acessos indevidos. |

---

## 🥷 Privacidade, OPSEC e Anonimato

| Nome do Sistema | Base | Citações e Propósito |
| :--- | :--- | :--- |
| **Qubes OS** | Xen / Fedora | Compartimentação extrema. Isolamento de aplicações e redes em máquinas virtuais individuais (qubes) com bordas coloridas indicativas de confiança. |
| **Tails OS** | Debian | Sistema amnésico inicializável via USB que executa na memória RAM e direciona obrigatoriamente todo o tráfego através da rede Tor. Destrói dados no desligamento. |
| **Whonix** | Debian/Kicksecure| Arquitetura virtualizada que divide o sistema em Gateway (Tor) e Workstation para neutralizar completamente o vazamento de IP real. |
| **Linux Kodachi** | Debian/Xubuntu | Distribuição configurada com múltiplas camadas de criptografia, VPN nativa integrada e rede Tor, anti-forense "out-of-the-box". |
| **Ubuntu Privacy Remix** | Ubuntu | Execução segura e offline em RAM, impedindo roubo físico de chaves e dados. |
| **Lightweight Portable Security (LPS)**| Linux | Navegação temporária e anônima para conexões corporativas sem persistência de disco. |
| **Jondo Live-CD** | Debian | Roteamento de pacotes através do mix cascades JonDonym para ocultar o IP do tráfego. |
| **Webconverger** | Debian | Ambiente de Kiosk na web altamente travado e anônimo para terminais públicos. |
| **Septor Linux** | Debian KDE | Projetado para surfar em serviços ocultos descentralizados (Deep/Dark Web). |
| **PureOS** | Debian | Software livre da Purism focado em privacidade ativista. |
| **Tinfoil Hat Linux** | Slackware | Distribuição minimalista para ultra-paranóia contra espionagem física. |
| **Discreete Linux** | Debian | Proteção isolada contra Trojans estatais e espionagem de governos (Antigo UPR). |
| **IprediaOS** | Fedora | Roteamento anônimo usando a rede I2P em vez da rede Tor. |
| **Subgraph OS** | Debian | (Descontinuado). Usava contêineres sandbox para isolar o navegador de aplicativos do sistema base. |

---

## 📱 Segurança e Privacidade Móvel (Mobile)

| Nome do Sistema | Base | Citações e Propósito |
| :--- | :--- | :--- |
| **GrapheneOS** | Android (AOSP) | Sistema de código aberto sem serviços Google, baseado em sandboxing rigoroso de processos e mitigação de exploits. (Padrão ouro de OpSec Mobile). |
| **CalyxOS** | Android (AOSP) | Privacidade simplificada com microG anônimo, firewall Datura e criptografia. |
| **/e/OS** | Android (AOSP) | Ecossistema de-googled com repositório próprio, focado em conformidade de dados. |
| **DivestOS** | Android (AOSP) | Hardening de drivers, remoção de scripts de telemetria proprietária e blindagem celular. |
| **IodeOS (iodèOS)** | Android (AOSP) | Bloqueio de conexões invisíveis via firewall integrado nativo. |
| **LineageOS (Sem GApps)** | Android (AOSP) | ROM limpa sem o rastreio corporativo do Google; atua como base segura. |
| **VoltageOS** | Android (AOSP) | ROM voltada para o controle granular de permissões em smartphones. |
| **crDroid** | Android (AOSP) | Extensão dos controles do LineageOS com ajustes profundos de privacidade. |
| **CopperheadOS** | Android (AOSP) | Pioneira comercial em endurecimento de kernel móvel (explorou conceitos hoje no Graphene). |

---

## 🛠️ Diagnóstico, Recuperação e Sanitização

| Nome do Sistema | Base | Citações e Propósito |
| :--- | :--- | :--- |
| **Darik's Boot And Nuke (DBAN)** | Linux | Destruição física-lógica permanente de dados residuais para impedir a recuperação forense (Wipe). |
| **Ophcrack LiveCD** | Linux | Recuperação emergencial de credenciais (quebra) do Windows utilizando tabelas rainbow criptográficas. |
| **SystemRescueCD** | Gentoo/Arch | Reparo emergencial de partições corrompidas e administração de baixo nível de discos físicos. |
| **HirensBootCD** | Windows PE | Ambiente emergencial com ferramentas pesadas de diagnóstico de hardware e recuperação de sistema. |
| **Parted Magic** | Linux | Ferramenta especializada para particionamento de baixo nível e resgate de arquivos e diagnóstico. |
| **ALT Linux Rescue** | ALT Linux | Resgate forense, verificação de vírus de inicialização e diagnóstico de mídias de armazenamento físicas. |
| **Dr.Web LiveCD** | Linux | Inicialização emergencial focada na varredura e neutralização de malwares residentes em setores de boot (Bootkits). |

---

## 🏛️ Distros Históricas (Legado)
*Sistemas descontinuados ou incorporados por distros modernas que revolucionaram o setor.*

| Nome do Sistema | Base | Citações e Propósito |
| :--- | :--- | :--- |
| **BackTrack Linux** | Slackware/Ubuntu | O avô de todos. Fusão histórica que estabeleceu os padrões de usabilidade para testes de intrusão antes de evoluir para o atual Kali Linux. |
| **Whoppix (WhiteHat Knoppix)**| Knoppix | Live CD pioneiro no empacotamento integrado de ferramentas de segurança de rede. |
| **WHAX (WhiteHat Slax)** | Slax | Sucessor modular do Whoppix que oferecia portabilidade superior para operadores. |
| **Auditor Security Collection** | Linux | Distribuição primitiva focada em testes em adaptadores sem fio. Mais tarde uniu-se ao WHAX para formar o BackTrack. |
