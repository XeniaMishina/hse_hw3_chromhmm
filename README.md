# hse_hw3_chromhmm

## Ссылки на:
- [Google Colab](https://colab.research.google.com/drive/1VchHZvC4e_xKI_uDGyqCLTHOeINZ8aHz?usp=sharing)
- [Этот же файл на github](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/src/Mishina_HW3.ipynb)

## Гистоновые метки и соответствующие файлы

Гистоновая метка | Файл
--- | ---
H3K27ac	| wgEncodeBroadHistoneA549H3k27acDex100nmAlnRep1.bam
H3K27me3	| wgEncodeBroadHistoneA549H3k27me3Dex100nmAlnRep1.bam
H3K36me3	| wgEncodeBroadHistoneA549H3k36me3Dex100nmAlnRep1.bam
H3K4me1	| wgEncodeBroadHistoneA549H3k04me1Dex100nmAlnRep1.bam
H3K4me2	| wgEncodeBroadHistoneA549H3k04me2Dex100nmAlnRep1.bam
H3K4me3	| wgEncodeBroadHistoneA549H3k04me3Dex100nmAlnRep1.bam 
H3K79me2	| wgEncodeBroadHistoneA549H3k79me2Dex100nmAlnRep1.bam
H3K9ac	| wgEncodeBroadHistoneA549H3k09acEtoh02AlnRep1.bam
H3K9me3	| wgEncodeBroadHistoneA549H3k09me3Etoh02AlnRep1.bam
H4K20me1	| wgEncodeBroadHistoneA549H4k20me1Etoh02AlnRep1.bam	

## cellmarkfiletable.txt

Тип клеток | Гистоновая метка| Файл гистоновой метки | Контрольный файл
--- | --- | --- | ---
A549	| H3K27ac	| H3K27ac.bam	| Control.bam
A549	| H3K27me3	| H3K27me3.bam	| Control.bam
A549	| H3K36me3	| H3K36me3.bam	| Control.bam
A549	| H3K04me1	| H3K04me1.bam	| Control.bam
A549	| H3K04me2	| H3K04me2.bam	| Control.bam
A549	| H3K04me3	| H3K04me3.bam	| Control.bam
A549	| H3K79me2	| H3K79me2.bam	| Control.bam
A549	| H3K09ac	| H3K09ac.bam	| Control.bam
A549	| H3K09me3	| H3K09me3.bam	| Control.bam
A549	| H4K20me1	| H4K20me1.bam	| Control.bam

## Графики ChromHMM

  <p>
    <img src="https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/data/emissions_15.png" alt="Фотография" width="320" height="500">
    <img src="https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/data/transitions_15.png" alt="Фотография" width="320" height="500">
    <img src="https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/data/A549_15_overlap.png" alt="Фотография" width="320" height="500">
  </p>
    <p>
    <img src="https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/data/A549_15_RefSeqTSS_neighborhood.png" alt="Фотография" width="470" height="370">
    <img src="https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/data/A549_15_RefSeqTES_neighborhood.png" alt="Фотография" width="470" height="370">
  </p>
  
  ## Эпигенетические типы
  
  Тип | Название | Описание | Картинка
 --- | --- | ---| ---
1 | - | <ul><li> наиболее выражен в H3K27me3 </li><li> чаще попадает на laminB1lads(участок репрессированного гетерохроматима) </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/1.png)
2 | - | <ul><li> не попадает на ген  </li><li> чаще попадает на laminB1lads(участок репрессированного гетерохроматима) </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/2.png)
3 | - | <ul><li> наиболее выражен в H3K9me3 </li><li> чаще попадает на laminB1lads(участок репрессированного гетерохроматима) </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/3.png)
4 | - | <ul><li> наиболее выражен в H3K9me3, H3K36me3, менее выражен в H3K79me2 </li><li> чаще попадает на RefSeqGene, RefSeqTES, реже на RefSeqExon </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/4.png)
5 | - | <ul><li> наиболее выражен в H3K36me3 </li><li> чаще попадает на RefSeqTES, RefSeqGene, реже на RefSeqExon </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/5.png)
6 | - | <ul><li> наиболее выражен в H3K79me2, менее выражен в H4K20me1, H3K36me3 </li><li> чаще попадает на RefSeqGene </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/6.png)
7 | - | <ul><li> наиболее выражен в H3K79me2, H3K4me1 </li><li> чаще попадает на RefSeqGene, реже на RefSeqTES </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/7.png)
8 | - | <ul><li> наиболее выражен в H3K4me1 </li><li> чаще попадает на RefSeqTES, RefSeqGene, реже на laminB1lads(участок репрессированного гетерохроматима) </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/8.png)
9 | - | <ul><li> наиболее выражен в H3K4me1, менее выражен в H3K4me2, H3K27ac, H3K9ac </li><li> чаще попадает на RefSeqTES, реже на RefSeqGene, RefSeqExon </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/9.png)
10 | - | <ul><li> наиболее выражен в H3K4me1, H3K4me2, H3K4me3, H3K27ac, H3K9ac </li><li> чаще попадает на RefSeqTES, RefSeqTSS2Kb, реже на RefSeqGene, RefSeqExon </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/10.png)
11 | - | <ul><li> наиболее выражен в H3K4me2, H3K4me3, H3K27ac, H3K9ac </li><li> чаще попадает на CpGIslands, RefSeqExon, RefSeqTSS и RefSeqTSS2Kb, реже на  RefSeqTES </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/11.png)
12 | - | <ul><li> наиболее выражен в H3K4me2, H3K4me3, H3K27ac, H3K9ac, H3K79me2 </li><li> чаще попадает на RefSeqTSS2Kb, реже на RefSeqTES, RefSeqExon, CpGIslands, и RefSeqGene </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/12.png)
13 | - | <ul><li> наиболее выражен в H3K4me1, H3K4me2, H3K4me3, H3K27ac, H3K9ac, H3K79me2 </li><li> чаще попадает на RefSeqTES, RefSeqGene </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/13.png)
14 | - | <ul><li> наиболее выражен в H3K4me1, H3K4me2 </li><li> чаще попадает на RefSeqTES, RefSeqGene и laminB1lads(участок репрессированного гетерохроматима) </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/14.png)
15 | - | <ul><li> наиболее выражен в H3K4me2, менее выражен в H3K4me3, H3K27me3 </li><li> чаще попадает на laminB1lads(участок репрессированного гетерохроматима),  RefSeqTSS2Kb, CpGIslands, реже на RefSeqTES, RefSeqTSS, RefSeqExon </li> | ![Image](https://github.com/XeniaMishina/hse_hw3_chromhmm/blob/main/screens/15.png)
