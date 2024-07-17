# SougouDict 搜狗词库
词库来源 [搜狗词库](https://pinyin.sogou.com/dict/)

搜狗词库爬虫 [Sougou_dict_spider](https://github.com/StuPeter/Sougou_dict_spider)

词库转换 [imewlconverter](https://github.com/studyzy/imewlconverter)

## 文件说明

1. 目录结构：

        .
        ├── scel
        ├── txt
        ├── txtMerge
            ├── txtMerge.txt   
        ├── txtMerge2Gboard
            ├── Gboard.zip  
        └── txtMerge2Rime
            ├── sougou2Rime.dict.yaml  

2. 文件说明
    + `scel`，搜狗所有的词库 `scel` 文件
    + `txt`，搜狗 `scel` 文件转换为 `txt` 文件
    + `txtMerge`，`txt` 文件合并，合并后文件为 `txtMerge.txt`
    + `txtMerge2Gboard`，`txtMerge.txt` 转换为 `Gboard` 词库，转化后的文件为 `Gboard.zip`
    + `txtMerge2Rime`，`txtMerge.txt` 转换为 `Rime` 词库，转化后的文件为 `sougou2Rime.dict.yaml`
