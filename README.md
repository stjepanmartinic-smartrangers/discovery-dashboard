# Salesforce discovery workspace

A local discovery dashboard for a Salesforce consulting partner. The first screen lists every discovery topic. Open a topic to work through its questions, risks, and assumptions. Each item has an answer (for questions), a working note, and a comment thread.

## Published page

https://cdn.jsdelivr.net/gh/stjepanmartinic-smartrangers/discovery-dashboard@main/index.html

That address stays up. It is the `index.html` page. Notes and comments are saved in the browser you use, not on GitHub.

## Run locally

```bash
python3 -m http.server 41731 --bind 127.0.0.1
```

Open http://127.0.0.1:41731/index.html
