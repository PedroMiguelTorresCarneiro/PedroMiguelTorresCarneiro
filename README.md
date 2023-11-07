```python
  class SoftwareEngineerInTraining:
  
      def __init__(self):
          self.name = "Pedro Carneiro"
          self.role = "SoftwareEngineer In Training"
          self.languages_spoken = ["pt_PT", "en_US"]
          self.location = "Aveiro, Portugal"
          self.alma_mater = "Universidade de Aveiro"
          self.interests = ["Java", "AI", "Data Science", "Python", "Flask", "IT Management"]
  
      def greet(self):
          greetings = [
              f"Hello, I'm {self.name} and I'm crafting my path towards becoming a {self.role}.",
              f"Originally from Vila Nova de Famalicão, I've found a second home amidst the tech vibrancy of {self.location}.",
              f"At {self.alma_mater}, I'm merging theory with practice, preparing to innovate in Computer Science.",
              f"My interests span from {', '.join(self.interests[:-1])}, to {self.interests[-1]}.",
              "Driven by technology, I am on a quest to leave a digital footprint that resonates with progress and purpose."
          ]
          return "\n".join(greetings)
  
      def say_hi(self):
          print(self.greet())
  
  me = SoftwareEngineerInTraining()
  me.say_hi()
```
---
## <span style="color: #e67e22;">Brief Presentation</span>

 - From an early age, my pursuit has been to excel both personally and professionally. This drive has led me to diverse roles across different sectors, from hospitality to retail and notably, technology. Working in various capacities has granted me invaluable, multifaceted insights and honed a wide array of skills, including teamwork, responsibility, and dedication.

- However, the core of my ambition has always revolved around technology and engineering. My academic background in Computer Technology at Universidade de Aveiro and my professional experience in IT sales and troubleshooting have cemented this focus. In fact, the skills I've gained from non-tech roles have been instrumental in shaping a holistic understanding of technology's impact on various aspects of life and business.

- As I continue my journey toward becoming a professional IT engineer, my objective is to bring a unique blend of technical acumen and people skills to a forward-thinking tech startup. I am particularly interested in Java development, having achieved certification in the field, and am eager to contribute to innovative projects that challenge the status quo.

## In a nutshell, I don't see my varied experience as a detour but as a foundation that enriches my contributions to the tech industry. I am committed to leveraging this diverse skill set to achieve my ultimate goal: making impactful contributions to the world of technology.
