<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <script src="https://telegram.org"></script>
    <style>
        body { font-family: sans-serif; background: #000; color: #fff; text-align: center; padding: 20px; }
        .card { background: #111; border: 1px solid #333; border-radius: 15px; padding: 20px; margin: 15px 0; font-size: 20px; }
        h2 { color: #0088cc; }
    </style>
</head>
<body>
    <h2>🏔 GOLOS GOR</h2>
    <div class="card" onclick="window.Telegram.WebApp.sendData('w');window.Telegram.WebApp.close();">🏔 ПОГОДА</div>
    <div class="card" onclick="window.Telegram.WebApp.sendData('f');window.Telegram.WebApp.close();">🥩 ГАСТРО</div>
    <div class="card" onclick="window.Telegram.WebApp.sendData('s');window.Telegram.WebApp.close();" style="color:#ff4444;">🆘 SOS</div>
    <script>window.Telegram.WebApp.expand();</script>
</body>
</html>
