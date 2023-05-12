# tatoo-repository
Images for data-science training

## Como executar o código do trabalho:
- Instalar os pacotes explicitados no arquivo 'requirements.txt' no seu ambiente Python de escolha;
- Executar o notebook incluso no repositório, na sequência e seguindo os comentários existentes no mesmo;

## Acesso pelo Colab
Caso deseje acessar o notebook existente no colab, pode fazê-lo pelo link: https://colab.research.google.com/drive/1NGDFzN7UE4whN-L0i0EF0vv4SmcIKqQp?usp=sharing

Para executar o trabalho no colab corretamente, é necessário:
- Executar o primeiro bloco de código para que sejam instalados os pacotes que não existem no Colab;
- Importar um arquivo chamado 'dataset.rar' (Pode ser alterado no código) contendo os 3 diretórios (train, test, valid) para o ambiente do colab, e executar o bloco de código responsável por descompactar o mesmo;
- Alterar o caminho 'download_dir' e 'database_dir' de acordo com o caminho dos diretórios extraidos;
- Pular o código de importação dos modelos na primeira execução, visto que não foi possível adicioná-los devido ao limite de tamanho de arquivos do Github.

Pontos importantes:
- Os modelos não foram adicionados devido ao limite de tamanho, portanto é necessário treinar os modelos uma primeira vez.
- Caso tente carregar os modelos na primeira execução, receberá um erro;
- Todas as demais instruções se encontram em comentários do notebook Jupyter incluso no repositório.
