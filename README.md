# INICIALIZACION DE PROYECTO EN REACT NATIVE
```
npx react-native init AwesomeTSProject --template react-native-template-typescript
```

# Configuracion extra para los hooks
La forma más rápida de quitar el warn, es añadir en la línea anterior a la violación:
Esto solo afecta a la línea siguiente, no a todo el proyecto.

```
eslint-disable-next-line react-hooks/exhaustive-deps.
```

Para cambiar la configuración global, en el archivo de configuración, añadir en las rules del overrides: 
```
"react-hooks/exhaustive-deps": "off".
```
