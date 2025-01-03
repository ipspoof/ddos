# Comprehensive Network Security Tools Project / 综合网络安全工具项目

This project includes various network security tools and resources, including social engineering bot, DDoS scripts, social engineering database, botnet management scripts, vulnerability exploit tools, scanning servers, IP spoofing servers, botnet server management, cheap host resource management, honeypots, DDoS defense scripts, scanning tools, and remote control cluster source code. It aims to provide comprehensive support for network security research and defense.

本项目集合了多种网络安全相关的工具与资源，包含社工库机器人、DDoS脚本、社工库数据、僵尸网络管理脚本、漏洞利用工具、扫描服务器、IP欺骗服务器、僵尸网络服务器管理、廉价主机的资源管理、蜜罐、DDoS防御脚本、扫描工具以及远控集群源码。旨在为网络安全研究和防御提供全面的支持。

---

## 📚 Project Directory / 项目目录

1. **Social Engineering Bot / 社工库机器人**
   - Automates social engineering information queries / 自动化社工信息查询。
   - Supports quick search and data filtering / 支持快速检索、数据筛选。
   - Can be integrated with Telegram, WeChat, and other platforms / 可集成到 Telegram、微信等平台。

2. **DDoS Scripts / DDoS 脚本**
   - Provides various high-efficiency attack scripts (e.g., NTP, DNS, HTTP amplification) / 提供多种高效攻击脚本（如 NTP、DNS、HTTP 放大）。
   - Supports custom parameter configuration / 支持自定义参数配置。
   - Compatible with various server environments / 适配多种服务器环境。

3. **Social Engineering Database / 社工库数据**
   - Large-scale social engineering data files / 大规模社工数据文件。
   - Supports keyword search / 支持关键词检索。
   - Data can be filtered and exported as needed / 数据可按需筛选导出。

4. **Botnet Management / 僵尸网络管理**
   - Manage botnet nodes in batches / 批量管理僵尸节点。
   - Supports dynamic IP updates and task assignment / 支持动态 IP 更新和任务分配。
   - Provides both web interface and command-line operation modes / 提供 Web 界面和命令行操作两种模式。

5. **Vulnerability Exploit Tools / 漏洞利用工具**
   - Collects and develops the latest vulnerability PoCs (Proof of Concepts) / 收集与开发最新的漏洞 PoC（概念验证代码）。
   - Supports bypassing comment validation, code execution, information leakage, and other attack scenarios / 支持注释验证绕过、代码执行、信息泄露等多种攻击场景。
   - Includes exploitation templates for common services / 包含常见服务的漏洞利用模板。

6. **Scanning Servers / 扫描服务器**
   - Efficiently scans target servers / 高效扫描目标服务器。
   - Supports port scanning, service detection, vulnerability scanning, and more / 支持端口扫描、服务检测、漏洞扫描等功能。
   - Provides export functionality in multiple formats (CSV, JSON, etc.) / 提供结果导出功能，支持多种格式（如CSV、JSON）。

7. **IP Spoofing Servers / IP 欺骗服务器**
   - Used for generating spoofed IP traffic to simulate attacks or conduct testing / 用于生成伪造的 IP 地址流量，模拟攻击或进行测试。
   - Supports customizable spoofed IP address pools / 支持定制化设置伪造 IP 地址池。

8. **Botnet Server Management / 僵尸网络服务器**
   - Botnet management and control platform / 僵尸网络管理与控制平台。
   - Supports adding, updating, and removing botnet nodes / 支持添加、更新和删除僵尸节点。
   - Provides centralized instruction distribution and status monitoring / 提供集中的指令分发与状态监控功能。

9. **Cheap Host Resource Management / 廉价主机资源管理**
   - Provides resource management tools for cheap hosts, suitable for large-scale deployment of attacks or testing environments / 提供廉价主机的资源管理工具，适用于大规模部署攻击或测试环境。
   - Supports batch operations and efficient resource configuration / 支持批量操作和高效资源配置。

10. **Honeypots / 蜜罐**
    - Provides honeypot system simulation and monitoring / 提供蜜罐系统模拟和监控。
    - Used to trap attackers, analyze attack behaviors, and collect data / 用于诱捕攻击者，分析攻击行为并收集数据。

11. **DDoS Defense Scripts / DDoS 防御脚本**
    - Provides defense scripts against DDoS attacks / 提供针对 DDoS 攻击的防御脚本。
    - Supports traffic monitoring, automated protection, IP banning, and more / 支持流量监控、自动化防护、IP 封禁等功能。

12. **Scanning Tools / 扫描工具**
    - Batch scanning and automated security detection tools / 批量扫描、自动化安全检测工具。
    - Supports common vulnerability scanning, port detection, web application security testing, etc. / 支持常见漏洞扫描、端口探测、Web 应用安全测试等。

13. **Remote Control Cluster Source Code / 远控集群源码**
    - Remote control cluster management source code / 远程控制集群管理源码。
    - Supports distributed remote control, cluster monitoring, task scheduling, etc. / 支持分布式远控、集群监控、任务调度等功能。

---

## 🚀 Features / 功能特色

- **Modular Design**: Each component is independent, making it easy to integrate or use individually / **模块化设计**：各组件相互独立，方便集成或单独使用。
- **High Efficiency**: Optimized performance for different functional points / **高效执行**：针对不同功能点优化了性能。
- **Continuous Updates**: Regular updates with the latest security industry trends / **持续更新**：紧跟安全行业最新动态，定期更新工具与资源。
- **Cross-Platform Support**: Can be run on Windows, Linux, and other operating systems / **跨平台支持**：可在 Windows、Linux 等多种操作系统中运行。

---

 Installation & Usage / 安装与使用
Requirements / 环境要求
Before starting, make sure your environment meets the following requirements:

在开始之前，请确保您的环境满足以下要求：

Python 3.8 and above / Python 3.8 及以上版本
Ensure that you have Python 3.8 or higher installed. You can check your Python version by running: 确保你已经安装了 Python 3.8 或更高版本。可以通过运行以下命令检查 Python 版本：

bash
复制代码
python --version
MySQL / SQLite
MySQL 或 SQLite 数据库。如果使用 MySQL，请确保已经安装并且配置了数据库实例。如果使用 SQLite，则无需进行额外配置。

Redis
Redis 数据库。如果没有安装 Redis，可以参考Redis 官方文档进行安装。

Required network connection / 必要的网络连接
Please make sure your network connection is stable, as the tool may need to access external services for some features.
请确保你的网络连接稳定，因为该工具可能需要访问外部服务来实现某些功能。

Quick Start / 快速开始
Follow these steps to quickly set up and start using the project:

按照以下步骤快速设置并开始使用该项目：

Clone the project / 克隆项目
Clone this repository to your local machine using Git: 使用 Git 克隆该项目到本地机器：

bash
复制代码
git clone https://github.com/ipspoof/ddos.git
Navigate into the project directory / 进入项目目录
Once the repository is cloned, move into the project directory: 克隆完成后，进入项目目录：

bash
复制代码
cd ddos
Install the required dependencies / 安装所需的依赖
Run the following command to install the required Python dependencies: 运行以下命令来安装所需的 Python 依赖：

bash
复制代码
pip install -r requirements.txt
Configure the database / 配置数据库
Set up your MySQL or SQLite database as required.
根据需要设置 MySQL 或 SQLite 数据库。

For MySQL, create a new database and update the connection settings in the configuration file. 对于 MySQL，创建一个新的数据库并在配置文件中更新连接设置。

Start the application / 启动应用程序
To start the application, simply run: 启动应用程序，只需运行以下命令：

bash
复制代码
python main.py
This will launch the DDoS attack script or related functionality based on the configuration you've set up. 这将根据您设置的配置启动 DDoS 攻击脚本或相关功能。

Additional Configuration / 其他配置
If you want to customize the attack methods, database settings, or network configurations, you can edit the configuration files in the /config directory.
如果你想自定义攻击方法、数据库设置或网络配置，可以编辑 /config 目录中的配置文件。

Resources for Support / 支持资源
If you need further assistance or have any questions, feel free to reach out via Telegram at @qVmfbI.
如果你需要进一步的帮助或有任何问题，欢迎通过电报联系 @qVmfbI。

For more information, check out the official documentation and FAQs.
欲了解更多信息，请查看官方文档和常见问题解答。

   
