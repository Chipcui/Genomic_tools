# 基因组学工具合集

整理了一些我所知道的和基因组学相关的工具，可能不全面，欢迎补充

## 一代组装

- [Celera Assembler](http://wgs-assembler.sourceforge.net/): 最具代表性的工具
          
## 二代组装

- [Minia](https://github.com/GATB/minia)
- [SPAdes](https://github.com/ablab/spades): 细菌基因组常用
- [ALLPaths-LG](http://software.broadinstitute.org/allpaths-lg/blog/?page_id=12)
- [SOAPdenovo2](https://github.com/aquaskyline/SOAPdenovo2): 华大出品
- [SGA](https://github.com/jts/sga)

### 泛基因组分析

- [HUPAN](http://cgm.sjtu.edu.cn/hupan/)

## 三代contig组装

- [falcon](https://github.com/PacificBiosciences/pb-assembly): PacBio专用组装工具        
- [Canu](https://canu.readthedocs.io/en/latest/): 老牌工具，资源消耗大
- [MECAT](https://github.com/xiaochuanle/MECAT): 高效的三代组装工具
- [MECAT2](https://github.com/xiaochuanle/MECAT2): PacBio专用组装工具
- [NECAT](https://github.com/xiaochuanle/NECAT): Nanopore专用组装工具
- [NextDenovo](https://github.com/Nextomics/NextDenovo): 可用于Nanopore的组装工具
- [FLYE](https://github.com/fenderglass/Flye)
- [SMARTdenovo](https://github.com/ruanjue/smartdenovo)       
- [WTDBG2](https://github.com/ruanjue/wtdbg2): 不对原始数据纠错,快速的组装工具
- [Shasta](https://github.com/chanzuckerberg/shasta): Nanopore组装工具
- [HASLR](https://github.com/vpc-ccg/haslr): 快速混合组装长reads（PacBio或Nanopore）和二代数据

## GFA相关

GFA是目前组装比较认可的格式

- [GFA格式声明](http://gfa-spec.github.io/GFA-spec/GFA1.html)        
- [Gfakluge](https://github.com/edawson/gfakluge): GFA操作工具         
- [Bandage](https://github.com/rrwick/Bandage): 全平台GUI可视化工具
- [GfaViz](https://github.com/ggonnella/gfaviz): 命令行的可视化        
- [AGB](https://github.com/almiheenko/AGB): Linux分析，网页展示
          

##  三代组装polish

- [Pilon](https://github.com/broadinstitute/pilon/wiki): 利用二代进行polish
- [Racon](https://github.com/isovic/racon): 利用三代进行polish
- [NextPolish](https://github.com/Nextomics/NextPolish): 利用二代进行polish
- [Medaka](https://github.com/nanoporetech/medaka): 利用三代对Nanopore进行polish

## 去除冗余序列

- [purge_haplotigs](https://bitbucket.org/mroachawri/purge_haplotigs)
- [HaploMerger2](https://github.com/mapleforest/HaploMerger2)
- [Redundans](https://github.com/lpryszcz/redundans)

##  辅助组装

使用遗传图谱，光学图谱，Hi-C和物种间共线性对contig进行scaffold的工具

### HiC

- [SALSA](https://github.com/marbl/SALSA): 高效率，能纠错使用GFA信息
- [HiCAssembler](https://github.com/maxplanck-ie/HiCAssembler): 借鉴了3D-DNA
- [3D-DNA](https://github.com/theaidenlab/3d-dna): 搭配JuicerBox效果极佳（但是速度有点慢） 
- [ALLHiC](https://github.com/tangerzhang/ALLHiC): 多倍体HiC组装             
- LACHESIS: 古老的工具，已不再维护
- [HiC-Pro](https://github.com/nservant/HiC-Pro)
- [HiCPlotter](https://github.com/kcakdemir/HiCPlotter)


### 光学图谱

- [Bionano Solve](https://bionanogenomics.com/support/software-downloads/): BioNano提供的一系列分析脚本工具
- [BIONANO ACCESS](https://bionanogenomics.com/support/software-downloads/): BioNano提供的网页工具
- [OMSV](http://yiplab.cse.cuhk.edu.hk/omsv/): 基于光学图谱鉴定SV
- [OMTools](https://github.com/TF-Chan-Lab/OMTools): 光学图谱数据处理，分析和可视化



### 遗传图谱

### 整合工具

- [ALLMAPS](https://github.com/tanghaibao/jcvi/): 可以整合多张图谱做一套比较好的染色体组装

## 组装质量评估

- [BUSCO](https://busco.ezlab.org/)
- [CEGMA](http://korflab.ucdavis.edu/datasets/cegma/)
- [LAI](https://github.com/oushujun/LTR_retriever)

## 重复序列注释

- [RepeatModeler](http://www.repeatmasker.org/RepeatModeler/)
- [RepeatMasker](http://www.repeatmasker.org/)
- [EDTA](https://github.com/oushujun/EDTA)
- [LTRpred](https://hajkd.github.io/LTRpred/)
          

## 基因注释

### 从头预测
- [AUGUSTUS](http://bioinf.uni-greifswald.de/augustus/)
- [SNAP](https://github.com/KorfLab/SNAP)
- [GeneMark](http://exon.gatech.edu/GeneMark/)

### 注释流程
- [Braker2](https://github.com/Gaius-Augustus/BRAKER)
- [MAKER-P](http://www.yandell-lab.org/software/maker-p.html): 针对植物基因组的注释流程
- [PASA](https://github.com/PASApipeline/PASApipeline)             

## WGD分析

- [wgd](https://github.com/arzwa/wgd)
- [GenoDup](https://github.com/MaoYafei/GenoDup-Pipeline)
- [WGDdetector](https://github.com/yongzhiyang2012/WGDdetector)

## 全基因组比对软件

- [LAST](http://last.cbrc.jp/)
- [LASTZ](https://github.com/lastz/lastz)
- [MUMMER](https://mummer4.github.io/index.html)
- [minimap2](https://github.com/lh3/minimap2)
- [NGMLR](https://github.com/philres/ngmlr)
- [BLASR](https://github.com/PacificBiosciences/blasr): PacBio数据比对工具

## 共线性可视化

- [dotPlotly](https://github.com/tpoorten/dotPlotly)
- [MCscan (Python version)](https://github.com/tanghaibao/jcvi/wiki/MCscan-(Python-version))         
- [Circos](http://circos.ca/)

## 群体结构

- [STRUTURE](https://web.stanford.edu/group/pritchardlab/structure.html)
- [Admixture](http://software.genetics.ucla.edu/admixture/)
- [lostruct](https://github.com/petrelharp/local_pca)

## 基因组结构变异
### 二代数据

- [iSVP](http://nagasakilab.csml.org/en/isvp)
- [intansv](https://venyao.github.io/intansv/): 对多个软件的结构变异鉴定结果进行整合和可视化
- [SpeedSeq](https://github.com/hall-lab/speedseq)
- [novoBreak](https://github.com/czc/nb_distribution)
- [HugeSeq](https://github.com/StanfordBioinformatics/HugeSeq)
- [Delly](https://github.com/dellytools/delly)
- [freebayes](https://github.com/ekg/freebayes)
- [Pindel](https://github.com/genome/pindel)
- [LUMPY](https://github.com/arq5x/lumpy-sv)
- [MetaSV](https://github.com/bioinform/metasv)
- [FusorSV](https://github.com/timothyjamesbecker/FusorSV)
- [Manta](https://github.com/Illumina/manta)
- [Parliament2](https://github.com/dnanexus/parliament2)
- [BreakDancer](http://gmt.genome.wustl.edu/packages/breakdancer/index.html)
- [BreakSeq2](https://github.com/bioinform/breakseq2)
- [CNVnator](https://github.com/abyzovlab/CNVnator)

### 三代数据
- [Sniffles](https://github.com/fritzsedlazeck/Sniffles)
- [SVIM](https://github.com/eldariont/svim)
- [NextSV2](https://github.com/Nextomics/nextsv)
- [PBHoney](https://sourceforge.net/projects/pb-jelly/)
- [SMRT-SV](https://github.com/EichlerLab/smrtsv2): 使用PacBio RS II or Sequel数据来鉴定SV
- [smartie-sv](https://github.com/zeeev/smartie-sv)

### 综合性工具
- [multibreak-sv](https://github.com/raphael-group/multibreak-sv): 支持检测二代和三代数据中的结构变异
