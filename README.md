# browse-lightshot
Browse screenshots pubically available on LightShot. It's comparable to changing letters/numbers in your uploaded screenshot to see someone else's. This app just speeds up the process.

**Educational Purposes:** This project is for educational purposes ONLY, please do not misuse this tool. This tool is designed to show why one should never upload anything confidential to LightShot.

**Warning:** Not everything uploaded to LigthShot is SFW.

### 1) Only works with CORS sameorigin turned off

Run Chrome with CORS off: https://alfilatov.com/posts/run-chrome-without-cors/

*Firefox does not support no CORS mode*

**TL;DR**

Start Chrome on Win10: `"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --disable-web-security --disable-gpu --user-data-dir=~/chromeTemp`

### 2) Launch a localhost server to open the index.html

This app does not launch the server for you, use NPX or Python to view the index.html file. `file://` will not work due to CORS errors.

**For example**

`cd browse-lightshot; npx http-server .` then visit `localhost:8080/index.html`

**or**

`cd browse-lightshot; python -m http.server` then visit `localhost:8000/index.html`

### Screenshot

![Screenshot of app](https://user-images.githubusercontent.com/6013871/71645958-c851f480-2cad-11ea-9a4b-3bc5b5be4cd4.png)
