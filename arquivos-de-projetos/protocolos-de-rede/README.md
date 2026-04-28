# Protocolos de Transferência de Rede

Este diretório contém documentação e recursos relacionados aos protocolos de transferência de dados e acesso remoto em redes de computadores.

## Protocolos disponíveis

### FTP (File Transfer Protocol)
- **Descrição:** Protocolo clássico de transferência de arquivos
- **Segurança:** Nenhuma (dados em texto plano)
- **Porta padrão:** 21
- **Uso:** Transferência de arquivos em redes isoladas, sistemas legados
- **Guia completo:** [guia-ftp.html](../../guia-ftp.html)

### SFTP (SSH File Transfer Protocol)
- **Descrição:** Transferência segura de arquivos sobre SSH
- **Segurança:** Criptografia de ponta a ponta
- **Porta padrão:** 22
- **Uso:** Ambiente de produção, dados sensíveis, transferência segura
- **Guia completo:** [guia-ftp.html](../../guia-ftp.html)

### SSH (Secure Shell)
- **Descrição:** Acesso remoto seguro e administração de sistemas
- **Segurança:** Criptografia de ponta a ponta
- **Porta padrão:** 22
- **Uso:** Administração remota, acesso a servidores
- **Guia completo:** [guia-telnet-ssh.html](../../guia-telnet-ssh.html)

### Telnet
- **Descrição:** Protocolo clássico de acesso remoto (obsoleto)
- **Segurança:** Nenhuma (dados em texto plano)
- **Porta padrão:** 23
- **Uso:** Diagnóstico, redes isoladas, sistemas legados
- **Guia completo:** [guia-telnet-ssh.html](../../guia-telnet-ssh.html)

## Recomendações de Uso

| Cenário | Protocolo Recomendado |
|---------|----------------------|
| Ambientes de produção | SFTP / SSH |
| Dados sensíveis | SFTP / SSH |
| Redes internas isoladas | FTP |
| Diagnóstico/teste | Telnet / FTP |
| Sistemas legados | Depende do suporte |
| Internet pública | SSH / SFTP |

## Recursos educacionais

Todos os protocolos possuem guias interativos e exemplos práticos disponíveis na página principal do projeto.
