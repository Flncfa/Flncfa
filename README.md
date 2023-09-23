- 👋 Hi, I’m @Flncfa
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Flncfa/Flncfa is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import trio
import httpx

from holehe.modules.social_media.snapchat import snapchat


async def main():
    email = "camillefolin@gmail.com"
    out = []
    client = ()

    await snapchat(email, client, out)

    print(out)
    await client.aclose()

trio.run(main)
