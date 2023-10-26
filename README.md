```python
from pedro.barbosa import Developer
from pedro.barbosa.models import History

History.objects.create(company="Napp Solutions", start_date="2020-01-13", end_date=None)

class AboutMe(Developer):
    name = "Pedro Barbosa"
    area = "Backend Developer"
    works_at = "Napp Solutions"
    location = "Brazil"

    def get_short_description(self):
        return "Python Developer with 2+ years experience"

    def get_long_description(self):
        raise NotImplementedError("I'm Think about this") 

class Skills(Developer):
    languages = ["Python" for _ in range(100)]
    libraries = ["pytest", "Pandas", "Django Ninja", "Django Ninja JWT", "Pydantic"]
    frameworks = ["Django", "djangorestframework", "selenium", "Spyder"]
    databases = ["PostgreSQL", "MongoDB", "MySQL"]
    learning = ["Golang", "Javascript", "React"]
```

<p align="left">
  <a href="mailto:pedrohsbarbosa99@gmail.com" alt="Gmail">
  <img src="https://img.shields.io/badge/-Gmail-FF0000?style=flat-square&labelColor=FF0000&logo=gmail&logoColor=white&link=mailto:pedrohsbarbosa99@gmail.com" /></a>

  <a href="https://www.linkedin.com/in/pedro-barbosa-6bb200165/" alt="LinkedIn">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/pedro-barbosa-6bb200165/" /></a>
</p>

<details open>
  <summary>
    <h2>📊 Github Stats and Activity</h2>
  </summary>

  <h3>🔥 Streak Stats</h3>

  <!-- GitHub Readme Streak Stats - https://github.com/PedroHsBarbosa/github-readme-streak-stats -->
  <p>
    <a href="https://github.com/pedrohsbarbosa99/github-readme-streak-stats">
      <img title="🔥 Get streak stats for your profile at git.io/streak-stats" alt="PedroHsBarbosa's streak"
        src="https://github-readme-streak-stats-six-kappa.vercel.app?user=pedrohsbarbosa99&theme=dracula&hide_border=true&exclude_days=Sun" />
    </a>
  </p>

  <h3>💻 GitHub Profile Stats</h3>

  <!-- https://github.com/anuraghazra/github-readme-stats -->


<a href="https://github.com/anuraghazra/github-readme-stats"><img alt="PedroHsBarbosa's Github Stats" src="https://github-readme-stats-tau-eight-87.vercel.app/api/?username=pedrohsbarbosa99&show_icons=true&include_all_commits=true&count_private=true&theme=dracula&hide_border=true&title_color=F85D7F&icon_color=F8D866" height="192px"/></a>
  <a href="https://github.com/anuraghazra/github-readme-stats"><img alt="PedroHsBarbosa's Top Languages" src="https://github-readme-stats-tau-eight-87.vercel.app/api/top-langs/?username=pedrohsbarbosa99&langs_count=8&layout=compact&theme=dracula&hide_border=true&title_color=F85D7F&icon_color=F8D866&exclude_repo=github-readme-streak-stats,github-readme-stats" height="192px"/></a>
  <br/>
  <br />
  <b>Note:</b> Top languages is only a metric of the languages my public code consists of and doesn't reflect experience
  or skill level.
  <br />
  <br />

  <!-- https://github.com/ashutosh00710/github-readme-activity-graph -->

  <a href="https://github.com/ashutosh00710/github-readme-activity-graph"><img alt="PedroHsBarbosa's Activity Graph"
      src="https://github-readme-activity-graph.vercel.app/graph/?username=pedrohsbarbosa99&hide_border=true&theme=dracula&bg_color=282A36" /></a>

</details>
