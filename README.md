# hse_hw3_chromhmm
# [Collab](https://colab.research.google.com/drive/1hSkS2KFa6viYEBIRvdvyynoz6Y7EsDir?usp=sharing) 
## Список 10-ти гистоновых меток (и соотв имен файлов) , для которых был сделан анализ
|**Клеточная линия**|**Файл**|**Метка**|**Контроль**|
|-|-|-|-|
|HeLa-S3|wgEncodeBroadHistoneHelas3H2azAlnRep1.bam|H2afz|Helas3Control.bam|
|HeLa-S3|wgEncodeBroadHistoneHelas3H3k27acStdAlnRep1.bam|H3k27ac|Helas3Control.bam|
|HeLa-S3|wgEncodeBroadHistoneHelas3H3k27me3StdAlnRep1.bam|H3k27me3|Helas3Control.bam|
|HeLa-S3|wgEncodeBroadHistoneHelas3H3k36me3StdAlnRep1.bam|H3k36me3|Helas3Control.bam|
|HeLa-S3|wgEncodeBroadHistoneHelas3H3k04me1StdAlnRep1.bam|H3k04me1|Helas3Control.bam|
|HeLa-S3|wgEncodeBroadHistoneHelas3H3k4me2StdAlnRep1.bam|H3k4me2|Helas3Control.bam|
|HeLa-S3|wgEncodeBroadHistoneHelas3H3k4me3StdAlnRep1.bam|H3k4me3|Helas3Control.bam|
|HeLa-S3|wgEncodeBroadHistoneHelas3H3k79me2StdAlnRep1.bam|H3k79me2|Helas3Control.bam|
|HeLa-S3|wgEncodeBroadHistoneHelas3H3k9acStdAlnRep1.bam|H3k9ac|Helas3Control.bam|
|HeLa-S3|wgEncodeBroadHistoneHelas3H3k09me3AlnRep1.bam|H3k09me3|Helas3Control.bam|
## Aнализ с помощью ChromHMM
Генерируем с помощью скрипта текстовый файл cellmarkfiletable.txt, файл приложен в репозитории.
#### Картинки сгенерированные ChromHMM
![emissions_15](https://user-images.githubusercontent.com/43317906/229843377-db448eed-1a6f-4a73-96f7-d684c477e7eb.png)
![HeLa-S3_15_overlap](https://user-images.githubusercontent.com/43317906/229843395-f801c359-f3da-4e6c-b6d0-f0bdf5b88122.png)
![HeLa-S3_15_RefSeqTES_neighborhood](https://user-images.githubusercontent.com/43317906/229843411-c78bcbf2-0558-4fff-a254-75767e0786d0.png)
![HeLa-S3_15_RefSeqTSS_neighborhood](https://user-images.githubusercontent.com/43317906/229843428-5bb28f29-a968-426b-a5fb-c6b97632c990.png)
![transitions_15](https://user-images.githubusercontent.com/43317906/229843448-106ed017-60b3-4255-9cee-7a63fefb0357.png)
## UCSC GenomeBrowser
### HeLa-S3_15_dense_titled.bed уже с бонусной частью
![image](https://user-images.githubusercontent.com/43317906/229842633-8fb805fe-4faf-48e4-8ab7-26cb3a73f33d.png)
![image](https://user-images.githubusercontent.com/43317906/229846974-64f3a0cd-24a5-42e6-b756-423ca0b6f520.png)
### Скрипт изменения наименований в [коллабе](https://colab.research.google.com/drive/1hSkS2KFa6viYEBIRvdvyynoz6Y7EsDir?usp=sharing)
