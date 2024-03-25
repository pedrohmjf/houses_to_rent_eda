# Análise Exploratória de Casas Para Alugar
Este notebook tem como objetivo realizar uma análise exploratória dos dados de casas para alugar no Brasil e, com isso, verificar as relações existentes entre os diferentes valores (aluguel, conodomínio, seguro incêndio e IPTU) e como as outras variáveis do dataset influenciam nesses números. Além disso, serão feitas outras verificações, como as cidades mais caras e mais baratas para se viver.

Os dados foram obtidos com um web crawler (o site não foi especificado) e são de 2020. Por isso, esta EDA têm um objetivo estritamente de aprendizado, pois não se sabe se os dados são confiáveis (o crawler está sujeito a erros e, como veremos adiante, existem muitos outliers nos dados) ou se estão atualizados.

Esperamos, ao final da análise, entender melhor como cada característica de um imóvel influencia em seus preços de aluguel, condomínio, IPTU e seguro incêndio, bem como saber quais são as características que mais aparecem nos imóveis.

O dataset pode ser encontrado no link a seguir: https://www.kaggle.com/datasets/rubenssjr/brasilian-houses-to-rent

Algumas das perguntas que foram respondidas nesta EDA são:
- Qual cidade é mais cara para se viver?
- Qual cidade oferece mais imoveis para alugar, proporcionalmente ao numero de habitantes?
- Existe correlação entre as diversas características dos imóveis e o seu preço de aluguel?
