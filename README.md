# Automação de Infraestrutura no Linux (IaC)

Este repositório contém um **script de Infraestrutura como Código (IaC)** para configurar automaticamente **usuários, grupos, diretórios e permissões** em sistemas Linux. Com este script, é possível provisionar um ambiente padronizado e pronto para uso em novas máquinas virtuais.

## Funcionalidades

- Criação automática de usuários
- Configuração de grupos de usuários
- Geração e organização de diretórios
- Definição de permissões de acesso
- Execução rápida e reutilizável


## Tecnologias Utilizadas

- Shell Script (Bash)
- Linux (Ubuntu)

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/BrunoHenriqueOliveira/linux_IAC

2. Dê permissão de executar ao script:
   ```bash
   chmod +x criar_estrutura

3. Execute o script como superusuário:
   ```bash
   sudo ./criar_estrutura

## Como Reverter as Ações

Caso precise remover os usuários, grupos e diretórios criados, utilize o script de remoção:

1. Dê permissão de execução ao script de remoção:
   ```bash
   chmod +x desfazer_script.sh

2. Execute o script de remoção:
   ```bash
   sudo ./desfazer_script.sh
