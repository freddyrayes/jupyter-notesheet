## creating tables in jupyter
* https://stackoverflow.com/questions/35160256/how-do-i-output-lists-as-a-table-in-jupyter-notebook


## displaying a map with coordinates
* Use mplleaflet
* https://forum.openstreetmap.org/viewtopic.php?id=66607


## convert mdf file to pandas data frame
* using the asammdf library
``` 
from asammdf import MDF
mdf_obj = MDF('file.mf4')
df = mdf_obj.to_dataframe()
```
