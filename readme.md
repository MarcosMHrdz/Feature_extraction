![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Laboratorio | Extracción de características

Para esta práctica de laboratorio, usaremos el mismo conjunto de datos que usamos en las prácticas de laboratorio anteriores. Recomendamos usar el mismo cuaderno, ya que reutilizará las mismas variables que creó y usó anteriormente en los laboratorios.

### Instrucciones

1. Abra la variable `categoricals` que creamos antes.

```pitón
categóricos = data.select_dtypes(np.object)
categóricos.head()
```

2. Trazar todas las variables categóricas con el gráfico adecuado. ¿Que puedes ver?
3. Puede haber algunas columnas que parezcan redundantes; verifique sus valores para estar seguro. ¿Qué debemos hacer con ellos?
4. Trazar la variable tiempo. ¿Puedes extraer algo de él?