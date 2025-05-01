Para quem se interessa em estudar por flashcards, criei um código (obrigada, ChatGPT) para transformar os flashcards no formato de PDF do Estratégia em flashcards para o formato do Anki. Não tenho todo o deck porque estou fazendo a medida em que estudo o conteúdo.

O uso do código é simples, ele é pra ser utilizado no Google Colaboratory. O passo a passo seria:

Criar uma pasta no drve onde os PDFs vão ser upados e uma pasta de saída, como descrito na parte do código :

Defina a pasta que contém os PDFs
Você pode escolher a pasta clicando na opção "Arquivos" (penúltimo botão da coluna à esquerda), depois "Montar Drve" (terceiro botão) > "Drve" > "My Drve" > 3 pontinhos na pasta selecionada > "Copiar Caminho" e então colar em:

pasta_pdfs = 'COLE AQUI'  # Substitua pelo caminho correto da sua pasta de PDFs
base_output_folder = 'COLE AQUI'  # Pasta base para salvar as imagens e CSVs
2. Iniciar os códigos na ordem e aguardar a conclusão de todos os anteriores (incluindo sua conexão à conta do Google) para então iniciar o último código. Isso precisa ser feito apenas na primeira vez de uso, nas vezes seguintes é necessário iniciar apenas o 1º e o 3º código, depois pode pular para o último. (Inclusive acredito que alguns deles sejam desnecessários, mas não entendo de programação, então está aberto a edições).

Após a conclusão, serão criadas pastas com os respectivos flashcards, contendo uma pasta com imagens "Anki_Media" e uma planilha de flashcards.

3. Coloque todas as imagens do "Anki_Media" na pasta "collection.media" do arquivo Anki. Você pode encontrar essa pasta em "Ferramentas" > "Verificar Mídia" > "Ver arquivos" (eu coloquei a pasta no acesso rápido para facilitar o processo).

4. Crie um novo baralho com o nome do assunto desejado e clique em "Arquivo > Importar" e selecione a planilha de flashcards. Selecione a opção "Separado de Campo = Vírgula" e clique em "Importar" (essa configuração só precisa ser feita uma única vez).

Fim, agora você tem os flashcards no Anki.

ALGUNS DETALHES:

- Meu computador não tolera rodar o código em PDFs grandes (em geral > 80 páginas), quando tento ocorre erro por sobrecarga de RAM. Você pode testar no seu computador, mas quando tem arquivos desse tamanho eu uso o ILovePDF para dividir e gero 2 arquivos (lembre de checar se inicia com uma pergunta e finaliza com uma resposta)

- Vantagem: Você pode fazer quantos flashcards quiser de uma só vez, o processo é muito mais rápido do que seria criando à mão. Além de que você pode colocar para fazer dezenas de flashcards e deixar o código rodando. (Eu por ex. fiz o deck inteiro de obstetrícia de uma vez)

- Desvantagem: O carregamento de imagens no momento de responder os flashcards é lento no computador (acho o da web mais rápido do que o app), mas sempre utilizo esses flashcards no celular e funcionam rápido sem problema.
