# mininet-fattree

The implementation of a FatTree topology in mininet. 

Start topology with : 

```bash
sudo mn --custom ~/mininet/custom/fattree.py --topo fattree,4 --mac --switch ovsk --link tc --controller remote, ip="your-ip"
```

After the fattree it follows the k-parameter of a FatTree topology, the number of ports per switch.
