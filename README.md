# postgresql

# Important commands:
### Import SQL dump on windows (SQL text content)
```
type dump.sql | pgsql --USERNAME="username" dbname (leave dbname out if dbname fails)
```

# python anaconda:
### Activate the new environment: 
``` conda activate myenv. ```
### Verify that the new environment was installed correctly: 
```conda env list. ```

# install postgres connectivty
Install a pip package in the current Jupyter kernel
```
import sys
!{sys.executable} -m pip install psycopg2
```
