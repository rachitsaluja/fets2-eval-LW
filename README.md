# fets2-eval-LW
Lesionwise eval for Fets

To easily set up the code:

```
conda create --name fets-metrics python=3.11
conda activate fets-metrics
pip install -r requirements.txt
```

To use the code: 

```
from metrics_GLI import *

results_df, _ = = get_LesionWiseResults(pred_file, 
                      gt_file, 
                      "Fets2.0", 
                      output=None)

```

You can add a location of a csv file for saving the output. 

