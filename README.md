# Normative Cooperation in Global Artificial Intelligence Governance

# 人工智能全球治理的规范合作空间

[![License: CC BY-NC 4.0](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## English

### Overview

This repository contains research data associated with the following unpublished manuscript:

**Scope for Normative Cooperation in Global Artificial Intelligence Governance: An Automated Text Analysis of Normative Documents**

**Authors:** Lu Yao and Zehao Wang (姚璐、王泽昊)

This study examines convergence and divergence in the core concerns, thematic structures and attitudes expressed in normative documents on artificial intelligence (AI) governance, identifying potential areas for normative cooperation in global AI governance. It uses automated text analysis, including word frequency and term frequency–inverse document frequency (TF-IDF) analysis, topic analysis, and sentiment analysis.

The repository makes the analytical materials publicly accessible to support research transparency, empirical verification, and reproducibility. The associated manuscript has not yet been formally published and does not have a DOI.

### Data coverage

**Data collection cutoff: April 2025.**

| Governance actor | Documents | Source data directory |
|---|---:|---|
| China | 4 | [China](Data/China/) |
| United States | 1 | [US](Data/US/) |
| Canada | 2 | [Canada](Data/Canada/) |
| European Union (EU) | 1 | [EU](Data/EU/) |
| United Nations General Assembly (UNGA) | 3 | [UNGA](Data/UNGA/) |
| United Nations Educational, Scientific and Cultural Organization (UNESCO) | 1 | [unesco](Data/unesco/) |
| **Total** | **12** | |

See [Document_List.csv](Data/Document_List.csv) for document titles, dates and official source links. Dates distinguish issuance, adoption, publication and other relevant date types; they do not represent the date on which a document was downloaded.

### Repository structure

| Path | Contents |
|---|---|
| `Data/China/`, `Data/US/`, `Data/Canada/`, `Data/EU/`, `Data/UNGA/`, `Data/unesco/` | Original analytical project files for each governance actor |
| [Data after theme renamed](Data/Data%20after%20theme%20renamed/) | Topic classification project files after topic labels were renamed |
| [Theme of Each Country.xlsx](Data/Theme%20of%20Each%20Country.xlsx) | Original cross-actor topic comparison workbook |
| [Document_List.csv](Data/Document_List.csv) | Inventory of 12 sampled normative documents |
| [Topic_Translation.csv](Data/Topic_Translation.csv) | English reading key for the non-header topic labels in the original comparison workbook, with source cell references |
| [CITATION.cff](CITATION.cff) | Machine-readable dataset citation metadata |
| [LICENSE](LICENSE) | Creative Commons Attribution–NonCommercial 4.0 International legal text |
| [ADDITIONAL_PERMISSIONS.md](ADDITIONAL_PERMISSIONS.md) | Additional permissions for academic use |

### File formats and reproducibility

The analytical files retain the native project formats of Weiciyun (微词云), the text analysis platform used in this study.

| Extension | Contents |
|---|---|
| `.wcy` | Chinese-language text analysis project |
| `.wcyeng` | English-language text analysis project |
| `.wcytopic` | Chinese-language topic classification project |
| `.wcyengtopic` | English-language topic classification project |
| `.xlsx` | Original tabular research data |
| `.csv` | Supplementary UTF-8 tables |

The project files can be downloaded and imported into Weiciyun for inspection of the analytical materials. **A paid Weiciyun membership is required to import the native project files.** The CSV files are accessible independently of Weiciyun.

### Language and translation

Chinese-language data are preserved in Chinese, and English-language data in English. The original topic labels are presented in Chinese. The supplementary English reading key preserves the original Chinese labels and workbook cell references; it does not alter the original project files or constitute a complete inventory of all topics in the native project files.

English translations supplied for reference were generated using ChatGPT (GPT-6.2; translation credit specified by the repository maintainer: “ChatGPT 6.2 Sol”). The researchers do not guarantee the accuracy of the English translations. In the event of any discrepancy, the original Chinese text and topic labels shall prevail.

### Citation

If you use the research data in this repository, please cite the dataset using the metadata in [CITATION.cff](CITATION.cff), or select **Cite this repository** on GitHub when available. Until the associated manuscript is formally published, cite the repository directly and include the URL and, where relevant, the commit identifier or access date.

Suggested citation:

Yao, L., & Wang, Z. (n.d.). *Research data for Scope for Normative Cooperation in Global Artificial Intelligence Governance: An Automated Text Analysis of Normative Documents* [Data set]. GitHub. https://github.com/CHNAQW/Normative-Cooperation-in-GAIG

Please also cite the associated article once it is formally published.

### License

Research data and materials that the Licensor has the authority to license are licensed under the [Creative Commons Attribution–NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

As additional permissions, graduate students may use the data in academic conference or forum presentations, and authors may use the data in academic publications for which they receive remuneration, including where those uses would otherwise be considered commercial. Attribution remains required. See [ADDITIONAL_PERMISSIONS.md](ADDITIONAL_PERMISSIONS.md) for details. Third-party source documents remain subject to their own rights and terms.

Questions about the research data may be submitted through [GitHub Issues](https://github.com/CHNAQW/Normative-Cooperation-in-GAIG/issues).

---

## 中文

### 仓库简介

本仓库收录研究论文《人工智能全球治理的规范合作空间——基于规范性文件的自动文本分析》的研究数据及相关分析材料。

**作者：姚璐、王泽昊。**

本研究运用词频分析、词频—逆文档频率（TF-IDF）分析、主题分析及情感分析等自动文本分析方法，比较不同治理行为体规范性文件中的核心关切、主题结构及情感取向，探讨人工智能全球治理中的规范合作空间。

本仓库公开相关研究数据，以提高研究透明度，为研究结论的经验检验及研究过程的复现提供数据支持。关联论文尚未正式发表，暂无 DOI。

### 数据范围

**数据收集截止时间：2025年4月。**

| 治理行为体 | 文件数量 | 原始数据目录 |
|---|---:|---|
| 中国 | 4 | [China](Data/China/) |
| 美国 | 1 | [US](Data/US/) |
| 加拿大 | 2 | [Canada](Data/Canada/) |
| 欧盟 | 1 | [EU](Data/EU/) |
| 联合国大会（UNGA） | 3 | [UNGA](Data/UNGA/) |
| 联合国教科文组织（UNESCO） | 1 | [unesco](Data/unesco/) |
| **合计** | **12** | |

有关规范性文件的名称、日期及官方来源链接，见 [Document_List.csv](Data/Document_List.csv)。表中日期分别标注文件的发布、通过或其他相关日期类型，不代表文件的下载时间。

### 仓库结构

| 路径 | 内容 |
|---|---|
| `Data/China/`、`Data/US/`、`Data/Canada/`、`Data/EU/`、`Data/UNGA/`、`Data/unesco/` | 各治理行为体的原始分析项目文件 |
| [Data after theme renamed](Data/Data%20after%20theme%20renamed/) | 完成主题重命名后的主题分类项目文件 |
| [Theme of Each Country.xlsx](Data/Theme%20of%20Each%20Country.xlsx) | 原始跨行为体主题比较汇总表 |
| [Document_List.csv](Data/Document_List.csv) | 12份纳入研究的规范性文件清单 |
| [Topic_Translation.csv](Data/Topic_Translation.csv) | 原始主题比较汇总表中非表头主题标签的中英对照及单元格位置 |
| [CITATION.cff](CITATION.cff) | 机器可读的数据集引用元数据 |
| [LICENSE](LICENSE) | 知识共享署名—非商业性使用4.0国际许可协议法律文本 |
| [ADDITIONAL_PERMISSIONS.md](ADDITIONAL_PERMISSIONS.md) | 学术用途的额外授权条款 |

### 文件格式与研究复现

原始分析项目文件采用本研究所使用的文本分析平台“微词云”的原生数据格式。

| 扩展名 | 内容 |
|---|---|
| `.wcy` | 中文文本分析项目文件 |
| `.wcyeng` | 英文文本分析项目文件 |
| `.wcytopic` | 中文文本主题分类项目文件 |
| `.wcyengtopic` | 英文文本主题分类项目文件 |
| `.xlsx` | 原始表格研究数据 |
| `.csv` | UTF-8 编码的补充数据表 |

研究者可下载相关项目文件，并将其导入微词云平台查阅分析材料。**导入微词云原生项目文件需要开通该平台的付费会员。** CSV 格式的补充数据表可独立于微词云平台查阅。

### 数据语言及翻译说明

本仓库保留中文数据的中文呈现形式及英文数据的英文呈现形式，原始文本主题名称以中文呈现。补充的主题中英对照表保留中文主题名称及原始表格单元格位置，不修改原始分析项目文件，其范围为原始主题比较汇总表中的主题标签。

本仓库补充提供的英文译文由 ChatGPT（GPT-6.2；仓库维护者指定的翻译署名为“ChatGPT 6.2 Sol”）翻译，仅供参考。研究者不保证英文译文的准确性。如英文译文与中文原始文本或主题名称存在差异，以中文原始文本为准。

### 引用说明

如在学术研究中使用本仓库数据，请依据 [CITATION.cff](CITATION.cff) 所提供的信息引用本数据集，或通过 GitHub 仓库页面的 **Cite this repository** 功能获取引用格式。在关联论文正式发表之前，请引用本数据集，并注明仓库地址；必要时可注明对应的提交版本或访问日期。

建议引用格式：

姚璐, 王泽昊. 《人工智能全球治理的规范合作空间——基于规范性文件的自动文本分析》研究数据集. GitHub. https://github.com/CHNAQW/Normative-Cooperation-in-GAIG

关联论文正式发表后，请同时引用该论文。

### 许可协议

本仓库中许可人有权授权的研究数据及相关材料采用[知识共享署名—非商业性使用4.0国际许可协议（CC BY-NC 4.0）](https://creativecommons.org/licenses/by-nc/4.0/)授权使用。

研究生因参加学术会议、学术论坛等进行的报告或展示，以及使用者在可获得稿酬或其他出版报酬的学术成果中使用本数据，不受“非商业性使用”条款限制。上述使用仍须履行署名义务。具体内容见 [ADDITIONAL_PERMISSIONS.md](ADDITIONAL_PERMISSIONS.md)。第三方规范性文件适用其各自的权利及使用条款。

有关研究数据的问题，可通过本仓库的 [GitHub Issues](https://github.com/CHNAQW/Normative-Cooperation-in-GAIG/issues) 功能提出。
