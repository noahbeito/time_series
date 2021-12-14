![timeseries](https://blog.glugmvit.com/assets/images/time_series/cover.jpg)
# time_series
Analyzing a possible correlation between search traffic and stock prices using time series models and Facebook Prophet.
---
## Technologies
This analysis leverages python 3.7 with the following packages and libraries:
* [pandas](https://github.com/pandas-dev/pandas)
* [holoviews](https://holoviews.org/)
* [fbprophet](https://facebook.github.io/prophet/)
* [hvplot](https://github.com/holoviz/hvplot)
* [matplotlib](https://matplotlib.org/)

---
## Installations
```python
# Install the required libraries
from IPython.display import clear_output
try:
  !pip install pystan
  !pip install fbprophet
  !pip install hvplot
  !pip install holoviews
except:
  print("Error installing libraries")
finally:
  clear_output()
  print('Libraries successfully installed')
```

```python
#import the required libraries and dependencies
import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
```
---
## Contributors
[Noah Beito](https://www.linkedin.com/in/noah-beito/)
---
## License
[MIT](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)
