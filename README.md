# ConsoleMenu
Consolemenu on python 3 with pynput    
Powered by [pynput](https://pypi.org/project/pynput/) and [colorama](https://pypi.org/project/colorama/)
# Description 
Модуль позволяющий сделать меню выбора с помощью стрелок для управления. 
# Pip`s
```
pip install pynput
```
# Code
```Python
import consolemenu

massiv = ['One','Two','Three','Four','Five','Six','Seven','Eight','Nine','Ten']
sel = consolemenu.start(massiv, mode=1, title='Select number')

print('You selected: ' + str(int(sel + 1)))
input()
```
# In console
```
1. One <
2. Two
3. Three

0
```
