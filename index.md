---
title: Common Sense Beyond English
subtitle: Evaluating and Improving Multilingual Language Models for Commonsense Reasoning
layout: page
show_sidebar: false
hide_footer: true
---

{: .fs-8 .fw-800 .text-green-300 style="font-family: 'Agency FB Bold', arial;"}
✍️ [***Bill Yuchen Lin***](https://yuchenlin.xyz/){: target="blank"}, [***Seyeon Lee***](https://seyeon-lee.github.io/){: target="blank"}, [***Xiaoyang Qiao***](https://www.linkedin.com/in/xiaoyang-qiao/){: target="blank"}, [***Xiang Ren***](http://www-bcf.usc.edu/~xiangren/){: target="blank"} \
🏢 ***in Proc. of ACL 2021***{: .text-red-300}
<br>

<span class="fs-2">
[Paper](XCSR_paper.pdf){: target="_blank" .btn .btn-green .mr-1 .fs-3}
[Video](https://vimeo.com/manage/videos/582210443){: target="_blank" .btn .btn-green .mr-1 .fs-3}
[Slides](csbe_final_slides.pdf){: target="_blank" .btn .btn-green .mr-1 .fs-3}
[Github](https://github.com/INK-USC/XCSR/){: target="_blank" .btn .btn-purple .mr-1 .fs-3 }
[MickeyCorpus](https://forms.gle/fCxN1YAyqKpQ4cXNA){: target="_blank" .btn .btn-blue .mr-1 .fs-3 }
[X-CSR Datasets](https://forms.gle/gVCNgVXr1tyYkDya9){: target="_blank" .btn .btn-blue .mr-1 .fs-3 }
<!-- [Video](https://mega.nz/file/5SpQjJKS#J82pfZVDzy3r4aWdNF4R6O8EP5gsepbY20vYihANfgE){: target="_blank" .btn .btn-blue .mr-1 .fs-3 }
[Slides](opencsr_naacl_slides.pptx){: target="_blank" .btn .btn-red .mr-1 .fs-3 } -->
</span> 

---



<!-- This is the project site for the paper, [_Differentiable Cross-Lingual Commonsense Reasoning_](https://www.aclweb.org/anthology/2021.naacl-main.366/){: target="_blank"}, by [_Bill Yuchen Lin_](https://yuchenlin.xyz/){: target="_blank"}, [_Haitian Sun_](https://scholar.google.com/citations?user=opSHsTQAAAAJ&hl=en){: target="_blank"}, [_Bhuwan Dhingra_](http://www.cs.cmu.edu/~bdhingra/){: target="_blank"}, [_Manzil Zaheer_](https://scholar.google.com/citations?user=A33FhJMAAAAJ&hl=en){: target="_blank"}, [_Xiang Ren_](http://ink-ron.usc.edu/xiangren/){: target="_blank"}, and [_William W. Cohen_](https://wwcohen.github.io/){: target="_blank"}, in Proc. of [*NAACL 2021*](https://2021.naacl.org/){: target="_blank"}. 
This is a joint work by Google Research and USC. -->

 
<!-- ##  -->

![Intro](images/authors.png){: style="text-align:left; display:block; margin-left: auto; margin-right: auto;" width="75%"}

***Abstract.***{: .text-red-100} Commonsense reasoning research has so far been limited to English.
We aim to evaluate and improve popular multilingual language models (ML-LMs) to help advance commonsense reasoning (CSR) beyond English.
We collect the ***[Mickey Corpus](mickey#mickeycorpus)***, consisting of 561k sentences in 11 different languages, which
can be used for analyzing and improving ML-LMs.
We propose ***[Mickey Probe](mickey)***, a language-agnostic  probing task for fairly evaluating the common sense of popular ML-LMs across different languages.
In addition, we also create two new datasets, **[X-CSQA](xcsr_datasets#x-csqa)** and **[X-CODAH](xcsr_datasets#x-codah)**, by translating their English versions to **15** other languages, so that we can evaluate popular ML-LMs for cross-lingual commonsense reasoning.
To improve the performance beyond English, 
we propose a simple yet effective method --- ***multilingual contrastive pre-training*** (MCP).
It significantly enhances sentence representations, yielding a large performance gain on both benchmarks.


<!-- ## Website  -->
Herein, we provide our resources and method for studying cross-lingual commonsense reasoning.

- A multi-lingual corpus for ***[MickeyProbe](mickey)*** task towards analyzing and pre-training ML-LMs.
- Two ***[X-CSR datasets](xcsr_datasets)*** (i.e., X-CSQA and X-CODAH) for evaluation.
- The multilingual contrastive pre-training (MCP) method for improving ML-LMs' performance (on Github).

We also build **[X-CSR leaderboard](leaderboard)** so that people can compare their cross-lingual/multilingual models with each other in a unified evaluation protocol like [X-GLUE](https://microsoft.github.io/XGLUE/){: target="_blank"} and [XTREME](https://sites.research.google/xtreme){: target="_blank"}.




## Citation

```bibtex
@inproceedings{lin-etal-2021-xcsr,
    title = "Common Sense Beyond English: Evaluating and Improving Multilingual Language Models for Commonsense Reasoning",
    author = "Lin, Bill Yuchen and Lee, Seyeon and Qiao, Xiaoyang and Ren, Xiang",
    booktitle = "Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics (ACL-IJCNLP 2021)",
    year = "2021",
    note={to appear}
}
``` 
{: .fs-3}
<!-- 
[The site is under development. Please email [***yuchen.lin@usc.edu***] if you have any questions.](){: .btn .btn-red .fs-4 target="_blank"} -->

