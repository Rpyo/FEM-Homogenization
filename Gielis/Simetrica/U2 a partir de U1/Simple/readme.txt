Esta es una modificación del programa original donde se asume una simetría por reflexión a la recta y=x. 
Basicamente lo que se hace es tomar (*) u2(x,y)=u1(y,x)
Resultado: 
- Se reducen los cálculos a la mitad con tiempos de ejecución menores al 50% del programa original y requerimiento de recursos en 50-55% del programa original
- Mucho más inestable, debido a la no simetría de la maya aparecen errores en la transcripción de (*) [coeficientes que se suponen iguales y en el original lo son dejan de serlo]
-- Los mallados más finos evitan este problema pero se pierde el sentido de optimización esperado.