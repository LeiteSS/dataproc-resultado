# Google Cloud

**Objetivo:** Sua missão será criar um ecossistema de Big Data usando o Google Cloud Platform (GCP). Para isso, o expert te ensinará a configurar o Google Cloud Dataproc, um Hadoop totalmente gerenciado, usando seus créditos gratuitos da GCP.

## Passos

1. Criar um bucket no Cloud Storage
2. Referenciar o bucket criado no arquivo ```main.py```.
3. Fazer o [upload dos arquivos](https://cloud.google.com/storage/docs/uploading-objects) ```main.py``` e ```livro.txt``` no bucket criado.
4. Utilizar o código em um cluster Dataproc, executando um Job do tipo PySpark.
5. O Job irá gerar uma pasta no bucket chamada ```output```. Dentro dessa pasta o arquivo ```part-00000``` irá conter a lista de palavras e quantas vezes ela é repetida em todo o livro.
2. Criar um arquivo chamado ```resultado.txt```. Dentro desse arquivo, colocar as 10 palavras que mais são usadas no livro, de acordo com o resultado do Job.
