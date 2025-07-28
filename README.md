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
    - [File I/O](./src/basics/file_io.ipynb)
    - [Functions](./src/basics/functions.ipynb)
    - [Classes](./src/basics/classes.ipynb)
    - [Exceptions](./src/basics/exceptions.ipynb)
- **Graphical user interfaces**
    - [TKinter (modern)](./src/GUI/tkinter.ipynb)
    - [QT](./src/GUI/qt.ipynb)
- **Games and Simulations**
    - [PyGame](./src/games/pygame/pygame.ipynb)
    - [Rendering with OpenGL](./src/rendering/moderngl.ipynb)



