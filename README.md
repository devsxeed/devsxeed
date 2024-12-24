<h1 align="center">Hey there 👋, I'm Saeed!</h1>

<p align="center">
    <a href="https://hits.seeyoufarm.com">
        <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fdevsxeed&count_bg=%2322AA55&title_bg=%232D2D2D&icon=github.svg&icon_color=%23E7E7E7&title=Views+%28Day+%2F+All%29&edge_flat=false" />
    </a>
    <a href="https://github.com/STRRL/serverless-github-badges">
        <img src="https://badges.strrl.dev/years/devsxeed?style=flat&labelColor=333333&logoColor=E7E7E7&color=0089FF&label=Years&logo=github" />
    </a>
    <a href="https://github.com/devsxeed?tab=followers">
        <img src="https://img.shields.io/github/followers/devsxeed?style=flat&labelColor=333333&logoColor=E7E7E7&color=8939FF&label=Followers&logo=github" />
    </a>
    <a href="#">
        <img src="https://img.shields.io/github/stars/devsxeed?style=flat&affiliations=OWNER%2CCOLLABORATOR&labelColor=333333&logoColor=E7E7E7&color=EEAA00&label=Stars&logo=github" />
    </a>
    <br />
    <a href="https://github.com/STRRL/serverless-github-badges">
        <img src="https://badges.strrl.dev/contributions/yearly/devsxeed?style=flat&labelColor=333333&logoColor=E7E7E7&color=BA4AB9&label=Yearly%20Contributions&logo=github" />
    </a>
    <a href="https://github.com/STRRL/serverless-github-badges">
        <img src="https://badges.strrl.dev/contributions/all/devsxeed?style=flat&labelColor=333333&logoColor=E7E7E7&color=E96F24&label=All%20Contributions&logo=github" />
    </a>
</p>

```py
from datetime import date

class AboutMe():
    def __init__(self):
        self.username = "devsxeed"
        self.pronouns = ("he", "him")
        self.location = "Iran"
        self.occupation = "Computer Engineering Student"
        self.birthday = date(day=6, month=3, year=2004)
        self.age = (date.today()-self.birthday).days/365  # 20 y/o
        self.hobbies = ["Coding", "Gaming", "Music", "YouTube"]
        self.interests = ["Programming", "Security", "Linux"]

if __name__ == "__main__":
    me = AboutMe()
```
