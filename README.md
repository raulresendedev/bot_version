# Visão Geral

O repositório bot_version é dedicado a hospedar e gerenciar as atualizações para o botzapp, um bot de WhatsApp utilizado para envio automatizado de mensagens personalizadas, como parte de uma estratégia de mala direta. Este repositório é uma parte crucial do sistema de atualizações do botzapp, garantindo que os usuários sempre tenham a versão mais recente e eficiente do software.

## O repositório contém os seguintes arquivos principais:

**botzapp.exe:** O executável principal do bot de WhatsApp.

**updater.exe:** Um utilitário que gerencia as atualizações do botzapp.

**version.txt:** Um arquivo de texto que registra a versão atual do botzapp.

# Funcionamento
**Verificação de Versão:** Ao ser executado, o botzapp inicialmente verifica a versão mais recente disponível. Ele faz isso baixando o conteúdo do arquivo version.txt do último commit no repositório. Este arquivo contém o número da versão mais atual.

**Decisão de Atualização:** Se a versão do botzapp em execução no usuário não corresponder à versão mais recente, conforme indicado no version.txt, o processo de atualização é iniciado.

**Download do Atualizador:** Caso o arquivo updater.exe não esteja presente no diretório local do botzapp, o botzapp baixa esse utilitário do repositório.

**Atualização:** O updater.exe é então executado. Sua função é baixar a versão mais recente do botzapp do repositório e substituir a versão antiga na máquina do usuário.

**Execução da Nova Versão:** Uma vez atualizado, o botzapp é reiniciado automaticamente, agora rodando na versão mais recente.

# Usos do botzapp

O botzapp é um bot automatizado para o WhatsApp que facilita o envio de mensagens personalizadas para diversos usuários. Ele permite a inclusão de parâmetros personalizados em mensagens, tornando possível o envio de uma mensagem base para diferentes usuários com suas informações específicas, uma estratégia eficaz para mala direta e comunicação personalizada.

# Nota Importante sobre Conformidade e Uso Responsável
O botzapp utiliza os parâmetros da URL do WhatsApp e Selenium para facilitar o envio de mensagens. Este processo é feito em estrita aderência às políticas e regulamentos estabelecidos pela Meta Platforms Inc., controladora do WhatsApp. O bot foi desenvolvido para estar em conformidade com as normas relativas à automação e uso de bots na plataforma.

É fundamental salientar que o botzapp não é destinado para atividades de spam ou envio de mensagens em massa não solicitadas. Seu objetivo principal é permitir uma comunicação personalizada e automatizada, respeitando os padrões de uso aceitáveis e as expectativas de privacidade dos usuários.

Incentivamos todos os usuários a operar o botzapp de forma responsável e ética, alinhando-se com as diretrizes do WhatsApp e com as leis e regulamentos locais aplicáveis à comunicação digital e ao marketing direto.
