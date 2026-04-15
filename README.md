# 点击右边Releases下载👉👉👉
# Excel文件夹生成器 v2.0 2026/4/15

根据 Excel 指定列的内容批量生成文件夹。

## 功能

- **格式兼容**：自动识别 `.xls` 和 `.xlsx` 文件
- **多工作表**：支持切换不同 Sheet 页
- **首行处理**：可选第一行是否为列标题（无标题时使用数字索引）
- **数据预览**：生成前预览前10行数据
- **命名清理**：自动移除 Windows 非法字符（`&lt;&gt;:"/\|?*`）及保留名（CON/PRN 等）
- **重复处理**：支持跳过、自动重命名（加序号）、覆盖三种模式
- **空值过滤**：自动跳过空白单元格

## 安装

```bash
pip install pandas openpyxl xlrd
### 准备数据(表格抬头第一行必须为中文)
![63c60c4db0438d3369f4fd76200fad2](https://github.com/user-attachments/assets/0f86dfd3-d2f2-4147-b1f0-12f33aa33400)

### 读取表格
![afd761c4ca9c0920a9759ec47899c33](https://github.com/user-attachments/assets/6d6812d6-1ecb-4fd4-ba15-9f1c6ed19ad4)

### 选择生成位置
![0e8ed3cac1923aa7c2b334f14db5bdd](https://github.com/user-attachments/assets/4264d666-2993-4bfb-b936-bd72c69ebfe2)

### 选择要生成的列
![dff7d264020e6e135b596e6e9129b6b](https://github.com/user-attachments/assets/0e51e644-bf50-45cd-81a7-3a0aba290938)

### 生成效果 会默认忽略第一行
![010c906658edfa72670c4297c0118b7](https://github.com/user-attachments/assets/f5b3e783-54d7-4bc9-a0d2-a806d8a36de5)

