# API providing channels data to www.mirror.fm

## Dev

    python3 main.py

## Deploy

    apex build to-www-channels >/dev/null && apex deploy to-www-channels --region eu-west-1 -ldebug

## Result

https://qdfngarl1b.execute-api.eu-west-1.amazonaws.com/get
