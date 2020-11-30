La medición de la distancia de la estación terrena al satelite se realiza por diferentes métodos, en procedimientos programados por diferentes instituciones, por ejemplo, un recurso común para operadores de sistemas satelitales y aficionados de vigilancia del espacio es [Celestrak](https://celestrak.com), en donde se ofrece la información más actual de las órbitas de los satelites rastreados (satelites en orbitas LEO, MEO y GEO), así como de objetos grandes rastreados por la red de vigilancia del espacio de los Estados Unidos de Norteamérica.

Celestrak ofrece esta información en un formato aceptado universalmente por software de determinación de óribitas, simulación y sistemas de rastreo, al cual se le denomina TLE. Podemos ver un ejemplo de TLE con el satelite Bicentenario:
```
MEXSAT 3                
1 39035U 12075B   20334.51699238 -.00000006  00000-0  00000+0 0  9996
2 39035   0.0213  55.9935 0002143 167.5948 276.6080  1.00272980 29160
```

Este TLE se puede obtener en cualquier momento por medio de la siguiente [liga](https://celestrak.com/satcat/tle.php?CATNR=39035).

Cabe señalar que los TLE obtenidos por medio de Celestrak no siempre serán actuales, ni lo suficientemente precisos para la toma de decisiones dentro de la operación de un sistema satelital, estos son realizados por radar en su mayoria, por la fuerza aeroespacial estadounidense, y aunque estos son suficientemente buenos para identificar, en la mayoria de las situaciones, a cada nave espacial, no constituyen una fuente autoritativa de información para la planeación de operaciones espaciales.

Para obtener valores mas precisos y exactos, debemos estudiar el procedimiento de medición de [[Rango, Acimut y Elevación]] en una estación de control.