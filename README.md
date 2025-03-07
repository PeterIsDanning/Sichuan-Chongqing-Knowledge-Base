# Sichuan & Chongqing Listed Companies Daily Information Knowledge Base

## Project Overview
This project aims to establish a **daily information knowledge base** for listed companies in Sichuan and Chongqing. It collects and organizes daily reports and essential company information, enabling intelligent Q&A interactions using large language models.
本项目旨在建立**川渝地区上市公司的每日资讯知识库**，收集并整理每日报告及公司关键信息，同时利用大模型构建智能问答系统。

## Project Structure
- **`daily/`**: Stores daily reports on Sichuan and Chongqing listed companies. 存储川渝上市公司每日资讯报告。
- **`data/`**: Contains CSV files used in the project, including executive information. 包含项目使用的 CSV 数据文件，如高管信息等。
- **`infobase/`**: Holds basic information about all Sichuan and Chongqing listed companies. 存储所有川渝上市公司的基本信息。
- **`output_categories/`**: Categorizes all listed companies based on their industry sectors. 按照行业对所有川渝上市公司进行分类。

### Code & Usage
- **`company_daily_extraction.ipynb`**: Extracts daily news reports for listed companies. 用于提取川渝上市公司每日资讯。
  - Running this notebook generates daily reports stored in the `daily/` folder. 运行后会在 `daily/` 文件夹中生成当日资讯文件。
  - Execution time: **15-25 minutes**, depending on local network conditions. 运行时间：**15-25 分钟**，取决于本地网络情况。
  - If errors occur due to webpage timeouts, adjust `time.sleep(2)` to a higher value to wait longer for webpage loading. 若出现超时错误，可适当调整 `time.sleep(2)` 的数值，增加网页加载等待时间。

- **`company_information_extraction.ipynb`**: Crawls basic company information. 用于爬取川渝上市公司的基本信息。
  - Outputs are saved as individual company information files in the `infobase/` folder. 采集的高管信息存储在 `data/executive.csv` 中。

- **`executive_information_extraction.ipynb`**: Extracts executive details of listed companies.
  - The collected information is stored in `data/executive.csv`.

## Legal & Intellectual Property
- The collected data is for **research and educational purposes only**. 本项目所收集数据仅供**学术研究和教育用途**。
- Ensure compliance with **data access policies** of the original sources. 请确保遵守原始数据来源的**访问和使用政策**。
- The project does not claim ownership over the extracted data. 本项目不对所爬取数据拥有所有权。

For any inquiries, feel free to raise an issue or contribute to the project. 🚀 如有任何问题，欢迎提交 Issue 或贡献代码！🚀
