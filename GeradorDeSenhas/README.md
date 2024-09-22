# Gerador de Senhas

Uma extensão do Google Chrome que permite gerar senhas aleatórias de forma rápida e fácil.

## Características

- Gera senhas aleatórias com 12 caracteres por padrão.
- Inclui letras maiúsculas, minúsculas, números e caracteres especiais.
- Interface simples e intuitiva.

## Como Usar

1. **Instalação**:
   - Clone ou baixe este repositório.
   - Abra o Chrome e vá para `chrome://extensions/`.
   - Ative o "Modo de desenvolvedor" no canto superior direito.
   - Clique em "Carregar sem compactação" e selecione a pasta onde os arquivos estão localizados.

2. **Geração de Senhas**:
   - Clique no ícone da extensão na barra de ferramentas do Chrome.
   - Pressione o botão "Gerar Senha".
   - A senha gerada será exibida no campo de entrada e pode ser copiada para uso.

## Estrutura do Projeto

password-generator/ │ ├── manifest.json # Configurações da extensão ├── popup.html # HTML da interface ├── popup.js # Lógica da interface ├── styles.css # Estilos da interface ├── passwordGenerator.js # Lógica de geração de senhas ├── passwordGenerator.test.js # Testes unitários └── integration.test.js # Testes de integração