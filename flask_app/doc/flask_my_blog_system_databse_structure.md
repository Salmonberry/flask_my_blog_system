# Flask My Blog System Databse Structure

## 命名规则
- 表名：小写、 下划线、 复数
- 字段名：小写、下划线

## 业务描述

## 数据结构

### 多语言本地化 Localizations

localizations_en 英文表

| 字段名 | 数据类型 | 是否为空（Y/N）(是否为空) | 注释 |
| :----: | :------: | :-----------------------: | ---- |
|        |          |                           |      |
|        |          |                           |      |
|        |          |                           |      |

localizations_zh_tc 繁体中文表

| 字段名 | 数据类型 | 是否为空（Y/N）(是否为空) | 注释 |
| :----: | :------: | :-----------------------: | ---- |
|        |          |                           |      |
|        |          |                           |      |
|        |          |                           |      |

localizations_zh_tc 简体中文表

| 字段名 | 数据类型 | 是否为空（Y/N）(是否为空) | 注释 |
| :----: | :------: | :-----------------------: | ---- |
|        |          |                           |      |
|        |          |                           |      |
|        |          |                           |      |

### 目标 Target

target 目标表

|     字段名     |   数据类型    | 是否为空（Y/N） | 注释         |
| :------------: | :-----------: | :-------------: | ------------ |
|       id       |      int      |        N        |              |
|     title      |  VARCHAR(20)  |        N        | 目标标题     |
|   image_url    |    VARCHAR    |        N        | 图片链接     |
|  description   | VARCHAR(2000) |        N        | 目标描述     |
|    summary     | VARCHAR(2000) |        N        | 总结目标     |
| key_point_list |     JSON      |        Y        | 目标的关键点 |

