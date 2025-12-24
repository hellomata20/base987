# base987
Building a Daily Summary Report
summary = {
    "block": w3.eth.block_number,
    "gas": w3.eth.gas_price,
    "txs": len(w3.eth.get_block("latest").transactions)
}
print(summary)
