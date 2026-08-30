# Kelo World — Economía V1

## Objetivo
Validar primero la economía como un juego por sí sola, en navegador y móvil, antes de integrarla con el mundo 2D.

## Bucle principal
1. Producir recursos.
2. Elegir vender, guardar, tradear o transformar.
3. Cumplir contratos o fabricar equipo.
4. Fusionar objetos para buscar mayor calidad.
5. Reinvertir el oro y repetir.

## Recursos iniciales
- Huevos
- Trigo
- Madera
- Mineral

## Producción
Cada sector tiene coste operativo y tiempo de producción. Producir aumenta oferta y ejerce presión bajista sobre el precio del recurso.

## Mercado
- Precio dinámico por oferta/demanda.
- Compra y venta instantánea en la beta.
- Comisión del 5% como money sink.
- Play Market con bots para aportar liquidez cuando falten jugadores.
- El bot intenta evitar mercados completamente muertos, no fijar un precio permanente.

## Trueque
Permite intercambiar recursos sin oro. Es una vía alternativa cuando un jugador tiene inventario pero poca liquidez.

## Contratos
Los contratos consumen recursos a cambio de oro. Sirven para crear demanda y retirar exceso de inventario. En el juego final pueden venir de jugadores, gremios, ciudades o Play Market.

## Crafting
Receta beta: 2 madera + 2 mineral + 8 oro = 1 objeto Común.

## Fusión
Tres objetos de la misma calidad intentan crear uno de la calidad siguiente.

Probabilidades beta:
- Común → Raro: 70% éxito, 18% queda uno Común, 12% destrucción.
- Raro → Épico: 54% éxito, 23% queda uno Raro, 10% downgrade, 13% destrucción.
- Épico → Legendario: 36% éxito, 27% queda uno Épico, 18% downgrade, 19% destrucción.

La fusión también cobra oro. Así quema objetos y moneda simultáneamente.

## Faucets y sinks
### Faucets
- Contratos.
- Capital inicial de prueba.

### Sinks
- Costes de producción.
- Comisión de mercado.
- Crafting.
- Coste de fusión.
- Destrucción de materiales.
- Búsqueda de nuevos contratos.

## Telemetría
La beta registra:
- oro creado;
- oro quemado;
- objetos destruidos;
- operaciones;
- bitácora de movimientos.

## Regla de diseño
La interfaz debe ser entendible en menos de 30 segundos. La profundidad debe estar en las decisiones y en la interacción entre sistemas, no en menús difíciles de entender.

## Próximas pruebas
- Ajustar velocidad de producción.
- Medir si vender siempre domina otras estrategias.
- Medir inflación de oro.
- Medir escasez real de cada recurso.
- Añadir órdenes P2P reales y doble confirmación.
- Añadir almacenamiento, mantenimiento y caducidad donde tenga sentido.
- Simular múltiples jugadores y reducir bots conforme crece la liquidez humana.
