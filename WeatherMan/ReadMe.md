# WeatherMan 天氣管家機器人

### 快速上手

1. 編輯`GetWeatherData.py`。

	- AuthorizationKEY 氣象局 OpenData API key

2. 取得未來一週的氣象預報

	```python3 GetWeatherData.py```

### 2 建立 Loki Bot

1. 登入 [Loki 控制台](https://api.droidtown.co/loki/)。

2. 在 Loki 控制台中新建一個專案`WeatherMan`，並進入專案。

3. 在專案下方選擇`ArticutModel`並依序點擊 [瀏覽] > 選擇`ref/Weather.ref` > [讀取意圖] ，並進入意圖。

4. 在`5. 生成模型`區塊中點擊 [生成模型 (Weather)]。完成後，在畫面最上面點擊左邊的「房子」圖示，回到專案頁。這裡有`WeatherMan`的專案金鑰。

5. 編輯`WeatherMan.py`及`intent/Loki_Weather.py`。
	- USERNAME 填入你的 Droidtown 使用者帳號 (email)
	- API_KEY 填入你的 [Articut 金鑰](https://api.droidtown.co/member/)
	- LOKI_KEY 填入你產生的`WeatherMan`專案金鑰

6. 安裝 `chatgpt-wrapper`

	```pip install git+https://github.com/mmabrouk/chatgpt-wrapper```
	
7. 安裝 `requirements.txt`

	```pip install -r requirements.txt```
	
8. 在 `playwright` 中下載瀏覽器

	```playwright install```
	
9. 設定 chatGPT

	```chatGPT install```
   
   此時會打開 OpenAI 的登入/註冊頁面，登入帳戶至看到 chatgpt 的使用頁面後即可關閉瀏覽器

10. 開始使用`WeatherMan`。
