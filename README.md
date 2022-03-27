# hse_hw3_chromhmm
Ссылка на гугл-колаб: https://colab.research.google.com/drive/1tmlIYCE-CkFooEKoX2zTpDs-ncwJzCoL?usp=sharing  
# Список гистоновых меток
| Гистоновая метка | Файл |  
| --- | --- |  
| H3K4me2 | wgEncodeBroadHistoneHelas3H3k4me2StdAlnRep1.bam |  
| H3K27ac | wgEncodeBroadHistoneHelas3H3k27acStdAlnRep1.bam |  
| H2AFZ | wgEncodeBroadHistoneHelas3H2azAlnRep1.bam |  
| H4K20me1 | wgEncodeBroadHistoneHelas3H4k20me1StdAlnRep1.bam |  
| H3K4me3 | wgEncodeBroadHistoneHelas3H3k4me3StdAlnRep1.bam |  
| H3K9ac | wgEncodeBroadHistoneHelas3H3k9acStdAlnRep1.bam |  
| H3K9me3 | wgEncodeBroadHistoneHelas3H3k09me3AlnRep1.bam |  
| H3K36me3 | wgEncodeBroadHistoneHelas3H3k36me3StdAlnRep1.bam |  
| H3K4me1 | wgEncodeBroadHistoneHelas3H3k04me1StdAlnRep1.bam |  
| H3K79me2 | wgEncodeBroadHistoneHelas3H3k79me2StdAlnRep1.bam |  
# Картинки из выдачи ChromHmm  
![emissions_10](https://user-images.githubusercontent.com/91226664/160286307-a510aa86-1db8-4a52-a4e7-de4286ef2c8b.png)  
![HeLa-S3_10_overlap](https://user-images.githubusercontent.com/91226664/160286320-bf76be39-ac24-4c7c-b72f-6a2aab91ddf5.png)  
![HeLa-S3_10_RefSeqTES_neighborhood](https://user-images.githubusercontent.com/91226664/160286322-5c5b5a85-9479-49cd-9381-0d0495cde1d3.png)  
![HeLa-S3_10_RefSeqTSS_neighborhood](https://user-images.githubusercontent.com/91226664/160286323-c4472e0c-4bfe-4236-bbc0-701d0b231f23.png)  
![transitions_10](https://user-images.githubusercontent.com/91226664/160286329-d29ccd46-a96a-4ef1-84d8-d277a0154905.png)  
Файл cellmarkfiletable.txt находится в основной папке репозитория.  
Выдача программы ChromHMM находится в папке ChromHmm (файл HeLa-S3_10_expanded.bed модифицирован, в него добавлены названия эпигенетических типов).  
# Эпигенетические типы
| Номер | Возможная функция | Обоснование | Характерные гистоновые метки |  
| --- | --- | --- | --- | 
| 1 | промотер | Часто встречается с CpG островками (что характерно для промотеров), а также они присутствуют на сайте начала транскрипции (TSS). | H3K4me2, H3K4me3, H3K9ac, H3K27ac |  
| 2 | промотер | Часто встречается с CpG островками (что характерно для промотеров), а также они присутствуют на сайте начала транскрипции (TSS). | H3K4me2 |  
| 3 | энхансер | Ассоциируются с гистоновой меткой H3K4me1, которая является признаком энхансеров. | H3K4me1, H3K4me2, H3K27ac |  
| 4 | энхансер | Ассоциируются с гистоновой меткой H3K4me1, которая является признаком энхансеров. | H3K4me1 |  
| 5 | активный ген | Тесно ассоциирован с генами (RefSeqGene), а также имеет гистоновую метку H3K79me2, которая встречается в активных генах. | H3K79me2, H3K4me2 |  
| 6 | активный ген | Тесно ассоциирован с генами (RefSeqGene), а также имеет гистоновую метку H3K79me2, которая встречается в активных генах. | H3K79me2 |  
| 7 | тело гена | Имеет тесную связь с генами, также связана с гистоновой модификацией H3K36me3, ассоциируемой с телом гена. | H3K36me3 |  
| 8 | репрессированный гетерохроматин | Тесно связан с ядерной ламиной, скорее всего представляют собой репрессированный гетерохроматин. Также имеет наиболее высокий процент в геноме, большая часть генома не является активной, что также подтверждает гипотезу. | H4K20me1 |  
| 9 | неактивная ДНК | Тесно связана с ядерной ламиной. | H4K20me1 |  
| 10 | неактивная ДНК | Тесно связана с ядерной ламиной. | H3K9me3 |  
