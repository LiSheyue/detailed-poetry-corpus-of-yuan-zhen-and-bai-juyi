# Detailed Poetry Corpus of Yuan Zhen and Bai Juyi

## Statistics

- Number of poems:  
  - Yuan Zhen: 880  
  - Bai Juyi: 2918  

- Number of metadata dimensions: 14  


## Format

The corpus is stored in **JSON** format, where each **poem is represented as a dictionary (object)**.  
Each key corresponds to a specific metadata field, and the poem text is stored as a list of strings in the `"正文"` field.

A sample excerpt is shown below:

```json
{
  "id": "B0880",
  "作者": "白居易",
  "標題": "雨中題衰柳",
  "時間": "元和十年（815）",
  "來源": "朱《箋》",
  "地點": "長安至江州途中",
  "體裁": "五言絕句",
  "格式": "",
  "卷數": "卷十五",
  "卷首一": "律詩",
  "卷首二": "五言 七言",
  "序言": "",
  "用韻": "押五歌",
  "自注": "",
  "正文": [
    "濕屈青條折，寒飄黃葉多。",
    "不知秋雨意，更遣欲如何。"
  ]
}
```


## Resources

- Poem texts are extracted from *Quan Tang Shi Analysis System*:  
  https://vpn2.nlc.cn/prx/000/http/202.106.125.44:8082/tang/

- Metadata is manually annotated based on the following sources:

  - Yuan Zhen:  
    *Yuan Zhen Ji Jiao Zhu*. Annotated by Zhou Xiang. Shanghai: Shanghai Guji Publishing House, 2011.

  - Bai Juyi:  
    *Bai Juyi Ji*. Edited by Zhonghua Book Company, proofread by Gu Xuejie. Beijing: Zhonghua Book Company, 1979.  
    *Bai Juyi Shi Ji Jiao Zhu*. Annotated by Xie Siwei. Beijing: Zhonghua Book Company, 2006.


## Citation

If you use this dataset in your research, please cite this GitHub repository https://github.com/LiSheyue/detailed-poetry-corpus-of-yuan-zhen-and-bai-juyi


## Contributors

- Project Leader:  
  Ziyi Qin

- Group Members:  
  Yiqing Gong  
  Qianpei Huang  
  Peilin Li  
  Xinyi Zhang  

Beijing Foreign Studies University


## License

This work is licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/4.0/


---


# 元稹与白居易诗歌详注语料库

## 数据统计

- 诗歌数量：  
  - 元稹：880首
  - 白居易：2918首 

- 元数据维度：14


## 数据格式

本语料库以 **JSON 格式** 存储。  
每首诗对应一个 **字典（dictionary）对象**，每个字段为该诗歌的一项元信息，正文则以字符串列表的形式存储在 `"正文"` 字段中。

以下为示例片段：

```json
{
  "id": "B0880",
  "作者": "白居易",
  "標題": "雨中題衰柳",
  "時間": "元和十年（815）",
  "來源": "朱《箋》",
  "地點": "長安至江州途中",
  "體裁": "五言絕句",
  "格式": "",
  "卷數": "卷十五",
  "卷首一": "律詩",
  "卷首二": "五言 七言",
  "序言": "",
  "用韻": "押五歌",
  "自注": "",
  "正文": [
    "濕屈青條折，寒飄黃葉多。",
    "不知秋雨意，更遣欲如何。"
  ]
}
```


## 数据来源

- 诗歌原文来自“全唐诗分析系统”：  
  https://vpn2.nlc.cn/prx/000/http/202.106.125.44:8082/tang/

- 元数据由项目组成员参考以下书籍人工整理：

  - 元稹：  
    （唐）元稹著；周相录校注. 元稹集校注[M]. 上海：上海古籍出版社, 2011.12.

  - 白居易：  
    中华书局编；顾学颉校. 白居易集[M]. 北京：中华书局, 1979. 
    谢思炜撰. 白居易诗集校注[M]. 北京：中华书局, 2006.07.


## 引用方式

若您在研究中使用本数据集，请注明本项目的 GitHub 仓库地址 https://github.com/LiSheyue/detailed-poetry-corpus-of-yuan-zhen-and-bai-juyi


## 项目成员

- 项目负责人：  
  覃子懿

- 团队成员：  
  龚奕晴  
  黄芊沛  
  李沛霖  
  张鑫怡  

北京外国语大学


## 许可协议
本项目以 Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International 协议发布。如需查看该许可，请访问 https://creativecommons.org/licenses/by-nc-sa/4.0/
