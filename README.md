```python
class Maarten(Human):
  def __init__(self) -> None:
    self.alias: str = "citharus"
    self.languages: List[Language] = [Python, CSS3, HTML5]
    self.programms: List[Programm] = [Pycharm, Neovim, Git, Github, Spotify, Linux] 
    self.projects: Dict[str, Projects] = {"active": CPAW, "inactive": Horarium, "archived": WhatShouldIRead}
```
