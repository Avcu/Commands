# Virtual Environment Commands

I prefer handling virtual environments using only **pip**, **venv**. Following are some useful commands on *Linux* and *Windows*.

| Linux Command | Description |
| --- | --- |
| python3 -m venv /path/to/new/virtual/my_env | create a virtual environment called \<my_env\> |
| source my_env/bin/activate | open \<my_env\> virtual environment |
| deactivate | close the current environment |
| pip install -r requirements.txt | install packages from a txt file |

| Windows Command | Description |
| --- | --- |
| c:\Python35\python -m venv c:\path\to\my_env | create a virtual environment called \<my_env\> |
| my_env\Scripts\activate | open \<my_env\> virtual environment |
| deactivate | close the current environment |
| pip install -r requirements.txt | install packages from a txt file |
