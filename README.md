```python
class ReadMe:
    def __init__(self, username="pamellabiotec", year=2021):
        self.usuario = pamellbiotec
        self.nome = 'Pâmella Araújo Balcaçar'
        self.escolaridade = {
            'Tecnologia em Informática': ['Faculdades Integradas de Tangará da Serra', 'Tangará da Serra', 'MT'],
            'Ciências Biológicas': ['Universidade Federal de Mato Grosso', 'Rondonópolis', 'MT'],
            'MBA em Perícia, Auditoria e Análise Ambiental': ['Universidade Cândido Mendes', 'Rio de Janeiro', 'RJ']
            'Especialização em Biotecnologia e Bioprocessos': ['Universidade Estadual de Maringá', 'Maringá', 'PR']            
        }
        self.experiencia = {
            'dev': ['Rondonópolis', 'MT'],
            'consultora': ['Rondonópolis','MT'],
            'Professora': ['Secretaria de Educação do Estado de Mato Grosso', 'Rondonópolis', 'MT'],            
        }

    def fazendo(self, agora=2021):
        hoje = self.ano

        if agora = hoje:
            sonho = self.escolaridade['Bioinformática']
            return """
            Atualmente estou aprendendo {codigo} at {intituicao_de_ensino}.
            """.format(codigo=sonho[0], intituicao_de_ensino=sonho[1])

        elif agora > hoje:
            meta = self.experiencia['dev']
            return """
            Eu gostaria de colaborar com {equipe} em {projetos}.
            """.format(equipe=meta[0], projetos='desenvolvimento de software')
        else:
            return """
            ### Eu aqui 👋
            """
        
    def colaboracao(self, funcao, organziacao, localizacao):
        oportunidade = self.experiencia
        oportunidade[funcao] = [organizacao, localizacao]

me = ReadMe(2021)
```

[![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/lhnuwm0kcboyjgi7gytg.png)](https://www.linkedin.com/in/pamellabiotec/)
[![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/r4s2aiy4v39jywj6zh8c.png)](https://dev.to/pamellabiotec)
[![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/uxulcfk3nur9d1ybs9w9.png)](https://twitter.com/pamellabiotec)
