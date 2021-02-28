```python
from typing import List, Dict

from hobbies import Hobby, Calisthenics, Programming, CSGO
from languages import Language ,Python, CSS3, HTML5, Markdown
from programms import Programm, Pycharm, Neovim, Git, GitHub, Spotify, Linux
from projects.github import Project, CPAW, Horarium, WhatShouldIRead, Dotfiles

class Maarten(Human):
  def __init__(self) -> None:
    self.alias: str = "citharus"
    self.hobbies: List[Hobby] = [Calisthenics, Programming, CSGO]
    self.languages: List[Language] = [Python, CSS3, HTML5, Markdown]
    self.programms: List[Programm] = [Pycharm, Neovim, Git, GitHub, Spotify, Linux] 
    self.projects: Dict[str, Projects] = {"active": CPAW, "inactive": Horarium, Dotfiles "archived": WhatShouldIRead}
```
