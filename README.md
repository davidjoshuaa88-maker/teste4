# Máquina Linux Ubuntu no GitHub Codespaces

Este repositório configura um ambiente Linux Ubuntu na nuvem usando **GitHub Codespaces**.

> Observação: isso não é uma máquina virtual tradicional com interface gráfica. É um contêiner Linux na nuvem, acessado pelo navegador, com terminal de comandos.

## O que vem instalado

- Ubuntu (imagem base de desenvolvimento)
- Python 3.12
- Git
- curl e wget
- nano e vim

## Como iniciar

1. Abra este repositório no GitHub.
2. Clique no botão **Code**.
3. Abra a aba **Codespaces**.
4. Clique em **Create codespace on main**.
5. Aguarde a preparação do ambiente.
6. Quando abrir, use o terminal integrado para executar comandos Linux.

## Teste o ambiente

No terminal do Codespaces, execute:

```bash
uname -a
python3 --version
git --version
```

Para abrir um terminal: menu **Terminal → New Terminal**.

## Personalização

A configuração do ambiente fica em `.devcontainer/devcontainer.json`. Ao alterar esse arquivo, recrie o Codespace para aplicar as mudanças.

## Observação sobre uso

O Codespaces é um ambiente de desenvolvimento hospedado pelo GitHub e está sujeito aos limites, cotas e cobrança da conta. Pare ou exclua o Codespace quando não estiver usando.
