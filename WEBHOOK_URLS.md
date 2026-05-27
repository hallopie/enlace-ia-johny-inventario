# WEBHOOK URLS · Ópticas Johny
⚠️ Este archivo es privado — NO compartir con el cliente.

## Escenarios DEV (pruebas)
```
WEBHOOK_INGRESO  = [URL del escenario johny-ingreso-armazon-DEV]
WEBHOOK_VENTA    = [URL del escenario johny-venta-armazon-DEV]
WEBHOOK_CONSULTA = [URL del escenario johny-consulta-inventario-DEV]
```

## Escenarios PROD (go-live)
```
WEBHOOK_INGRESO  = [URL del escenario johny-ingreso-armazon-PROD]
WEBHOOK_VENTA    = [URL del escenario johny-venta-armazon-PROD]
WEBHOOK_CONSULTA = [URL del escenario johny-consulta-inventario-PROD]
```

## Instrucciones
Para cambiar de DEV a PROD, editar las tres constantes al inicio del JS en index.html:
```
const WEBHOOK_INGRESO  = '...';
const WEBHOOK_VENTA    = '...';
const WEBHOOK_CONSULTA = '...';
```
Commit con mensaje: "go-live: conectar a PROD [fecha]"
