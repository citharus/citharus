```python
class Maarten(Human):
  def __init__(self) -> None:
    self.alias: str = "citharus"
    self.hobbies: List[Hobby] = [Calisthenics, Programming, CSGO]
    self.languages: List[Language] = [Python, CSS3, HTML5, Markdown]
    self.programms: List[Program] = [Pycharm, Neovim, Git, GitHub, Spotify, Linux] 
    self.projects: Dict[str, Project] = {"active": CPAW, 
                                         "inactive": Horarium, Dotfiles, 
                                         "archived": WhatShouldIRead}
```
