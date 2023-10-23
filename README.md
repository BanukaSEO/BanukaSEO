```python
class SoftwareDeveloper:
    def __init__(self):
        self.name = "Banuka Liyanage"
        self.interested_in = ["SEO Tools", "AI Tools"]
        self.skills = ["Python"]
        self.api_experience = ["OpenAI API"]

    def about_me(self):
        return f"Hello, my name is {self.name}. I am a newbie in coding, keen on building {self.interested_in[0]} and {self.interested_in[1]} \
using my {self.skills[0]} skills. I'm experienced in working with {self.api_experience[0]}."

developer = SoftwareDeveloper()
print(developer.about_me())
```
