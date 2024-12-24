<h1 align="center">Hey there 👋, I'm Saeed!</h1>


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
