# Lab 01 – Recon em ambiente didático (vpsadmin)

## 1. Objetivo
Mapear serviços e possíveis superfícies de ataque em um alvo controlado (minha própria VPS / máquina de laboratório), utilizando ferramentas de recon disponíveis no Kali Linux.

## 2. Ambiente
- Atacante: Kali Linux (máquina principal)
- Alvo: Sony Vaio / VPS própria (ambiente didático e autorizado)
- Tipo de teste: Laboratório de estudo (Não é ambiente de terceiros)

## 3. Ferramentas planejadas
- `nslookup` / `dig` – coleta de informações DNS
- `nmap` – varredura de portas e identificação de serviços
- `gobuster` – descoberta de diretórios/paths (se houver web)
- Outros: (anotar aqui se usar mais algum)

## 4. Comandos executados e saídas (resumo)
> Aqui você vai colar depois os comandos e os trechos importantes das saídas.

### 4.1. DNS / Nome → IP
Comando:
`dig exemplo.com`  
Resumo da saída:  
- IP: ...
- Servidor DNS: ...
- Observações: ...

### 4.2. Varredura Nmap
Comando:
`nmap -sS -sV -O ALVO`  
Resumo da saída:  
- Portas abertas:
- Serviços identificados:
- Sistema operacional provável:

## 5. Análise técnica (raciocínio)
- O que essas informações revelam sobre o alvo?
- Que tipo de serviço parece mais sensível?
- Há alguma porta/serviço que chama atenção?

## 6. Visão Blue Team (como defender)
- O que um Blue Team deveria fazer para:
  - Reduzir exposição desnecessária
  - Esconder banners/versões sensíveis
  - Configurar firewall, IDS/IPS, etc.

## 7. Conclusão do lab
- O que foi aprendido neste exercício?
- Próximos passos sugeridos para próximos labs.
