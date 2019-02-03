# MarkdownPad2破解过程
## [下载地址](https://markdown-here.com/)
![MarkdownPad2](https://markdown-here.com/img/icon256.png)
## 一、破解工具
	1.win10 专业版
	2.dnSpy v6.0.2
	3.MarkdownPad2安装包
## 二、破解过程
### 寻找验证函数，直接替换

	try
	{
		this.License = new License();
		this.License.Email = email;
		this.License.CreationDate = DateTime.Now;
		this.License.Name = email;
		this.License.Product = "MarkdownPad2";
		this.License.LicenseTypeId = 1;
		this.LicenseProcessed = true;
	}
	catch (FormatException exception)

![t2](./MarkDownPad.png)
![t1](./MarkDownPad2.png)
## 三、下载
[替换文件](./MarkdownPad2.exe)
[安装文件](./markdownpad2-setup.exe)
[注册机](./MarkdownPad.rar)