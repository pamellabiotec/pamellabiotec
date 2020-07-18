```python
class ReadMe:
    def __init__(self, username="pamellabiotec", year=2020):
        self.username = username
        self.name = 'Pâmella Araújo Balcaçar'
        self.education = {
            'Tecnologia em Informática': ['Faculdades Integradas de Tangará da Serra'],
            'Ciências Biológicas': ['Universidade Federal de Mato Grosso'],
            'MBA em Perícia, Auditoria e Análise Ambiental': ['Universidade Cândido Mendes']
            'Especialização em Biotecnologia e Bioprocessos': ['Universidade Estadual de Maringá']            
        }
        self.employment = {
            'developer': ['company', 'city'],
            'consultora': ['Rondonópolis'],
            'Professora': ['Secretaria de Educação do Estado de Mato Grosso'],            
        }

    def doing(self, now=2020):
        today = self.year

        if now = today:
            dream = self.education['Bioinformática']
            return """
            I am currently learning {code} at {code_institute}.
            """.format(code=dream[0], code_institute=dream[1])

        elif now > today:
            goal = self.employment['developer']
            return """
            I am eager to collaborate with {teams} on {projects}.
            """.format(teams=goal[0], projects='software development')
        else:
            return """
            ### Hi there 👋
            """
        
    def collaborate(self, role, organization, location):
        opportunity = self.employment
        opportunity[role] = [organization, location]

me = ReadMe(2020)
```

[![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/lhnuwm0kcboyjgi7gytg.png)](https://www.linkedin.com/in/pamellabiotec/)
[![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/r4s2aiy4v39jywj6zh8c.png)](https://dev.to/pamellabiotec)
[![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/uxulcfk3nur9d1ybs9w9.png)](https://twitter.com/pamellabiotec)
