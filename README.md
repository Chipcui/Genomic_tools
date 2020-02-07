# 组学工具合集

整理了一些目前知道的与组学相关的工具，可能不全面，欢迎补充

# 基因组学

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
- [HiCPlotter](https://github.com/kcakdemir/HiCPlotter)：HiC数据可视化
- [HiPiler](http://hipiler.lekschas.de/): 对HiC数据进行可视化的交互式网页工具


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
- [MAKER-P](http://www.yandell-lab.org/software/maker-p.html): 专门针对植物基因组的注释流程
- [PASA](https://github.com/PASApipeline/PASApipeline)             

## WGD分析

- [wgd](https://github.com/arzwa/wgd)
- [GenoDup](https://github.com/MaoYafei/GenoDup-Pipeline)
- [WGDdetector](https://github.com/yongzhiyang2012/WGDdetector)

## 基因组进化

- [CHROnicle](http://www.lcqb.upmc.fr/CHROnicle/)

## 同源分析

- [OrthoFinder](http://www.stevekellylab.com/software/orthofinder): 可以推断直系同源组和直系同源基因
- [OrthoMCL](https://orthomcl.org/orthomcl/)
- [OrthoCluster](http://genome.sfu.ca/orthoclusterdb/index.html)
- [InParanoid](http://inparanoid.sbc.su.se/cgi-bin/index.cgi)

## 全基因组比对软件

- [LAST](http://last.cbrc.jp/)
- [LASTZ](https://github.com/lastz/lastz)
- [MUMMER](https://mummer4.github.io/index.html)
- [minimap2](https://github.com/lh3/minimap2)
- [NGMLR](https://github.com/philres/ngmlr)
- [BLASR](https://github.com/PacificBiosciences/blasr): PacBio数据比对工具

## 共线性分析

- [MCScanX](http://chibba.pgml.uga.edu/mcscan2/)
- [SynChro](http://www.lcqb.upmc.fr/CHROnicle/SynChro.html)

## 共线性可视化

- [dotPlotly](https://github.com/tpoorten/dotPlotly)
- [MCscan (Python version)](https://github.com/tanghaibao/jcvi/wiki/MCscan-(Python-version))         
- [Circos](http://circos.ca/)

## 群体结构

- [STRUTURE](https://web.stanford.edu/group/pritchardlab/structure.html)
- [Admixture](http://software.genetics.ucla.edu/admixture/)
- [lostruct](https://github.com/petrelharp/local_pca)

## 结构变异
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

### 基因组可视化

- [JBrowse](https://jbrowse.org/): 支持多种文件格式的基因组浏览器
- [IGV](https://software.broadinstitute.org/software/igv/): 支持多种文件格式的基因组浏览器
- [Epiviz](https://epiviz.github.io/): 可以对功能基因组数据进行交互式可视化
- [TASUKE+](https://tasuke.dna.affrc.go.jp/): 基于web的基因组浏览器

## 系统进化
### 多序列比对

- [Clustal W/X](http://www.clustal.org/clustal2/)
- [MUSCLE](https://www.drive5.com/muscle/)
- [T-Coffee](http://www.tcoffee.org/Projects/tcoffee/index.html)
- [MAFFT](https://mafft.cbrc.jp/alignment/software/)
- [PROBCONS](http://probcons.stanford.edu/)

### 多序列比对可视化

- [NCBI Multiple Sequence Alignment Viewer](https://www.ncbi.nlm.nih.gov/projects/msaviewer/)
- [BoxShade](https://embnet.vital-it.ch/software/BOX_form.html)
- [ESPript](http://espript.ibcp.fr/ESPript/cgi-bin/ESPript.cgi)
- [Tablet](https://ics.hutton.ac.uk/tablet/)

### 进化模型选择

- [ModelTest-NG](https://github.com/ddarriba/modeltest)
- [MrModeltest2](https://github.com/nylander/MrModeltest2)

### 进化树构建

- [MEGA](https://www.megasoftware.net/): 功能全面的进化树构建工具，包括序列编辑、进化树构建、祖先序列重构、进化模型选择、选择压检验等
- [Mesquite](http://www.mesquiteproject.org/): 提供ML和MP方法构建进化树
- [PHYLIP](http://evolution.genetics.washington.edu/phylip.html)：提供NJ，ML和MP方法构建进化树
- [PhyML](http://www.atgc-montpellier.fr/phyml/)：提供ML法构建进化树
- [PAUP](https://paup.phylosolutions.com/)：提供MP法构建进化树
- [PAML](http://abacus.gene.ucl.ac.uk/software/paml.html)：提供ML法构建进化树
- [MrBayes](https://nbisweden.github.io/MrBayes/index.html)：提供贝叶斯法构建进化树
- [IQ-TREE](http://www.iqtree.org/): 使用ML法快速构建进化树
- [BEAST](https://www.beast2.org/): 提供贝叶斯法构建进化树

### 进化树可视化

- [FigTree](http://tree.bio.ed.ac.uk/software/figtree/)
- [Dendroscope3](http://dendroscope.org/)
- [TreeGraph](http://treegraph.bioinfweb.info/)
- [DensiTree](https://www.cs.auckland.ac.nz/~remco/DensiTree/)
- [NJplot](http://doua.prabi.fr/software/njplot)
- [iTOL](https://itol.embl.de/)
- [Evolview](https://www.evolgenius.info//evolview/#login)
- [ggtree](https://guangchuangyu.github.io/software/ggtree/): 对进化树进行可视化和注释的R包

# 表观组学
## 可视化

- [WashU Epigenome Browser](https://epigenomegateway.wustl.edu/)

# 转录组学
## 标准分析流程

- [UBiT2](http://pklab.med.harvard.edu/jean/ubit2/index.html)

## 可视化

- [SparK](https://github.com/harbourlab/SparK): 新型能达到发表水平的NGS可视化工具
