# Prophet Remodel
Repositório para armazenar o que foi uma tentativa de replicar a performance da biblioteca Prophet no Python partindo da referência do próprio paper de publicação do modelo
https://facebook.github.io/prophet/static/prophet_paper_20170113.pdf?utm_source=chatgpt.com

Minha maior motivação foi, bom, meu interesse por séries temporais e o interesse de meus colega no Núcleo de Economia computacional e Finanças da Liga de IA Mackenzie (Mack IA)

De forma geral, o projeto esclareceu o funcionamento do Prophet para séries temporais e evidenciou alguns problemas (já conhecidos) da biblioteca; como o fato de que ele não tem em sua composição qualquer fator autorregressivo, deixando a pedição da tendência da série somente a critério da última tendência traçada.
Para futuros projetos, tentarei implementar regessores AR e traçar comparações com modelos de séries temporais tradicionais, comparando as diferentes performance, especialmente para séries cujas tendências são menos regulares
