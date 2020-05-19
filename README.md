# Repx3y2z1
Anaconda3 Spider issue
Problem with running Spider from Anaconda Navigator. Bellow are error messages. Help if you can. Thanks!
Traceback (most recent call last):
File "C:\ProgramData\Anaconda3\Scripts\spyder-script.py", line 6, in 
from spyder.app.start import main
File "C:\ProgramData\Anaconda3\lib\site-packages\spyder\app\start.py", line 22, in 
import zmq
File "C:\Users\Vladimir\AppData\Roaming\Python\Python37\site-packages\zmq\__init__.py", line 47, in 
from zmq import backend
File "C:\Users\Vladimir\AppData\Roaming\Python\Python37\site-packages\zmq\backend\__init__.py", line 40, in 
reraise(*exc_info)
File "C:\Users\Vladimir\AppData\Roaming\Python\Python37\site-packages\zmq\utils\sixcerpt.py", line 34, in reraise
raise value
File "C:\Users\Vladimir\AppData\Roaming\Python\Python37\site-packages\zmq\backend\__init__.py", line 27, in 
_ns = select_backend(first)
File "C:\Users\Vladimir\AppData\Roaming\Python\Python37\site-packages\zmq\backend\select.py", line 28, in select_backend
mod = __import__(name, fromlist=public_api)
File "C:\Users\Vladimir\AppData\Roaming\Python\Python37\site-packages\zmq\backend\cython\__init__.py", line 6, in 
from . import (constants, error, message, context,
ImportError: cannot import name 'constants' from 'zmq.backend.cython' (C:\Users\Vladimir\AppData\Roaming\Python\Python37\site-packages\zmq\backend\cython\__init__.py)
