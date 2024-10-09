# Setup api key
Get your key at https://aistudio.google.com/app/apikey
Then put it in at /api/generate_sse.php
People can bypass the api for generateing so fix it
# Fixing needed 
find // Block People From useing api on browser -- Rok574 was here
$allowed_referrer = 'https://exoro.scartch123.serv00.net'; in /api/generate_sse.php replace the url with yours 


