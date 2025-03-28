# mcp-server-taiwan-aqi
取得目前及過去 24 小時台灣各地空氣品質監測站資料。
Get current and past 24 hours air quality monitoring station data of Taiwan (R.O.C).

# 使用方法

1. [下載 PHP 8.2.x](https://www.php.net/downloads.php#v8.2.28)
2. 下載打包好的檔案並解壓縮
3. 修改 claude_desktop_config.json
```
{
  "mcpServers": {
	"taiwanaqi": {
	"command": "php",
	"args": [
		"D:\\[YOUR_PATH_FOLDER]\\client.php",
		"api_key=YOUR_API_KEY"
		]
	}
}

```
將 YOUR_PATH_FOLDER 更改成前一步驟解壓縮後的存放路徑
   
4. 重啟 Claude Desktop 應用程式
5. 重啟參考[官方說明](https://modelcontextprotocol.io/quickstart/user)操作，確認看到以下 Tools：
* aqi-health-guidance
* aqi-query
* aqi-query-recent

   

