# Introdução
sysinfo é um shell Script gerador de informações sobre o computador utilizado.
Com ele você pode verificar informações como:
- Sistema Operacional Utilizado
- Uptime (tempo ligado)
- Usuários logados
- Espaço do sistema de arquivos e partições montadas
- Espaço da /home por usuário
- Utilização de RAM e Swap
- Processos que mais consomem RAM
- Processador
- Dispositivos PCI
- Dispositivos USB conectados

# Utilização
/caminho/para/sysinfo

## Parâmetros
`-f [arq], --file [arq]`

Utiliza [arq] como nome do arquivo de saída.
Caso seja omitido, o nome padrão é info_sistema


`-i, --interativo`
  
Ativa modo interativo, para perguntar ao usuário, caso o arquivo especificado já exista, se ele deseja ou não sobrescrevê-lo.


`-p N, --processos N`
  
Exibe os primeiros N processos que mais consomem RAM.
Se omitido, os 5 primeiros serão mostrados.


`-w, --web`
  
Salva um arquivo no formato html ao invés de texto.


# INFORMAÇÃO EXTRA
Caso rode o script como superusuário, lgumas informações extra são dadas, como espaço do /home de cada usuário e detalhes de partições.
