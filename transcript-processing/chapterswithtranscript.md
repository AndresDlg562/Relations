# Introducción y Presentación de Joaquín Bravo

00:00:01 - Alumnos de sexto semestre y tesistas de tequila en el campus Monterrey. 

00:00:11 - Gracias, Álvaro, por conectarte. También quiero darle la bienvenida a Joaquín Bravo. Joaquín Bravo es programador con 20 años de experiencia. Trabajó en su propio despacho de software durante 10 años, desarrollando soluciones con Drupal para periódicos, revistas y universidades. También ayudó a organizar conferencias de código abierto en Latinoamérica, lo cual es muy padre. Después estuvo 6 años en Wayland, donde empezó como Tellez y terminó como director de innovación. Actualmente trabaja en Vicks, desarrollando soluciones de allá. Es un experto en el área, y me da mucho gusto que podamos tenerlo aquí, en este espacio, en el salón, compartiendo sus conocimientos con nosotros. Joaquín, muchas gracias. Bienvenido.

00:00:53 - Gracias, Elvia, por invitarme otra vez a estar aquí. El semestre pasado, Joaquín nos acompañó también en el salón. Gracias por volver a repetirlo, Joaquín. Con mucho gusto. 

00:01:09 - Pueden ver mi pantalla. ¿Sabes? Perdí la conexión un poco. Déjame volver a conectar mientras muevo la computadora. Ha estado fallando. 

00:01:23 - ¿Me escuchan? Bueno, sí, te escuchamos. Si quieren irse conectando por Teams, también pueden hacerlo, por si no logro conectar aquí la pantalla. Solo necesito que todos en mi otra llamada se mantengan en silencio para que no se vicie el micrófono. 

00:01:37 - ¿Ah, sí? Pero sí se pueden desmontar en cualquier momento si tienen dudas, con toda confianza. 

00:01:44 - Hola, buenos días. 

00:02:14 - Hola, hola. No creo que aprendí. Ahí está, ya estamos. Ahora, sí, déjame ver si conecta mi laptop. Hola, hola. 

00:02:47 - Sí, no. Ya había funcionado, pero mientras movía la computadora, como que dejó de funcionar. Siento que está fallando, más bien es el cable de HDMI, ¿no? A veces hay que revisar el audio para ver a dónde se está mandando. 

00:03:21 - Sí, pero no hay problema. Ni siquiera está recibiendo la señal. No, no, no puedo acceder. Pero creo que sí te escuchamos. No sé si alcanzan a escuchar hasta atrás. 

00:03:34 - Sí, sí, y nos conectamos por Teams. Entonces, adelante, Joaquín. Ustedes me dicen. 

# Desarrollo de Soluciones con Inteligencia Artificial

00:03:39 - Bueno, esta presentación es como una introducción a cómo desarrollar soluciones con inteligencia artificial. Hay un término que está muy de moda, que es el de ingenieros de IA, que creo que es una combinación de cosas que ustedes ya saben y que están aprendiendo como ingenieros en sistemas, más algunas otras cosas. 

00:04:00 - Es un poquito de lo que vamos a estar hablando, pero siempre tenemos que estar muy enfocados en construir soluciones, no tanto en la tecnología, sino al final en el producto que queremos hacer. 

00:04:19 - ¿Ya me presentó Elvia? Entonces, soy ingeniero, y sí, es un poquito diferente a otros roles ya establecidos en la industria, como un data scientist o un machine learning engineer. En el sentido de que, por ejemplo, un engineer no está construyendo o desarrollando nuevos modelos, ni siquiera está haciendo reentrenamiento de modelos existentes. 

00:04:46 - No requiere, al menos para esta parte de construir soluciones con inteligencia artificial, de teoría muy avanzada sobre inteligencia artificial, redes neuronales o matemáticas. No se enfoca en ese estilo, sino simplemente en conocer muy bien los modelos y las herramientas que se pueden utilizar para crear soluciones aumentadas, en inglés, con inteligencia artificial. 

00:05:18 - Mucho de esta presentación, además, ya hay, o sea, como el término está muy de moda, a lo mejor ya han visto esta página de Roach, que es muy buena, y justo acaban de estrenar este nuevo de Einer, que trae muchos términos y buenos links para profundizar más. 

00:05:38 - A grandes rasgos, podemos decir que cuando vamos a construir este tipo de soluciones, vamos a tener ciertos binding blocks, ciertas piezas de lego que vamos a usar para construir estas soluciones. La primera, muy obvia, es esta herramienta, que es como ChatGPT, que nos vino a revolucionar toda esta industria y acelerar todo por ahí a finales del 2022. 

00:06:06 - Esa es una herramienta, los prompts, que es la manera en la que vamos a estar interactuando principalmente con estos elementos. El conocimiento que pueden obtener estos elementos no es solo el que ya tienen porque ya fueron entrenados por alguien más, sino el que les vamos a dar nosotros de nuestros usuarios y de nuestra tecnología para mejorar la aplicación. 

00:06:29 - También hay integraciones con otros servicios, y vamos a ver que hay muchos otros modelos de los que podemos servir. No todos son modelos de lenguaje. Hay muchos otros modelos que, como ingenieros, es muy bueno conocerlos para no centrarnos únicamente en matar mosquitos a escopetazos. 

00:06:57 - Además, es importante saber cómo implementar algo de integración continua y despliegue continuo en nuestras soluciones para que sean robustas y funcionen bien en producción. Esto también está basado en otra presentación interesante de Look Marchán, que se titula "Todos podemos ser ingenieros". Esto se basa en el conocimiento que ya tienen. Es decir, si ustedes ya saben lenguajes de programación, librerías, bases de datos e integraciones con servicios, ya tienen mucho de lo que se necesita.

# Componentes y Evaluación de Modelos de IA

00:07:28 - Ahora, vamos a ver algunos de estos componentes, estas piezas del ecosistema. La primera, la más importante, es donde vamos a pasar más tiempo, en la parte de LLMs. Tenemos que escoger entre dos grandes grupos: los LLMs en la nube y los LLMs de código abierto. En realidad, esa línea es un poco difusa, pero es útil para entender mejor las variaciones que vamos a ver entre los LLMs disponibles para nosotros. Estas variaciones vienen dadas por la calidad del modelo, es decir, qué tan buenas respuestas da y qué tanto conocimiento tiene.

00:08:11 - Otro aspecto importante es el tamaño del contexto, o "context window", que es fundamental conocer. También debemos considerar el precio: cuánto nos va a costar hospedarlo, ya sea en nuestros propios equipos o usando un servicio en la nube. Hay muchas maneras de evaluar esto, y hay muchos recursos disponibles, como tablas y gráficos en donde podemos ver cómo están evaluados los diferentes modelos. 

00:08:44 - Por ejemplo, hay un sitio llamado artificialanalysis.ai donde siempre están comparando modelos de inteligencia artificial. Se puede hacer un "drill down" de las pruebas que están realizando. Actualmente, no está actualizado con el último modelo que salió esta semana, que es el Claude 3.7. De hecho, sí está disponible, y lo actualizan muy rápido.

00:09:18 - En cuanto a la velocidad de respuesta, esto también es importante a considerar dependiendo del tipo de aplicación que estemos usando. Por ejemplo, en la parte superior de las evaluaciones está el modelo "Owned Mini". El precio también es un factor a tener en cuenta. Muchos modelos tienen una opción gratuita, pero cuando quieres lanzar algo en producción, esa opción probablemente no será suficiente, y el precio comenzará a ser importante.

00:10:08 - Algo más que quería mencionar sobre el precio es que estas son evaluaciones de otros modelos, y conviene familiarizarse con algunas de ellas. Aquí, por ejemplo, explican exactamente qué evaluación están usando, como la de Nigma, el Multi Challenge o la de Visual Understanding. Dependiendo del tipo de solución que queremos hacer, si tiene mucho de visual, tal vez nos convenga usar Gemini en lugar de otro modelo.

00:10:34 - Esta otra opción es un repositorio de GitHub donde se puede ver cómo está hecho este sitio, lstats.stats.com. Ellos traen una historia de cómo han ido evolucionando algunos modelos con el tiempo. Podemos ver cómo han ido subiendo en sus puntuaciones. En la parte superior, podemos ver a Brock y OpenAI, mientras que más abajo está Mistral, que es una empresa francesa. Ellos tienen más evaluaciones sobre cuál es el mejor para código y razonamiento.

# Introducción a Modelos de Lenguaje y Tamaño de Contexto

00:11:22 - El tamaño del contexto ya lo mencionamos brevemente, pero el campeón indiscutible en este momento es el modelo de Google, que tiene un tamaño de contexto de 2,000,000 de tokens. Cuando necesitamos enviar mucha información, este modelo será de las mejores opciones, junto con otros factores como el precio y la velocidad.

00:12:19 - Parece que ya logré conectar el salón. Déjame cambiar la bocina un segundo. ¿Me escuchan bien? Hola, hola, ¿me escuchan? Sí, los escuchamos.

00:12:39 - Muy bien, esta es otra gráfica que creo que es de las últimas que les quería mostrar. La pongo ahorita; está comparando otra vez el score, ahora contra el precio. Entonces, está nuevamente a la hora de que vamos a salir. A producción va a ser muy relevante, ¿no? Mientras más para acá, mejor calidad de las respuestas, y mientras más arriba son, más caros, ¿no? Entonces, estos que están abajo, pues tienen un súper precio. La versión mini también tiene muy buen precio, y Claud Sweet, pues es un poquito más caro, pero también ahorita es el que tiene la corona del que entiende la mejor calidad de respuestas. 

00:13:22 - Incluso este de Sonnet, este de Claud, en la parte de código es súper relevante, ya que tiene una calificación muy por encima de muchos otros modelos. Estaba escuchando de parte de la comunidad que desarrolla este tipo de soluciones que están impresionados, ¿no?, de la calidad. Además, esto es porque junto con el nuevo modelo, liberaron un software Open Source que puedes usar en tu computadora para ayudarte a codificar, que es como una gente, ¿no?, del código. 

00:13:58 - Entonces, eso lo hace aún más relevante. Hablamos hasta ahorita casi de puros modelos hospedados en la nube. Si se fijan, por ahí había algunos Open Source. De hecho, por ejemplo, de Ipsec lo puedes, lo Torres, normalmente en la nube, porque de hecho correrlo en Python en tu propia computadora no es tan fácil. Para empezar, por el tamaño del modelo, que es un modelo muy grande, no como los modelos de Lama, que hay versiones más chiquitas. Sí, es enorme y no es factible correrlo; más que versiones ya muy reducidas que no tienen la misma calidad de respuestas.

# Privacidad y Soberanía en Modelos Open Source

00:14:32 - ¿Entonces estamos hablando de Claud models? Ahora, ¿por qué querría uno usar o por qué considerar de cualquier manera modelos Open Source? Bueno, hay varias razones muy buenas. La primera que luego sale y que pesa mucho es la privacidad de la información. Si vamos a estar tratando con datos privados de nuestra empresa que no quieren que se estén mandando a proveedores terceros, entonces la única opción que queda es correr modelos Open Source, que puedes correr en tus propios equipos, en tus propios servidores, en tu propia LAN. Así evitas cualquier problema de privacidad o de seguridad de la información.

00:15:16 - Muchas veces, el Gobierno de Estados Unidos, por ejemplo, tiene ese tipo de políticas. Seguramente muchos bancos y muchos clientes van a tener ese tipo de restricciones, a pesar de que muchos Claud providers, como el mismo OpenAI, Concha, GPT, Claud, todos ellos te dicen que si estás usando la versión free, pues nada es gratis en esta vida. Al usarlo gratis, lo que te están cobrando es que van a usar los datos que tú les mandes para seguir entrenando sus modelos. Cuando pagas por sus APIs, ellos te dicen que no, que en la licencia, justo por pagar por sus APIs, ya no van a usar esos datos para entrenar sus modelos. Pero aún con eso, con esa promesa, no hay nada que te la asegure. Con esa promesa de los proveedores cloud, de todas formas, muchos clientes optan por no utilizar estos modelos y más bien pulsar modelos que puedas correr en tu propia computadora, en tus propios servidores.

00:16:15 - Entonces, la privacidad de la información es muy importante. Muy relacionado a ese término está la parte de soberanía, no soberanía de la información y de la tecnología. Ahí podemos ver, por ejemplo, cómo famosamente Estados Unidos, en su Gobierno, no va a querer que usen modelos chinos. Los chinos seguramente también tienen restricciones similares en donde, por nada del mundo, van a estar usando modelos gringos. Los europeos invierten también fuertemente en modelos propios, como esta compañía de Mistral. Israel tiene sus propios modelos, y así. Esta parte de soberanía de la información es no depender de fuerzas externas, tener control sobre la tecnología y la información que manejas, es un concepto muy importante. 

00:17:01 - No solo aplica a países, también puede aplicar a empresas. Esto está muy relacionado con la privacidad, pero la soberanía también te puede orientar a usar modelos Open Source, que además van a tener más transparencia. Puedes tener más confianza en ellos, porque si tienes alguna duda de por qué se está comportando de cierta manera, los puedes ver. No son Open Source y, por eso, al ser abiertos, puedes ver cómo es que las respuestas se están generando de cierta manera. 

00:17:31 - Algo que hay que mencionar es qué tan Open Source realmente es el modelo, ¿no? ¿Qué tan abierto realmente es? Porque hay tres cosas que pueden abrir. Una cosa es abrir los pesos del modelo, que es como quien dice que puedas usar el ejecutable, el bajarte el punto exe y usarlo. Eso depende de la licencia que le pongan, y muchas licencias de estos modelos son licencias abiertas, que puedes usar para lo que gustes. Algunas tienen licencias no comerciales. Algunos de estos modelos los puedes usar, pero para usos más bien educativos, académicos o de investigación, pero no para uso comercial. Hay que revisar la licencia, pero eso de liberar los pesos es, es, es como liberarte una estable. No, realmente no hay una transparencia sobre cómo funciona el modelo.

00:18:22 - Algunos liberan también el dataset, que es lo más raro; en realidad, muy poco liberal en el dataset, pero sí hay algunos datasets libres que puedes ver, o pueden liberar el código. El código necesario también para, ya sea que usaron para entrenarlo o el que se usa para correrlo, ¿no? Y bueno, dentro de estos niveles de transparencia es donde vas a ir ganando confianza también en el modelo. Con esta transparencia y con esto que podemos ver del modelo, de cómo funciona, pues también nos permite customizarlo de mejor manera. Es más fácil customizar modelos Open Source, que puedes bajar el modelo y entrenarlo en tu propio equipo, que hacer este tipo de customizaciones contra modelos como los de OpenAI y otros proveedores.

00:19:14 - Siempre se habla primero de OpenAI porque es el primero y es de donde muchos se están copiando muchas de estas buenas prácticas. Te ofrece de manera de hacer fine-tuning de su modelo, pero es difícil, es costoso y te estás atando a ese modelo. Mientras que si lo haces con un modelo Open Source, tienes un poco más de libertad hacia donde moverte. Te estás dejando de depender de un proveedor externo.

# Ventajas de Usar Modelos Open Source

00:19:45 - Finalmente, otra parte que se menciona aquí es usar Open Source para ahorrarnos dinero. Bueno, con todo lo que han sido abaratados los costos. Les mostraba yo esta tablita anterior, donde los más baratos realmente son OpenAI con GPT-3.5, que es súper barato. Claude de Anthropic tampoco es tan caro. A Jiminy, no sé por qué, pero es baratísimo; realmente es ridículo lo que cuesta el token. Entonces, a veces no tanto, vamos a ahorrar en el costo. Sí, pueden ser mucho más eficientes algunos de estos modelos en la nube, pero está también este componente en donde un modelo Open Source puede llegar a correr incluso en tu computadora.

00:20:28 - Hay modelos Open Source que puedo correr en mi computadora personal, en una MacBook Pro, por ejemplo, o en una computadora que tenga estos últimos chips que está sacando Intel o AMD, que tienen soporte para inteligencia artificial. Con cierto RAM, pueden correr en esos, o incluso en celulares. En el edge, le llaman. Hay modelos tan pequeños que pueden correr también ya en tu celular o en dispositivos pequeños como Raspberry Pi, por ejemplo. Entonces, ciertamente puede haber también un ahorro en costos, puesto que no estás necesitando ni siquiera correrlo en un equipo que ya tienes.

00:21:06 - Aquí también puede haber cierto ahorro a la ecología. Además, estos modelos, como se sabe, cómo funcionan los modelos Open Source, son los que han avanzado mucho más en esta parte de la eficiencia y del ahorro en qué tan caro es correrlos. Son los que han empujado 100% a que bajen los precios tan dramáticamente los modelos en la nube. Entonces, sí vale la pena considerar eso también.

# Evaluación de Modelos Open Source

00:21:38 - Entrando ya a evaluaciones de modelos Open Source, está este, por ejemplo, el leaderboard de Hugging Face. Para estos screenshots, solo listé los proveedores oficiales como para alistar aquí los más famosos, justo para que salga. Por ejemplo, cuenta que es un modelo chino, de los mejores modelos que puedes correr justo en hardware relativamente que no necesitas un supercomputador. Está Mistral, este modelo europeo que les llamaba la AMA, obviamente de Meta. 

00:22:08 - Entonces, estos modelos los podemos ver en este listado. Hay otros filtros en donde si dices tú: "Oye, ¿cuál puedo correr en un consumer device? ¿No? ¿En una PC? ¿Cuál puedo correr en un celular?" Y si se fijan, lo que baja principalmente es el número de parámetros. Estos modelos cuentan con 72 billones de parámetros. Vic tiene 600 billones de parámetros. En realidad, no es factible correrlo más que en un supercomputador. 

00:22:33 - Estos modelos, para que puedan correr en computadoras personales, tienen 3.5. Esta es la versión a 3 billones de parámetros, a 6 billones de parámetros, y corren en una computadora personal. 

00:22:49 - Si nos vamos a los que son para edge, no tengo aquí abierta la ventana, pero seguramente nos van a salir modelos de un billón de parámetros, máximo dos billones de parámetros. Y esos sí que son modelos que podrás correr también hasta en tu celular muchas veces. Ah, hay por ahí, creo que el link lo tenía por acá, donde lo dejé. 

00:23:12 - Ah, sí, este. Bueno, también la pregunta que luego sale es porque no sale de ipsec, ¿no? En estos sí, si es de los más chidos Open Source, pues bueno, ahí cierta especulación. En el mismo foro, Foro de Joaquín FACE, en donde, seguramente una parte es porque es un modelo de 600 billones de parámetros. Es grandísimo y los modelos que salen en esa tabla llegan hasta 140,000,000 de parámetros. O tal vez también porque dic todavía no corre con la librería de Transformers, que es una de las librerías Open Source más usadas. 

00:23:44 - ¿Sino es que la más usada para correr este tipo de modelos, no? Bueno, entonces, si tenemos alguna de estas características que nos dice, creo que un modelo Open Source sería una buena idea. ¿Cómo los corremos? 

# Implementación y Ejecución de Modelos Locales

00:24:01 - Lo más sencillo y por donde les diría que comenzar es por este software de O Lama. Por detrás, usa la más P o otro proyecto en C++ que corre. No puede correr en GPU, pero también corre en CPU, es decir, no necesitas una super tarjeta gráfica para correr O Lama o para correr algunos de estos modelos. Entonces, esa es la manera más sencilla. Es como el Docker de los L Tnes. Yo lo tengo instalado en mi computadora, tengo varios modelos ahí y es muy eficiente. 

00:24:28 - Yolanda, después también lo podrías correr en producción en algún servidor Linux. Podrías correr O Lama y estar corriendo ahí tus modelos ya para sistemas en producción. Correrlo tal cual sobre Python también es una opción porque permite ciertas optimizaciones que tal vez O Lama no soporta para CUDA. Por ejemplo, hay un proyecto que se llama BLM que es muy eficiente para servir a millones de clientes, desde Python o para la Mac. 

00:25:01 - Hay cierto código de Python que utiliza bien los procesadores de Mac optimizados para inteligencia artificial, específicamente la arquitectura MLX, que O Lama hoy en día no lo soporta. Hay un ticket abierto por ahí, pero no han agregado esa funcionalidad. Entonces, hay ciertos casos en donde conviene correr este código de Python. 

00:25:27 - Ah, o si está. Nada más probando, hay uno que se llama El Estudio. Este no es Open Source, O Lama sí es Open Source. El Estudio no es Open Source, pero también si quieren jugar con modelos en su computadora, esta es una buena solución que sí corre esta arquitectura de MLX con Python en la mano. Entonces, también vale la pena considerarlo para jugar, no para producción. 

00:25:53 - Y hay algunos estimadores de qué tanto RAM necesitarías para correr un modelo de manera local en tu computadora. Por ejemplo, aquí te está diciendo que tengo un modelo de 25,000,000 de billones de parámetros que está cuantizado. Cuantizado es una palabra que usan para decir que los modelos normalmente están basados en arreglos de vectores que tienen 16 bits y luego le reducen el número de bits en cada uno de esos vectores para reducir el tamaño del modelo. 

00:26:25 - Sigue teniendo 25,000,000 de parámetros, pero en números más chiquitos que los hacen más eficientes. Si bien pierden, claro, bastante de la calidad en la respuesta, no toda. O sea, no se vuelven tontos, pero no tienen la misma calidad en las respuestas. Entonces, un modelo de estos de 25 billones de parámetros cuantizado a cuatro bits se estima que pudiera correr, por ejemplo, con una computadora que tenga 16 GB de RAM. 

00:26:50 - Así que podemos ver que si bajamos los números de parámetros a algo más chiquito, por ejemplo, yo tengo 8 gigas de RAM. ¿Puedo correr? Tal vez hasta 9 billones de parámetros con una cuantización de cuatro bits. Este fue el primero que encontré en Internet. Hay otras calculadoras, ya no me gustó esta, que no pude más bien modificar yo los parámetros y que me diga el RAM. 

00:27:20 - ¿El RAM te dice cuál modelo estima que vas a poder correr? Hay más, hay más calculadoras y nos da una idea general. Esta computadora que tengo yo aquí tiene 36 gigas en RAM. Entonces, puedo poner modelos más grandes. 

# Integrating Large and Small Models

00:27:36 - Finalmente, esta frase que me gusta mucho de este comercial: ¿por qué no los dos? Acaban de anunciar también esta semana un proyecto en colaboración, me parece que es la Universidad de Stanford, junto con Obama, en donde están haciendo proyectos en los que corren, por un lado, un modelo muy grande, remoto, como ChatGPT o como Claude, junto con modelos chiquitos locales de 8,000,000 de parámetros como O Lama. 

00:28:08 - Juntos pueden resolver problemas a una fracción del costo que si se lo mandaras nada más al modelo grande. El costo de resolver el problema es muy, muy alto, y la calidad de la respuesta es la mejor. Pero si usas esta combinación de un modelo grandote orquestando muchos modelos chiquitos para cosas más sencillas, obtienes una muy buena calidad de respuesta a una fracción del costo.

00:28:37 - Entonces, este tipo de soluciones para algunos problemas, obviamente, no funciona para todo. Es un nicho muy específico de problemas, por lo que vale la pena investigar este tipo de soluciones. No solo se trata de usar ambos modelos, sino que algo más que les diría es que intenten desacoplar, de todas formas, al principio que están desarrollando una solución. Desacoplar no significa casarse por completo con algún modelo, puesto que este está evolucionando constantemente. Es bueno usar librerías; hay libros para empezar. La mayoría de muchos de los proveedores soportan el mismo API que OpenAI.

00:29:21 - Por ejemplo, el mismo cliente que estás usando en Python o en JavaScript de OpenAI para conectarte a la API, si le cambias el servidor y en vez de apuntar a OpenAI, apuntas a tu local host corriendo, va a funcionar. Entonces, hay mucha interoperabilidad. Por un principio, conviene no casarse tanto con un modelo específico. Me gustó muchísimo la idea de no casarse con el API de OpenAI, sino usar herramientas que te atraigan un poquito.

00:29:49 - OpenAI y su cliente son una de estas herramientas. Otras en Python son algunas librerías como Little Lem, que es una sola librería con la que te conectas a todos los que quieras. Esta librería soporta muchísimos proveedores. Hay otra de un compañero llamado Andrew en G, que es famoso porque tiene un sitio de "AI for Everyone" y ofrecen cursos gratuitos de inteligencia artificial. Su equipo liberó una librería que se llama AI Suite. También hay ejemplos de esa librería que es multi.

00:30:23 - En JavaScript, también hay librerías como Lem 10. Ross tiene las suyas. Hay otra de una persona llamada Jason Lee que se llama Instructor, que es muy interesante. Esa misma librería tiene soporte para Python, TypeScript, PHP, Ruby, Elixir, y seguramente con distintos niveles de soporte. En realidad, Python casi siempre es lo más importante en este tipo de soluciones. En segundo lugar, diría que JavaScript es relevante.

00:30:50 - Una opinión que tengo, que puede ser un poco controversial, es que siento que es mejor evitar, al menos en un principio, o sobre todo ustedes que están aprendiendo a desarrollar este tipo de soluciones, librerías grandísimas que tratan de abarcarlo todo, como LangChain o como LlamaIndex. Se convierten en una capa de abstracción tan grande que te conviertes más en un ingeniero de LangChain o de LlamaIndex y en realidad no aprendes el detalle fino de algunos de los componentes de estas soluciones. 

00:31:30 - El lenguaje es un componente muy importante que puede tener su propia capa de abstracción, pero hay muchas otras partes de estas soluciones. Son bloques de Lego que les comentaba. Si todo lo estás usando con LangChain, creo que al final más bien te va a limitar, además de que tiene su propia curva de aprendizaje muy grande. Esa es mi opinión personal, y es una opinión muy compartida también en algunos foros.

# Knowledge Management in AI Solutions

00:31:53 - Ahora, pasemos al siguiente bloque de Lego, que es el conocimiento. Bueno, los modelos ya tienen conocimiento, pero ¿cómo doy conocimiento que ellos no tienen porque es propio de mi compañía, de mi organización? Lo más normal es, por un lado, pensar en el fine-tuning. Pero el fine-tuning es muy caro. En realidad, la solución por defecto que más se usa es aumentar justo el conocimiento que ya tiene, haciendo copy-paste, como quien dice, en el prompt de la información a la que tiene acceso el modelo para lograr hacer esto. 

00:32:35 - Para ello, necesitamos una base de datos. Esta es una presentación más larga que tengo, nada más con un resumen de sistemas RAG, en donde normalmente tienes dos pasos. Por un lado, en tu base de datos, tienes toda la información que tú tengas de tu compañía, que bien puede ser las órdenes de compra, documentos en PDF o lo que sea. La indexas para que pueda ser buscada cuando el usuario esté interactuando.

00:33:12 - En un primer momento, indexas toda esta información para las búsquedas, y cuando el usuario esté interactuando, ya sea haciendo una pregunta directamente en un chat o interactuando con algún filtro, vas a poder convertir esa interacción del usuario en un vector o algo que puedas buscar fácilmente en esta base de datos que tienes de toda tu información. Así, puedes traerte el contenido relevante de la base de datos y enviárselo al usuario para dar una respuesta.

00:33:47 - Este tipo de soluciones RAG son súper típicas. En aprender más o menos cómo funciona, ¿no? Pero a grandes rasgos, estos son todos sus componentes. No es una base de datos de vectores que bien puede ser el mismo PostgreSQL. Ya manejan Esquivel Light, MySQL; son bases de datos que soportan también búsqueda de vectores. 

00:34:08 - ¿O hay bases de datos especializadas? Pero si ya están usando alguna base de datos de estas no relacionales, les diría que simplemente le agreguen este componente de vectores. Si quieren usar una base de datos especializada como Chroma, hay muchas opciones; también lo pueden hacer, ¿no? Este componente de búsqueda es la parte importante, ya que pueden hacer búsquedas de texto normales. Full text search, que tiene sus propios índices para full text search en MySQL. Lo mismo ocurre con otras bases de datos, o lo pueden combinar con estas búsquedas de vectores para hacer búsquedas no tanto basadas en los keywords, sino en el sentido de lo que estás buscando en la aplicación. 

00:34:56 - Y eso, entonces, ya ese conocimiento que tú tenías en la base de datos se lo vas dando al LLM conforme el usuario lo necesita para poder ir produciendo respuestas. Eso es, a grandes rasgos, cómo funciona una solución RAG. Este es un prompt, uno de los componentes que mencionamos. También estos Lego blocks son los prompts. Este es un producto típico para una solución RAG, ¿no? En donde, tal cual, ya hiciste la pregunta del usuario. 

00:35:25 - Llegó la pregunta del usuario, hiciste una búsqueda en la base de datos y te trajiste documentos relevantes que le vas a dar al LLM en el prompt. Entonces, al front, casi casi le pones casi literal el contexto y le pones todos los documentos que te trajiste de la base de datos. Los puedes poner formateados en JSON o en XML, o si es puro texto, pues simplemente copypaste del contexto. Luego, unas instrucciones típicas de un programa de RAG son: "Utiliza este contexto para contestar la pregunta. Si la respuesta no está en el contexto, di que no sabes". 

00:36:01 - Y ahí estás un poquito, también evitando las alucinaciones, y lo hago con mi padre de la pregunta, ¿no? Y esto es un solo plan que le mandé a Salem y ya te va a dar una respuesta basada en tu conocimiento. Entonces, si se fijan, esto es algo en realidad bastante sencillo. 

# Data Integration and Structuring Outputs

00:36:17 - Otro componente que mencionamos son las integraciones. Para hacer estas integraciones, como esta misma, no lo estamos integrando con nuestra base de datos. Hay que pensar en dos cosas. Por una parte, tenemos que estructurar el output que nos genera para poder hacer estas integraciones. Muchas veces necesitamos que la respuesta que venga del LLM, ya junto con el input del usuario, etcétera, venga formateada de cierta manera que nosotros la podamos usar en nuestro sistema. 

00:36:48 - No nada más para un chat. Un chat es lo primero que pensamos cuando estamos hablando de soluciones aumentadas por LLMs o por inteligencia artificial. Pero no, no nada más con los chats. Si queremos otro tipo de cosas, por ejemplo, podemos extraer información de los inputs del usuario, de un texto o de una imagen. 

00:37:08 - ¿Podríamos sacar, por ejemplo, de un recibo que nos está dando el usuario? Podemos sacar los line items, cada ítem, cuánto cuesta y el total. De una foto que era difícil de parchear, el LLM nos ayuda a obtener un JSON con esta información. O si tenemos recetas de cocina, un recetario, y lo escaneamos, podemos pedirle a un LLM que nos vaya dando de cada receta el nombre de la receta, una lista de ingredientes en formato JSON y las instrucciones de cómo prepararlo. 

00:37:39 - Entonces, estamos de contenido no estructurado, sacando contenido estructurado que podemos utilizar de distintas maneras en nuestra aplicación. O le damos un CSV, un PDF que tiene tablas, a lo mejor información financiera, y queremos que esa tabla nos la convierta en un CSV para poderlo usar en nuestra aplicación de cierta manera. Esto es un uso muy típico de este tipo de soluciones, estos modelos en donde de contenido no estructurado estamos sacando contenido ya útil para nuestras aplicaciones. 

00:38:11 - Ya se hizo, nosotros podemos operarlo dentro de nuestro sistema. Podemos acceder a cierto campo y mostrarlo en cierta parte de nuestra interfaz. Entonces, como se hace mucho de esto, puede ser en el mismo prompt. En el mismo prompt, por favor, quiero que des la instrucción de que el output venga de esta manera y le das un ejemplo de cómo quieres formateado el output. Esta es una manera, o hay librerías que te facilitan esto. También OpenAI tiene su formato para hacer estructural, para que te devuelva JSON y lo mandas de cierta manera en su API. 

00:38:51 - Lo mismo con Jenny. Tienes algunos ejemplos muy buenos aquí, justo para, por ejemplo, extraer las recetas, ¿no? ¿Y cómo logras que te mande? Así es, eso que les comentaba: el nombre de la receta, los ingredientes, las instrucciones. Vienen ejemplos de cómo lograrlo. Casi todos los ejemplos en realidad que están mostrando son como este, cómo obtener el clima, me parece. No les voy a EH.

00:39:15 - Hola, Ma. Si usan la librería de Obama o Llama, también tiene facilidades para intentar obligar a los QL Tnes que usó la AMA para que te manden output estructurado en algún formato específico, como JSON. Cuando te vas a esa funcionalidad, hay ciertos modelos que puedo usar y otros que no. Entonces, también hay foros en donde dicen: "Oigan, estoy usando la AMA, pero no me funciona bien con tal modelo para producir JSON". Ah, es que te recomiendo usar este otro, no esta librería que les mencioné antes de Instructor. Este es un código de Instructor, nada más. Así, muy rápido, para ver cómo funcionaría.

00:39:51 - Algo así están usando un modelo cloud que es de coger, pero si le cambias de aquí a en vez de usar coger a usar OpenAI, es el mismo código. Entonces, simplemente le dices, "from coger" o "from OpenAI", le mandas el cliente, le mandas tu prompt y le dices qué modelo quieres usar. Le mandas, a lo mejor, un pedazo de texto en donde alguien te está diciendo: "Ah, pues tengo 25 años y tú quieres extraer el nombre de la persona y su edad". Entonces, parchear esto con un retweet, ¿sí? Pues cambia constantemente, ¿no? 

00:40:24 - Entonces, para nosotros, programarlo tradicionalmente sería difícil extraer ese tipo de datos. Para LM es muy sencillo, ¿no? Entonces, más bien defines en Instructor una clase de los campos que necesitas extraer y es lo que mandas. Respondes, modelas y esto te va a hacer más o menos lo que necesita OpenAI o lo que necesitan distintas librerías para hacer esa estructura. Al final, ya vamos a tener un objeto que tiene esos campos parcheados.

# Integrating Functions with Language Models

00:40:55 - Este es un ejemplo muy pequeño usando Instructor, no para hacer todo, sino para hacer integraciones. Es una de las cosas que necesitas. Otra muy importante es función Collins, o Tool, que es otro nombre con el que se le conoce a estas funcionalidades. En el ambiente OpenAI, Cloud Mining o Llama, también tienen tus PS para cómo hacer que los LM mismos. 

00:41:21 - Acá nosotros estamos más bien de la respuesta del LM. La vamos a usar para nosotros insertar algo en la base de datos, pero nosotros en nuestro código que escribimos no. Mientras que en función Collins le vamos a decir al LM qué funciones tiene disponibles para que él decida si las quiere llamar o no, en base a las instrucciones del usuario. Entonces, es un uso un poco diferente, ¿no? Este es más reactivo y no depende de nosotros si se va a llamar la función.

00:41:53 - Los ejemplos también están padres. Casi siempre, casi todos estos ejemplos son acerca del clima, de que el LM responde de acuerdo a las preguntas del usuario. Si tiene que, si tiene una función para obtener el clima actual, este provee al usuario, ¿no? Bien, las instrucciones. Vamos a ver otra vez un ejemplo muy pequeño con esta otra librería que les mencionaba, que se llama E-Suite, que te ayuda a usar, te abstrae un poco la dificultad de hacer esto.

00:42:20 - Función Collins, desde estos elementos, es un ejemplo chiquito, ¿no? Entonces, defines tu función "Willy Trains" y necesitas mandar la ubicación, ¿no? De en dónde estás y la hora del día. En base a eso, tú ya checas algún servicio externo o algo que tengas por ahí para devolver una respuesta. 

00:42:45 - Por ejemplo, en este caso, esta es la función que quieres que el LM pueda llamar. Tienes los inputs del usuario que llegan y, por ejemplo, aquí hay un usuario que está diciendo en su input: "Yo vivo en San Francisco, ¿pudieras checar el clima? Planeo hacer un picnic alrededor de las dos". Entonces, a la hora de que usas esta librería, simplemente le mandas las herramientas disponibles, las funciones que va a tener el LM para decidir si la va a llamar o no. Le agregas un parámetro de cuántas veces puede iterar en estas llamadas para mandar la respuesta final al usuario y listo.

00:43:19 - El LM solito va a llamar tu función y va a crear una respuesta con el output de la función para responder la pregunta del usuario. Otro ejemplo muy típico es llamar funciones externas que el LM pueda llamar para checar el clima, checar tu base de datos, insertar nuevos récords en la base de datos, leer récords de la base de datos, etcétera.

# Understanding Agents in AI

00:43:46 - Y eso nos lleva un poquito a este buzzword que está muy de moda hoy en día, que es "agentes". Vamos a hablar un poco de agentes. 

00:43:54 - Hubo, esta semana, no, la semana pasada, una conferencia en Nueva York que era el "Engineering Summit", donde, por ejemplo, justo Adrián habló mucho de agentes. Alguien definía a los agentes; él es uno de los organizadores de la conferencia. Decía que normalmente un agente consiste en tener tu modelo equipado con instrucciones que puede dar el usuario sobre lo que quiere hacer. Hay que definir qué cosas sí puede hacer y qué cosas no. Además, hay herramientas o funciones que puede usar para extender las capacidades de este modelo que corre en un runtime. 

00:44:37 - Esta definición está un poco rebuscada, pero es útil. Después salió una definición mucho más sencilla, que diría que es: un agente es simplemente un modelo que tiene acceso a funciones y herramientas, y que está corriendo en un loop, en un "while true". Este modelo tiene acceso a ciertas herramientas y las puede usar si lo necesita. Por ejemplo, el agente que liberó Anthropic, y tú puedes ver el código fuente, es bastante más completo. Te dice cómo funciona esta herramienta de Anthropic que todo el mundo amó, cómo te ayuda a hacer código, y tú le puedes leer el código fuente, te lee todo tu directorio, te puede modificar algunas cosas, agregar comentarios a tu repositorio de Git, etcétera. 

00:45:33 - Tiene muchos tools disponibles, como un "dispatch agent", que puede correr cosas en el backend, leer archivos de tu línea de comandos, editarlos, reemplazar pequeñas cosas, etcétera. No tiene muchas herramientas disponibles que simplemente están corriendo en un loop dentro de su código. No es realmente un "while true"; se ejecuta esto y no es más que eso, no tiene un servidor externo. En resumen, un agente es un modelo con acceso a funciones que corre en un loop. 

# Testing and Validation in AI Solutions

00:46:10 - Esto es para intentar desmitificar esa palabra. Tiene mucho buzz hoy en día, pero no es más que eso. ¿Ya pueden construir ustedes sus propios agentes? Bueno, esto va a ser muy importante, también la parte de cómo probar, ya que les están enseñando a ustedes todo acerca de "unit testing", "functional testing" y "automation". Cuando haces soluciones con inteligencia artificial, también vas a necesitar probarlas. 

00:46:41 - Algunas recomendaciones: obviamente, estas pruebas deben estar corriendo de manera automática, con integración continua, mientras están haciendo el código, para que constantemente lo estén evolucionando. Si cambian el modelo, por ejemplo, si estaban usando Claude 3.5 y salió el 3.7, se actualizan. Seguramente algunas pruebas se van a romper porque está cambiando el modelo que estás corriendo por detrás. Entonces, correrlas en un loop continuo con tus pruebas va a ser súper importante. 

00:47:16 - Va a ser muy importante involucrar a "subject matter experts", es el término, a gente que entienda muy bien el conocimiento de tu aplicación, de qué se trata, qué tipo de conocimiento es importante, qué tipo de respuestas son las que esperamos y que sean ejemplos realmente significativos para que esos ejemplos de uso real de tu aplicación los puedas probar. Es importante tener un set de pruebas que sea significativo. 

00:47:49 - Normalmente es muy famosa esta frase cuando se habla de datos en sistemas: "si le metes basura al sistema, te va a sacar basura". Entonces, es importante que estas pruebas sean buenas. Normalmente vas a estar checando la entrada del sistema de información. Si estás usando algún sistema para traer información de tu base de datos para responderle al usuario sobre alguna cosa, algo que puedas probar sin siquiera irte a la parte de LM son tus mecanismos de búsqueda que te estén regresando los registros de la base de datos que tú esperas que te regresen en los primeros lugares. 

00:48:27 - Es muy sencillo: simplemente haz pruebas de integración de tu base de datos. Cuando llega cierto input del usuario y tú buscas en la base de datos, esperas que el resultado top sea este, porque sabes que ese es el documento relevante. Ahí es donde es muy importante el experto de tu base de datos, que sepa realmente cuáles son las respuestas relevantes que estás esperando. Eso es muy fácil de probar; es simplemente un query en la base de datos. 

00:48:58 - ¿Y cuáles son los resultados que estás esperando? Conforme a eso, probablemente las pruebas las vas a tener que cambiar cuando cambien los queries de datos, pero te van a dar una idea de si tu sistema se está rompiendo desde el input de conocimiento que le estás mandando. 

00:49:12 - Otro tip es que también el output del modelo, es decir, las respuestas que generas, tienen que ser revisadas. Si se fijan, hay este argumento de temperatura, que te dicen que si le pones una temperatura alta, el modelo es más creativo. Lo que está haciendo es agregarle un elemento aleatorio a las respuestas que genera. Si tú pones esa temperatura en cero, le quitas el elemento aleatorio y a un input te debe devolver siempre el mismo output. 

00:49:46 - Entonces, en tus pruebas del contenido que esperas generar con el modelo, pones la temperatura en cero, envías un input del usuario y vas a esperar cierta respuesta, ¿no? Esa puede ser una prueba de integración muy buena y certera. Si modificas algo en tu sistema y se rompe, vas a ver que algo pasó y necesitas modificar algo en el código.

# Exploring Specialized AI Models

00:50:08 - Y bueno, ya casi se nos acaba el tiempo, pero también creo que es muy importante aprender que estábamos hablando de modelos de lenguaje, pero hay muchos otros modelos que vale la pena considerar cuando estamos empezando a hacer soluciones aumentadas con inteligencia artificial. La inteligencia artificial no solamente son estos modelos de lenguaje; hay muchos modelos. 

00:50:29 - Voy a mencionar algunos, por ejemplo, modelos más especializados. Unos son los modelos de embedding que se usan justamente en estas soluciones. Hay de muchos tipos, algunos son solo para inglés o para chino. Hay otros modelos de embedding que son multilingües o solo de francés, o creo que solo de español. No he visto muchos de esos modelos que te pueden sacar también cuál es el vector que define una imagen, no solo un texto, para poder buscar imágenes o videos. También hay modelos de embedding que te ayudan a sacar el vector de medios, de una imagen, de un video, de un sonido. 

00:51:08 - Así podemos, desde nuestra base de datos, traernos el contenido relevante. Para eso sirven estos modelos de embedding. Hablando de todos estos ejemplos, la gran diferencia es que son modelos especializados y mucho más pequeños que corren de manera más eficiente. Normalmente, los modelos de lenguaje, incluso los de código abierto, van a necesitar un servidor potente, probablemente, si quieres respuestas de calidad. Pero estos modelos especializados, por ser más pequeños, pueden correr en hardware más limitado. 

00:51:36 - Hay algunos de estos modelos de embedding, por ejemplo, que corren en mi Raspberry Pi. Entonces, tú puedes tener tu sistema en producción, con la base de datos de vectores ya indexada. Cuando llega una pregunta del usuario, todo está corriendo en la Raspberry Pi, que está tomando la pregunta del usuario, convirtiéndola en vectores para comparar y buscar cuáles vectores son los más cercanos a esa pregunta. Luego, generas la respuesta con un modelo que está hospedado en otro lado, no en la Raspberry Pi, pero el modelo de embedding sí puede correr en ella.

00:52:12 - Otros modelos, como los modelos de visión, te permiten extraer información de imágenes. Claro que puedes usar modelos grandes para eso, pero hay otros modelos más pequeños, como Mondrian o Small Vision Language Model, que también te permiten hacer este tipo de cosas, como la detección de un coche en un video, extrayendo marca y modelo. Esto puede estar corriendo con un modelo pequeño, en lugar de un modelo enorme de 600 millones de parámetros; estos modelos son de 2 billones de parámetros y saben correr en dispositivos mucho más pequeños. 

00:52:54 - Entonces, vale mucho la pena verlos. Puedes describir imágenes, detectar objetos, extraer información. Por ejemplo, extraer de un recibo los precios individuales y el total lo puedes hacer con modelos grandes, pero también con estos modelos pequeños y gratuitos en tu computadora o en tu teléfono. 

# Applications of AI in Text and Speech Processing

00:53:15 - Otros modelos especializados son para extracción de texto, como el OCR, que era el reconocimiento óptico de caracteres. Convertir un PDF a texto. Hay dos proyectos de código abierto que se usan en otros modelos, como IBM Markup, que si tú le das un PDF, te van a extraer todo el texto, incluso de fotos de documentos, y lo van a formatear en texto. 

00:54:01 - También hay modelos de speech to text. Por ejemplo, Whisper, que es un modelo de código abierto que puedes usar para escuchar audio y traducirlo a texto. Esto puede ser muy útil. Justo hicimos unas aplicaciones hace algunos semestres, donde los alumnos ayudaban a practicar inglés. Entonces, tú le hablabas a la computadora, extraía el texto, y ese texto después lo evaluaban con algunos problemas usando un modelo de lenguaje que te decía si estaba bien o mal. 

00:54:31 - La calificación te iba evaluando tu nivel de inglés o te ayudaba a practicar tu inglés. No, y eso es con el modelo speech to text. Por ejemplo, hay un Whisper web, una versión de Whisper que corre en el navegador. Entonces, tú puedes directamente en el navegador, sin usar un servidor. Es un modelo más pequeño que puede correr en el browser. 

00:54:52 - ¿Depende de la computadora y de qué browser, verdad? Y te puede ir extrayendo en el mismo navegador este texto de audios o de archivos, o de la cámara del video. También. Este es un ejemplo de Mondrian, Bustamante extrayendo, y esto de cómo se usan estos modelos. Es código muy sencillo. 

# Creating Proofs of Concept with Python Libraries

00:55:17 - Finalmente, esto te va a ayudar a crear pruebas de concepto. Hay librerías en Python muy sencillas para esto. Streamline, Graderío, Marimo. Aquí son excelentes librerías de prototipado en Python. Fast HTML también es muy bueno si quieres un poco más de personalización. Incluso aquí hay un código open source hecho por mí, no hay promocionándolo, que es justo toda una aplicación sencilla de cómo extraer texto, hacer búsquedas y luego crear un chat muy sencillo con Fast HTML. 

00:55:54 - Hasta ahí no está súper avanzado, pero es un ejemplo completo de cómo hacer esto en Python. En JavaScript también se puede hacer mucho de esto y hay algunos workshops por ahí de cómo funcionan los embeddings. Hay un video que grabé hace poquito, un repositorio y unos slides. 

# Ethical Considerations in AI Development

00:56:13 - Ah, muy importante, consideraciones éticas. Ustedes que son privilegiados, no simplemente por estudiar en la universidad, digamos en el TEC de Monterrey, y de aprender este tipo de tecnologías, no podemos dejar de mencionar qué es lo que queremos hacer con la inteligencia artificial. Tal cual, como en Spiderman, con gran poder, conlleva gran responsabilidad. Es increíble lo cínicos que son algunas personas. 

00:56:41 - Ahorita que estoy en este espacio, hay quienes dicen que con esto vamos a poder eliminar o cambiar a todo nuestro call center y que sean simplemente algunos agentes. Entonces, nosotros que estamos permitiendo el desarrollo de este tipo de soluciones, ¿cuál es nuestro objetivo? ¿Es realmente reducir la fuerza laboral, ahorrarnos dinero y ganarlo nosotros mismos? ¿O realmente estamos buscando empoderar, ayudar a que más gente tenga acceso a estas tecnologías para beneficio de todos? 

00:57:17 - Los invito a que, conforme aprendan de estas tecnologías, intenten compartir este conocimiento no solo con sus compañeros, sino también con sus papás, con sus vecinos, sobre cómo se usan estas herramientas. Siempre tengan en cuenta para quién están creando estas soluciones. No es para el beneficio de unos pocos, sino de la manera lógica y no solo para ustedes o el cliente de Alcatraz. 

00:57:44 - Es muy importante porque es algo muy nuevo que viene a revolucionar nuestra industria. Cuanto menos cínicos seamos con el tipo de soluciones que desarrollamos, mejor. Hay algunos slides que hablan un poco más sobre otros problemas éticos que están imbuidos en los sistemas de lenguaje. 

00:58:03 - ¿Tienen ciertas tendencias o prejuicios? Casi se pueden mapear. Este modelo es un poco más libertario, es más autoritario, está más alineado a la derecha o a la izquierda. Los modelos ya traen esos prejuicios. Ya hay ejemplos de las preguntas. Hay papeles completos que vienen desde los datos de entrenamiento o a veces simplemente en el fine-tuning. 

00:58:30 - Eran muy famosos ejemplos de los DEC. Si le preguntaban sobre Tiananmen, no te respondía, y no es porque los datos no estén ahí. Luego podían hacer trucos de que, ah, respóndeme, pero reemplazando las "a" por "1" y las "6" por "1". Y sí, respondía. ¿Qué pasó en Tiananmen? Lo mismo pasa con los modelos americanos. Si tú le preguntas a muchos modelos sobre Donald Trump o sobre algún problema político actual, muy probablemente te da una respuesta muy vaga. 

00:58:59 - Muchas veces no sabemos cuál es el resultado óptimo. Si queremos que nuestros modelos reflejen fielmente la realidad, que en nuestra realidad típica siempre hay desigualdades, o si queremos que nuestros modelos de lenguaje sean un reflejo del futuro ideal que estamos buscando. Eso muchas veces nos termina disparando en el pie, como esos ejemplos ridículos que había de Gemini que te mostraba cuando le pedías que te dibujara a los founding fathers de Estados Unidos y todos eran racialmente diversos. 

# Community Engagement and Open Source Tools

00:59:39 - Es difícil encontrar el balance. Bueno, tenemos una comunidad. También los invito a que, si quieren participar, estamos construyendo algunas herramientas open source del RAC para el Diario Oficial de la Federación. Estamos ahorita penetrando ese proyecto.

00:59:52 - Algunos ejemplos de código que les mostré, un canal de Discord que apenas está empezando, entonces en realidad está ahorita muy callado, pero hay otros por fuera. Por ejemplo, hasta este de Jogging FACE tiene un canal de Discord, y ese sí, con muchísima gente que está interactuando sobre cómo construir soluciones con Open Source e inteligencia artificial. Este sí busca hogar, Johnny FACE, Discord.

# Reflections and Questions

01:00:33 - Creo que sería todo por ahorita. Si tienen preguntas, esperen un momento. A ver si me cambio, me cambio también. Ahí, ¿me escuchas mejor? Sí, o K. Estuvo este Joaquín, pues estuvo padrísimo, la verdad. O sea, demasiada información. La forma en que la concentraste toda se me hizo muy, muy padre.

01:01:08 - Yo creo que es un video que grabamos para que después lo puedan volver a ver. Sé que ahora llevan trabajado con ella en clases anteriores o por su cuenta. No sé, ahorita ya están pensando cómo lo van a integrar. Creo que fue un gran momento tener ahorita la sanción para que empiecen a ver dónde más o cómo lo pueden integrar, qué opciones hay.

01:01:35 - Yo sí quiero abrir un poco, si tienes tiempo, Joaquín, para preguntas. Si tienes alguna pregunta o comentario, no sé, creo que si tienes unos minutos, estaría muy padre escuchar a los alumnos y ver sus impresiones. También a todos los que están aquí presentes, a los que estamos conectados.

01:02:00 - A ver si adelante, Felipe, si quieres hacer tu pregunta. Porque el micrófono del salón no funciona. No importa. Silva, ¿qué piensas que va a ser el futuro? Por ejemplo, la cantes una hace un año era como una tecnología super nueva. ¿Qué veo ahora que puede ser el próximo? 

01:02:25 - Pues mira, por un lado, en la parte de RAC, hoy en día todo el mundo habla de agentes. Los estamos desmitificando un poco en la presentación en Rack. Hay muchas mejoras que vienen. Una de ellas es que, ahorita, nada más Yamile, pero Jenny tiene este tamaño de contexto de 2,000,000 de caracteres, de tokens. Entonces, muchas veces ya ni necesitas una base de datos; le puedes mandar así toda la información y que te dé la respuesta.

01:02:54 - Sé que por ahí realmente no es lo más factible, pero hoy, porque nada más Jenny tiene eso y algún otro modelo Open Source que no es fácil de correr, pero para allá va. Yo creo que hacia adelante van a seguir aumentando estos tamaños de contexto. Les diría que más bien ustedes pongan mucha atención a cómo funciona por detrás. El problema va a seguir siendo el mismo: cómo traer información relevante, aunque tú le puedas pegar 2,000,000 de tokens.

01:03:27 - ¿Va a ser importante cuando tienes millones de PDF con información? No la puedes alimentar toda de un jalón. Justo ahorita que estamos con lo del Diario Oficial de la Federación, una sola edición del Diario Oficial es como medio millón de tokens. Entonces, con dos ediciones, con cuatro ediciones, y sale una edición cada día, ya te llenaste el tamaño de contexto. 

01:03:51 - La solución es RAC. Las han querido matar muchas veces, pero van a seguir siendo relevantes por un buen rato. Entonces, simplemente sí, aprendan muy bien por la parte de agentes. Esta parte, Tully de función Colin, y por el lado de Raz, entiendan bien cómo funciona por detrás, porque ahí hay muchas mejoras en Rack. También se habla mucho de cómo mejoran los LSY, cómo están evolucionando constantemente los modelos RAC. 

01:04:21 - El que yo estaba usando hace un año, hoy en día ya sacaron tres versiones nuevas, sacaron Modern Bird, y entonces ahí creo que todavía es un campo que no ha explotado. No hay modelos de EADS, por ejemplo, nada más de español, que podrían ser más chiquitos y correr todavía más eficientemente. Casi hay nada más, casi casi, o en inglés, o en chino, o multilenguaje, que son bien grandes. 

01:04:44 - Si no tienen tan buena eficiencia, hacer fine-tuning de un modelo de embedding tampoco es complicado, y muy poca gente lo hace. Eso sí puede correr en mi computadora. Un fine-tuning de un modelo en vez de inglés, para que sea todavía más eficiente o para que sea nada más para español, por ejemplo, y tener un modelo chiquito que funcione para español. 

01:05:04 - Entonces, en esa parte de Racks, sí hay mucho, mucha blogspot, mucho de dónde cortar con ganancias que a futuro vienen, como esas que les comento, fine-tuning de modelo, RAC y modelos más especializados. 

# Insights on AI Models and Future Directions

01:05:25 - ¿Alguna otra pregunta o comentario? Veo que hay mucho interés. ¿Con qué se quedan hoy? ¿Con qué de la plática los dejó pensando? ¿Qué aprendieron o con qué se quedan? ¿Alguien que quiera compartir?

01:05:48 - Yo diría que ha habido muchas cosas interesantes. Bueno, mensaje a ver si puedes. ¿También pregunto alguna vez o K? Hola Joaquín, ¿qué tal? Muchas gracias. Bueno, yo creo que es muy interesante. Creo que nos habló un poquito sobre las bases que de repente vemos mucho en Internet, pero que no logramos comprender completamente. 

01:06:07 - Por ejemplo, eso de Rack, todos los nuevos modelos que están saliendo. Creo que si yo me llevara algo, sería que existen muchos nuevos modelos que salen muy rápido y que parece que nunca dejan de avanzar. Pero yo te diría, ¿cuál es tu opinión? Justamente, en esa área donde buscamos la innovación y buscamos como decorar los modelos existentes, ¿podemos menospreciar el área de la seguridad en la inteligencia artificial? No, como que la inteligencia artificial que desarrollamos se asegura. Por ejemplo, he escuchado que en Europa dicen que están retrasando mucho el desarrollo de nuevos modelos precisamente por tener mucho control sobre esos modelos. 

01:06:50 - Entonces, no sé cuál es tu opinión sobre eso. Yo diría que primero es importante aprender cómo funcionan por detrás. A mí todo este tema de modelos Open Source y dejar de depender de los grandes proveedores, entender cómo funciona un sistema RAC, cómo funcionan otros modelos pequeños de lenguaje y estarlos utilizando, nos va a habilitar a depender menos de ellos y a entender mejor cómo asegurar la calidad de las respuestas. 

01:07:38 - Si siempre estamos usando lo que los grandes proveedores nos dan, creo que vamos a perder justo ahí, en el entendimiento de cómo funcionan esos sistemas. Sé que, por ejemplo, hay sistemas que te facilitan hacer una integración RAC, y tú nada más le mandas tus documentos y le mandas tu query a través de una llamada. Te devuelve los resultados, pero ahí también te estás perdiendo de ciertas cosas, como hacer el chonqing, de cómo hacer los queries, de qué modelos hay disponibles para hacer estos en Bearings. 

01:08:24 - Entre mejor entiendan las bases de cómo funcionan estos modelos, van a poder asegurar sus sistemas. Van a tener menos dependencia y más libertad. Luego de ir cambiando algunos componentes, los invitaría a leer mucho la documentación para estar al tanto de muchas de estas cosas nuevas. Conéctense con la comunidad, ya sea con esta de Joaquín en Twitter. Sé que está muerto para muchos, pero en el ámbito de inteligencia artificial está más vivo que nunca. Todos los grandes investigadores y muchos de los grandes laboratorios de inteligencia artificial tienen sus cuentas de Twitter, y las personas que lo están desarrollando también las tienen y están todos los días. 

01:09:13 - ¿Hay algo nuevo? A veces te explota la cabeza, pero está padre. 

# Conclusion and Farewell

01:09:17 - Bueno, perfecto. Muchas gracias, Joaquín. Un último comentario, y si no, ya despedimos a Joaquín. ¿Alguien más quiere preguntar algo o ya despedimos a nuestro invitado? No, que es muy interesante la plática, Joaquín. Bueno, pues muchísimas gracias de vuelta. Es un gusto poder escucharte y que hayas estado en este espacio. Vamos a ir contándote cómo va todo esto por acá. 

01:09:49 - Gracias a Álvaro también por conectarse. Álvaro, no sé si quieres comentar algo, preguntar algo. No, de momento no. Digo, fue bastante interesante el tema que abordó Joaquín. Para mí, fue muchas cosas nuevas, de verdad, muy interesante. 

01:10:05 - Sí, muchas gracias por este resumen de información y parte global de cómo se va moviendo la inteligencia artificial. Pues nada, muchas gracias de vuelta. Gracias a Álvaro. Nos vemos al ratito, a las 11, para que veas las presentaciones de los alumnos. Salen las propuestas. 

01:10:23 - Gracias, Joaquín. Nos vemos. ¡Bye! Y ahí tienes el link para que lo compartas después con los alumnos de la presentación. Ah, sí, les paso la presentación. Ahorita se las subo en Teams y subo el video en Teams también y te lo paso de vuelta. 

01:10:37 - ¡Dale, gracias! Nos vemos. ¡Bye, bye!

