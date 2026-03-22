```
class MyBio:
    def __init__(self):
        self.name = "Gavin Qu"
        self.role = ["Data Engineer", "Economics Research", "Analyst", "Curiosity-driven"]
        self.location = ["Seattle"]
        self.languages = ["Python", "R", "Java", "Bash", "SQL"]
        self.interests = ["ML for Economics", "Causal Inference", "Open Source", "Blogging", "Linux"]

    def current_project(self):
        return "Learning Julia"

    def contact(self):
        return {
            "LinkedIn": "linkedin.com/in/gavinqu/"
            "email": "gavinqu dot dev at gmail"
        }

    def about_me(self):
        return """
            Outside of work, you'll often find me hiking, climbing, skiing, and reading Sci-fi. 
        """

bio = MyBio()
print(bio.about_me())
print("Current Project:", bio.current_project())
print("Contact Info:", bio.contact())
```
