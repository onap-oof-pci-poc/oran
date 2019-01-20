# oran

Models of Radio Access Network (RAN) cells in support of a ONAP OOF (ONAP Optimization Framework) and PCI (Physical Cell ID) Optimization. 

## Verification

For yang validation the tool "pyang" is used: https://github.com/mbj4668/pyang.

Usage: 
```
pyang ./yang/standards/*.yang
pyang ./yang/*.yang --path ./yang/standards
pyang ./yang/*.yang --path ./yang/standards --lint (check against RFC 6087)
```