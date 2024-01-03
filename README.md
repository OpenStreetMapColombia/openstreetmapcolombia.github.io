# Blog OpenStreetMap Colombia

## Uso diario

Para añadir un nuevo post de entrada, en el directorio `_posts` coloca
tu archivo. Asegurate de que la fecha siga cronología
de forma que quede organizado adecuadamente.

Te invitamos a que consultes las entradas previas para aprender trucos y
hacer tu entrada nueva lo más mejor posible.

Para visualizar la edición de tus documentos puedes ejecutar

```
jekyll serve
```

Puedes usar html al interior de cada uno de los artículos, también
puedes emplear el [formato markdown](http://daringfireball.net/projects/markdown/syntax),
con este se podrán tener más limpios los escritos que hagas.

## Para instalar

```
sudo apt-get install libmagickcore-6.q16-dev libmagickwand-6-headers
gem install bundler
bundle install
```

## Estilo y CSS

Si quieres contribuir con el estilo del sitio vas a usar grunt, primero
debes contar con npm instalado, por ejemplo

```
apt-get install npm
```

en el directorio raíz de este proyecto aplicarás

```
npm install
```

Y para ver los resultados de los archivos de estilo less, puedes usar grunt
para que los compile automáticamente con

```
grunt watch
```
