#Fractal de Lorenz

Se tomo las ecuaciones diferenciales del caos de Lorenz

```
Ecuaciones originales
	dx/dt = G(y - x)
	dy/dt = Rx - y - xz
	dz/dt = xy - Bz
```
```
Ecuaciones usadas en el programa
	dx = (G(y - x)) . dt
	dy = (Rx - y - xz) . dt
	dz = (xy - Bz) . dt
```

Para la generacion del fractal se inicia en el punto (1, 1, 1)
y se desplaza conforme los valores dx, dy, y dz se van actualizando



Puedes encontrar informacion sobre la libreria p5 en la siguiente pagina
https://p5js.org