# nlp-lab
## pip 複製開發環境
1. 匯出環境的package: `pip freeze > requirements.txt`
2. 下載到自己電腦: `pip download -r requirements.txt -d download_dir`
3. 將下載好的whl及requirements.txt上傳到github
4. 在新環境下載github內的whl檔等安裝檔
5. 安裝: `pip install -r requirements.txt --no-index --find-link=dir_path`<br>
    e.g. `pip install -r requirements.txt --no-index --find-link=C:\Users\jason\nlp-lab`
