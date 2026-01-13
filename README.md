# MyBatis Generator GUI Extension

![Java](https://img.shields.io/badge/Java-17%2B-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

这是一个为 MyBatis Generator (MBG) 提供的图形化界面工具。它旨在简化 MyBatis 代码生成的配置过程，提供直观的 UI 操作，支持多种数据库，并集成了常用的插件和高级配置选项。

---

## 📥 快速开始 (Quick Start)

### 方式一：直接下载运行 (推荐)

我们在项目中提供了开箱即用的绿色版，无需繁琐的安装步骤。

1.  下载[**`MyBatisGeneratorGUI.7z`**](./release/MyBatisGeneratorGUI.7z)并解压。
2.  进入解压后的文件夹，双击 **`MyBatisGeneratorGUI.exe`** 即可启动。

> **注意**：该版本已内置必要的运行环境，支持 Windows 系统。

---

### 方式二：源码构建

如果您想自己修改代码或重新打包，请按照以下步骤操作：

#### 环境要求
* **JDK 17** 或更高版本
* Maven 3.x

#### 构建步骤
1.  克隆项目到本地：
    ```bash
    git clone [https://github.com/chenglei1986/mybatis-generator-gui-extension.git](https://github.com/chenglei1986/mybatis-generator-gui-extension.git)
    ```
2.  进入项目目录并执行 Maven 构建命令：
    ```bash
    # 生成绿色免安装版 (Windows)
    mvn clean package -Pwin-exe
    ```
3.  构建成功后，在 `target/dist/` 目录下即可找到生成的可执行程序。

---

## ✨ 主要功能

* **可视化配置**：摆脱繁琐的 XML 配置文件，通过图形界面轻松设置数据库连接、表名映射、包名等。
* **多数据库支持**：支持 MySQL, Oracle, PostgreSQL, SQL Server 等主流数据库。
* **内置插件**：集成了常用的 MyBatis 插件（如分页插件、注释插件、Lombok支持等），一键启用。
* **实时预览**：在生成代码前可以预览生成的文件内容。
* **高版本兼容**：项目已升级适配 JDK 17+，使用现代化技术栈。

---

## 🛠️ 技术栈

* **语言**: Java 17
* **GUI框架**: JavaFX (OpenJFX 17)
* **构建工具**: Maven
* **打包工具**: JPackage (Native Image)

---

## 📄 许可证

本项目采用 MIT 许可证，详情请参阅 [LICENSE](LICENSE) 文件。