# Python-Reference

This Project tries to collect some basic and advanced knowledge about Python. From basic syntax, file i/o, it security, networking, GUI and rendering. Python is a awesome language and therefore this repo tries to collect most important knowledge about Python for reference during work and projects.<br>
Of course this repo can't cover everything and the topic artificial intelligence (including plotting and stuff) is intentionally ignored, since I already have an [repo for AI](https://github.com/xXAI-botXx/AI) (also for [PyTorch](https://github.com/xXAI-botXx/PyTorch-Reference) and [TensorFlow](https://github.com/xXAI-botXx/TensorFlow-Reference)).<br>
Also see [the helper repo](https://github.com/xXAI-botXx/Project-Helper) which is kinda the toplevel repo for such reference repos.

This repo consists of multiple notebooks which covers the given topics. The notebooks have the advantage that you can see my results and also provide textual information beside code.

<br><br>

---
### Installation

Python can be installed through the offical website, but I recommend installing and using anaconda, since it manages different Python versions much better. A little tutorial for anaconda can be found here: https://github.com/xXAI-botXx/Project-Helper#anaconda <br>

Your python environment just needs IPython and an ipykernel package through the usage of notebooks.

```bash
conda create -n ref python=3.12 pip -y 
conda activate ref
pip install ipykernel ipython pygame moderngl moderngl-window
```

Documentation/help can be found on the official website https://docs.python.org/3/ or the documentation website of the module/library you use. And which mostlikely works is the built-in function `help`. For example:
```python
print(help(my_module.func))
```

```python
print(help(print))
```

> The outside `print` is not always needed. The help function return a string and therefore it need no print around when using in the interactive mode or in a notebook cell. 

<br><br>

---
### Topics

- **Basics**
    - [Program Execution](./src/basics/execution.ipynb)
    - [Syntax](./src/basics/syntax.ipynb)
    - [Data Types](./src/basics/data_types.ipynb)
    - [Functions (self defined and built-in)](./src/basics/functions.ipynb)
    - [Classes](./src/basics/classes.ipynb)
    - [Exceptions (including Context Managers)](./src/basics/exceptions.ipynb)
    - [File I/O](./src/basics/file_io.ipynb)
    - [Iterators & Generators](./src/basics/iterators_and_generators.ipynb)
- **Standard Library Modules**
    - [Math](./src/standard_lib/math.ipynb)
    - [Cryptography](./src/standard_lib/crypto.ipynb)
    - [Regular Expressions](./src/standard_lib/regular_expressions.ipynb)
    - [OS and Runtime Environment](./src/standard_lib/os_and_runtime.ipynb)
    - [Filesystem](./src/standard_lib/file_system.ipynb)
    - [Commandlineparameter Parsing](./src/standard_lib/commandline_parsing.ipynb)
    - [Parallel Computing](./src/standard_lib/parallel_computing.ipynb)
    - [Data I/O](./src/standard_lib/data_io.ipynb)
    - [Networking](./src/standard_lib/networking.ipynb)
    - [Debugging](./src/standard_lib/debugging.ipynb)
    - [Documentation](./src/standard_lib/documentation.ipynb)
    - [External program calls](./src/standard_lib/subprocess.ipynb)
    - [Python and other languages](./src/standard_lib/other_languages.ipynb)
    - [GUIs with TKinter (modern)](./src/standard_lib/tkinter.ipynb)
    - *... -> are there important missing standard library modules?*
- **Additional (External) Library Modules**
    - [Image Handling via Pillow](./src/standard_lib/pillow.ipynb)
    - [Argumentparsing via PyDantic](./src/standard_lib/pydantic.ipynb)
    - [HTTP interaction with request module](./src/standard_lib/request.ipynb)
    - [Server with Django (or fastapi))](./src/standard_lib/server.ipynb)
    - **Graphical user interfaces**
        - [QT](./src/external_libs/GUI/qt.ipynb)
    - **Games and Simulations**
        - [PyGame](./src/external_libs/games/pygame/pygame.ipynb)
        - [Rendering with OpenGL](./src/external_libs/rendering/moderngl.ipynb)
    - *... -> are there important missing external library modules? (for sure there are much more)*
    - *user input control? (mouse/keyboard)*
    - *Ursina Engine?*
    - *Selenium?*
    - *PyAutoGUI?*
    - > Hint: OpenCV/Numpy/Pandas/Matplotlib/Seaborn/SciPy/PyTorch/TensorFlow... are covered in the [AI repo](https://github.com/xXAI-botXx/AI), (and [PyTorch](https://github.com/xXAI-botXx/PyTorch-Reference), [TensorFlow](https://github.com/xXAI-botXx/TensorFlow-Reference))



