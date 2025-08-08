## Olá, eu sou Fabio, aspirante a programador.

- Curso ADS na Universidade Cruzeiro do Sul e desenvolvo pesquisa voltada para a preservação arquivística digital em repositórios digitais confiáveis, durante meu curso Doutorado em Ciência da Informação.
- Pretendo utilizar o Github para aprender a programar e desenvolver códigos-fonte de aplicações relacionadas à preservação digital.📖📚📓
- Sinta-se à vonatde para tecer críticas e contribuir com minha pesquisa.

  
# Projeto: Criação de ferramenta simples para extração de metadados de arquivos em formato PDF, utilizando java.💻💾

## Objetivo:
Criar uma ferramenta para extração de metadados descritivos, estruturais e administrativos de Pacotes de Submissão de Informação (SIP), voltada para documentos em formato PDF.

## Tecnologias utilizadas:
- Biblioteca Apache PDFBox
- JSON

## Conhecimento adquirido:

### Manipulação de PDFs com Java:
- Aprendi a usar a classe PDDocument do PDFBox para carregar arquivos PDF e acessar metadados via PDDocumentInformation.
- Desafio: Lidar com PDFs criptografados (solução: implementar tratamento de exceções para InvalidPasswordException).

### Estruturação de Metadados em JSON:
- Utilizei a biblioteca Jackson para converter os metadados extraídos em um formato JSON padronizado.

### Validação de Integridade:
- Implementei checksums (SHA-256) para verificar se o arquivo PDF não foi alterado após a extração.

### Gestão de Dependências:
- Aprendi a usar o Maven para gerenciar as bibliotecas (PDFBox, Jackson) e garantir compatibilidade.

### Testes Unitários:
- Criei testes com JUnit para validar a extração de metadados em diferentes cenários (ex.: PDF sem metadados, PDF corrompido).

### Melhorias Futuras:
  - Adicionar suporte a metadados personalizados (XMP).
  - Integrar com bancos de dados para armazenamento automatizado.
 



