```python
import os
import sys
import traceback
import unittest

# appendでもいけそうな気はする
sys.path.insert(0, os.path.abspath(os.path.join(os.path.dirname(__file__), '..')))

from MY_PACKAGE.hoge import HogeClass
```
