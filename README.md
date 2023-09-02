# SnakeGame practice

-   Create new conda environment for python3.9 and check [requirements.txt](https://raw.githubusercontent.com/ElevnLi/SnakeGame15/master/requirements.txt) to install packages. <br/>
    `Make sure the Python and pip are set to 3.9 if you have installed multiple python versions. You may also check .bash_profile to see if you have set some alias.`

```zsh
conda create -n snake python=3.9
conda activate snake
pip install -r requirements.txt
```

-   Feature: OOP in Python -> Create 3 classes, including Fruit, Snake, and SnakeGame. The key function is draw() in SnakeGame class.