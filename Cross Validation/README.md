Cross Validation reliable untuk evaluasi training, lebih dari sekedar split biasa yang hanya sekali. Tapi tradeoff nya, dia lambat untuk dataset besar. 

Seberapa lambat? Dan, bagaimana perbandingannya dengan dataset kecil?: 

| Rows | Duration |
| --- | --- |
| 1,000 | 1.34 sec |
| 10,000 | 14.84 sec |
| 50,000 | 79.55 sec |
| 100,000 | 167.82 sec |