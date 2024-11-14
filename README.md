# Guia de Instalação do Ollama no Windows

## Requisitos do Sistema
- Windows 10/11 64-bit
- Mínimo de 8GB de RAM (16GB recomendado)
- Espaço em disco suficiente para os modelos

## Processo de Instalação

### 1. Download
- Acesse https://ollama.com/download/windows
- Baixe o arquivo instalador mais recente (formato .msi)

### 2. Instalação
1. Execute o arquivo .msi baixado
2. Siga o assistente de instalação
3. Aceite os termos e condições quando solicitado
4. Aguarde a conclusão da instalação

### 3. Iniciando o Ollama
- O Ollama será iniciado automaticamente como serviço do Windows
- Você verá o ícone do Ollama na bandeja do sistema (system tray)

### 4. Comandos Básicos
Abra o Prompt de Comando (CMD) ou PowerShell e use os seguintes comandos:

```powershell
# Executar um modelo
ollama run llama2

# Listar modelos disponíveis
ollama list

# Baixar um modelo específico
ollama pull llama2

# Remover um modelo
ollama rm llama2
```

## Dicas Importantes
- Certifique-se de ter RAM suficiente livre antes de executar modelos
- Verifique o espaço em disco disponível
- O serviço do Ollama pode ser gerenciado pelo ícone na bandeja do sistema
- Para modelos maiores, verifique os requisitos específicos de hardware

## Solução de Problemas
- Se o Ollama não iniciar, verifique se o serviço está rodando
- Em caso de erros de memória, feche aplicativos não utilizados
- Para problemas de instalação, tente executar o instalador como administrador

## Recursos Adicionais
Para mais informações e suporte:
- Documentação oficial: https://ollama.com/docs
- GitHub: https://github.com/ollama/ollama
