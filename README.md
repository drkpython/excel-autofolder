# Excel to 文件夹生成器 v2.0 更新说明

根据 Excel 指定列的内容批量生成文件夹。

👉 **点击右边 Releases 下载最新版**

## 功能

- **格式兼容**：自动识别 `.xls` 和 `.xlsx` 文件
- **多工作表**：支持切换不同 Sheet 页
- **首行处理**：可选第一行是否为列标题（无标题时使用数字索引）
- **数据预览**：生成前预览前10行数据，避免出错
- **命名清理**：自动移除 Windows 非法字符（`&lt;&gt;:"/\|?*`）及保留名（CON/PRN 等）
- **重复处理**：支持跳过、自动重命名（加序号）、覆盖三种模式
- **空值过滤**：自动跳过空白单元格

## 使用步骤

### 1. 准备数据
Excel 第一行可以是列标题（如"客户名称"），也可以是数据本身，软件会自动识别。

![数据准备](https://github.com/user-attachments/assets/0f86dfd3-d2f2-4147-b1f0-12f33aa33400)

### 2. 加载表格
选择 Excel 文件，程序自动识别所有工作表和列。

![加载文件](https://github.com/user-attachments/assets/6d6812d6-1ecb-4fd4-ba15-9f1c6ed19ad4)

### 3. 选择目标列
- 选择要读取的工作表（如果有多个 Sheet）
- 选择要生成的列（支持下拉选择）
- 勾选「跳过第一行」如果第一行是标题而非数据

![选择列](https://github.com/user-attachments/assets/0e51e644-bf50-45cd-81a7-3a0aba290938)

### 4. 设置输出位置
选择文件夹生成的目标目录。

![选择输出位置](https://github.com/user-attachments/assets/4264d666-2993-4bfb-b936-bd72c69ebfe2)

### 5. 生成文件夹
点击「开始生成」，批量创建以单元格内容命名的文件夹。

![生成效果](https://github.com/user-attachments/assets/f5b3e783-54d7-4bc9-a0d2-a806d8a36de5)
