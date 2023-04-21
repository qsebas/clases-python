| Clase | Ejercicios |
|-------|------------|
|[clase 1 - tipos](https://colab.research.google.com/github/qsebas/clases-python/blob/main/clases/Curso_Python_clase_1.ipynb)|[Ejercicios resueltos Clase 1](https://colab.research.google.com/github/qsebas/clases-python/blob/main/clases/ejercicios_resueltos_clase_1.ipynb)|
|[clase 2 - loops](https://colab.research.google.com/github/qsebas/clases-python/blob/main/clases/Curso_Python_clase_2.ipynb)|     |
|[clase 3 - módulos](https://colab.research.google.com/github/qsebas/clases-python/blob/main/clases/Curso_Python_clase_3.ipynb)|     |

<!--

def ejercicio_1(texto):
  # return ""
  if texto:
    conectores = ["a", "al", "en", "el", "la", "los", "las", "de", "del"]
    acrónimo = "".join([x[0].lower() if x in conectores else x[0].upper() for x in texto.split()])
    return acrónimo[0].upper() + acrónimo[1:]
  else:
    return ""
  

print("Prueba ejercicio 1:", ejercicio_1("volver al futuro"))

def ejercicio_2(numero):
  # return ""
  if numero:
    positivos = [1] + [i for i in range(2, (abs(numero) // 2) + 1) if numero % i == 0] + [abs(numero)]
    result = set()
    for x in positivos:
      result.add(x)
      result.add(-x)
    return result

print("Prueba ejercicio 2:", ejercicio_2(15))

def ejercicio_3(lista):
  # return (None, None)
  return [(e, lista.count(e)) for e in {x for x in lista }]

print("Prueba ejercicio 3:", ejercicio_3([3, 4, 3]))


def ejercicio_4(lista):
  # return (None, None)
  from functools import reduce
  return reduce(lambda x, y: (y if x[0] is None else max(x[0], y), y if x[1] is None else min(x[1], y)), lista, (None, None))

print("Prueba ejercicio 4:", ejercicio_4([44, -33, 11, 22, 0, 42, 47, 12, 14]))

-->

