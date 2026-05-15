# Module Magisk Toknux

Um módulo Magisk focado em otimização, segurança ou utilitários através do binário `test-su` no ambiente Android.

## 📱 Requisitos

- Dispositivo Android com root via **Magisk** (v20.4 ou superior recomendado).
- Recuperação customizada (TWRP/OrangeFox) ou acesso ao aplicativo Magisk para instalação.

## 📦 Estrutura do Módulo

O repositório está organizado da seguinte forma:

- `META-INF/com/google/android/`: Contém os scripts de instalação do instalador zip (`update-binary` e `updater-script`).
- `module.prop`: Arquivo de metadados do módulo (nome, versão, autor e descrição).
- `system/bin/test-su`: O binário executável principal que roda no sistema Android.

## 🛠️ Como Contribuir ou Modificar

Se você estiver editando este módulo no Windows, é **obrigatório** desativar a conversão automática de quebras de linha (`CRLF`), caso contrário, o Android não conseguirá executar os scripts (`LF`).

Antes de commitar suas alterações, execute no terminal:
```bash
git config core.autocrlf false
```

### Comandos úteis de desenvolvimento:
```bash
# Adicionar alterações
git add .

# Criar um ponto de salvamento
git commit -m "Minhas modificações"

# Enviar para o GitHub
git push
```

## ⚡ Instalação

1. Baixe o código do repositório ou o arquivo `.zip` da aba de Releases.
2. Se baixou o código fonte, compacte o conteúdo da raiz em um arquivo `.zip` (atenção: compacte os arquivos diretamente, não a pasta que os contém).
3. Abra o aplicativo **Magisk**.
4. Vá até a aba **Módulos** e clique em **Instalar a partir do armazenamento**.
5. Selecione o arquivo `.zip` gerado e reinicie o dispositivo após a instalação.

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes (opcional).
