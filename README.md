# gke_efk

cluster namespace:efk
服務名:kibana

helm 指令 範例：

建置
helm install kibana .

更新檔案
helm upgrade -i kibana .

刪除
helm -n efk delete kibana
