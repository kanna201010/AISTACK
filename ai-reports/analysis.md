{
  "id": 90,
  "code": 1,
  "signal": " ",
  "stdout": "PROJECT=arbitrum_dex_liquidity_monitor\nPYTHON PROJECT DETECTED\nRUNNING PROJECT\nMonitoring Uniswap V3 Pool creations on Arbitrum at 0x1F98431c8aD98523631AE4a59f267346ea31F984",
  "stderr": "Traceback (most recent call last):\n  File \"/home/ubuntu/projects/arbitrum_dex_liquidity_monitor/main.py\", line 30, in <module>\n    monitor_liquidity()\n  File \"/home/ubuntu/projects/arbitrum_dex_liquidity_monitor/main.py\", line 24, in monitor_liquidity\n    event_filter = factory_contract.events.PoolCreated.create_filter(fromBlock=latest_block - 1000)\n                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^\n  File \"/home/ubuntu/projects/arbitrum_dex_liquidity_monitor/venv/lib/python3.12/site-packages/eth_utils/decorators.py\", line 28, in _wrapper\n    return self.method(obj, *args, **kwargs)\n           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^\nTypeError: ContractEvent.create_filter() got an unexpected keyword argument 'fromBlock'",
  "created_at": "2026-06-08T22:59:19.899Z"
}