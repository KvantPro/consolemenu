# ConsoleMenu
Consolemenu on python 3 with pynput    
Powered by [pynput](https://pypi.org/project/pynput/)
# Description 
Модуль позволяющий сделать меню выбора с помощью стрелок для управления. 
# Pip`s
```
pip install pynput
```
# Code
```Python
import consolemenu

selection = consolemenu.start(['One','Two','Three'])
print(selection)

```
# In console
```
1. One <
2. Two
3. Three

0
```
