# 动手学CADD(TeachOpenCADD)


使用开源工具包和数据的计算机辅助药物设计(CADD)教学平台

![TOC](https://img.shields.io/badge/Project-TeachOpenCADD-pink)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1486226.svg)](https://doi.org/10.5281/zenodo.1486226)

<!-- markdown-link-check-disable-next-line -->
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/volkamerlab/TeachOpenCADD/master)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/volkamerlab/teachopencadd)
[![GH Actions CI ](https://github.com/volkamerlab/teachopencadd/workflows/CI/badge.svg)](https://github.com/volkamerlab/teachopencadd/actions?query=branch%3Amaster+workflow%3ACI)
[![GH Actions Docs](https://github.com/volkamerlab/teachopencadd/workflows/Docs/badge.svg)](https://projects.volkamerlab.org/teachopencadd/)
[![Anaconda-Server Badge](https://anaconda.org/conda-forge/teachopencadd/badges/downloads.svg)](https://anaconda.org/conda-forge/teachopencadd)

![GitHub closed pr](https://img.shields.io/github/issues-pr-closed-raw/volkamerlab/teachopencadd) ![GitHub open pr](https://img.shields.io/github/issues-pr-raw/volkamerlab/teachopencadd) ![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/volkamerlab/teachopencadd) ![GitHub open issues](https://img.shields.io/github/issues/volkamerlab/teachopencadd)

> 如果您在出版物中使用了 TeachOpenCADD，请[引用](https://projects.volkamerlab.org/teachopencadd/citation.html)我们！
> 如果您在课堂上使用了 TeachOpenCADD，请包含一个链接回到我们的代码库。
<!-- markdown-link-check-disable-next-line -->
>无论哪种情况，请[star](https://docs.github.com/en/get-started/exploring-projects-on-github/saving-repositories-with-stars)那些您认为对您的学习或教学活动有用的代码库（并告诉您的学生也给它们点赞😄）。



## 概览

<p align="center">
  <img src="docs/_static/images/TeachOpenCADD_topics.png" alt="TeachOpenCADD topics" width="800"/>
  <br>
  <font size="1">
  图改编自《TeachOpenCADD》出版物中的Figure 1
  <a href="https://jcheminf.biomedcentral.com/articles/10.1186/s13321-019-0351-x">
  (D. Sydow <i>et al.</i>, J. Cheminformatics, 2019)</a>.
  </font>
</p>

开源可编程工具包在化学信息学和结构生物信息学中是强大的工具，它们可以构建模块化、可复现和可重用的计算机辅助药物设计（CADD）流程。尽管这些工具的文档是可用的，但只有少数免费可访问的例子教授以CADD应用为重点的基本概念，特别是针对该领域的新用户。

动手学CADD是一个由学生为学生开发的教育平台，提供以计算机辅助药物设计（CADD）为核心主题的教学材料。由于我们涵盖了这些主题的理论和实践方面，平台面向具有生物学/化学背景以及计算背景的学生和研究人员。


每个主题都通过交互式的 Jupyter Notebook 进行讲解，使用开源包，如 Python包 `rdkit`, `pypdb`, `biopandas`, `nglview`以及 `mdanalysis`等(在 [这里](https://projects.volkamerlab.org/teachopencadd/external_dependencies.html)找到完整列表)。主题正在不断扩展，并对社区的贡献开放。除了教学目的外，动手学CADD材料可以作为用户项目导向修改和扩展的起点。


**版本更新**: 我们已经扩展了动手学CADD平台，新增了6个Notebook，介绍了深度学习及其在与CADD相关主题的应用。

## 让我们开始吧！

<!-- markdown-link-check-disable -->
[![GH Actions Docs](https://github.com/volkamerlab/teachopencadd/workflows/Docs/badge.svg)](https://projects.volkamerlab.org/teachopencadd/)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/volkamerlab/TeachOpenCADD/master)
<!-- markdown-link-check-enable -->

如果您迫不及待地想要阅读材料，请访问[这里](https://projects.volkamerlab.org/teachopencadd/talktorials.html)的只读版本。

If you'd like to execute the provided notebooks, we offer two possibilities:

<!-- markdown-link-check-disable-next-line -->
- Online thanks to [Binder](https://mybinder.org/). This takes around 10 minutes to get ready, but does not require any kind of setup on your end. Click here to get started: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/volkamerlab/TeachOpenCADD/master). Once it has loaded, you can navigate to `teachopencadd/talktorials/` to find the executable notebooks.
- Locally using our `conda` package. More details in this [section of the documentation](https://projects.volkamerlab.org/teachopencadd/installing.html).

## TeachOpenCADD KNIME workflows

<!-- markdown-link-check-disable-next-line -->
[![DOI](https://img.shields.io/badge/DOI-10.1021%2Facs.jcim.9b00662-blue.svg)](https://pubs.acs.org/doi/10.1021/acs.jcim.9b00662)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3626897.svg)](https://doi.org/10.5281/zenodo.3626897)
[![KNIME Hub](https://img.shields.io/badge/KNIME%20Hub-TeachOpenCADD--KNIME-yellow.svg)](https://hub.knime.com/volkamerlab/spaces/Public/latest/TeachOpenCADD/TeachOpenCADD)

If you prefer to work in the context of a graphical interface, talktorials T001-T008 are also available as [KNIME workflows](https://hub.knime.com/volkamerlab/space/TeachOpenCADD/TeachOpenCADD). Questions regarding this version should be addressed using the "Discussion section" available at [this post](https://forum.knime.com/t/teachopencadd-knime/17174). You need to create a KNIME account to use the forum.

## About TeachOpenCADD

- [Contact](https://projects.volkamerlab.org/teachopencadd/contact.html)
- [Acknowledgments](https://projects.volkamerlab.org/teachopencadd/acknowledgments.html)
- [Citation](https://projects.volkamerlab.org/teachopencadd/citation.html)
- [License](https://projects.volkamerlab.org/teachopencadd/license.html)
- [Funding](https://projects.volkamerlab.org/teachopencadd/funding.html)


## External resources

Please refer to our TeachOpenCADD website to find a list of external resources:
- [External packages and webservices](https://projects.volkamerlab.org/teachopencadd/external_dependencies.html) that are used in the TeachOpenCADD material
- [Further reading material](https://projects.volkamerlab.org/teachopencadd/external_tutorials_collections.html) on Python programming, cheminformatics, structural bioinformatics, and more.
