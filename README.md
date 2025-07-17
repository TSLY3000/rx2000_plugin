
#  NX Witness + RX2000 Plugin 使用說明

## 安裝說明（Install Instructions）

1. **停止伺服器 (Stop the server)**  
2. 將 `rx2000.dll` 檔案複製至以下路徑：  
   ```
   C:/Program Files/Network Optix/Nx Witness/MediaServer/plugins
   ```
3. **重新啟動伺服器 (Restart the server)**


## 插件安裝確認

1. 於 NX Witness 右鍵點擊任一相機，選擇 **Camera Settings**。
2. 確認左側出現 **RX2000 Plugin**，表示已安裝成功。

## 注意事項

- 使用 Plugin 時，請務必開啟 **Object Search**，才能查看分析結果。
- 記得打開錄像模式

---

## 參數以及設定

請依下列說明填寫設定欄位：

- **Detection Interval（偵測間距）**  
  輸入數值（單位：毫秒），表示系統每隔幾毫秒向相機請求一次 AI 資料。  
  例如：輸入 `100`，則每 0.1 秒抓取一次 AI 偵測結果。

- **IP Address**  
  請輸入目標相機的 IP 位址，例如：`192.168.1.100`。

- **Port**  
  請輸入相機使用的 HTTP 通訊埠號，例如：`80` 或 `8080`。

- 勾選下方的「啟用 AI 偵測」選項（checkbox），表示您確認啟動資料請求流程。
  - 勾選後，系統將依照您設定的間隔時間，與指定的相機 IP 與 Port 建立連線，定期取得 AI 結果。

---


For more info, see https://drive.google.com/file/d/1STGE3Cn_XrfU6sBD9p5OQWb3hnUyxZrj/view?usp=sharing for a user manual video.
