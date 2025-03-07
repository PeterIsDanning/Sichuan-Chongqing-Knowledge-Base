# Sichuan & Chongqing Listed Companies Daily Information Knowledge Base

## Project Overview
This project aims to establish a **daily information knowledge base** for listed companies in Sichuan and Chongqing. It collects and organizes daily reports and essential company information, enabling intelligent Q&A interactions using large language models.

## Project Structure
- **`daily/`**: Stores daily reports on Sichuan and Chongqing listed companies.
- **`data/`**: Contains CSV files used in the project, including executive information.
- **`infobase/`**: Holds basic information about all Sichuan and Chongqing listed companies.
- **`output_categories/`**: Categorizes all listed companies based on their industry sectors.

### Code & Usage
- **`company_daily_extraction.ipynb`**: Extracts daily news reports for listed companies.
  - Running this notebook generates daily reports stored in the `daily/` folder.
  - Execution time: **15-25 minutes**, depending on local network conditions.
  - If errors occur due to webpage timeouts, adjust `time.sleep(2)` to a higher value to wait longer for webpage loading.

- **`company_information_extraction.ipynb`**: Crawls basic company information.
  - Outputs are saved as individual company information files in the `infobase/` folder.

- **`executive_information_extraction.ipynb`**: Extracts executive details of listed companies.
  - The collected information is stored in `data/executive.csv`.

## Legal & Intellectual Property
- The collected data is for **research and educational purposes only**.
- Ensure compliance with **data access policies** of the original sources.
- The project does not claim ownership over the extracted data.

For any inquiries, feel free to raise an issue or contribute to the project. 🚀
