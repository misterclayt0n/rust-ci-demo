# Relatório de Configuração de CI com GitHub Actions

## Objetivo

Automatizar a compilação, testes e verificação de boas práticas de codificação em um projeto Rust utilizando GitHub Actions.

## Etapas Realizadas

1. Criação de repositório GitHub: `rust-ci-demo`.
2. Inicialização do projeto Rust com `cargo init`.
3. Implementação de função simples e teste correspondente em `src/lib.rs`.
4. Configuração do workflow de CI em `.github/workflows/ci.yml` para:
   - Compilar o projeto (`cargo build`).
   - Executar testes (`cargo test`).
   - Verificar boas práticas com Clippy (`cargo clippy`).
   - Verificar formatação do código (`cargo fmt`).

## Evidências

*Incluir aqui capturas de tela ou logs da execução bem-sucedida do workflow no GitHub Actions.*


