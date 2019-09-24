# graph-comb-pg
```
python train with device=$DEVICE tag=$EXPERIMENT_NAME
```

# Evaluation
```
python evaluate.py with device=3 generalize=False base_net_class=GraphConvNet num_layers=6 tag=\"20190829-deep\"  
python evaluate.py with device=3 generalize=False base_net_class=GraphConvNet hidden_dim=256 tag=\"20190829-ent-wide\"  
python evlauate.py with device=3 generalize=False base_net_class=GraphConvNet num_layers=6 hidden_dim=256 tag=\"20190829-ent-wide-deep\"
python evaluate.py with device=3 generalize=False base_net_class=GraphConvNet tag=\"20190829-baseline\"  
```
