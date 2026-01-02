在 /backend 路徑下執行

建立虛擬環境
uv venv

初始化環境
uv init

進入虛擬環境
source .venv/bin/activate

安裝現有套件全部
uv sync

在 backend 下方建立 .env 放上 GOOGLE_API_KEY
在 backend/app/data 下方放入 access_log_part1.log access_log_part2.log

啟動後端服務 fastapi
uvicorn app.main:app --reload --port 8000



測試API
curl -X POST http://localhost:8000/web-log/invoke \
  -H "Content-Type: application/json" \
  -d '{"input": "請幫我計算 5 + 5"}'



 curl -X OPTIONS https://cathay-log.onrender.com/api/infer \
  -H "Origin: https://thriving-alfajores-e1c9ee.netlify.app" \
  -H "Access-Control-Request-Method: POST" \
  -H "Access-Control-Request-Headers: content-type" \
  -i
