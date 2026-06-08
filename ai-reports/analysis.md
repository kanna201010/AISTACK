{
  "id": 92,
  "code": 1,
  "signal": " ",
  "stdout": "PROJECT=arbitrum_liquidity_monitor\nPYTHON PROJECT DETECTED\nRUNNING PROJECT",
  "stderr": "Traceback (most recent call last):\n  File \"/home/ubuntu/projects/arbitrum_liquidity_monitor/main.py\", line 9, in <module>\n    FACTORY_ABI = json.dumps([{\"anonymous\":false,\"inputs\":[{\"indexed\":true,\"internalType\":\"address\",\"name\":\"token0\",\"type\":\"address\"},{\"indexed\":true,\"internalType\":\"address\",\"name\":\"token1\",\"type\":\"address\"},{\"indexed\":true,\"internalType\":\"uint24\",\"name\":\"fee\",\"type\":\"uint24\"},{\"indexed\":{\"internalType\":\"int24\",\"name\":\"tickSpacing\",\"type\":\"int24\"},\"name\":\"tickSpacing\",\"type\":\"int24\"},{\"indexed\":false,\"internalType\":\"address\",\"name\":\"pool\",\"type\":\"address\"}],\"name\":\"PoolCreated\",\"type\":\"event\"}])\n                                           ^^^^^\nNameError: name 'false' is not defined. Did you mean: 'False'?",
  "created_at": "2026-06-08T23:02:17.638Z"
}