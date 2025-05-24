<div align="center">
<!-- 
<h1>
  <img src="static/images/logo.png" alt="DanceTogether logo" style="height: 1em; vertical-align: -0.15em; margin-right: 0.3em;">
  <a href="https://dancetog.github.io/">DanceTogether! Identity-Preserving Multi-Person Interactive Video Generation</a>
</h1> -->


<h1>
  <!-- <img src="static/images/logo.png" alt="DanceTogether logo" style="height: 1em; vertical-align: -0.15em; margin-right: 0.3em;"> -->
  <img src="static/images/dance-gradient0.svg" href="https://dancetog.github.io/"
       alt="DanceTogether! Identity-Preserving Multi-Person Interactive Video Generation">
</h1>

<!-- 
<p align="center">
  <img src="static/images/dance-gradient0.svg"
       alt="DanceTogether! Identity-Preserving Multi-Person Interactive Video Generation">
</p> -->



**[Junhao Chen](https://scholar.google.com/citations?hl=en&user=uVMnzPMAAAAJ)<sup>1</sup>**, **Mingjin Chen<sup>2</sup>**, **[Jianjin Xu](https://scholar.google.com/citations?hl=en&user=mTV0usAAAAAJ)<sup>3</sup>**, **[Xiang Li](https://scholar.google.com/citations?user=_wyYvQsAAAAJ&hl=en&oi=sra)<sup>4</sup>**, **[Junting Dong](https://scholar.google.com/citations?user=dEzL5pAAAAAJ&hl=en)<sup>5†</sup>**

**[Mingze Sun](https://scholar.google.com/citations?user=TTW2mVoAAAAJ&hl=en)<sup>1</sup>**, **[Puhua Jiang](https://scholar.google.com/citations?user=E-k3WcgAAAAJ&hl=en)<sup>1</sup>**, **[Hongxiang Li](https://scholar.google.com/citations?user=U4AwycUAAAAJ&hl=en&oi=ao)<sup>4</sup>**, **[Yuhang Yang](https://scholar.google.com/citations?hl=en&user=x3aClGEAAAAJ)<sup>6</sup>**

**[Hao Zhao](https://scholar.google.com/citations?user=ygQznUQAAAAJ&hl=en)<sup>1</sup>**, **[Xiaoxiao Long](https://scholar.google.com/citations?hl=en&user=W3G5kZEAAAAJ)<sup>7</sup>**, **[Ruqi Huang](https://scholar.google.com/citations?user=cgRY63gAAAAJ&hl=en)<sup>1†</sup>**

<sup>1</sup>Tsinghua University  <sup>2</sup>Beijing Normal–Hong Kong Baptist University  <sup>3</sup>Carnegie Mellon University  
<sup>4</sup>Peking University  <sup>5</sup>Shanghai AI Laboratory  <sup>6</sup>University of Science & Technology of China  <sup>7</sup>Nanjing University  


<!-- [![hf_space](https://img.shields.io/badge/🤗-LeaderBoard-blue.svg)](xxx)
[![hf_space](https://img.shields.io/badge/🤗-Paper%20In%20HF-red.svg)](xxx)
[![hf_space](https://img.shields.io/badge/🤗-Online_Demo-yellow.svg)](xxx)
[![arXiv](https://img.shields.io/badge/Arxiv-2406.18522-b31b1b.svg?logo=arXiv)](xxx)  -->
[![Home Page](https://img.shields.io/badge/Project_Page-DanceTog-blue.svg?logo=data:image/png;base64,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)](https://dancetog.github.io/) 
<!-- [![Dataset](https://img.shields.io/badge/Dataset-PairFS_4K-green)](xxx)
[![Dataset](https://img.shields.io/badge/Dataset-HumanRob_300-green)](xxx)
[![Dataset](https://img.shields.io/badge/Dataset-DanceTogEval_100-green)](xxx)
[![Dataset Download](https://img.shields.io/badge/Benchmark-TogetherVideoBench-red)](xxx) -->
[![github](https://img.shields.io/github/stars/yisuanwang/DanceTog.svg?style=social)](https://github.com/yisuanwang/DanceTog/)
![visitors](https://visitor-badge.laobi.icu/badge?page_id=yisuanwang.DanceTog&left_color=green&right_color=red)  




![teaser](static/images/case01.gif)




</div>



```bibtex
xxx
```


# ⭐️ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yisuanwang/DanceTog&type=Date)](https://star-history.com/#yisuanwang/DanceTog&Date)
