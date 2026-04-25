MBA em Desenvolvimento FullStack pela IGTI e Analista de desenvolvimento de sistemas pela UNIP.

✨ Dicas especiais aqui no Git. 

(https://dotnet.microsoft.com/pt-br/download/dotnet/thank-you/sdk-2.1.818-linux-arm64-binaries)

    Crie o diretório de destino:
    bash

    mkdir -p $HOME/dotnet

    Use o código com cuidado.
    Baixe o arquivo usando wget ou curl:
    bash

    wget https://builds.dotnet.microsoft.com/dotnet/Sdk/2.1.818/dotnet-sdk-2.1.818-linux-arm64.tar.gz

    Use o código com cuidado.
    Extraia o conteúdo para a pasta criada:
    bash

    tar -zxf dotnet-sdk-2.1.818-linux-arm64.tar.gz -C $HOME/dotnet

    Use o código com cuidado.
    Configure as variáveis de ambiente:
    Adicione as linhas abaixo ao seu arquivo de perfil (como ~/.bashrc ou ~/.zshrc) para que o comando dotnet fique disponível globalmente:
    bash

    export DOTNET_ROOT=$HOME/dotnet
    export PATH=$PATH:$HOME/dotnet

    Use o código com cuidado.
    Depois, atualize o terminal com source ~/.bashrc. 
