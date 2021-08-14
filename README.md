- 👋 Hi, I’m @fabber82
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
fabber82/fabber82 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import requests
import json 

tvl_history = requests.get('https://api.defillama.com/protocol/MNE')
tvl_history = positions.json()
latest_tvl = float(positions['tvl'][-1]['totalLiquidityUSD'])
