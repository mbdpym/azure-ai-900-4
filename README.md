# azure-ai-900-4
# Passo a passo de como realizar uma pesquisa de documentos utilizando Azure AI Services

1. Criar um *Azure AI Search* resource (utilizado para vasculhar informações de documentos e categorizá-las
2. Criar um container (meio de armazenamento de arquivos) e realizar o upload de documentos a serem analizados
3. Conectar o AI Search ao container e realizar a indexação dos arquivos, selecionando quais informações desejamos que sejam extraídas, como a localização, sentimento, etc.
4. No AI Search, utilizar a função "Search Explorer" para explorar o resultado obtido na etapa 4
5. Pode-se também analisar imagens e base de conhecimento que foram geradas no container utilizado no projeto
6. Para maior manipulação e melhor visualização dos dados, exportar arquivo JSON para uma ferramenta como o Python
