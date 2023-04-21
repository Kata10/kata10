### Hi there 👋

<!--
**Kata10/kata10** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## Hi, I'm Henry!

```python

class HenrySuarez:
    def __init__(self, username='kata10'):
        self.username = username
        self.name = 'Henry Suarez'
        self.education = {
            'programming': {'Deep Learning': 'AI Saturdays', 'Bootcamp IA': 'Factoria F5'},
            'history': {'MSC in Contemporary Latin America History': 'Universidad Central de Venezuela'}
        }
        self.profile = ['Artificial Intelligence Developer', 'Data Scientist', 'Data Analyst']
        self.tools = ['Python', 'VS Code', 'Jupyter']
        self.certification = ['Scrum', 'AI-900 Fundamentals']
        self.linkedin = 'https://www.linkedin.com/in/henry-su%C3%A1rez-b60419256/'

    def presentation(self):
        print(f"Hi there! I'm {self.name} and I have the {self.certification[0]} certification from SCRUMstudy and {self.certification[1]} certification from Microsoft.")
        print(f"I have studied the following topics in programming:")
        for topic, course in self.education['programming'].items():
            print(f"- {topic}: {course}")
        print(f"I also have a degree in {list(self.education['history'].keys())[0]}.")
        print(f"My profile includes {self.profile[0]}, {self.profile[1]} and {self.profile[2]}.")
        print("I work with the following tools:")

        for tool in self.tools:
            print(f"- {tool}")

        print(f"You can find me on LinkedIn: {self.linkedin}")

my_profile = HenrySuarez()
my_profile.presentation()

```

## Get in touch

- Linkedin: @henrysuarez
