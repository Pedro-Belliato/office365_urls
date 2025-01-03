URLs e Faixas de IP do Office 365 para pfSense
As URLs e faixas de IP do Office 365 foram extraídas do site oficial da Microsoft:

Fonte: Microsoft - URLs e Faixas de IP do Office 365
Essas informações são cruciais para garantir que o acesso aos serviços do Office 365 seja permitido através do firewall. As URLs e faixas de IP listadas são atualizadas regularmente pela Microsoft e são fundamentais para o funcionamento adequado dos serviços, como o Exchange Online, SharePoint Online, Teams e outros componentes do Office 365.

Como Utilizar no pfSense
As URLs e faixas de IP listadas podem ser configuradas como alias no pfSense. Isso facilita a manutenção e gestão do tráfego de rede para os serviços do Office 365, permitindo que as regras de firewall sejam aplicadas de forma centralizada e eficiente.

Passos para Configuração:

Acesse o pfSense e vá para o menu Firewall > Aliases.
Clique em Add para criar um novo alias.
No campo Name, insira um nome apropriado para o alias (ex.: Office365_URLs).
Selecione o tipo de alias como Host(s) ou Network(s), dependendo do tipo de informação que você está utilizando.
Cole as URLs ou faixas de IP extraídas da lista do Office 365.
Salve as configurações.


As URLs e faixas de IP do Office 365 podem ser alteradas ou atualizadas periodicamente pela Microsoft. É importante verificar regularmente se há atualizações na lista e mantê-la sincronizada com a configuração do seu firewall pfSense.
