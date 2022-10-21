# Intermediate Social Media Analysis

This repository contains materials from the Intermediate training on Social Media Analytics in Crisis Contexts run from November x through December x.  

## Organizers

This training is organized by [UNDP SURGE Data Hub](link). [UNDP Crisis Risk and Early Warning](link), and [QCRI](link) 

## Python Dependencies

If you are running the notebooks in Google Colab, you will need to create a new cell in the notebook
with the following content:

```
from pathlib import Path
requirements = Path.cwd().parent.parent / 'binder' / 'requirements.txt'

!pip install -r $requirements
```

In order to run the exercise notebooks, you will need to have have Python 3.x installed. You will also
need to install some Python dependencies. 

If you are running the notebooks on your local computer, go to the project root and run:

```
pip install -r requirements_dev.txt
```

> **Windows Users**
> 
>
