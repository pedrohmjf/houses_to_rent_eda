# Análise Exploratória de Casas Para Alugar

## Introdução

Este notebook tem como objetivo realizar uma análise exploratória dos dados de casas para alugar no Brasil e, com isso, verificar as relações existentes entre os diferentes valores (aluguel, conodomínio, seguro incêndio e IPTU) e como as outras variáveis do dataset influenciam nesses números. Além disso, serão feitas outras verificações, como as cidades mais caras e mais baratas para se viver.

Os dados foram obtidos com um web crawler (o site não foi especificado) e são de 2020. Por isso, esta EDA têm um objetivo estritamente de aprendizado, pois não se sabe se os dados são confiáveis (o crawler está sujeito a erros e, como veremos adiante, existem muitos outliers nos dados) ou se estão atualizados.

Esperamos, ao final da análise, entender melhor como cada característica de um imóvel influencia em seus preços de aluguel, condomínio, IPTU e seguro incêndio, bem como saber quais são as características que mais aparecem nos imóveis.

O dataset pode ser encontrado no link a seguir: https://www.kaggle.com/datasets/rubenssjr/brasilian-houses-to-rent

Algumas das perguntas que foram respondidas nesta EDA são:
- Qual cidade é mais cara para se viver?
- Qual cidade oferece mais imoveis para alugar, proporcionalmente ao numero de habitantes?
- Existe correlação entre as diversas características dos imóveis e o seu preço de aluguel?

## Exemplos

A título de exemplo, para a resposta da primeira pergunta apresentada anteriormente, o seguinte gráfico foi gerado:

![grafico_custos](https://github.com/pedrohmjf/houses_to_rent_eda/assets/126244260/72160c50-41fc-4c27-907d-9ff67e535998)

Para a análise completa e outros gráficos, sugiro a leitura do notebook que está nesse repositório.

## Conclusões

As conclusões a que chegamos ao fim da análise foram:
- A cidade de São Paulo possui os alugueis mais caros dentre as cidades apresentadas. Porém, Belo Horizonte acaba tendo um custo maior por ter o valor do condomínio mais alto;
- A cidade mais barata para se viver é Porto Alegre. Entretanto, Campinas não é tão mais cara e fica perto da cidade mais rica e desenvolvida do país, podendo ser uma boa opção para se viver dependendo da situação e dos objetivos de cada pessoa;
- São Paulo tem a maior quantidade bruta de imóveis para alugar. Todavia, proporcinalmente à quantidade de habitantes, São Paulo é a terceira cidade com menos oferta;
- A maioria dos imóveis possui de 1 a 3 quartos, sendo que a oferta de opções com mais cômodos do que isso diminui significativamente;
- É mais fácil encontrar imóveis que aceitam animais do que imóveis que não aceitam. Também existem bem mais imóveis não mobiliados do que mobiliados;
- O que mais encarece o aluguel dos imoveis são a quantidade de quartos e de banheiros (mais do que a area);
- Imoveis mobiliados tem um aluguel mais caro do que imoveis não mobiliados, em media (cerca de R$ 1000,00 de diferença). Se a pessoa planeja ficar muito tempo no imovel, talvez compense alugar um não mobiliado e usar a diferença para pagar a mobilia, que será quitada no medio prazo, enquanto a diferença no aluguel sera paga permanentemente;
- Existe uma diferença significativa entre o aluguel de imoveis com até 3 qaurtos e aqueles com mais quartos, mas essa diferença não é tão relevante quando comparamos entre os imoveis com mais que 3 quartos.
