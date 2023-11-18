# Hi, I'm Sérgio Matias 👋

[![GitHub followers](https://img.shields.io/github/followers/chiefmatias?style=social)](https://github.com/chiefmatias)

## About Me

I've always been a problem-solver, and I believe that software development is the perfect outlet for my curiosity and creativity. I love the process of breaking down complex problems into smaller, more manageable pieces and working to find the best solution.

```python
import builtins
import random

def random_exception():
    exceptions = [exc for exc in vars(builtins).values() if isinstance(exc, type) and issubclass(exc, BaseException)]

    chosen_exception = random.choice(exceptions)

    raise chosen_exception

if __name__ == "__main__":
    random_exception()
```
