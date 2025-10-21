## 🧰 ShellTools — Coleção de Scripts Úteis para Linux

**ShellTools** é um conjunto de scripts em **bash** criados para automatizar tarefas comuns no Linux, facilitando o diagnóstico, manutenção, segurança e utilitários diversos do sistema.
Ideal para administradores de sistemas, usuários avançados e entusiastas de shell scripting.

---

### 📂 Conteúdo Principal

| Script              | Função                                                        |
| ------------------- | ------------------------------------------------------------- |
| **FUSB**            | Monta e gerencia unidades USB.                                |
| **MakeUrban**       | Cria ambientes de desenvolvimento ou imagens personalizadas.  |
| **RaizQuadrada**    | Calcula a raiz quadrada de um número no terminal.             |
| **RecuperaGrub**    | Recupera o bootloader GRUB em sistemas Linux danificados.     |
| **SegundoGrau**     | Resolve equações do segundo grau diretamente no shell.        |
| **atalho**          | Cria atalhos e aliases personalizados para comandos.          |
| **checkdns**        | Testa a resolução de nomes DNS e verifica conectividade.      |
| **checklan**        | Diagnostica a rede local e checa conectividade entre hosts.   |
| **ddin / ddout**    | Facilita cópias de imagens (ISO/IMG) com `dd` e verificação.  |
| **dnstest**         | Executa testes de resolução de domínios.                      |
| **falar**           | Faz o sistema "falar" mensagens com suporte a TTS.            |
| **firewall**        | Configura e gerencia regras básicas de firewall.              |
| **jailsys**         | Isola processos em ambiente controlado (mini jail).           |
| **lanspeed**        | Mede a velocidade de transferência na rede local.             |
| **limpar**          | Remove arquivos temporários e limpa o sistema.                |
| **listUSB**         | Lista dispositivos USB conectados e suas informações.         |
| **mapear-ssh**      | Mapeia hosts acessíveis via SSH em uma rede.                  |
| **matematica**      | Calculadora avançada via terminal (suporta várias operações). |
| **myip**            | Mostra o IP público e local do sistema.                       |
| **pinga**           | Ping múltiplo com relatório rápido de latência.               |
| **prevtempo**       | Mostra a previsão do tempo via API ou comando `curl`.         |
| **relatoriohd**     | Gera relatório de uso e estado dos discos.                    |
| **removeMySQL**     | Remove completamente o MySQL e suas dependências.             |
| **removerapp**      | Desinstala aplicativos e limpa sobras do sistema.             |
| **reparar**         | Executa correções básicas de sistema e pacotes.               |
| **scan / scanrede** | Varre a rede local em busca de hosts ativos.                  |
| **syncTime**        | Sincroniza o horário do sistema com servidores NTP.           |
| **tar2**            | Compacta e extrai arquivos `.tar` com interface simplificada. |

---

### ⚙️ Instalação

```bash
git clone https://github.com/seuusuario/ShellTools.git
cd ShellTools
chmod +x ShellTools/*
```

Para facilitar o uso:

```bash
sudo cp ShellTools/* /usr/local/bin/
```

---

### 💡 Uso

Basta chamar o nome do script:

```bash
checkdns google.com
prevtempo São_Paulo
relatoriohd
```

---

### 🧠 Requisitos

* Distribuição Linux baseada em Debian, Arch, Fedora ou Alpine
* Bash 4.0+
* Ferramentas básicas: `curl`, `jq`, `bc`, `ip`, `awk`, `sed`, `nmap`, etc.

---

### 📜 Licença

Distribuído sob a **MIT License** — livre para uso, modificação e redistribuição.
Contribuições são bem-vindas!

---

Quer que eu monte também um **README.md** formatado com essa descrição (com emojis, seções, e comandos prontos para copiar)?
Posso gerar o arquivo completo para você enviar direto ao GitHub.
