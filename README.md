Dockerized M3U8 Proxy

A lightweight proxy server based on Flask and Requests, designed to:

📥 Download and edit .m3u / .m3u8 streams
🔁 Proxy .ts segments, keeping custom headers
🚫 Overcome restrictions like Referer, User-Agent, etc.
🐳 Be easily dockerizable on any machine or server

☁️ Deploy to Render

Go to Projects → Deploy a Web Service → Public Git Repo
Enter the repo: https://github.com/nzo66/tvproxy → Connect
Give it a name of your choice
Set Instance Type to Free
Click on Deploy Web Service

🤗 Deploy to HuggingFace

Remember to do a factory rebuild to update the proxy if there are updates!

Create a new Space
Choose any name and set Docker as type
Leave Public and create the Space
Go to the top right → ⋮ → Files → upload DockerfileHF renaming it Dockerfile
Finally go to ⋮ → Embed this Space to get the Direct URL
