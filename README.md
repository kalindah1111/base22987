# base22987
Building a Simple TPS Estimator
block = w3.eth.get_block("latest")
interval = 2
tps = len(block.transactions) / interval
print("Estimated TPS:", tps)
