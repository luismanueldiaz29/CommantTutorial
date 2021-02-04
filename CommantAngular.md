# Commands Angular

## Userful commands 🚀

### Create new angular project

_Initial command_

```
ng new ProyectName
```

_Ignore files for testing_

```
ng new ProyectName --skip-tests
```

### Generate a component

_Command:_

```
ng generate component NombreDelProyecto | ng g c NombreDelComponente
```

_Generate a commponent ignoring file "spec.ts"_

```
ng g c NombreDelComponente --skipTests=true|false
```
### Generate module

_Command:_

```
ng generate module NombreDelModulo | ng g m NombreDelModulo
```

_Command options:_

Generate module and routing.

```
ng g m NombreDelModulo --routing
```

Generate module, component and routing.

```
ng g m NombreDelModulo -m=app --route NombreRoute
```

### Generate services

_Command:_

```
ng g s NombreDelService --skipTest
```

### Generate interface NombreInterface

_Command:_

```
ng g interface NombreDelService
```

### Generate Class 

_Command:_

```
ng g class NombreClase
```

### Generate Guard

_Command:_

```
ng g guard NombreGuard
```

### Generate interceptor

_Command:_

```
ng g interceptor NombreInterceptor
```
