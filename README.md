# 王立任
# 智慧商務系
# 學生38號# 安裝手冊

## 前置需求

在開始安裝之前，請確保你的系統已經安裝以下軟體：

- Python 3.x
- pip

## 安裝步驟

1. 克隆專案到本地端：
    ```sh
    git clone <你的專案網址>
    cd <你的專案目錄>
    ```

2. 建立虛擬環境並啟動：
    ```sh
    python -m venv venv
    source venv/bin/activate  # 對於 Windows 系統，使用 `venv\Scripts\activate`
    ```

3. 安裝所需的套件：
    ```sh
    pip install -r requirements.txt
    ```

## 測試

要運行測試，請執行以下命令：

```sh
pytest
