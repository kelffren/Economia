# KELO WORLD — CAJA NEGRA LAB — ECONOMÍA VERSIÓN 2

Documento rector del módulo económico.

Este documento define únicamente la economía de Kelo World. Durante esta etapa no diseñaremos el mapa 2D, combate, animaciones ni presentación final. Todo deberá poder probarse primero como una “caja negra”: una interfaz web mínima, mobile-first, hecha con HTML, CSS y JavaScript, donde el jugador solo vea información, tome decisiones y compruebe consecuencias.

Pregunta central de producto:  
¿La economía sigue siendo divertida, estratégica y capaz de generar ganas de volver incluso si eliminamos temporalmente todo el mundo visual?

Si la respuesta es sí, el resto de Kelo World podrá construirse alrededor de un núcleo económico ya validado.

## 1\. PRINCIPIO CENTRAL

Kelo World debe funcionar como una economía viva creada principalmente por jugadores.

El jugador no entra únicamente a “ganar monedas”. Entra a producir, almacenar, transformar, negociar, invertir, especular, prestar servicios, adquirir propiedad, descubrir oportunidades y construir patrimonio.

La economía debe permitir progresar de varias maneras. Un jugador con poco efectivo no queda fuera del juego si posee recursos, objetos, tierra, conocimiento del mercado, capacidad productiva o habilidad para negociar.

Regla: dinero, recursos, tiempo, información y especialización son formas diferentes de capital.

## 2\. LOOP ECONÓMICO MAESTRO

Loop general:

PRODUCIR → CONSERVAR → TRANSFORMAR → COMERCIAR → ESPECULAR → CONSUMIR/DESTRUIR → VOLVER A PRODUCIR

El sistema necesita entradas y salidas. Si solo producimos recursos y nunca desaparecen, el mundo se satura y los precios colapsan. Si todo se destruye demasiado rápido, el jugador siente que no progresa.

El balance principal será encontrar la velocidad adecuada entre creación y destrucción de valor.

## 3\. FORMAS DE JUGAR LA ECONOMÍA

La misma economía debe permitir profesiones emergentes, sin obligar al jugador a elegir una clase económica permanente.

Productor: obtiene materias primas.  
Agricultor: cultiva productos y gestiona ciclos de maduración.  
Ganadero: alimenta animales y obtiene recursos como huevos.  
Leñador: tala y vende madera.  
Pescador: obtiene pescado y recursos del mar.  
Minero: extrae minerales.  
Fabricante: compra materias primas y crea objetos de mayor valor.  
Fusionador/especialista: utiliza experiencia de fusión para intentar crear objetos de rareza superior.  
Comerciante: compra y vende buscando margen.  
Especulador: compra inventario porque espera que su precio futuro suba.  
Arbitrajista: aprovecha diferencias entre mercados, órdenes, zonas o formas de intercambio.  
Almacenista: compra barato, paga almacenamiento y espera mejores condiciones.  
Propietario: utiliza parcelas, instalaciones y capacidad productiva como activos.  
Contratista: cumple pedidos de otros jugadores.  
Intermediario: conecta compradores y vendedores y obtiene margen.

Un mismo jugador podrá combinar varias de estas estrategias.

## 4\. RECURSOS COMO ACTIVOS

Los recursos no son únicamente materiales de crafting. También pueden ser activos económicos.

Ejemplo:  
Un jugador vende huevos a 5 monedas.  
Otro jugador considera que habrá escasez y compra 100\.  
Coste: 500\.  
Si posteriormente el mercado paga 8 por huevo, ese inventario vale 800\.

La diferencia de 300 es el beneficio económico del riesgo asumido.

El mismo principio debe poder aplicarse a madera, minerales, pescado, cultivos, ingredientes, objetos, piedras de habilidades y otros bienes comerciables.

El inventario, por tanto, forma parte del patrimonio del jugador.

## 5\. PATRIMONIO

El juego debe distinguir entre efectivo y riqueza.

Patrimonio aproximado \=  
efectivo  
\+ valor de mercado del inventario  
\+ valor de objetos comerciables  
\+ valor de propiedades  
\+ otros activos económicos reconocidos.

La caja negra podrá mostrar:  
Efectivo.  
Inventario.  
Coste medio.  
Valor actual estimado.  
Ganancia/pérdida realizada.  
Ganancia/pérdida no realizada.  
Patrimonio total.  
Máximo histórico de patrimonio.

Esto permite que un jugador con poco efectivo siga siendo económicamente poderoso.

## 6\. MERCADO JUGADOR A JUGADOR

El mercado principal debe permitir que los jugadores compren y vendan entre sí.

Modelo deseado:  
\- Listados de venta.  
\- Órdenes de compra.  
\- Mejor precio comprador.  
\- Mejor precio vendedor.  
\- Cantidad disponible.  
\- Volumen negociado.  
\- Historial de precios.  
\- Historial de volumen.

Ejemplo de libro simplificado:

VENTA  
100 huevos @ 5.00  
250 huevos @ 5.20  
80 huevos @ 5.45

COMPRA  
200 huevos @ 4.80  
100 huevos @ 4.50  
400 huevos @ 4.20

El jugador podrá comprar inmediatamente al mejor vendedor o dejar una orden esperando un precio determinado.

No queremos que un “precio oficial” dicte permanentemente el valor. El precio debe emerger de oferta, demanda, producción, consumo, expectativas y liquidez.

## 7\. TRADE DIRECTO Y TRUEQUE

Dos jugadores podrán negociar directamente sin necesidad de utilizar únicamente dinero.

Ejemplos:  
5 huevos ↔ 10 maderas.  
1 espada ↔ 200 minerales.  
30 huevos \+ 100 monedas ↔ una herramienta rara.  
Un objeto raro ↔ varios recursos \+ otro objeto \+ dinero.

Esto garantiza que un jugador sin efectivo todavía tenga cartas económicas si posee algo que otro jugador valore.

El trade debe aceptar combinaciones de:  
\- Moneda.  
\- Recursos.  
\- Objetos.  
\- Equipamiento comerciable.

Seguridad mínima:  
\- Cada lado construye su oferta.  
\- Ambos pueden revisar el valor.  
\- Cada jugador bloquea su oferta.  
\- Cualquier modificación posterior cancela las confirmaciones.  
\- Se requiere doble confirmación final.  
\- La operación se registra.

El sistema puede mostrar un valor de mercado aproximado de cada lado como referencia, pero nunca debe impedir voluntariamente un intercambio desigual. Regalos, acuerdos privados y valor sentimental también forman parte de una economía social.

## 8\. CONTRATOS ENTRE JUGADORES

Los contratos serán una extensión natural del comercio.

Ejemplo:  
“Entrego 500 monedas a quien me entregue 200 maderas.”

Variables posibles:  
\- Recurso u objeto solicitado.  
\- Cantidad.  
\- Recompensa.  
\- Fecha o duración límite.  
\- Depósito/garantía cuando corresponda.  
\- Cumplimiento parcial o total.  
\- Jugador que acepta.  
\- Estado del contrato.

Tipos futuros:  
Contrato de recolección.  
Contrato de fabricación.  
Contrato de suministro recurrente.  
Contrato de transporte si el mundo lo justifica.  
Contrato de fusión.  
Contrato de compra garantizada.

Esto permite que los propios jugadores generen trabajo para otros jugadores y reduce la dependencia de quests creadas por NPC.

## 9\. SUBASTAS

Los bienes de mayor incertidumbre o escasez pueden venderse mediante subasta.

Casos:  
\- Objetos únicos.  
\- Piezas con atributos excepcionales.  
\- Coleccionables Limited/Seasonal.  
\- Parcelas.  
\- Propiedades.  
\- Lotes grandes de recursos.

La subasta crea descubrimiento de precio cuando no existe un valor evidente.

Debe existir precio inicial, pujas, duración, ganador y registro. Más adelante podrá estudiarse reserva mínima o compra inmediata.

## 10\. PRODUCCIÓN

La producción deberá cubrir progresivamente varios sectores, todos conectados con el mismo mercado.

Agricultura:  
semillas → plantación → tiempo de maduración → cosecha → venta/uso.

Ganadería:  
alimentación → tiempo → producción → huevos u otros recursos.

Madera:  
acceso a árboles → tala → madera → mercado/crafting/construcción.

Pesca:  
actividad productiva → captura → mercado/consumo/crafting.

Minería:  
extracción → mineral → mercado/fusión/crafting/construcción.

Crafting:  
materias primas → coste \+ proceso → objeto → uso/venta/fusión.

En el juego final, la producción offline debe calcularse principalmente mediante timestamps del servidor en vez de simular permanentemente cada entidad.

Regla importante: producir algo debe tener algún coste económico o de oportunidad. No queremos una fuente infinita sin fricción.

## 11\. COSTES DE PRODUCCIÓN

Toda actividad económica relevante debe requerir recursos o moneda básica.

Ejemplos:  
Agricultura consume semillas, abono, agua o mantenimiento según el diseño final.  
Animales consumen alimento.  
Crafting consume materias primas.  
Fusión consume objetos y moneda.  
Construcción consume materiales y moneda.  
Instalaciones avanzadas tienen mantenimiento.  
Almacenamiento avanzado tiene renta/coste.

Los costes crean demanda recurrente y ayudan a retirar moneda de circulación.

## 12\. MADURACIÓN, DECAY Y CADUCIDAD

No todos los bienes deben poder almacenarse eternamente sin coste.

Algunos recursos podrán:  
\- Madurar.  
\- Perder calidad.  
\- Caducar.  
\- Tener una ventana óptima de venta.  
\- Requerir almacenamiento especializado.

Esto crea decisiones entre vender hoy o asumir el coste/riesgo de esperar.

Ejemplo:  
Un cultivo alcanza su punto óptimo. Guardarlo en un almacén básico prolonga ligeramente su vida. Un almacén avanzado permite conservarlo más tiempo, pero cuesta más.

La caducidad no debe sentirse arbitraria. Debe ser una herramienta económica predecible y visible.

## 13\. ALMACENES

El almacenamiento será parte estratégica de la economía, no solo un límite de inventario.

Los almacenes pueden escalar en:  
\- Capacidad.  
\- Coste de renta/mantenimiento.  
\- Tiempo de conservación.  
\- Protección de ciertos recursos.  
\- Velocidad o facilidad logística.

Crecer económicamente aumenta capacidad, pero también costes recurrentes.

Esto evita que la estrategia óptima sea acumular cantidades infinitas gratuitamente.

## 14\. CICLOS DE MERCADO

Los precios deben moverse por sistemas comprensibles, no mediante puro azar.

Queremos ciclos con:  
\- Oferta.  
\- Demanda.  
\- Producción.  
\- Consumo.  
\- Inventarios.  
\- Tendencia.  
\- Volumen.  
\- Eventos.  
\- Estacionalidad.  
\- Expectativas.

Se ha propuesto experimentar con ciclos amplios equivalentes a aproximadamente 30 días del juego final. En la caja negra estos ciclos podrán comprimirse para observarlos en minutos u horas.

Un recurso puede atravesar:  
acumulación → subida → euforia → sobreproducción → caída → capitulación → recuperación.

No será una secuencia rígida. Será un conjunto de presiones que hacen ciertos movimientos más probables.

## 15\. INFORMACIÓN IMPERFECTA Y HABILIDAD

El jugador no debe recibir mensajes del tipo “el precio subirá”.

Debe recibir señales:  
Demanda: alta.  
Oferta: baja.  
Volumen: creciendo.  
Inventarios globales: descendiendo.  
Producción: aumentando.  
Sentimiento: alcista.  
Evento: posible escasez.

El jugador interpreta.

La información puede ser útil sin garantizar resultados. La economía debe recompensar lectura, paciencia, gestión de riesgo y conocimiento del mundo.

La variación aleatoria existirá, pero no dominará el sistema.

## 16\. EVENTOS ECONÓMICOS

Los eventos modifican temporalmente algunas variables.

Ejemplos:  
Escasez.  
Sobreproducción.  
Pedido masivo.  
Nueva receta que consume madera.  
Temporada que aumenta consumo de pescado.  
Importación extraordinaria.  
Enfermedad que reduce producción.  
Nuevo edificio que requiere hierro.  
Actualización anunciada que cambia expectativas.

La parte interesante no es solo reaccionar después del evento. También queremos que exista especulación previa.

Ejemplo:  
Se anuncia que próximamente aparecerán barcos.  
Los jugadores deducen que la madera podría ganar demanda.  
Algunos comienzan a acumular antes de que el sistema entre en funcionamiento.

Así, la información del propio juego se convierte en información económica.

## 17\. CONSUMO Y SINKS

La economía necesita destrucción estructural de recursos y moneda.

Posibles sinks:  
\- Comida consumible.  
\- Crafting.  
\- Construcción.  
\- Reparación cuando exista.  
\- Semillas/abono/alimento.  
\- Fusión.  
\- Destrucción/degradación en fusión.  
\- Comisiones de mercado.  
\- Tarifas de subasta.  
\- Costes de contratos cuando se justifique.  
\- Renta/mantenimiento de almacenes.  
\- Construcción y mejoras de propiedad.  
\- Expansiones productivas.  
\- Eventos y servicios.

Objetivo: los objetos comunes y materias primas deben seguir teniendo demanda incluso cuando el servidor envejezca.

## 18\. FUSIÓN COMO MOTOR ECONÓMICO

La fusión es uno de los sinks más importantes.

Regla base propuesta:  
3 objetos/piedras compatibles de la misma calidad → intento de crear 1 del tier siguiente.

Posibles resultados:  
\- Éxito.  
\- Fallo sin mejora.  
\- Degradación.  
\- Destrucción.

Los tiers altos tendrán mayor dificultad y mayor coste.

El nivel o maestría de fusión del jugador puede mejorar gradualmente las probabilidades. Esto crea especialistas que fusionan para otros o compran materiales baratos para vender resultados.

Los atributos del objeto resultante pueden variar dentro de rangos permitidos. Una rareza mayor no garantiza un roll perfecto.

Consecuencia económica buscada:  
los objetos comunes siguen valiendo porque son combustible de progresión y los objetos excepcionales adquieren valor propio.

## 19\. PARCELAS Y ESCASEZ ARTIFICIAL CONTROLADA

Las parcelas pueden ser un activo económico deliberadamente escaso.

Ideas ya planteadas:  
\- Cantidad limitada de parcelas por distrito.  
\- Diferentes niveles de prestigio.  
\- Expansión del mundo financiada parcialmente mediante moneda retirada de circulación.  
\- Adjudicación mediante subastas y, en determinados casos, sistemas comunitarios/sorteos con reglas transparentes.  
\- Construcción y mejora como sinks.  
\- Mantenimiento o decay para evitar propiedad abandonada permanentemente.

La escasez debe crear aspiración sin bloquear por completo a nuevos jugadores. El diseño deberá incluir mecanismos de retorno de parcelas al mercado.

## 20\. DINERO Y MONEDAS

La moneda básica debe ser útil en toda actividad económica.

Ideas previas del diseño general contemplan ORO como moneda obtenible jugando, produciendo y comerciando, y KC como moneda interna secundaria. Durante esta fase económica no necesitamos cerrar todavía la matemática final entre ambas.

Regla de seguridad conceptual:  
las monedas del juego deben permanecer separadas de promesas de conversión directa a dinero real.

La caja negra deberá comenzar con una sola moneda funcional. Una segunda moneda solo se añadirá cuando sepamos qué problema económico resuelve.

## 21\. KELO EXCHANGE / PREDICCIÓN

Existe una idea separada de mercados de predicción internos basados en métricas auditables del propio juego.

Ejemplos:  
¿mañana aumentará el volumen del marketplace?  
¿subirá determinada métrica económica?  
¿habrá más producción en un sector?

El jugador arriesga moneda virtual y el payout depende de probabilidad/participación.

Esta función NO es necesaria para la primera caja negra. Se conserva como módulo futuro porque conecta bien con el perfil de jugador inversor, pero no debe distraernos de validar primero producción, mercado, trade y especulación con activos reales del juego.

## 22\. BOTS Y “PLAY MARKET” / LIQUIDEZ DE SISTEMA

La economía debe diseñarse desde el principio para seguir funcionando aunque haya pocos jugadores.

Cada función crítica debe tener un modo de participación sistémica.

Objetivo:  
si todavía no existe suficiente población humana, agentes automáticos mantienen actividad mínima, liquidez y oportunidades sin fijar artificialmente todos los precios.

Los bots/agentes de mercado podrán:  
\- Colocar órdenes de compra y venta.  
\- Comprar producción de jugadores dentro de límites.  
\- Vender inventario dentro de límites.  
\- Aceptar o crear determinados contratos.  
\- Participar en subastas cuando exista lógica económica.  
\- Producir o consumir recursos simulados cuando sea necesario.  
\- Generar volumen base.  
\- Crear shocks controlados de oferta/demanda.  
\- Simular diferentes perfiles: productor, consumidor, comerciante, especulador.

Regla fundamental:  
los bots no deben conocer el futuro ni operar con ventaja imposible. Deben obedecer las mismas señales y restricciones económicas o versiones explícitamente limitadas de ellas.

Regla de integridad:  
el sistema puede utilizar agentes automáticos para liquidez, pero no debe falsificar identidades humanas ni hacer creer deliberadamente al jugador que un bot es una persona real.

El porcentaje de actividad automática podrá reducirse dinámicamente a medida que aumente la actividad humana.

Meta final:  
HUMANOS \+ AGENTES DE LIQUIDEZ → un mercado que nunca se siente muerto.

## 23\. MARKET MAKER SISTÉMICO

Además de bots individuales, podemos probar un market maker del sistema.

Su función no será garantizar beneficios ni mantener un precio fijo.

Podrá:  
\- Mantener un spread máximo razonable cuando no exista liquidez.  
\- Comprar pequeñas cantidades cuando no haya compradores.  
\- Vender pequeñas cantidades cuando no haya vendedores.  
\- Ajustar precios según inventario propio.  
\- Retirarse parcialmente cuando hay suficiente mercado humano.

Ejemplo:  
si el sistema acumula demasiados huevos porque lleva horas comprando, reducirá progresivamente el precio al que está dispuesto a comprar y aumentará el precio al que vende.

De esta manera el propio inventario del market maker crea riesgo y evita una fuente infinita de dinero.

## 24\. FORMACIÓN DEL PRECIO

Modelo conceptual:

nuevo precio/estado del libro \=  
órdenes humanas  
\+ órdenes automáticas  
\+ producción  
\+ consumo  
\+ inventarios  
\+ tendencia  
\+ eventos  
\+ expectativas  
\+ pequeñas perturbaciones.

El precio no debería ser una cifra que JavaScript elige al azar y después intenta justificar.

En la simulación inicial podremos usar un motor sintético, pero deberá conservar relaciones causa → efecto observables.

## 25\. AUTOEQUILIBRIO POR INCENTIVOS

Queremos que los jugadores ayuden a equilibrar el mundo.

Ejemplo:  
La madera sube mucho.  
Más jugadores consideran rentable talar.  
La producción de madera aumenta.  
La oferta empieza a alcanzar la demanda.  
El precio deja de subir o cae.  
Al bajar la rentabilidad, algunos productores cambian de actividad.  
La oferta futura disminuye.

El objetivo no es eliminar ciclos. Es permitir que los incentivos produzcan reacciones naturales.

## 26\. COMISIONES Y CONTROL DE INFLACIÓN

Las comisiones pueden retirar moneda sin sentirse como impuestos arbitrarios si acompañan servicios útiles.

Ejemplos:  
Marketplace.  
Subastas.  
Construcción.  
Mejoras.  
Almacenes.  
Fusión.  
Servicios especiales.

No todas las operaciones necesitan comisión. El trade directo y el trueque pueden tener reglas diferentes.

Debemos medir:  
moneda creada por hora/día  
vs.  
moneda destruida por hora/día.

Si creación supera destrucción durante demasiado tiempo, aparece inflación.  
Si destrucción domina excesivamente, la economía se seca.

## 27\. SEGURIDAD ECONÓMICA DEL JUEGO FINAL

La caja negra inicial puede funcionar localmente para experimentar, pero la economía multijugador final deberá ser autoritativa en servidor.

Principios:  
\- El cliente nunca decide su balance.  
\- El cliente nunca decide propiedad.  
\- Compras/trades/subastas deben ser transacciones atómicas.  
\- Ledger auditable para movimientos importantes.  
\- Registro de fusiones y resultados.  
\- Protección contra duplicación de objetos.  
\- Rate limits.  
\- Detección de exploits.  
\- Timestamps del servidor.  
\- Herramientas administrativas de reversión controlada.

Esto se deja previsto desde ahora aunque no sea necesario para la simulación HTML inicial.

## 28\. LA CAJA NEGRA

La caja negra será nuestro laboratorio.

Tecnología inicial:  
HTML \+ CSS \+ JavaScript.  
Publicable en GitHub Pages.  
Interfaz principalmente negra y textual.  
Mobile-first.  
Pocos botones.  
Información económica clara.  
Persistencia inicial mediante localStorage.

No necesitamos gráficos 2D ni mundo visual para validar el sistema.

La interfaz debe permitir acelerar el tiempo, reiniciar simulaciones, observar variables y cambiar parámetros rápidamente.

## 29\. ORDEN DE PROTOTIPADO

FASE A — Un activo.  
Huevos, capital inicial, compra, venta, precio, inventario, señales y eventos.

FASE B — Mercado real simplificado.  
Órdenes de compra/venta, spread, volumen e historial.

FASE C — Varios activos.  
Huevos, madera y mineral con comportamientos diferentes.

FASE D — Producción.  
El jugador puede producir en lugar de comprar.

FASE E — Trueque y trade directo.  
Intercambio de recursos \+ moneda \+ objetos.

FASE F — Contratos.  
Jugadores/agentes publican pedidos.

FASE G — Almacenamiento, decay y costes.  
Aparece la decisión de conservar o vender.

FASE H — Bots y market maker.  
Simular mercado con diferentes niveles de población humana.

FASE I — Crafting/fusión y sinks.  
Cerrar el ciclo creación → destrucción.

FASE J — Parcelas/activos productivos.  
Probar escasez, mantenimiento e inversión de largo plazo.

Cada fase debe poder activarse/desactivarse para comparar si realmente mejora el juego.

## 30\. MÉTRICAS DEL LABORATORIO

No evaluaremos una mecánica porque “suena bien”.

Registraremos:  
\- Tiempo de sesión.  
\- Número de decisiones.  
\- Compras.  
\- Ventas.  
\- Trades.  
\- Contratos aceptados.  
\- Tiempo entre acciones.  
\- Patrimonio máximo/mínimo.  
\- Ganancia/pérdida.  
\- Porcentaje del patrimonio en efectivo vs activos.  
\- Recursos producidos.  
\- Recursos destruidos.  
\- Moneda creada.  
\- Moneda destruida.  
\- Spread medio.  
\- Volumen.  
\- Tiempo sin liquidez.  
\- Dependencia de bots.  
\- Concentración de riqueza.  
\- Frecuencia con la que un jugador cambia de actividad.

Luego compararemos versiones.

## 31\. PREGUNTAS QUE DEBEMOS RESOLVER EXPERIMENTANDO

1\. ¿Comprar/vender un solo recurso ya produce tensión y decisiones?  
2\. ¿Qué velocidad de precio es divertida?  
3\. ¿Cuánta información debe ver el jugador?  
4\. ¿Cuánto azar es tolerable?  
5\. ¿El jugador entiende por qué un precio cambia?  
6\. ¿El trueque añade estrategia o solo fricción?  
7\. ¿Los contratos generan objetivos interesantes?  
8\. ¿Qué nivel de decay evita acumulación sin castigar demasiado?  
9\. ¿Cuánto debe costar almacenar?  
10\. ¿Cuántos recursos distintos podemos añadir antes de diluir la liquidez?  
11\. ¿Cuándo deben entrar bots?  
12\. ¿Qué porcentaje de mercado puede ser automático sin deformar el comportamiento?  
13\. ¿Cómo impedimos que el market maker sea explotable?  
14\. ¿Qué sinks resultan naturales?  
15\. ¿Qué tasa de destrucción mantiene objetos comunes valiosos?  
16\. ¿Cómo evitamos que los jugadores ricos controlen permanentemente un mercado?  
17\. ¿Qué oportunidades quedan para un jugador nuevo?  
18\. ¿Qué mecánicas generan conversación y negociación entre personas?

## 32\. REGLAS DE DISEÑO

1\. Primero diversión y decisiones; después complejidad.  
2\. Ningún recurso importante debe existir sin una razón para consumirse.  
3\. Ninguna fuente importante de moneda debe existir sin sinks compensatorios.  
4\. Un jugador sin efectivo debe poder continuar participando mediante recursos, trabajo o trueque.  
5\. El precio debe responder a causas, no a azar puro.  
6\. La información debe orientar sin garantizar.  
7\. La especulación debe tener riesgo real.  
8\. El almacenamiento debe tener coste u oportunidad.  
9\. La especialización debe crear comercio entre jugadores.  
10\. Los bots deben aportar liquidez, no beneficios garantizados.  
11\. A medida que crece la población humana, la intervención automática debe poder disminuir.  
12\. Todas las funciones importantes deben poder probarse primero sin gráficos.  
13\. Cada nueva mecánica debe demostrar que crea una decisión, una interacción, una oportunidad o un sink útil.  
14\. Si una función hace el sistema más grande pero no más divertido, no entra todavía.

## 33\. VISIÓN ECONÓMICA

Kelo World no debe sentirse como un juego donde el desarrollador reparte dinero y objetos.

Debe sentirse como un pequeño mundo donde:

alguien produce lo que otro necesita;  
alguien vende porque necesita liquidez;  
alguien compra porque cree que mañana valdrá más;  
alguien cambia huevos por madera porque no tiene efectivo;  
alguien paga a otro para que produzca;  
alguien arriesga recursos intentando fusionar;  
alguien almacena esperando una escasez;  
alguien construye una propiedad y consume materiales;  
y el mercado reacciona a todas esas decisiones.

La meta de Economía versión 1 es demostrar que esas relaciones pueden ser divertidas antes de vestirlas con el mundo 2D.

PRÓXIMO OBJETIVO DE DISEÑO:  
construir y ajustar el motor de precio \+ oferta/demanda \+ inventario \+ bots de liquidez para un único recurso, y probarlo repetidamente en la caja negra antes de ampliar el sistema

34\. TELEMETRÍA MACROECONÓMICA DEL SERVIDOR

La caja negra debe tratar la economía como un sistema medible en tiempo real. El servidor debe conocer y registrar como mínimo: jugadores conectados, jugadores activos económicos, Oro total existente, Oro creado hoy, Oro destruido hoy, cambio neto de Oro, Oro medio y mediano por jugador, concentración de riqueza, volumen de mercado y ratio Sink/Faucet.

Fórmula base:  
CAMBIO NETO DE ORO \= ORO CREADO \- ORO DESTRUIDO.

Ratio de control:  
SINK/FAUCET \= ORO DESTRUIDO / ORO CREADO.

No se calculará el Oro quemado simplemente comparando el saldo de ayer y hoy. Cada creación y destrucción debe registrarse por causa en un ledger auditable: FARM\_REWARD, SELL\_TO\_SYSTEM, MARKET\_FEE, FUSION\_COST, WAREHOUSE\_RENT, PROPERTY\_COST, EVENT\_COST y cualquier otro faucet o sink futuro.

35\. TELEMETRÍA POR PROFESIÓN Y PRODUCTO

Cada profesión y cada recurso tendrá su propia mini-economía medible. Para cada producto, como tomate, huevo, pescado, madera o hierro, el sistema registrará: existencia total actual, producido hoy, vendido al sistema, comprado por el sistema, volumen P2P, cantidad intercambiada por trueque, consumido, usado en crafting, destruido/caducado, cantidad almacenada, cantidad próxima a caducar, productores activos, precio actual, precio histórico y volumen histórico.

Ejemplo conceptual — TOMATE:  
Existencia total: 85,241.  
Producidos 24h: \+12,421.  
Vendidos al sistema: 25,300.  
Volumen P2P: 8,420.  
Destruidos/caducados: 9,870.  
Productores activos: 381\.  
Precio actual: 18 Oro.  
Precio anterior: 14 Oro.

Parte de esta información podrá mostrarse al jugador como señales. El futuro exacto no se muestra. El jugador interpreta escasez, exceso de producción, demanda, volumen y tendencia para decidir producir, vender, almacenar o especular.

36\. PANEL ECONÓMICO VISIBLE PARA EL JUGADOR

La caja negra podrá mostrar una pantalla global tipo KELO WORLD ECONOMY con información como: jugadores conectados, Oro total, Oro creado 24h, Oro destruido 24h, cambio neto y mercados principales con variación porcentual.

Cada producto tendrá una ficha simple con precio, oferta total, producción 24h, consumo/retiro, volumen, tendencia e histórico 1D/7D/30D/90D/ALL cuando exista suficiente información.

La economía también podrá generar noticias automáticas basadas en datos reales del servidor, por ejemplo: “La producción de tomates cae 31%”, “Los inventarios de huevos alcanzan máximo semanal”, “Los jugadores destruyeron 4.8M Oro” o “La expansión de Kelo City eleva la demanda de madera”. Estas noticias son información económica, no decoración.

37\. OBJETIVO PRINCIPAL DE RETENCIÓN DE LA CAJA NEGRA

La prueba de fuego del laboratorio será extrema: comprobar si una persona puede permanecer jugando voluntariamente aproximadamente 60 minutos aunque el juego sea casi solo una interfaz negra con datos, botones y feedback mínimo.

KPI PRINCIPAL:  
¿Puede un usuario nuevo jugar voluntariamente 60 minutos con gráficos mínimos porque siempre siente que existe una próxima decisión económica interesante?

No diseñaremos una actividad de una hora. Diseñaremos una cadena continua de decisiones superpuestas. Objetivo inicial de prueba: aproximadamente 15 a 30 decisiones interesantes por hora, con una nueva decisión relevante cada 2 a 4 minutos en promedio.

Regla psicológica buscada:  
“Antes de irme quiero hacer una cosa más.”

38\. TRES HORIZONTES DE TIEMPO SUPERPUESTOS

Toda sesión económica debe mantener acciones abiertas en diferentes escalas.

Corto — aproximadamente 10 segundos a 2 minutos: comprar, vender, aceptar una oferta, reorganizar inventario, hacer un trade, revisar una oportunidad.

Medio — aproximadamente 3 a 15 minutos: pequeñas producciones, contratos, crafting, cambios de mercado, órdenes pendientes y eventos.

Largo — aproximadamente 20 minutos a días: cosechas importantes, construcciones, grandes contratos, almacenes, propiedades e inversiones.

Nunca dependeremos de un único timer que deje al jugador sin nada útil que hacer. Mientras algo madura, otras decisiones deben estar disponibles.

39\. CADENAS DE DECISIONES Y POSICIONES ABIERTAS

Los sistemas deben chocar entre sí. Ejemplo: el almacén está casi lleno, el pescado caduca pronto, el precio está bajo, una cosecha de tomate está por terminar y un contrato vence en pocos minutos. El jugador debe decidir qué vender, qué conservar, qué comprar y qué sacrificar.

La caja negra debe permitir varias “historias económicas abiertas” simultáneas: inventario almacenado esperando precio, producción en curso, órdenes P2P, contratos con límite, ofertas de trueque, crafting/fusión pendiente y objetivos de mejora.

La retención debe venir de oportunidades y consecuencias, no de castigos artificiales por ausentarse unos minutos.

40\. OPORTUNIDADES Y CONTRATOS TEMPORALES

El sistema podrá crear oportunidades económicas temporales que cambien decisiones sin regalar valor. Ejemplo: “Restaurante de Kelo City necesita 2,000 tomates durante 7 minutos y paga 19 Oro por unidad frente a un precio normal de 13”. Esto crea presión sobre inventarios, mercado P2P y producción.

Los contratos deben convertirse en problemas económicos, no simples quests. Ejemplo: entregar 500 huevos en 18 minutos por 14,000 Oro cuando el jugador posee solo 230\. Puede producir, comprar, negociar, hacer trueque, pagar caro o abandonar. La diversión está en resolver cómo cumplir todavía con beneficio.

41\. OBJETIVOS ESCALONADOS Y ‘CASI LLEGUÉ’

La economía debe generar metas emergentes. El jugador puede proponerse pasar de 22K a 40K para comprar Almacén II. Cuando está en 37.8K, naturalmente aparece la tentación de realizar una operación más para alcanzar el objetivo. Tras comprarlo aparece el siguiente objetivo más caro.

Principio: el jugador nunca debe sentir “ya tengo suficiente dinero”. Debe sentir “ahora gano más, pero lo siguiente que quiero cuesta muchísimo más”.

42\. KELO REWARD POOL — HIPÓTESIS DE INVESTIGACIÓN, NO APROBADA

Se conserva como concepto hipotético separado. Idea actual: un Reward Pool externo financiado por Kelo World podría relacionarse con una métrica de contribución generada al destruir Oro obtenido mediante gameplay. Una variante estudiada sería que una mayor proporción de Oro elegible destruido otorgue una mayor participación bajo reglas predefinidas.

Objetivo económico interno: convertir el Reward Pool en un gran sink voluntario y crear una decisión entre usar Oro para producción, propiedad, almacenamiento, objetos o destruirlo para aumentar contribución.

ESTADO: NO IMPLEMENTAR COMO RECOMPENSA DE DINERO REAL SIN REVISIÓN LEGAL, FISCAL, DE PAGOS, EDAD, TERRITORIO, FRAUDE Y CUMPLIMIENTO. La caja negra puede simular el sink y la contribución sin conectar dinero real.

43\. NUEVO ORDEN DE PRUEBA INICIAL

La primera experiencia jugable de Caja Negra Lab debe comenzar pequeña pero con suficiente interacción para medir retención: una moneda (Oro), tres productos iniciales recomendados (tomate, huevo y madera), producción, compra, venta, almacenamiento limitado, mercado del sistema, mercado P2P/bots, contratos temporales, inventario, timers, eventos económicos, señales e historial básico.

Meta de prueba sugerida: empezar con 10,000 Oro e intentar alcanzar 100,000 mediante decisiones económicas, no mediante una secuencia garantizada.

El prototipo debe registrar sesión, decisiones, tiempo entre acciones, faucets, sinks, productos creados/destruidos, operaciones, contratos, evolución del patrimonio y motivo de salida cuando podamos medirlo.

44\. REGLA RECTORA ACTUAL DEL LABORATORIO

Antes de añadir mapas, sprites, combate o presentación 2D, debemos demostrar que la economía desnuda funciona. Si mirar números, interpretar señales, abrir posiciones económicas, producir, comerciar, almacenar, cumplir contratos y perseguir mejoras mantiene al jugador interesado por sí solo, entonces el mundo 2D se construirá sobre un núcleo ya probado.

Pregunta permanente para cada mecánica nueva:  
¿Esta función aumenta la calidad o frecuencia de decisiones interesantes y ayuda a que el jugador quiera hacer una acción más antes de cerrar?  
.

