# To launch
# curl "localhost:5000/txion" \
#      -H "Content-Type: application/json" \
#      -d '{"from": "akjflw", "to":"fjlakdj", "amount": 3}'
     
# curl localhost:5000/mine
# Output:
# {
#   "index": 2,
#   "data": {
#     "transactions": [
#       {
#         "to": "fjlakdj",
#         "amount": 3,
#         "from": "akjflw"
#       },
#       {
#         "to": "q3nf394hjg-random-miner-address-34nf3i4nflkn3oi",
#         "amount": 1,
#         "from": "network"
#       }
#     ],
#     "proof-of-work": 36
#   },
#   "hash": "151edd3ef6af2e7eb8272245cb8ea91b4ecfc3e60af22d8518ef0bba8b4a6b18",
#   "timestamp": "2017-07-23 11:23:10.140996"
# }
