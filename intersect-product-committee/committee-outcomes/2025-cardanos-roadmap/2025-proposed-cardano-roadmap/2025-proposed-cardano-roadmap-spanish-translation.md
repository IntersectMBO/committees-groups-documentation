# 2025 Proposed Cardano Roadmap - Spanish translation

Visión y hoja de ruta para el 2025

## Visión

Cardano vislumbra un futuro en el que sirve como base sólida y escalable para una economía global descentralizada. Esto se logrará mejorando significativamente el rendimiento de la capa 1 a través del protocolo Leios y optimizando la base de código actual, expandiendo al mismo tiempo las capacidades de las soluciones de capa 2 como Hydra y Midgard.

Mediante la mejora de la experiencia de los desarrolladores a través de API modernizadas, herramientas efectivas, y un enfoque en la descentralización, Cardano tiene como objetivo capacitar a los desarrolladores para la creación de aplicaciones innovadoras e impactantes. Además, la expansión de los activos programables, incluidas funciones avanzadas como la abstracción de cuentas y stablecoins reguladas por entidades de custodia, revelará nuevas posibilidades para las finanzas descentralizadas y mucho más. Esta visión enfatiza un fuerte compromiso con la investigación, la colaboración comunitaria, y la sostenibilidad a largo plazo del ecosistema Cardano.

Un ecosistema próspero es esencial para hacer realidad esta visión. Esto requiere un enfoque multifacético que fomente la innovación, atraiga a nuevos usuarios y desarrolladores, e impulse la adopción en el mundo real. Un componente clave de esta estrategia es el cultivo de asociaciones estratégicas con organizaciones de diversos sectores, centrándose en el desarrollo e implementación de soluciones basadas en Cardano que aborden necesidades específicas de la industria. Priorizaremos colaboraciones que se alineen con los principios básicos de Cardano: seguridad, escalabilidad, y descentralización.

Más allá de las asociaciones estratégicas, es primordial fomentar una comunidad vibrante y dedicada. Invertiremos en iniciativas que permitan a los desarrolladores crear DApps y herramientas innovadoras en Cardano. Esto incluye establecer programas de incubación y aceleración, organizar hackathons periódicos, ofrecer subvenciones a desarrolladores, y ampliar un fondo de ecosistema para apoyar proyectos prometedores. Además, daremos prioridad a mejorar la experiencia de los desarrolladores a través de API mejoradas, herramientas efectivas, y documentación completa, lo que facilitará a los desarrolladores comenzar a crear aplicaciones impactantes en Cardano.

Finalmente, construir una comunidad fuerte, unida, y solidaria es crucial para el éxito a largo plazo. Nos centraremos en iniciativas que fomenten e involucren a la comunidad de Cardano, tales como reuniones, foros en línea, y programas de embajadores. Al combinar asociaciones estratégicas, apoyo a los desarrolladores, y participación de la comunidad, confiamos en nuestra capacidad para crear un ecosistema próspero que impulse la adopción de Cardano y realice todo su potencial.

Los temas generales de la visión a corto plazo de la comunidad, analizados a través de la encuesta de la hoja de ruta de la comunidad, se centran en aumentar la escalabilidad, la interoperabilidad y la usabilidad.

## Hoja de ruta

La hoja de ruta para 2025 incluye una serie de elementos propuestos por miembros de la comunidad, como se describe a continuación. Se espera que se logren avances en su mayor parte o en su totalidad. Es importante destacar que el alcance de la hoja de ruta no es fijo, sino que está abierto a nuevas contribuciones de la comunidad.

### Escalando el motor de capa 1

El rendimiento de la capa 1 es crucial para una adopción generalizada y para permitir que Cardano se convierta en un núcleo central para la comunicación en blockchain. Esto se logrará mediante una combinación de optimización de la base de código y mejoras arquitectónicas para aumentar la paralelización.

#### Excelencia arquitectónica

Cardano se compromete a mantener su posición de vanguardia de la tecnología blockchain, lo cual incluye una evaluación continua de las mejores prácticas de arquitectura de software. Reconocemos el panorama cambiante de los patrones arquitectónicos y nos dedicamos a explorar e implementar los enfoques más adecuados para las necesidades únicas de Cardano, incluida la operación de la blockchain más fiable y descentralizada del mundo.

* Diseño modular: daremos prioridad a un enfoque de diseño modular para el código base de Cardano, permitiendo el desarrollo e implementación independientes de componentes mientras mantenemos un sistema cohesivo y eficiente que cumpla con los requisitos de ritmo, seguridad, y fiabilidad que son fundamentales para Cardano. Esto permite flexibilidad y adaptabilidad a medida que evoluciona la plataforma.
* Optimización del rendimiento: analizaremos y optimizaremos continuamente el rendimiento de la arquitectura de Cardano, explorando y evaluando diferentes patrones arquitectónicos para garantizar la máxima eficiencia y escalabilidad, centrándonos en los peores casos de comportamiento que gobiernan la conducta general del sistema, en vez de centrarnos en comportamientos de promedio que pueden ser engañosos. Esto incluye investigar y comparar alternativas prometedoras a patrones establecidos para determinar el enfoque más adecuado para varios componentes de Cardano.
* Métodos formales y verificación: la seguridad y la fiabilidad son aspectos primordiales para los sistemas blockchain. Aprovecharemos los métodos formales y las técnicas de verificación para especificar y analizar rigurosamente los componentes críticos de la arquitectura de Cardano, incluida la puntualidad y los peores casos de comportamientos. Esto nos permitirá demostrar matemáticamente la exactitud de estos componentes y minimizar el riesgo de vulnerabilidades. Continuaremos invirtiendo en investigación y desarrollo de métodos formales para mejorar su aplicabilidad y eficacia en el contexto de Cardano.
* Investigación y exploración: dedicaremos recursos a investigar y explorar patrones y tecnologías arquitectónicas de vanguardia, asegurando que Cardano permanezca al frente de la excelencia técnica y pueda adaptarse al cambiante panorama de blockchain. Esto implicará un estrecho seguimiento de las tendencias de la industria y la colaboración con expertos en arquitectura de software, especialmente para sistemas distribuidos complejos en tiempo real.

#### Leios

Leios es una innovación revolucionaria diseñada para mejorar de forma significativa la escalabilidad y el rendimiento de las transacciones de Cardano. Leios introduce un enfoque novedoso para la creación de bloques, alejándose del modelo secuencial tradicional.

* Leios aprovecha un proceso de creación de bloques en paralelo. En lugar de una única cadena lineal de bloques, Leios introduce múltiples 'bloques de entrada' que son creados y respaldados de forma independiente por los stake pool operators (SPOs). Estos respaldos luego se agregan en 'bloques de respaldo' y, finalmente, un 'bloque de clasificación' determina el orden final y la validez de las transacciones en todos los bloques de entrada.
* Este enfoque paralelo tiene el potencial de aumentar drásticamente el rendimiento de las transacciones manteniendo al mismo tiempo la seguridad y la descentralización de Cardano.

La hoja de ruta para 2025 incluye varios pasos clave a alcanzar en preparación para el desarrollo y la implementación de Leios:

* Desarrollo de especificaciones formales para guiar las implementaciones de nodos y garantizar la corrección.
* Realización de simulaciones exhaustivas para validar el diseño teórico de Leios en condiciones de red del mundo real e identificar parámetros óptimos.
* Refactorización del nodo Cardano para facilitar la integración de Leios y garantizar un funcionamiento fluido y eficiente.

#### Optimizaciones

* Optimización de la base de código actual y abordamiento de la deuda técnica para mejorar el rendimiento. Esto permitirá ajustes más flexibles de parámetros por parte del comité correspondiente, lo que permitirá una mayor escalabilidad sin necesidad de un hard fork.
* Mejora de la descentralización de Mithril mediante su integración de forma más estrecha con el nodo y utilizando las capas de red existentes.

#### Anti-grinding

* Introducción de medidas para mitigar ataques a CPU basados en grinding, mejorando la velocidad de finalización y la seguridad de la red.

#### Integración de LSM

* Reducción de los requerimientos de memoria de los nodos mediante la integración de árboles Log-Structured Merge (LSM), con un foco inicial en el set de UTXO.

#### Liquidez entrante

Aumentar la liquidez de otros ecosistemas es vital para ampliar la base de usuarios de Cardano.

* Utilización de pruebas de conocimiento cero para permitir que Cardano sirva como una capa DeFi descentralizada para Bitcoin.
* Las tarifas de Babel (transacciones anidadas) facilitan las transacciones en la capa 1 para usuarios sin tenencias iniciales de ada a través de un mercado descentralizado que permite aceptar y combinar transacciones parciales de múltiples partes, donde un mercado puede arbitrar el valor en ada para que un usuario obtenga ada para gastar en una transacción, y tenga la mínima cantidad de ada requerida sin tener que comprar ada primero a través de un intercambio.

### Expansión de la capa 2

Para acomodar un volumen de transacciones mayor, Cardano se enfocará en la expansión de las capacidades de soluciones de capa 2.

#### Capa de servicios validados activamente (AVS) para partner chains

Este marco operativo describe un método para crear redes blockchain independientes y personalizables (partner chains) aprovechando una capa de validación de valor subyacente sólida y segura. Este enfoque permite una mayor flexibilidad y experimentación al tiempo que se beneficia de la seguridad y fiabilidad de Ouroboros, el mecanismo de consenso de Cardano. Este marco está también diseñado para facilitar una transferencia de valor fluida entre partner chains, formando la base de un estándar abierto descentralizado.

Los beneficios clave incluyen parámetros personalizables de la partner chain, creación de prototipos de nuevas funciones sin afectar la estabilidad de AVS, herencia de la seguridad de AVS y mayor escalabilidad de la partner chain. El enfoque técnico implica ampliar los mecanismos de consenso existentes para operar en múltiples modos, como agregar un modo FastBFT. Esto incluye la creación de una versión simplificada de los componentes centrales de blockchain y el desarrollo de formatos estandarizados de mensajes y transacciones para la comunicación entre cadenas.

Los casos de uso incluyen partner chains personalizadas para DApps, pruebas de nuevas tecnologías en partner chains, y partner chains privadas para consorcios.

En el futuro, el desarrollo se centrará en la integración de múltiples fuentes de consenso, permitir una comunicación fluida entre cadenas, definir un protocolo claro para las transacciones entre cadenas, desarrollar una interfaz estandarizada para la interacción AVS, y establecer gobernanza comunitaria.

#### Hydra

Exploración de nuevos casos de uso para Hydra, tales como herramientas de gobernanza, y continuar mejorando su escalabilidad y rendimiento.

* Aprovechamiento del éxito de Hydra Doom, identificando y desarrollando otros casos de uso que puedan aprovechar la escalabilidad de Hydra para beneficiar al ecosistema Cardano.
* Exploración del uso de Hydra como plataforma para debates y votaciones sobre gobernanza descentralizada, abordando los desafíos de gestionar grandes volúmenes de información en la capa 1.

#### Midgard

Midgard es el primer marco optimista de agrupaciones de Cardano, el cual aprovecha el modelo EUTXO para lograr operaciones sin permiso, pruebas de fraude eficientes, y resistencia a la censura, sin depender de secuenciadores centralizados o multifirmas de custodia. Este diseño único permite transacciones de alto rendimiento y bajas tarifas al tiempo que mantiene la sólida seguridad y descentralización de Cardano. Al agregar transacciones fuera de la cadena en representaciones compactas dentro de la cadena, Midgard garantiza que una mayor actividad beneficie directamente a la capa 1 de Cardano, permitiendo un ecosistema sostenible e innovador para aplicaciones descentralizadas.

#### Finalidad (Peras)

Peras es una mejora del protocolo Ouroboros Praos que tiene como objetivo acelerar los tiempos de finalización de transacciones. En el protocolo Praos actual, los nuevos bloques se agregan de manera probabilística y la cadena de bloques más larga generalmente se considera válida. Peras introduce un enfoque novedoso al incorporar un mecanismo de votación entre los SPOs.

Los SPOs pueden votar para respaldar bloques específicos, lo que aumenta de forma efectiva su peso dentro de la cadena. Este mecanismo de 'votación' permite un consenso más rápido sobre la cadena más válida, lo cual conduce a una finalización más rápida de la transacción. Esta finalidad acelerada puede mejorar significativamente la experiencia del usuario y permitir transacciones más eficientes y oportunas.

### Experiencia de desarrollador/usuario

Mejorar la experiencia de los desarrolladores y usuarios es crucial para impulsar una adopción más amplia.

* Generación de bibliotecas en varios idiomas para simplificar la interacción de los desarrolladores en blockchain.
* Ampliación de las capacidades de RPC para admitir consultas y creación de transacciones, lo que permite una integración perfecta con los servicios de nodo.
* Capacitación a los desarrolladores para que creen indexadores de cadenas personalizados para necesidades específicas, como el soporte a cadenas de socios. La creación de una capa de traducción de bloques y eventos de libro mayor ('ledger') a un sistema de mensajería de publicación/subscripción de Nats Core se puede utilizar como ejemplo de marco de indexación.
* Descentralización de los servicios de APIs de datos para reducir la dependencia de proveedores centralizados y empoderar a los SPOs.
* Promoción del uso de nodos locales y desarrollo de estándares para la interacción de billeteras con nodos completos.
* Establecimiento de un estándar unificado para rastrear, registrar, y monitorear diferentes implementaciones de nodos.

### Activos programables

Ampliar las capacidades de los activos programables revelará nuevas posibilidades para aplicaciones descentralizadas.

Mejorar las capacidades de los activos programables de Cardano es crucial para desbloquear todo el potencial de las DApps. Dichas capacidades expanden la funcionalidad de los activos en cadena más allá de las simples transferencias, permitiendo una lógica compleja y programable. Estos avances permitirán a los desarrolladores crear DApps innovadoras, explorando casos de uso como tokens vinculados al alma (del inglés 'soul-bound token (SBT)'). SBTs son tokens digitales intransferibles que están vinculados permanentemente a la billetera digital de un usuario específico. Esencialmente, estos tokens representan una parte de la identidad del usuario en línea. SBTs no se puede vender, intercambiar, o mover a otra billetera. El concepto está diseñado para almacenar credenciales verificables como historial laboral, logros académicos, u otra información personal e intransferible del usuario en una cadena de bloques de forma segura y transparente.

Otros casos de uso para SBTs incluyen mecanismos para stablecoins reguladas por custodios, y mecanismos de cobro por derechos de autor para apoyar a creadores.

* Desarrollo de marcos que permitan una nueva clase de activos programables más allá de los tokens nativos.
* Las firmas de intención de UTXO mejoran las interacciones en intercambios descentralizados al permitir a los usuarios indicar su intención de gastar UTXOs en condiciones específicas, lo que facilita los intercambios entre usuarios y al mismo tiempo mantener la propiedad de sus fondos.
* Exploración del uso de tokens vinculados al alma para identidades descentralizadas y otras aplicaciones.
* Implementación de mecanismos de cobro por derechos de autor para apoyar a creadores e incentivar la innovación.
* Habilitación de la emisión en Cardano de stablecoins reguladas por custodios a través de mecanismos basados ​​en políticas, como USDC/USDT.

### Implementaciones de múltiples nodos

El desarrollo y mantenimiento de implementaciones de múltiples nodos es absolutamente crucial para la resiliencia y la resistencia a la censura de Cardano. Sin embargo, solo si cumplen con una especificación segura y correctamente implementada. Esta diversidad fortalece la seguridad a través de una forma de revisión por pares distribuida, a medida que diferentes equipos examinan cada base de código, lo que aumenta la probabilidad de identificar y abordar fallas potenciales antes de que puedan ser explotadas. Además, diversas implementaciones descentralizan el proceso de desarrollo en sí, lo que reduce el riesgo asociado con depender de una sola entidad. Este modelo de desarrollo distribuido fomenta un ecosistema más robusto y adaptable, a medida que diferentes equipos aportan perspectivas y enfoques únicos a la evolución continua de la red Cardano. En última instancia, cuantas más implementaciones de nodos independientes y de alta calidad tengamos, Cardano se fortalece más, se hace más resistente a la censura, y es más descentralizado, todo lo cual garantiza su viabilidad y éxito a largo plazo.

Garantizar la conformidad de los nodos en Cardano depende en gran medida de especificaciones formales rigurosas. Estas especificaciones sirven como guía definitiva para la implementación de nodos y detallan el comportamiento preciso y la funcionalidad que se espera de cada nodo conforme. También permiten que las pruebas de propiedades se extraigan automáticamente, lo que permite que las implementaciones de nodos demuestren una conformidad total con las especificaciones. Al cumplir con estas especificaciones meticulosamente elaboradas, los desarrolladores de nodos pueden crear implementaciones que sean interoperables y compatibles con la red Cardano en general. Proporcionando instrucciones y directrices concretas y prácticas para construir y configurar nodos, garantizando la coherencia y el cumplimiento de los estándares establecidos. Esta combinación de especificaciones precisas es esencial para mantener la integridad y estabilidad de la red Cardano, garantizando que todos los nodos participantes operen de acuerdo con las reglas y protocolos acordados.

### Mejoras en los incentivos para SPOs

La comunidad ha sugerido que los incentivos para SPOs se pueden mejorar. Estas son algunas sugerencias de lo que se puede evaluar:

* Introducción de un parámetro de margen mínimo cuya modificación esté sujeta a votación a través de gobernanza
* Modificación de la curva de compromiso-beneficio para a0

Nota: esta visión y hoja de ruta representan una descripción general de alto nivel, y se perfeccionarán e iterarán en función de la investigación en curso, los comentarios de la comunidad, y los avances tecnológicos. Se basa en los resultados de la encuesta TSC. El autor inicial de esta hoja de ruta es Sam Leathers, presidente del Comité de Productos de Intersect.
