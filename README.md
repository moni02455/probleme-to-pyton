# probleme-to-pyton
Problem after converting a Python file to an exe file
Traceback (most recent call last):
  File "PyInstaller\loader\pyimod03_ctypes.py", line 53, in __init__
  File "ctypes\__init__.py", line 379, in __init__
OSError: [WinError 193] %1 is not a valid Win32 application

The above exception was the direct cause of the following exception:

Traceback (most recent call last):
  File "pyzbar\zbar_library.py", line 58, in load
  File "pyzbar\zbar_library.py", line 51, in load_objects
  File "ctypes\__init__.py", line 460, in LoadLibrary
  File "PyInstaller\loader\pyimod03_ctypes.py", line 55, in __init__
pyimod03_ctypes.install.<locals>.PyInstallerImportError: Failed to load dynlib/dll 'libiconv.dll'. Most likely this dynlib/dll was not found when the application was frozen.

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "PyInstaller\loader\pyimod03_ctypes.py", line 53, in __init__
  File "ctypes\__init__.py", line 379, in __init__
OSError: [WinError 193] %1 is not a valid Win32 application

The above exception was the direct cause of the following exception:

Traceback (most recent call last):
  File "main.py", line 11, in <module>
    from pyzbar.pyzbar import decode  # لاستخراج بيانات QR من الصورة
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "<frozen importlib._bootstrap>", line 1360, in _find_and_load
  File "<frozen importlib._bootstrap>", line 1331, in _find_and_load_unlocked
  File "<frozen importlib._bootstrap>", line 935, in _load_unlocked
  File "PyInstaller\loader\pyimod02_importers.py", line 384, in exec_module
  File "pyzbar\pyzbar.py", line 7, in <module>
  File "<frozen importlib._bootstrap>", line 1360, in _find_and_load
  File "<frozen importlib._bootstrap>", line 1331, in _find_and_load_unlocked
  File "<frozen importlib._bootstrap>", line 935, in _load_unlocked
  File "PyInstaller\loader\pyimod02_importers.py", line 384, in exec_module
  File "pyzbar\wrapper.py", line 151, in <module>
  File "pyzbar\wrapper.py", line 148, in zbar_function
  File "pyzbar\wrapper.py", line 127, in load_libzbar
  File "pyzbar\zbar_library.py", line 60, in load
  File "pyzbar\zbar_library.py", line 51, in load_objects
  File "ctypes\__init__.py", line 460, in LoadLibrary
  File "PyInstaller\loader\pyimod03_ctypes.py", line 55, in __init__
pyimod03_ctypes.install.<locals>.PyInstallerImportError: Failed to load dynlib/dll 'C:\\Users\\ramo\\AppData\\Local\\Temp\\_MEI58362\\libiconv.dll'. Most likely this dynlib/dll was not found when the application was frozen.

