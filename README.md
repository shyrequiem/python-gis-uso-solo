# python-gis-uso-solo

Essa aplicação em Python permite o usuário selecionar qualquer município do Brasil, e a partir disso, obter um mapa interativo de uso e ocupação do solo.

##Tecnologias Utilizadas:

- Python
- GeoPandas
- Google Earth Engine
- geemap
- Tkinter (interface gráfica)
- Folium

##Pipeline:

- Seleção de região, estado e município
- Interface gráfica em Tkinter
- Recorte automático do município selecionado
- Download de dados de uso do solo via Google Earth Engine
- Geração de raster (.tif)
- Criação de mapa interativo HTML
- Visualização de uso do solo com legenda

# Como instalar

##Clone o repositório:
```
git clone https://github.com/seuusuario/python-gis-uso-solo.git
```
##Entre na pasta:
```
cd python-gis-uso-solo
```
##Instale as dependências:
```
pip install -r requirements.txt
```

##Executando:

Execute o script:

*python main.py*

##Estrutura do projeto
```
python-gis-uso-solo/
│
├── main.py
├── municipios.shp
├── municipios.dbf
├── municipios.shx
├── README.md
├── requirements.txt
└── output/
    ├── uso_solo.tif
    └── mapa_uso_solo.html
```

# Autor

Desenvolvido por *Alberto Gabriel* para aprendizado em PythonGIS
