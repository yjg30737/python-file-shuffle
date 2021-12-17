# python-file-shuffle
Shuffle files' name with Python

## Setup
```pip3 install git+https://github.com/yjg30737/python-file-shuffle.git```

## Example
```python
from python_file_shuffle import shuffle_file

shuffle_file('src', 'dst')
# src is directory that contains files to shuffle
# dst is directory that shuffled files are supposed to be. The fact that it exists or not doesn't matter.
```

Result

Original files

![image](https://user-images.githubusercontent.com/55078043/146478619-ec8cab0e-32db-498e-96b1-4881cad87d7e.png)

New files

![image](https://user-images.githubusercontent.com/55078043/146478690-93741aba-c794-4315-9a7b-d8acf7c62a3b.png)

You can clearly see that files' name were modified. by the way, original files are remained in src directory also.



