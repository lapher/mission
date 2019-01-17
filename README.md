
描述

簡單描述message queue的應用場景，並簡介sqs

在docker-compose.yml檔內追加一個sqs container

sqs的域名須為 cc104.sqs.local

開啟一個sqs-example.ipynb，在裡面嘗試使用boto3套件連結至sqs進行 創建queue，丟message進入queue，從queue拉出message，刪除在queue裡的message

並將檔案上傳至github
