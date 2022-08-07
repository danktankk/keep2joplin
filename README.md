# keep2joplin

将 google keep 转换为 joplin 文件。

支持导入 标题、内容、连接(Annotations)、附件(Attachments)、创建时间、修改时间等。

使用方式：

* 访问 https://takeout.google.com/ 导出 google keep 数据
* 解压 `takeout-**********-***.zip` 等文件
* 执行 `keep2joplin.exe -src=C:\Users\***\Downloads\takeout-20220804T040209Z-002\Takeout` 或 `keep2joplin  -src=/home/***Downloadstakeout-20220804T040209Z-002akeout`
* keep2joplin 会创建 `keep` 目录来保存转换后的文件
* 打开 joplin, 点击 文件->导入->导入 MD - markdown + 文件前言(文件目录)，选择 `keep` 目录

# keep2joplin

Convert google keep to joplin file.

Support to import title, content, hyperlink(Annotations), attachments, creation time, modification time, etc.

How to use:

* Visit https://takeout.google.com to export google keep data
* Unzip files like `takeout-**********-***.zip`
* execute `keep2joplin.exe -src=C:\Users\***\Downloads\takeout-20220804T040209Z-002\Takeout` or `keep2joplin  -src=/home/***Downloadstakeout-20220804T040209Z-002akeout`
* keep2joplin will create a `keep` directory to hold the converted files
*Open joplin, click File->Import->Import MD - markdown + 文件前言(directory), select `keep` directory

