---
# obsidian-jupyter: 
#   interpreter: interpreter-path 
---

# Jupyter example


It's possible to write contents just like you would in a markdown cell, but without needing specific cells for it.

To add code cells, you need to use a codeblock with the `jupyter` language:

````
```jupyter
import numpy as np
from matplotlib import pyplot as plt

x = np.linspace(0,1)
y = np.exp(-x) * np.sin(4 * np.pi * x)
plt.plot(x,y)
pass # required by the plugin?

```
````

The plugin only works in Reading view right now, so before pressing the <kbd>Run</kbd> button, switch to reading view by clicking on the text in the status bar or on the button at the top right of this note:

```jupyter
import numpy as np
from matplotlib import pyplot as plt

x = np.linspace(0,1)
y = np.exp(-x) * np.sin(4 * np.pi * x)
plt.plot(x,y)
pass # required by the plugin?

```

If you are using a virtual environment, you can specify its path in the frontmatter of this note (check at the top).