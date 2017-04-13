# ThirdGenerationAssemblyHOWTO

HOWTO for third generation assembly

1. 二代测序Kmer算法估算基因组，这个在网上一搜索就有介绍

schatz的 GenomeScope 这篇文章有详细介绍：
【GenomeScope: Fast reference-free genome profiling from short reads】
biorxiv.org/content/early/2016/09/19/075978

JellyFish 这个软件也有详细介绍 ：
genome.umd.edu/jellyfish.html


2. 【二代测序的组装】
schatz lab 有个专门介绍二代组装流程的课程，虽然现在不怎么用了
schatzlab.cshl.edu/teaching/AssemblyClass/


3. 【三代测序的组装】和【三代mapping的连接】

这篇文章是第三代测序和第三代mapping的一个广泛介绍
【Third-generation sequencing and the future of genomics】
biorxiv.org/content/early/2016/04/13/048603

Pacbio数据和二代数据混合组装
MaSuRCA 3.2
http://masurca.blogspot.jp/

Pacbio数据自我组装（不用二代数据）
1.Canu
http://canu.readthedocs.io/en/stable/index.html
https://github.com/marbl/canu
2.Falcon
https://github.com/PacificBiosciences/FALCON
https://github.com/PacificBiosciences/FALCON/wiki/Manual
3.wgs assembler (PacbiotoCA)
http://wgs-assembler.sourceforge.net/wiki/index.php?title=Main_Page


10x genomics 数据比对组装
比对
https://support.10xgenomics.com/genome-exome/software/overview/welcome
组装
https://support.10xgenomics.com/de-novo-assembly/software/overview/welcome

Bionano 数据比对组装
http://bionanogenomics.com/support/software-downloads/

HiC 数据组装
主要是三篇文章：
De novo assembly of the Aedes aegypti genome using Hi-C yields chromosomelength scaffolds
Juicer Provides a One-Click System for Analyzing Loop-Resolution Hi-C Experiments
Juicebox Provides a Visualization System for Hi-C Contact Maps with Unlimited Zoom
https://github.com/theaidenlab

