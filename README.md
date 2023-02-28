# SourceGraphExtractor

`AutoExtractGraph.py`
* All functions in the smart contract code are automatically split and stored.
* Find the relationships between functions.
* Extract all smart contracts source code into the corresponding contract graph consisting of nodes and edges.
```shell
python3 AutoExtractGraph.py
```

`graph2vec.py`
* Feature ablation.
* Convert contract graph into vectors.
```shell
python3 graph2vec.py
```
