# Sistema de Efectos de Estados

Los estados negativos son condiciones adversas que afectan el rendimiento de un personaje, debilitando sus estadísticas, movilidad, percepción o capacidad de combate. Estos efectos pueden presentarse de manera leve o llegar a poner en riesgo la vida del afectado si no se tratan adecuadamente. La gestión de estos estados es crucial para la supervivencia en entornos hostiles.

## Fases de los Estados

Los efectos se clasifican según su gravedad en tres fases:

- **Leves:** Generan molestias o reducciones moderadas en estadísticas.
- **Intermedias:** Efectos más severos que requieren atención rápida.
- **Mortales:** Estados críticos que amenazan directamente la vida y requieren tratamiento inmediato.

## Tipos de Estado

### Sangrado (Hemorragia)

| Gravedad   | Descripción                                   | Efectos                              |
|------------|-----------------------------------------------|--------------------------------------|
| Leve       | Cortes superficiales                          | `-10% HP por turno`                  |
| Intermedia | Heridas graves o amputaciones parciales       | `-20% HP por turno`                  |
| Mortal     | Mutilaciones o daño en órganos vitales        | `-40% HP por turno`                  |

### Envenenamiento

| Gravedad   | Descripción                        | Efectos                                                      |
|------------|------------------------------------|--------------------------------------------------------------|
| Leve       | Mareos y náuseas                   | `-5% HP por turno`, `-5% Resistencia`                        |
| Intermedia | Percepción distorsionada           | `-10% HP`, `-10% Resistencia`, `-10% Percepción`            |
| Mortal     | Alucinaciones, desorientación      | `-30% HP`, `-20% Resistencia`, `-20% Percepción`, `-20% Fuerza` |

### Parálisis

| Gravedad   | Descripción                                | Efectos                          |
|------------|--------------------------------------------|----------------------------------|
| Leve       | Pesadez muscular                           | `-25% Velocidad`, `-5% Percepción` |
| Intermedia | Movilidad reducida                         | `-50% Velocidad`, `-10% Percepción` |
| Mortal     | Incapacidad de moverse                     | `-80% Velocidad`, `-30% Percepción` |

### Congelamiento

| Gravedad        | Descripción                                 | Efectos                                             |
|-----------------|---------------------------------------------|-----------------------------------------------------|
| Leve            | Entumecimiento en extremidades              | `-25% Resistencia`, `-5% Velocidad`                |
| Intermedia      | Quemaduras por congelamiento                | `-50% Resistencia`, `-25% Velocidad`, `-20% HP por turno` |
| Mortal          | Congelación completa de extremidades        | `-75% Resistencia`, `-30% Velocidad`, `-25% HP por turno` |
| Cero Absoluto   | Congelación instantánea (efecto mágico)     | `-60% Resistencia`, `-100% Velocidad`, `-20% HP por turno` |

### Quemaduras

| Gravedad   | Descripción                         | Efectos                                     |
|------------|-------------------------------------|---------------------------------------------|
| Leve       | Quemadura superficial en una zona   | `-5% HP por turno`, `-5% Resistencia`       |
| Intermedia | Afecta dos zonas o torso            | `-15% HP por turno`, `-10% Resistencia`     |
| Mortal     | Afecta cuerpo completo              | `-30% HP por turno`, `-20% Resistencia`     |

### Corrosión

| Gravedad   | Descripción                       | Efectos en el cuerpo                              | Efectos en el equipo                                |
|------------|-----------------------------------|---------------------------------------------------|-----------------------------------------------------|
| Leve       | Ardor y escozor                   | `-3% HP por turno`                                | `-10% Velocidad si lleva armadura`                  |
| Intermedia | Necrosis superficial              | `-9% HP por turno`, `-20% Velocidad`              | `-15% Daño`, `-30% Resistencia del equipo`          |
| Mortal     | Necrosis grave, sangre ácida      | `-18% HP por turno`, `-35% Velocidad`             | `-30% Daño`, `-60% Resistencia del equipo`          |

## Efectos de Estado Sin Nivel

### Aturdimiento

**Descripción:** Provoca que el personaje pierda parcial o totalmente la orientación, quedando incapacitado para moverse o actuar.

**Efecto:** Queda inmovilizado durante X turnos, sin posibilidad de realizar acciones ofensivas o defensivas.

### Confusión

**Descripción:** El personaje no puede distinguir entre aliados y enemigos, reaccionando de forma impredecible.

**Efecto:** Durante X turnos ataca a aliados y enemigos por igual, sin control consciente de sus acciones.

### Sueño

**Descripción:** Incapacita completamente al personaje, impidiéndole actuar hasta que despierte por tiempo o daño recibido.

**Efecto:** Queda dormido durante X turnos, despertando al recibir daño o al pasar el tiempo del efecto.

### Ceguera

**Descripción:** Reduce la percepción visual del personaje, afectando su capacidad para acertar ataques.

**Efecto:** Reducción de precisión entre 60% y 100% durante X turnos. Afecta golpes básicos y técnicas asociadas.

### Silencio

**Descripción:** Bloquea el uso de habilidades o hechizos que requieran MP.

**Efecto:** Durante X turnos no puede usar ninguna técnica que consuma MP, solo se permite ataques físicos sin gasto.

### Miedo

**Descripción:** El personaje reacciona de forma irracional ante una amenaza intensa.

**Efecto:** Durante X turnos puede huir o quedar paralizado dependiendo de la intensidad del miedo.

### Petrificación

**Descripción:** Endurecimiento del cuerpo parcial o total por magia o toxinas, reduciendo la movilidad.

**Efecto:** Pérdida del 50% de resistencia y movilidad completa en las zonas afectadas. Puede causar la muerte si no se trata.

### Reducción de Capacidades

**Descripción:** Disminuye temporalmente estadísticas clave del personaje.

**Efecto:** Reduce una o varias estadísticas entre un 5% y un 50%, pudiendo alcanzar un 100% en casos extremos durante X turnos.

### Levantamiento

**Descripción:** Suspensión forzada del personaje en el aire, dificultando su capacidad de reacción.

**Efecto:** Vulnerabilidad a ataques aéreos y desorientación leve durante 0.5 a 1 turno.

### Retroceso

**Descripción:** Desplazamiento forzado del personaje que interrumpe su acción.

**Efecto:** Interrumpe la acción actual o siguiente del afectado, otorgando doble acción al atacante.

### Sobrepeso

**Descripción:** Se produce al exceder la capacidad de carga del personaje, afectando su movilidad.

**Efecto:** Reducción de velocidad entre 4% y 90% según el exceso de peso. Puede llegar a inmovilizar completamente.
