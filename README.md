# Blog OpenStreetMap Colombia

## Uso diario

Para añadir un nuevo post de entrada, en el directorio `_posts` coloque
su archivo, por favor asegure que la fecha esté colocada cronológicamente
de forma que quede organizado adecuadamente.

Le invitamos a que consulte las entradas previas para aprender trucos y
hacer su entrada nueva lo más perfecta posible.

Para visualizar la edición de sus documentos puede ver

```
jekyll serve
```

Puede usar html al interior de cada uno de los artículos, también
puede emplear el [formato markdown](http://daringfireball.net/projects/markdown/syntax),
con este tenderá a tener más limpios los escritos que haga.

## Para instalar

```
sudo apt-get install libmagickcore-6.q16-dev libmagickwand-6-headers
gem install bundler
bundle install
```

## Estilo y CSS

Si usted queire contribuir con el estilo del sitio va a usar grunt, primero
debe contar con npm instalado, por ejemplo

```
apt-get install npm
```

en el directorio raíz de este proyecto aplicará

```
npm install
```

Y para ver los resultados de los archivos de estilo less, puede usar grunt
para que los compile automáticamente con

```
grunt watch
```
