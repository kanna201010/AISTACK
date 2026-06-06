{
  "id": 50,
  "code": 0,
  "signal": " ",
  "stdout": "Connected to: https://billowing-greatest-aura.arbitrum-mainnet.quiknode.pro/...\n/home/ubuntu/projects/environment_fix\ntotal 16\ndrwxrwxr-x  2 ubuntu ubuntu 4096 Jun  6 21:35 .\ndrwxrwxr-x 27 ubuntu ubuntu 4096 Jun  6 21:35 ..\n-rw-rw-r--  1 ubuntu ubuntu  171 Jun  6 21:35 main.py\n-rw-rw-r--  1 ubuntu ubuntu   44 Jun  6 21:35 requirements.txt\nimport os\n\nRPC_URL = os.getenv(\"RPC_URL\") or os.getenv(\"QUICKNODE_RPC_URL\")\n\nif not RPC_URL:\n    raise ValueError(\"RPC_URL is not set\")\n\nprint(f\"Connected to: {RPC_URL}\")\nConnected to: https://billowing-greatest-aura.arbitrum-mainnet.quiknode.pro/...",
  "stderr": "",
  "created_at": "2026-06-06T21:47:54.298Z"
}