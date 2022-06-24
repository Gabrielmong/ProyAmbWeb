# Proyecto final de Ambiente Web Cliente Servidor
![Triangulito](https://c.tenor.com/ezAOf1ODa80AAAAC/eskaymagico-triangulo.gif)
## Aplicaciones involucradas

- frontend
- backend

### Frontend

Por parte del front end tendremos la vista del sistema, acorde a los patrones de diseño y requerimientos fijados por los desarrolladores.

#### Estructura de folders

```
/src
    /components/[DOMAIN]/UpperCaseCompoment.tsx
    /hooks/[DOMAIN]/useSomething.ts
    /views/[DOMAIN]/UpperCaseViewComponent.tsx
    /context/[DOMAIN]/UpperCaseContext.tsx
    /lib/[TYPE(math,strings,graphql)]/[DOMAIN]/lowerCaseFile.ts
    /assets/[DOMAIN]/asset.png|jpeg|*
```

#### Guías de código

1. Ninguna clase puede exceder las 300 líneas.
2. Las funciones NO deben tener más de una responsabilidad.
3. Preferir `const fn = () => {}` antes de `function() {}`.
4. Preferir `map|reduce|filter` antes de `for loops`.
5. Preferir `fns` antes de `classes`.
6. Todas las funciones se escriben de manera: `lowerCamelCase`. IE `const performAddition(x: number, y: number) => {}`.
7. Las únicas funciones que se escriben con UpperCamelCase son los componentes `const Component = (props) => {}`;

#### Guías de trabajo

1. Cada vez que se comience a trabajar en un [DOMAIN] feature, se debe crear un branch con el formato: `git checkout -b feat|chore|fix/what-it-does`
2. Nomenclatura para un commit: `git commit -m "feat|chore|fix: small text regarding to commit"`