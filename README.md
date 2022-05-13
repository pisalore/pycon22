## pycon22

1. Clone this repo
   ```shell
   git clone git@github.com:pisalore/pycon22.git
   ```

2. Create a `virtualenv`


4. Install [jupyter](https://jupyter.org/install) and [nbconvert](https://pypi.org/project/nbconvert/).
You can use both `pip` or `conda`.


6. Run notebook:
   ```shell
   cd pycon2022/
   jupyter notebook
   ```
7. Convert to slides
    ```shell
   jupyter nbconvert pycon22.ipynb --to slides
   ```