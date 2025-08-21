---
## 👋 Hii, I’m VISHNU A, Welcome to my GitHub Profile
![Profile Views](https://envs.sh/F52.jpg)
![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=𝗪𝗘𝗟𝗖𝗢𝗠𝗘𝗧𝗢+𝙑𝙄𝙎𝙃𝙉𝙐-𝘼!;𝗖𝗥𝗘𝗔𝗧𝗘𝗗+𝗕𝗬+𝗧𝗘𝗔𝗠+𝙑𝙄𝙎𝙃𝙉𝙐-𝘼!;𝗜𝗔𝗠+𝗔+𝗦𝗜𝗠𝗣𝗟𝗘+𝗧𝗚+𝗗𝗘𝗩𝗢𝗟𝗣𝗘𝗥+𝗕𝗢𝗧!)</p>
[![Sparkline](https://stars.medv.io/MrMKN/PROFESSOR-BOT.svg)](https://stars.medv.io/MrMKN/PROFESSOR-BOT)

<p align="left">
𝚂𝚘𝚖𝚎 𝙿𝚛𝚒𝚟𝚊𝚝𝚎 𝚂𝚙𝚊𝚌𝚎
<p align="left">
• 𝙼𝚢 𝙽𝚊𝚖𝚎 : 𝙑𝙄𝙎𝙃𝙉𝙐 😉
<p align="left">
• 𝙰𝚐𝚎 : 17
<p align="left">
• 𝙿𝚕𝚊𝚌𝚎 : Calicut
<p align="left">
• 𝙻𝚊𝚗𝚐𝚞𝚊𝚐𝚎 : 𝙼𝚊𝚕𝚊𝚢𝚊𝚕𝚊𝚖
<p align="left">
• 𝚆𝚘𝚛𝚔 : 𝚂𝚝𝚞𝚍𝚢𝚒𝚗𝚐 𝙸𝚗 PLUS TWO
<p align="left">
- 𝗠𝗢𝗦𝗧 𝗔𝗖𝗧𝗜𝗩𝗘 𝗢𝗡 𝗧𝗘𝗟𝗘𝗚𝗥𝗔𝗠 @𝗩𝗜𝗦_𝗛𝗡𝗨_𝗕𝗢𝗧 🔥 
  
☎️ **Contect Here**

<a href="https://telegram.dog/vis_hnu_"><img alt="telegram" src="https://img.shields.io/badge/Telegram-%22B1B17.svg?&logo=telegram&logoColor=white"></a>
  
  
| 𝙀𝙢𝙤𝙟𝙞 | 𝘿𝙚𝙩𝙖𝙞𝙡𝙨 | 𝙄𝙣𝙛𝙤 |
| ---- | ---- | ---- |
| 🤵 | 𝙉𝙖𝙢𝙚 | 𝙑𝙞𝙨𝙝𝙣𝙪 |
|  📆 | 𝘼𝙜𝙚| 🔞 |
| 🏞️ | 𝙋𝙡𝙖𝙘𝙚 | 𝙆𝙚𝙧𝙖𝙡𝙖 𝘾𝙖𝙡𝙞𝙘𝙪𝙩 |
| 📣 | 𝙇𝙖𝙣𝙜𝙪𝙖𝙜𝙚 | 𝙈𝙖𝙡𝙖𝙮𝙖𝙡𝙖𝙢 |
# My Social Profiles


import random
from datetime import datetime

quotes = [
    "Dream big, work hard, stay humble.",
    "Code is like humor. When you have to explain it, it’s bad.",
    "Keep pushing forward, success is near!",
    "Eat, Sleep, Code, Repeat."
]

today_quote = random.choice(quotes)

with open("README.md", "r", encoding="utf-8") as f:
    content = f.read()

start_tag = "<!-- QUOTE-START -->"
end_tag = "<!-- QUOTE-END -->"

new_content = content.split(start_tag)[0] + start_tag + "\n" + today_quote + "\n" + end_tag + content.split(end_tag)[1]

with open("README.md", "w", encoding="utf-8") as f:
    f.write(new_content)

print(f"Updated README with quote: {today_quote}")
