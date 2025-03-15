# Introducci�n y Presentaci�n de Joaqu�n Bravo

00:00:01 - Alumnos de sexto semestre y tesistas de tequila en el campus Monterrey. 

00:00:11 - Gracias, �lvaro, por conectarte. Tambi�n quiero darle la bienvenida a Joaqu�n Bravo. Joaqu�n Bravo es programador con 20 a�os de experiencia. Trabaj� en su propio despacho de software durante 10 a�os, desarrollando soluciones con Drupal para peri�dicos, revistas y universidades. Tambi�n ayud� a organizar conferencias de c�digo abierto en Latinoam�rica, lo cual es muy interesante. Despu�s, estuvo 6 a�os en Wayland, donde empez� como Tellez y termin� como director de innovaci�n. Actualmente, trabaja en Vicks, desarrollando soluciones desde all�. Es un experto en el �rea y me da mucho gusto que podamos tenerlo aqu�, en este espacio, en el sal�n, compartiendo sus conocimientos con nosotros. Joaqu�n, muchas gracias. Bienvenido.

00:00:53 - Gracias, Elvia, por invitarme otra vez a estar aqu�. El semestre pasado, Joaqu�n nos acompa�� tambi�n en el sal�n. Gracias por volver a repetirlo, Joaqu�n. Con mucho gusto. 

00:01:11 - Pueden ver mi pantalla. Perd� la conexi�n un momento. D�jame volver a conectarme mientras muevo la computadora. Ha estado fallando. 

00:01:23 - �Me escuchan? Bueno, s�, te escuchamos. Si quieren irse conectando por Teams, tambi�n pueden hacerlo, por si no logro conectar aqu� la pantalla. Solo aseg�rense de que mi otra hija no interfiera con el micr�fono. 

00:01:37 - �Ah, s�? Pero s� se pueden desmontar en cualquier momento si tienen dudas, con toda confianza. 

00:01:44 - Hola, buenos d�as. 

00:01:44 - Hola, hola. No creo que aprendi�. Ah� est�, ya estamos. Ahora, s�, d�jame ver si conecta mi laptop. Hola, hola. 

00:02:47 - S�, no. Ya hab�a funcionado, pero al mover la computadora, dej� de funcionar. Siento que est� fallando, m�s bien es el cable de HDMI, �no? A veces hay que revisar el audio para ver a d�nde se est� mandando. 

00:03:25 - S�, pero no hay problema. Ni siquiera est� recibiendo la se�al. No, no puedo acceder. Pero creo que s� te escuchamos. �Alcanzan a escuchar hasta atr�s? 

00:03:34 - S�, s�. Entonces, nos conectamos por Teams. Adelante, Joaqu�n. Ustedes me dicen. 

# Desarrollo de Soluciones con Inteligencia Artificial

00:03:39 - Bueno, esta presentaci�n es como una introducci�n a c�mo desarrollar soluciones con inteligencia artificial. Hay un t�rmino que est� muy de moda, que es el de ingenieros de IA, que creo que es una combinaci�n de cosas que ustedes ya saben y que est�n aprendiendo como ingenieros en sistemas, m�s algunas otras cosas. 

00:04:00 - Es un poco de lo que vamos a estar hablando, pero siempre tenemos que estar muy enfocados en construir soluciones, no tanto en la tecnolog�a, sino en el producto que queremos hacer. 

00:04:19 - �Ya me present� Elvia? Entonces, soy ingeniero, y s�, es un poco diferente a otros roles ya establecidos en la industria, como un data scientist o un ingeniero de machine learning. 

00:04:36 - El objetivo de un ingeniero de IA no es estar construyendo o desarrollando nuevos modelos, ni siquiera hacer reentrenamiento de modelos existentes. No requiere, al menos para esta parte de construir soluciones con inteligencia artificial, de teor�a muy avanzada sobre inteligencia artificial, redes neuronales o matem�ticas. No se enfoca en ese estilo, sino simplemente en conocer muy bien los modelos y las herramientas que se pueden utilizar para crear soluciones aumentadas, en ingl�s, con inteligencia artificial. 

00:05:18 - Mucho de esta presentaci�n, adem�s, ya hay, o sea, como el t�rmino est� muy de moda, a lo mejor ya han visto esta p�gina de Roach, que es muy buena. Justo acaban de estrenar un nuevo de AI que trae muchos t�rminos y buenos links para profundizar m�s. 

00:05:38 - A grandes rasgos, podemos decir que cuando vamos a construir este tipo de soluciones, vamos a tener ciertos bloques, ciertas piezas de lego que vamos a usar para construir estas soluciones. La primera, muy obvia, son estos elementos que son como chatbots, que nos vinieron a revolucionar toda esta industria y acelerar todo por ah� de finales del 2022. 

00:06:06 - Esa es una herramienta, los prompts, que es la manera en la que vamos a estar interactuando principalmente con estos elementos. El conocimiento que pueden obtener estos elementos no es solo el que ya tienen porque fueron entrenados por alguien m�s, sino el que les vamos a dar nosotros, de nuestros usuarios y de nuestra tecnolog�a, para mejorar la aplicaci�n. 

00:06:29 - Tambi�n hay integraciones con otros servicios y veremos que hay muchos otros modelos de los que podemos servir. No todos son modelos de lenguaje. Hay muchos otros modelos que, como ingenieros, es muy bueno conocer para no centrarnos solo en un �rea. Sin querer, es como intentar matar mosquitos a escopetazos. No me acuerdo c�mo va la frase, pero es algo as�. 

00:06:57 - Adem�s, saber c�mo implementar algo de integraci�n continua y despliegue continuo en nuestras soluciones es fundamental para que sean robustas y funcionen bien en producci�n. Esto tambi�n est� basado en otra presentaci�n interesante de Look March�n, que se titula "Todos podemos ser ingenieros". Esto se basa en el conocimiento que ya tienen. Es decir, si ustedes ya saben sobre lenguajes de programaci�n, librer�as, bases de datos e integraciones con servicios, ya tienen mucho de lo que se necesita.

# Componentes y Evaluaci�n de Modelos de IA

00:07:28 - Ahora, vamos a ver algunos de estos componentes, estas "piececitas" del ecosistema. La primera y m�s importante, donde vamos a pasar m�s tiempo, es la parte de los LLMs. Tenemos que escoger entre dos grandes grupos: los LLMs en la nube y los LLMs de c�digo abierto. En realidad, esa l�nea es un poco difusa, pero es �til para entender mejor. Muchas de las variaciones que veremos entre los LLMs disponibles para nosotros vienen dadas por la calidad del modelo, es decir, qu� tan buenas respuestas da y cu�nto conoce.

00:08:06 - Otro aspecto importante es el tama�o del contexto, o "context window", que es esencial conocer. Tambi�n debemos considerar el precio, es decir, cu�nto nos va a costar hospedarlo, ya sea en nuestros propios equipos o usando un servicio en la nube. Para esto, hay muchas maneras y se han publicado muchos recursos, como tablas y gr�ficos, donde podemos ver c�mo est�n evaluados. Debemos estar atentos a estas cosas.

00:08:44 - Por ejemplo, hay un sitio llamado artificialanalysis.ai donde siempre est�n comparando en cuanto a inteligencia. Se puede hacer un "drill down" de las pruebas que est�n realizando. Por ejemplo, no est� actualizado con la �ltima versi�n que sali� esta semana, que es la de Claude 3.7. Acaban de sacar una nueva versi�n, y aqu� est�. De hecho, s� est� Claude 3.7, y lo actualizan muy r�pido.

00:09:23 - Tambi�n hay que considerar la velocidad de respuesta de los LLMs, que es importante dependiendo del tipo de aplicaci�n que estemos usando. Por ejemplo, en la parte superior est� el modelo "owned mini". El precio tambi�n es un factor a tener en cuenta. Muchos modelos tienen una opci�n gratuita, pero cuando quieres lanzar algo a producci�n, esa opci�n probablemente no ser� suficiente, y el precio comenzar� a ser importante.

00:09:57 - Algo m�s que quer�a mencionar sobre el precio... Bueno, a ver si me acuerdo. Entonces, estas son algunas evaluaciones. Estas son de otras fuentes donde se est�n poniendo otras comparaciones. Es conveniente familiarizarse con algunas de ellas. Aqu�, por ejemplo, explican exactamente qu� evaluaci�n est�n usando, como la de Nigma, el multi-challenge o la de visual understanding. Dependiendo del tipo de soluci�n que queremos hacer, si tiene mucho de visual, tal vez nos convenga usar Gemini en vez de otro modelo.

00:10:34 - Esta otra fuente es un repositorio de GitHub donde se puede ver c�mo est� hecha esta p�gina de lstats.stats.com. Ellos traen una historia de c�mo han ido evolucionando algunos modelos con el tiempo, mostrando c�mo han subido en sus puntuaciones. En la parte superior podemos ver a Brock y OpenAI, mientras que m�s abajo est� Mistral, que es una empresa francesa. Ellos tienen m�s evaluaciones sobre cu�l es el mejor para c�digo y razonamiento.

# Introducci�n a Modelos de Lenguaje y Tama�o de Contexto

00:11:22 - El tama�o del contexto ya lo mencionamos brevemente, pero el campe�n indiscutible en este momento es Yamile de Google, que tiene un tama�o de contexto de 2,000,000 de tokens. Cuando necesitamos enviar mucha informaci�n, Yamile ser� una de las mejores opciones, junto con otros factores como el precio y la velocidad.

00:12:19 - Parece que ya logr� conectar el sal�n. D�jame cambiar la bocina un segundo. �Me escuchan bien? Hola, hola, �me escuchan? S�, los escuchamos.

00:12:39 - Muy bien, esta es otra gr�fica que creo que es de las �ltimas que les quer�a mostrar. La pongo ahorita; est� comparando otra vez el score, ahora contra el precio. Entonces, est� nuevamente a la hora de que vamos a salir. A producci�n va a ser muy relevante, �no? Mientras m�s para ac�, mejor calidad de las respuestas, y mientras m�s arriba son, m�s caros, �no? Entonces, estos que est�n abajo, pues tienen un s�per precio. La versi�n mini tambi�n tiene muy buen precio, y Claud Sweet, pues es un poquito m�s caro, pero tambi�n ahorita es el que tiene la corona del que entiende la mejor calidad de respuestas. 

00:13:22 - Incluso este de Sonnet, este de Claud, en la parte de c�digo es s�per relevante, ya que tiene una calificaci�n muy por encima de muchos otros modelos. Estaba escuchando de parte de la comunidad que desarrolla este tipo de soluciones que est�n impresionados, �no?, de la calidad. Adem�s, esto es porque junto con el nuevo modelo, liberaron un software Open Source que puedes usar en tu computadora para ayudarte a codificar, que es como una gente, �no?, del c�digo. 

# Modelos Open Source y Privacidad

00:14:03 - Hasta ahorita hemos hablado casi de puros modelos hospedados en la nube. Si se fijan, por ah� hab�a algunos Open Source. De hecho, por ejemplo, de Ipsec lo puedes correr normalmente en la nube, porque de hecho correrlo en Python en tu propia computadora no es tan f�cil. Para empezar, por el tama�o del modelo, que es un modelo muy grande, no como los modelos de Lama, que hay versiones m�s chiquitas. S�, es enorme y no es factible correrlo; m�s que versiones ya muy reducidas que no tienen la misma calidad de respuestas.

00:14:32 - �Entonces estamos hablando de Claud models? Ahora, �por qu� querr�a uno usar o por qu� considerar de cualquier manera modelos Open Source? Bueno, hay varias razones muy buenas. La primera que luego sale y que pesa mucho es la privacidad de la informaci�n. Si vamos a estar tratando con datos privados de nuestra empresa que no queremos que se est�n mandando a proveedores terceros, entonces la �nica opci�n que queda es correr modelos Open Source, que puedes correr en tus propios equipos, en tus propios servidores, en tu propia LAN. As� evitas cualquier problema de privacidad o de seguridad de la informaci�n.

00:15:16 - Muchas veces, el Gobierno de Estados Unidos, por ejemplo, tiene ese tipo de pol�ticas. Seguramente muchos bancos y muchos clientes tendr�n ese tipo de restricciones, a pesar de que muchos proveedores de la nube, como el mismo OpenAI, Concha, GPT, Claud, todos ellos te dicen que si est�s usando la versi�n free, pues nada es gratis en esta vida. Al usarlo gratis, lo que te est�n cobrando es que van a usar los datos que t� les mandes para seguir entrenando sus modelos. Cuando pagas por sus APIs, ellos te dicen que no, que en la licencia, justo por pagar por sus APIs, ya no van a usar esos datos para entrenar sus modelos. Pero a�n con eso, con esa promesa, no hay nada que te la asegure. 

00:16:00 - Con esa promesa de los proveedores de la nube, de todas formas, muchos clientes optan por no utilizar estos modelos y m�s bien por usar modelos Open Source que puedas correr en tu propia computadora, en tus propios servidores. Entonces, la privacidad de la informaci�n es muy importante. Muy relacionado a ese t�rmino est� la parte de soberan�a, la soberan�a de la informaci�n y de la tecnolog�a. 

00:16:23 - Ah� podemos ver, por ejemplo, c�mo famosamente Estados Unidos, en su Gobierno, no va a querer que usen modelos chinos. Los chinos seguramente tambi�n tienen restricciones similares en donde, por nada del mundo, van a estar usando modelos gringos. Los europeos invierten tambi�n fuertemente en modelos propios, como esta compa��a de Mistral. Israel tiene sus propios modelos, y as�. Esta parte de soberan�a de la informaci�n, que es no depender de fuerzas externas, que t� tengas control sobre la tecnolog�a y la informaci�n que manejas, es tambi�n un concepto muy importante. 

00:17:01 - No solo aplica a pa�ses, tambi�n puede aplicar a empresas. Esto est� muy relacionado con la privacidad, pero la soberan�a tambi�n te puede orientar a usar modelos Open Source, que adem�s van a tener m�s transparencia y puedes tener m�s confianza en ellos. Si tienes alguna duda de por qu� se est� comportando de cierta manera, los puedes ver. Son Open Source y, por eso, al ser abiertos, puedes ver c�mo es que las respuestas se est�n generando de cierta manera.

# Transparencia y Customizaci�n de Modelos Open Source

00:17:31 - Algo que hay que mencionar es qu� tan Open Source realmente es el modelo, �no? �Qu� tan abierto realmente es? Porque hay tres cosas que pueden abrir. Una cosa es abrir los pesos del modelo, que es como quien dice que puedas usar el ejecutable, el bajarte el punto exe y usarlo. Eso depende de la licencia que le pongan, y muchas licencias de estos modelos son licencias abiertas, que puedes usar para lo que gustes. Algunas tienen licencias no comerciales; algunos de estos modelos los puedes usar, pero para usos m�s bien educativos, acad�micos o de investigaci�n, pero no para uso comercial. Hay que revisar la licencia, pero eso de liberar los pesos es, es, es como liberarte una estable. No, realmente no hay una transparencia sobre c�mo funciona el modelo. 

00:18:22 - Algunos liberan tambi�n el dataset, que es lo m�s raro; en realidad, muy poco liberal en el dataset, pero s� hay algunos datasets libres que puedes ver, o pueden liberar el c�digo. El c�digo necesario tambi�n para, ya sea que usaron para entrenarlo o el que se usa para correrlo, �no? Y bueno, dentro de estos niveles de transparencia es donde vas a ir ganando confianza tambi�n en el modelo. Con esta transparencia y con esto que podemos ver del modelo y c�mo funciona, tambi�n nos permite customizarlo de mejor manera. Es m�s f�cil customizar modelos Open Source, que puedes bajar el modelo y entrenarlo en tu propio equipo, que hacer este tipo de customizaciones contra modelos como los de OpenAI y otros proveedores. 

00:19:14 - Siempre se habla primero de OpenAI porque es el primero y es de donde muchos se est�n copiando muchas de estas buenas pr�cticas. Te ofrece de manera de hacer fine-tuning de su modelo, pero es dif�cil, es costoso y te est�s atando a ese modelo. Mientras que si lo haces con un modelo Open Source, tienes un poco m�s de libertad hacia donde moverte. Te est�s dejando de depender de un proveedor externo. 

# Eficiencia y Ahorro con Modelos Open Source

00:19:39 - Finalmente, otra parte que se menciona aqu� es usar Open Source para ahorrarnos dinero. Con todo lo que han sido abaratados los costos, les mostraba yo esta tablita anterior, donde los m�s baratos realmente son OpenAI con su modelo GPT-3.5, que es s�per barato. Claude de Anthropic tampoco es tan caro. A Jiminy, no s� por qu�, pero es barat�simo; realmente es rid�culo lo que cuesta el token. Entonces, a veces no tanto, vamos a ahorrar en el costo. S�, pueden ser mucho m�s eficientes algunos de estos modelos en la nube, pero est� tambi�n este componente en donde un modelo Open Source puede llegar a correr incluso en tu computadora. 

00:20:28 - Hay modelos Open Source que puedo correr en mi computadora personal, en una MacBook Pro, por ejemplo, o en una computadora que tenga estos �ltimos chips que est� sacando Intel o AMD, que tienen soporte para inteligencia artificial. Con cierto RAM, pueden correr en esos, o incluso en celulares. En el edge, le llaman. Hay modelos tan peque�os que pueden correr tambi�n ya en tu celular o en dispositivos peque�os como Raspberry Pi, por ejemplo. Entonces, ciertamente puede haber tambi�n un ahorro en costos, puesto que no est�s necesitando ni siquiera correrlo en un equipo que ya tienes. 

00:21:06 - Aqu� tambi�n puede haber cierto ahorro a la ecolog�a. Adem�s, estos modelos, como se sabe c�mo funcionan los modelos Open Source, son los que han avanzado mucho m�s en esta parte de la eficiencia y del ahorro en qu� tan caro es correrlo. Son los que han empujado 100% a que bajen los precios tan dram�ticamente los modelos en la nube. Entonces, s� vale la pena considerar eso tambi�n. 

# Evaluaci�n de Modelos Open Source

00:21:32 - Entrando ya a evaluaciones de modelos Open Source, est� este, por ejemplo, el leaderboard de Hugging Face. Para estos screenshots, le puse nada m�s listar los proveedores oficiales como para alistar aqu� los m�s famosos, justo para que salga. Por ejemplo, cuenta que es un modelo chino, que es de los mejores modelos que puedes correr justo en hardware relativamente que no necesitas un supercomputador. Est� Mistral, este modelo europeo que les llamaba la AMA, obviamente de Meta. 

00:22:08 - Entonces, estos modelos los podemos ver en este listado. Hay otros filtros en donde si dices t�, oye, �cu�l puedo correr en un consumer device? �No en una PC? �Cu�l puedo correr en un celular? Y si se fijan, lo que baja principalmente es el n�mero de par�metros. Estos modelos tienen 72 billones de par�metros; Vic tiene 600 billones de par�metros. En realidad, no es factible correrlo m�s que en un supercomputador. Estos modelos, para que puedan correr en computadoras personales, tienen 3.5 billones de par�metros, esta es la versi�n a 3 billones de par�metros a 6 billones de par�metros, y corren en una computadora personal. 

00:22:49 - Si nos vamos a los modelos para edge, no tengo aqu� abierta la ventana, pero seguramente nos saldr�n modelos de un bill�n de par�metros, m�ximo dos billones de par�metros. Y esos s� son modelos que podr�s correr tambi�n en tu celular muchas veces.

00:23:07 - Ah, hay por ah� un link que creo que ten�a por ac�. �Ah, s� este? Bueno, tambi�n surge la pregunta de por qu� no sale de IPSec, �no? En estos casos, si es de los m�s destacados en Open Source, pues hay cierta especulaci�n. En el mismo foro, el Foro de Joaqu�n FACE, seguramente una parte es porque es un modelo de 600 billones de par�metros. Es grand�simo, y los modelos que aparecen en esa tabla llegan hasta 140,000,000 de par�metros. O tal vez tambi�n porque DIC todav�a no corre con la librer�a de Transformers, que es una de las librer�as Open Source m�s usadas, si no es que la m�s usada para correr este tipo de modelos.

00:23:51 - Entonces, si tenemos alguna de estas caracter�sticas que nos dice, creo que un modelo Open Source ser�a una buena idea. �C�mo los corremos? Lo m�s sencillo y por donde les dir�a que comiencen es por este software. O Llama, por detr�s, usa la m�s P o alg�n otro proyecto en C++, que puede correr en GPU, pero tambi�n corre en CPU. Es decir, no necesitas una super tarjeta gr�fica para correr O Llama o para correr algunos de estos modelos. Esa es la manera m�s sencilla. Es como el Docker de los LLMs. Yo lo tengo instalado en mi computadora, tengo varios modelos ah� y es muy eficiente.

00:24:28 - Yolanda, despu�s tambi�n podr�as correrlo en producci�n en alg�n servidor Linux. Podr�as correr O Llama y estar ejecutando tus modelos ya para sistemas en producci�n. Correrlo tal cual sobre Python tambi�n es una opci�n porque permite ciertas optimizaciones que tal vez O Llama no soporta para CUDA. Por ejemplo, hay un proyecto que se llama BLM, que es muy eficiente para servir a millones de clientes, desde Python o para la Mac. Hay cierto c�digo de Python que utiliza bien los procesadores de Mac optimizados para inteligencia artificial, espec�ficamente la arquitectura MLX, que O Llama hoy en d�a no soporta. Hay un ticket abierto por ah�, pero no han agregado esa funcionalidad.

00:25:19 - Entonces, hay ciertos casos en donde conviene correr este c�digo de Python. Ah, o si est�. Nada m�s probando, hay uno que se llama El Estudio. Este no es Open Source, pero O Llama s� lo es. El Estudio no es Open Source, pero tambi�n si quieren jugar con modelos en su computadora, esta es una buena soluci�n que s� corre esta arquitectura de MLX con Python en la mano. Entonces, tambi�n vale la pena considerarlo para jugar, aunque no para producci�n.

00:25:53 - Hay algunos estimadores de cu�nta RAM necesitar�as para correr un modelo de manera local en tu computadora. Por ejemplo, aqu� te est� diciendo que yo tengo un modelo de 25,000,000 de billones de par�metros que est� cuantizado. Cuantizado es una palabra que usan para decir que los modelos normalmente est�n basados en arreglos de vectores que tienen 16 bits, y luego le reducen el n�mero de bits en cada uno de esos vectores para reducir el tama�o del modelo. Sigue teniendo 25,000,000 de par�metros, pero en n�meros m�s peque�os que los hacen m�s eficientes. Si bien pierden bastante de la calidad en la respuesta, no se vuelven tontos, pero no tienen la misma calidad en las respuestas.

00:26:38 - Entonces, un modelo de estos de 25 billones de par�metros cuantizado a cuatro bits se estima que podr�a correr, por ejemplo, con una computadora que tenga 16 GB de RAM. As�, podemos ver que si bajamos los n�meros de par�metros a algo m�s peque�o, por ejemplo, yo tengo 8 GB de RAM. �Puedo correr? Tal vez hasta 9 billones de par�metros con una cuantizaci�n de cuatro bits. Este fue el primero que encontr� en Internet. Hay otras calculadoras, pero no me gust� esta, ya que no pude modificar los par�metros y que me diga el RAM. Hay m�s calculadoras que nos dan una idea general.

# Integraci�n de Modelos Locales y Remotos

00:27:27 - Esta computadora que tengo aqu� tiene 36 GB de RAM. Entonces, puedo poner modelos m�s grandes. Y finalmente, esta frase que me gusta mucho de este comercial: "�Por qu� no los dos?" Acaban de anunciar tambi�n esta semana un proyecto en colaboraci�n, me parece que es con la Universidad de Stanford, junto con Obama, en donde est�n haciendo proyectos en los que puedes correr, por un lado, un modelo muy grande y remoto, como ChatGPT o Claude, junto con modelos peque�os locales de 8,000,000 de par�metros como O Llama. 

00:28:08 - Juntos pueden resolver problemas a una fracci�n del costo que si se lo mandaras solo al modelo grande. El costo de resolver el problema es muy alto, y la calidad de la respuesta es la mejor. Pero si usas esta combinaci�n de un modelo grande orquestando muchos modelos peque�os para cosas m�s sencillas, obtienes una muy buena calidad de respuesta a una fracci�n del costo. 

# Introducci�n a Soluciones de Modelos de Lenguaje

00:28:40 - Entonces, este tipo de soluciones para algunos problemas, obviamente, no funciona para todo; es un nicho muy espec�fico de problemas. Vale la pena investigar este tipo de soluciones. Usar ambos es bueno. Algo m�s que les dir�a es que intenten desacoplar, de todas formas, al principio que est�n desarrollando una soluci�n. Desacoplar y no casarse por completo con alg�n modelo, puesto que est� en constante evoluci�n. Es bueno usar librer�as; hay libros para empezar. La mayor�a de los proveedores soportan el mismo API que OpenAI. 

00:29:21 - Por ejemplo, el mismo cliente que est�s usando en Python o en JavaScript de OpenAI para conectarte, si le cambias el servidor y en vez de apuntar a OpenAI a ChatGPT, apuntas a tu local host corriendo O Llama, va a funcionar. Entonces, hay mucha interoperabilidad. Por un principio, conviene no casarse tanto con un solo modelo. Me gust� much�simo la idea de no casarse con el API de OpenAI, sino usar herramientas que te atraigan un poquito. 

00:29:47 - OpenAI y su cliente son una de estas herramientas. Otras en Python hay algunas librer�as como Little Lem, que es una sola librer�a con la que te conectas a todos los que quieras. Esta librer�a soporta much�simos proveedores. Hay otra de un compa�ero, Andrew Ng, que es famoso porque tiene un sitio llamado "AI for Everyone" y ofrecen cursos gratuitos de inteligencia artificial. Este equipo liber� una librer�a que se llama AI Suite. 

00:30:21 - M�s adelante, hay algunos ejemplos de esa librer�a que tambi�n es multi. En JavaScript tambi�n hay librer�as, as� como Lem 10. Ross tiene las suyas. Hay otra de esta persona, Jason Lee, que se llama Instructor, que es muy interesante. Esa misma librer�a tiene soporte para Python, TypeScript, PHP, Ruby, Elixir, y seguramente con distintos niveles de soporte. En realidad, Python casi siempre es lo m�s importante en este tipo de soluciones. 

00:30:50 - En segundo lugar, dir�a que JavaScript. Y una opini�n que tengo, un poco controversial, es que siento que es mejor evitar, al menos en un principio, o sobre todo para ustedes que est�n aprendiendo a desarrollar este tipo de soluciones, librer�as grand�simas que tratan de abarcarlo todo, como LangChain o LlamaIndex. Porque se convierten en una capa de abstracci�n tan grande que te conviertes m�s en un ingeniero de LangChain o de LlamaIndex y en realidad no aprendes el detalle fino de algunos de los componentes de estas soluciones. 

00:31:30 - Es un componente muy importante que puede tener su propia capa de abstracci�n, pero hay muchas otras partes de estas soluciones. Es como estos bloques de Lego que les comentaba; si todo lo est�s usando con LangChain, creo que al final m�s bien te va a limitar, adem�s de que tiene su propia curva de aprendizaje muy grande. Esa es mi opini�n personal y es una opini�n muy compartida tambi�n en algunos foros. 

# Integraci�n de Conocimiento en Modelos de Lenguaje

00:31:53 - Bueno, pasemos al siguiente bloque de Lego, que es el conocimiento. Los LLM ya tienen conocimiento, pero �c�mo doy conocimiento que ellos no tienen porque es propio de mi compa��a, de mi organizaci�n? Lo m�s normal es, por un lado, pensar en el fine-tuning. Pero el fine-tuning es muy caro. En realidad, la soluci�n por defecto que m�s se usa es aumentar justo el conocimiento que ya tiene, haciendo copy-paste de la informaci�n a la que tiene acceso el LLM para lograr hacer esto. 

00:32:35 - Para ello, necesitamos una base de datos. Esta es una presentaci�n m�s larga que tengo, nada m�s con un resumen de sistemas RAG, en donde normalmente tienes dos pasos. Por un lado, en tu base de datos, toda la informaci�n que t� tengas de tu compa��a, que bien puede ser las �rdenes de compra, documentos en PDF o lo que sea, la indexas. La indexas para que pueda ser buscada cuando el usuario est� interactuando. 

00:33:12 - En un segundo momento, cuando el usuario est� interactuando y haga una pregunta directamente en un chat, o m�s bien, interactuando con alg�n filtro, t� vas a poder convertir esa interacci�n del usuario en un vector o algo que puedas buscar f�cilmente en esta base de datos que tienes de toda tu informaci�n para traerte el contenido relevante. Y entonces, ese contenido relevante a la interacci�n del usuario se lo mandas para dar una respuesta al usuario. 

00:33:47 - Este tipo de soluciones RAG son s�per t�picas. En aprender m�s o menos c�mo funciona, �no? Pero a grandes rasgos, estos son todos sus componentes. No es una base de datos de vectores que bien puede ser el mismo PostgreSQL. Ya manejan Esquivel Light, MySQL; son bases de datos que soportan tambi�n b�squeda de vectores. 

00:34:08 - �O hay bases de datos especializadas? Pero si ya est�n usando alguna base de datos de estas no relacionales, les dir�a que simplemente le agreguen este componente de vectores. Si quieren usar una base de datos especializada como Chroma, hay muchas opciones; tambi�n lo pueden hacer, �no? Este componente de b�squeda es la parte importante, ya que pueden hacer b�squedas de texto normales. Full text search, que tiene sus propios �ndices para full text search en MySQL. Lo mismo ocurre con otras bases de datos, o lo pueden combinar con estas b�squedas de vectores para hacer b�squedas no tanto basadas en los keywords, sino en el sentido de lo que est�s buscando en la aplicaci�n. 

00:34:56 - Y eso, entonces, ya ese conocimiento que t� ten�as en la base de datos se lo vas dando al LLM conforme el usuario lo necesita para poder ir produciendo respuestas. Eso es, a grandes rasgos, c�mo funciona una soluci�n RAG. Este es un prompt, uno de los componentes que mencionamos. Tambi�n estos Lego blocks son los prompts. Este es un producto t�pico para una soluci�n RAG, �no? En donde, tal cual, ya hiciste la pregunta del usuario. 

00:35:25 - Lleg� la pregunta del usuario, hiciste una b�squeda en la base de datos y te trajiste documentos relevantes que le vas a dar al LLM en el prompt. Entonces, al front, casi, casi le pones casi literal el contexto y le pones todos los documentos que te trajiste de la base de datos. Los puedes poner formateados en JSON o en XML, o si es puro texto, pues simplemente copypaste del contexto. Luego, unas instrucciones t�picas de un programa de RAG son: "Utiliza este contexto para contestar la pregunta. Si la respuesta no est� en el contexto, di que no sabes". 

00:36:01 - Y ah� est�s un poquito, tambi�n evitando las alucinaciones. Y lo hago con mi padre de la pregunta, �no? Y esto es un solo plan que le mand� a Salem y ya te va a dar una respuesta basada en tu conocimiento. Entonces, si se fijan, esto es algo en realidad bastante sencillo. 

# Integraciones y Extracci�n de Datos

00:36:17 - Integraciones, otro componente que mencionamos, son las integraciones. Para hacer estas integraciones, como esta misma, en la que estamos integrando con nuestra base de datos, hay que pensar en dos cosas. Por una parte, tenemos que estructurar el output que nos genera para poder hacer estas integraciones. Muchas veces necesitamos que la respuesta que venga del LLM, junto con el input del usuario, etc�tera, venga formateada de cierta manera que nosotros la podamos usar en nuestro sistema. 

00:36:48 - No nada m�s para un chat. Un chat es lo primero que pensamos cuando estamos hablando de soluciones aumentadas por LLMs o por inteligencia artificial. Pero no, no nada m�s con los chats. Si queremos otro tipo de cosas, por ejemplo, podemos extraer informaci�n de los inputs del usuario de un texto o de una imagen. 

00:37:08 - �Podr�amos sacar, por ejemplo, de un recibo que nos est� dando el usuario? Podemos sacar los line items, cada �tem, cu�nto cuesta y el total. Y de una foto que era dif�cil de parchear, el LLM nos ayuda a obtener un JSON con esta informaci�n. O si tenemos recetas de cocina, un recetario, y lo escaneamos, podemos pedirle a un LLM que nos vaya dando de cada receta el nombre de la receta, una lista de ingredientes en formato JSON y las instrucciones de c�mo prepararlo. 

00:37:39 - Entonces, estamos de contenido no estructurado, sacando contenido estructurado que podemos utilizar de distintas maneras en nuestra aplicaci�n. O le damos un CSV, un PDF que tiene tablas, a lo mejor informaci�n financiera, y queremos que esa tabla nos la convierta en un CSV para poderlo usar en nuestra aplicaci�n de cierta manera. 

00:37:59 - Esto es un uso muy t�pico de este tipo de soluciones, estos modelos en donde de contenido no estructurado estamos sacando contenido ya �til para nuestras aplicaciones. Ya se hizo, nosotros podemos operarlo dentro de nuestro sistema. Podemos acceder a cierto campo y mostrarlo en cierta parte de nuestra interfaz. 

00:38:20 - Entonces, como se hace mucho de esto, puede ser en el mismo prompt. En el mismo prompt, por favor, quiero que des la instrucci�n de que el output venga de esta manera y le des un ejemplo de c�mo quieres que est� formateado. Esta es una manera, o hay librer�as que te facilitan esto. Tambi�n OpenAI tiene su formato para hacer estructural, que te devuelva JSON y lo mandas de cierta manera en su API. Gemini, lo mismo.

00:38:51 - Tienes algunos ejemplos muy buenos aqu�, justo para, por ejemplo, extraer las recetas. �Y c�mo logras que te mande? As� es eso que les comentaba: el nombre de la receta, los ingredientes, las instrucciones. Vienen ejemplos de c�mo lograrlo. Casi todos los ejemplos en realidad que est�n mostrando son como este, c�mo obtener el clima. Me parece que no les voy a... 

00:39:15 - Hola, Ma. Si usan la librer�a de Obama o Llama, tambi�n tiene facilidades para intentar obligar a los LLMs que us� la AMA para que te manden output estructurado en alg�n formato espec�fico como JSON. Cuando te vas a esa funcionalidad, hay ciertos modelos que puedo usar y otros que no. Entonces, tambi�n hay foros en donde, "Oigan, estoy usando la AMA, pero no me funciona bien con tal modelo para producir JSON". Ah, es que te recomiendo usar este otro, no esta librer�a que les mencion� antes de Instructor.

00:39:49 - Este es un c�digo de Instructor, nada m�s. As�, muy r�pido, para ver c�mo funcionar�a. Algo as� est�n usando un modelo cloud que es de Cojear, pero si le cambias de aqu�, en vez de usar Cojear, a usar OpenAI, es el mismo c�digo. Entonces, simplemente le dices, "from Cojear" o "from OpenAI", le mandas el cliente, le mandas tu prompt y le dices qu� modelo quieres usar. 

00:40:11 - Le mandas, a lo mejor, un pedazo de texto en donde alguien te est� diciendo: "Ah, pues tengo 25 a�os y t� quieres extraer el nombre de la persona y su edad". Entonces, parchear esto con un retweet. Esto cambia constantemente, �no? Entonces, para nosotros programarlo tradicionalmente ser�a dif�cil extraer ese tipo de datos. Para un LLM es muy sencillo.

00:40:31 - Entonces, m�s bien defines en Instructor una clase de los campos que necesitas extraer y es lo que mandas. Respondes, modelas y esto te va a hacer m�s o menos lo que necesita OpenAI o lo que necesitan distintas librer�as para hacer esa estructura. Al final, ya vamos a tener un objeto que tiene esos campos parcheados.

# Introducci�n a Function Calling y Agentes

00:40:57 - Este es un ejemplo muy peque�o, usando Instructor, para hacer integraciones. Es una de las cosas que necesitas. Otra muy importante es Function Calling, o Tool Use, otro nombre con el que se le conoce a estas funcionalidades. En el ambiente OpenAI, Cloud Mining o Llama, tambi�n tienen APIs para c�mo hacer que los LLMs mismos... 

00:41:21 - Ac� nosotros estamos m�s bien de la respuesta del LLM. La vamos a usar para nosotros insertar algo en la base de datos, pero en nuestro c�digo que nosotros escribimos no. Mientras que en Function Calling, le vamos a decir al LLM qu� funciones tiene �l disponibles para que decida si las quiere llamar o no, en base a las instrucciones del usuario. 

00:41:43 - Entonces, es un uso un poco diferente. Este es m�s reactivo y no depende de nosotros si se va a llamar la funci�n. Los ejemplos tambi�n est�n padres. Casi siempre, casi todos estos ejemplos son acerca del clima, de que el LLM responde de acuerdo a las preguntas del usuario. Si tiene una funci�n para obtener el clima actual, se provee al usuario.

00:42:08 - Vamos a ver otra vez un ejemplo muy peque�o con esta otra librer�a que les mencionaba, que se llama E-Suite, que te ayuda a usar y te abstrae un poco la dificultad de hacer Function Calling desde estos elementos. Es un ejemplo chiquito. Entonces, defines tu funci�n, Willy Trains, y necesitas mandar la ubicaci�n de d�nde est�s y la hora del d�a. En base a eso, t� ya checar�s alg�n servicio externo o algo que tengas por ah� para devolver una respuesta.

00:42:45 - Por ejemplo, en este caso, esta es la funci�n que quieres que el LLM pueda llamar. Tienes los inputs del usuario que llegan. Por ejemplo, aqu� hay un usuario que est� diciendo en su input: "Yo vivo en San Francisco, �pudieras checar el clima? Planeo estar haciendo un picnic alrededor de las dos". 

00:43:02 - A la hora de que usas esta librer�a, simplemente le mandas las herramientas disponibles, las funciones que va a tener el LLM para decidir si las va a llamar o no, y le agregas un par�metro de cu�ntas veces puede iterar en estas llamadas para mandar la respuesta final al usuario. 

00:43:19 - El LLM solo va a llamar tu funci�n y va a crear una respuesta con el output de la funci�n para responder la pregunta del usuario. Otro ejemplo muy t�pico es llamar funciones externas, que el LLM pueda llamar funciones externas para checar el clima, checar tu base de datos, insertar nuevos r�cords en la base de datos, leer r�cords de la base de datos, etc�tera.

# Definici�n y Funcionalidad de Agentes

00:43:50 - Esto nos lleva un poquito a este buzzword que est� muy de moda hoy en d�a: "agentes". Vamos a hablar un poco de agentes. 

00:43:54 - Hubo esta semana, la semana pasada, una conferencia en Nueva York que era el Engineering Summit, donde, por ejemplo, Adri�n habl� mucho de agentes. Alguien defin�a a los agentes; �l es uno de los organizadores de la conferencia. Dec�a que normalmente un agente consiste en tener tu modelo equipado con instrucciones que puede dar el usuario sobre lo que quiere hacer. Hay que definir qu� cosas s� puede hacer y qu� cosas no. Adem�s, hay herramientas o funciones que puede usar para extender las capacidades de este modelo que corre en un runtime. 

00:44:37 - Esta definici�n est� un poco rebuscada, pero es �til. Despu�s, sali� una definici�n mucho m�s sencilla: un agente es simplemente un modelo que tiene acceso a funciones y herramientas, y que est� corriendo en un bucle, en un "while true". Este modelo tiene acceso a ciertas herramientas y las puede usar si lo necesita. Por ejemplo, el agente que liber� Anthropic, cuyo c�digo fuente puedes ver, es bastante m�s completo. Te dice c�mo funciona y c�mo te ayuda a hacer c�digo. Te puede leer el c�digo fuente, leer todo tu directorio, modificar algunas cosas, agregar comentarios a tu repositorio de Git, etc�tera. Tiene muchas herramientas disponibles, como un agente que puede correr cosas en el backend, leer archivos de tu l�nea de comandos, editarlos, reemplazar peque�as cosas, etc�tera. 

00:45:56 - No tiene muchas herramientas disponibles que simplemente est�n corriendo en un bucle dentro de su c�digo. No es m�s que eso; no tiene un servidor externo. En resumen, un agente es un modelo con acceso a funciones que corre en un bucle. Esto es para intentar desmitificar esa palabra que tiene mucho buzz hoy en d�a, pero no es m�s que eso. 

# Pruebas y Automatizaci�n en Soluciones de IA

00:46:21 - �Ya pueden construir ustedes sus propios agentes? Bueno, esto va a ser muy importante, tambi�n la parte de c�mo probar. Ya que les est�n ense�ando todo acerca de testing funcional y automatizaci�n, cuando haces soluciones con inteligencia artificial, tambi�n vas a necesitar probarlas. 

00:46:41 - Algunas recomendaciones: que estas pruebas est�n corriendo de manera autom�tica, con integraci�n continua, mientras est�n haciendo el c�digo, para que constantemente lo est�n evolucionando. Si cambian el modelo, por ejemplo, si estaban usando Claude 3.5 y sali� el 3.7, se actualizan. Seguramente algunas pruebas se van a romper porque est� cambiando el modelo que est�s corriendo por detr�s. Entonces, correrlas en un bucle continuo con tus pruebas va a ser s�per importante. 

00:47:22 - Tambi�n es crucial involucrar a expertos en la materia, es decir, a personas que entiendan muy bien el conocimiento de tu aplicaci�n. �Qu� tipo de conocimiento es importante? �Qu� tipo de respuestas son las que esperamos? Es fundamental que sean ejemplos realmente significativos para que esos ejemplos de uso real de tu aplicaci�n los puedas probar. Debes tener un conjunto de pruebas que sea significativo. 

00:47:49 - Normalmente, es muy famosa esta frase cuando se habla de datos en sistemas: "si le metes basura al sistema, te va a sacar basura". Entonces, es importante que estas pruebas sean buenas. Normalmente, vas a estar checando la entrada del sistema de informaci�n. Si est�s usando alg�n sistema para traer informaci�n de tu base de datos y responderle al usuario sobre algo, puedes probar sin siquiera irte a la parte de modelos. 

00:48:18 - Es importante que tus mecanismos de b�squeda te est�n regresando los registros de la base de datos que esperas que te regresen en los primeros lugares. Es muy sencillo: simplemente haz pruebas de integraci�n de tu base de datos. Cuando llega cierto input del usuario y buscas en la base de datos, esperas que el resultado top sea el documento relevante. Aqu� es donde es muy importante contar con un experto de tu base de datos que sepa realmente cu�les son las respuestas relevantes que est�s esperando. Esto es muy f�cil de probar; es simplemente un query en la base de datos y cu�les son los resultados que est�s esperando. 

00:49:03 - Conforme a eso, tendr�s que cambiar esas pruebas cuando cambien los datos, pero te dar�n una idea de si tu sistema se est� rompiendo desde el input de conocimiento que le est�s mandando. 

00:49:12 - Otro tip es que tambi�n debes considerar el output del modelo. Las respuestas que generas con el modelo tienen un argumento de temperatura. Si le pones una temperatura alta, el modelo es m�s creativo, lo que hace es agregar un elemento aleatorio a las respuestas que genera. Si pones la temperatura en cero, le quitas el elemento aleatorio y el modelo debe devolverte siempre la misma respuesta para un input determinado.

00:49:46 - En tus pruebas del contenido que esperas generar con el modelo, pon la temperatura en cero, env�a un input del usuario y esperar�s cierta respuesta. Esto puede ser una prueba de integraci�n muy buena y certera. Si modificas algo en tu sistema y se rompe, podr�s ver que algo pas� y necesitar�s modificar algo en el c�digo.

# Modelos Especializados en Inteligencia Artificial

00:50:08 - Y bueno, ya casi se nos acaba el tiempo, pero tambi�n creo que es muy importante aprender que est�bamos hablando de modelos de lenguaje, pero hay muchos otros modelos que vale la pena considerar cuando estamos empezando a hacer soluciones aumentadas con inteligencia artificial. La inteligencia artificial no solamente son estos modelos de lenguaje; hay muchos modelos.

00:50:29 - Voy a mencionar algunos. Por ejemplo, hay modelos m�s especializados, como los modelos de embedding que se usan en estas soluciones. Hay de muchos tipos, algunos son solo para ingl�s o para chino. Hay otros modelos de embedding que son multiling�es o solo para franc�s. Tambi�n hay modelos que te pueden ayudar a definir un vector que representa una imagen, no solo texto, para poder buscar im�genes o videos. Existen modelos de embedding que te ayudan a extraer el vector de una imagen, de un video o de un sonido.

00:51:08 - As�, podemos extraer contenido relevante de nuestra base de datos. Para eso sirven estos modelos de embedding. Hablando de todos estos ejemplos, la gran diferencia es que son modelos especializados y mucho m�s peque�os que corren de manera m�s eficiente. Normalmente, los modelos de lenguaje, incluso los de c�digo abierto, necesitan un servidor potente si quieres respuestas de calidad. Pero estos modelos especializados, al ser m�s peque�os, pueden correr en hardware m�s modesto.

00:51:36 - Hay algunos modelos de embedding que, por ejemplo, pueden correr en una Raspberry Pi. Entonces, puedes tener tu sistema en producci�n, con la base de datos de vectores ya indexada. Cuando llega una pregunta del usuario, todo est� corriendo en la Raspberry Pi, que convierte la pregunta en vectores para comparar y buscar cu�les son los m�s cercanos a esa pregunta. Luego, se generan las respuestas con un modelo de lenguaje que est� hospedado en otro lugar, no en la Raspberry Pi, pero el modelo de embedding s� puede correr en ella.

00:52:12 - Otros modelos, como los modelos de visi�n, te permiten extraer informaci�n de im�genes. Claro que puedes usar modelos grandes para eso, pero hay otros modelos m�s peque�os, como Mondrian o Small Vision Language Model, que tambi�n permiten hacer este tipo de tareas, como la detecci�n de un coche en un video y extraer su marca y modelo. Esto se puede hacer con un modelo peque�o en lugar de uno enorme.

00:52:49 - Estos modelos son m�s eficientes, con menos par�metros, y pueden correr en dispositivos m�s peque�os. Vale la pena considerarlos para describir im�genes, detectar objetos y extraer informaci�n. Por ejemplo, puedes extraer precios individuales y totales de un recibo con estos modelos peque�os y gratuitos en tu computadora o tel�fono.

# Modelos de Extracci�n de Texto y Aplicaciones Educativas

00:53:15 - Otros modelos especializados son para la extracci�n de texto, como el reconocimiento �ptico de caracteres (OCR). Hay modelos de c�digo abierto que pueden extraer texto de PDFs, incluso de fotos de documentos, y formatearlo adecuadamente. Un ejemplo es el modelo Whisper, que es de c�digo abierto y permite convertir audio a texto. Esto puede ser muy �til en aplicaciones educativas, como las que desarrollaron algunos alumnos para practicar ingl�s, donde se extra�a el texto hablado y se evaluaba con un modelo de lenguaje.

00:54:31 - La calificaci�n YY te iba evaluando tu nivel de ingl�s o te ayudaba a practicar tu ingl�s. No, y eso es con un modelo de speech to text, que por ejemplo hay un Whisper web, una versi�n de Whisper que corre en el navegador. Entonces, t� puedes directamente en el navegador, sin usar un servidor; es un modelo m�s peque�o que puede correr en el browser. �Depende de la computadora y de qu� browser, verdad? Y te puede ir extrayendo en el mismo navegador este texto de audios o de archivos, o de la c�mara del video. Tambi�n.

00:55:07 - Este es un ejemplo de Mondrian, Bustamante extrayendo, y esto de c�mo se usan estos modelos. Es c�digo muy sencillo. Finalmente, esto te va a ayudar a crear pruebas de concepto. Hay librer�as en Python muy sencillas para esto, como Streamline, Grader�o y Marimo. Aqu� son excelentes librer�as de prototipado en Python. Fast HTML tambi�n es muy bueno, si quieres un poco m�s de personalizaci�n. Incluso aqu� hay un c�digo open source hecho por m�, no lo estoy promocionando, que es justo toda una aplicaci�n sencilla de c�mo extraer texto, hacer b�squedas y luego crear un chat muy sencillo con Fast HTML. Hasta ah� no est� s�per avanzado, pero es un ejemplo completo de c�mo hacer esto en Python.

00:56:01 - En JavaScript tambi�n se puede hacer mucho de esto y hay algunos workshops por ah� sobre c�mo funcionan los embeddings. Hay un video que grab� hace poquito, un repositorio y unos slides. 

# �tica en la Inteligencia Artificial

00:56:17 - Es muy importante considerar las cuestiones �ticas. Ustedes, que son privilegiados, no solo por estudiar en la universidad, como en el TEC de Monterrey, y aprender este tipo de tecnolog�as, no podemos dejar de mencionar qu� es lo que queremos hacer con la inteligencia artificial. Tal cual, como en Spiderman, con gran poder conlleva una gran responsabilidad. Es incre�ble lo c�nicos que son algunas personas, ahora que estoy en este espacio, que dicen que con esto vamos a poder eliminar y cambiar todo nuestro call center y que sean simplemente algunos agentes. Entonces, nosotros, �qu� estamos permitiendo al desarrollar este tipo de soluciones? �Cu�l es nuestro objetivo? �Es realmente reducir la fuerza laboral, ahorrarnos dinero y ganarlo nosotros mismos? �O realmente estamos buscando empoderar, ayudar a que m�s gente tenga acceso a estas tecnolog�as para el beneficio de todos?

00:57:17 - Los invito a que, conforme aprendan de estas tecnolog�as, intenten compartir este conocimiento no solo con sus compa�eros, sino tambi�n con sus pap�s, con sus vecinos, sobre c�mo se usan estas herramientas. Siempre tengan en cuenta que para aquellos que est�n creando estas soluciones, no es para el beneficio de unos pocos, sino de la manera l�gica y no solo para ustedes o el cliente de Alcatraz. Creo que es muy importante porque es algo muy nuevo que viene a revolucionar nuestra industria. Cuanto menos c�nicos seamos con el tipo de soluciones que desarrollamos, mejor ser�.

00:57:54 - Hay algunos slides que hablan un poco m�s sobre otros problemas �ticos que est�n imbuidos en los sistemas de lenguaje. Estos s� tienen ciertas tendencias o prejuicios, y casi se pueden mapear. Este modelo es un poco m�s libertario, es m�s autoritario, est� m�s alineado a la derecha o a la izquierda. Los modelos ya traen esos prejuicios. Hay ejemplos de preguntas y hay papeles completos que est�n aqu�, que vienen desde los datos de entrenamiento o a veces simplemente en el fine-tuning. Eran muy famosos los ejemplos de los DEC, que si le preguntaban sobre Tiananmen, no te respond�a, y no es porque los datos no est�n ah�. Luego pod�an hacer trucos de que, "Resp�ndeme", pero reemplazando las "haz" por "1" y las "6" por "unos". Y s�, respond�a. �Qu� pas� en Tiananmen? Lo mismo pasa con los modelos americanos. Si t� le preguntas a muchos modelos sobre Donald Trump o alg�n problema pol�tico actual, muy probablemente te dar� una respuesta muy vaga.

00:58:59 - Muchas veces no sabemos cu�l es el resultado �ptimo: si queremos que nuestros modelos reflejen fielmente la realidad, que en nuestra realidad t�pica siempre hay desigualdades, o si queremos que nuestros modelos sean un reflejo del futuro ideal que estamos buscando. Esto muchas veces nos termina disparando en el pie, como esos ejemplos rid�culos que hab�a de Gemini, que te mostraba cuando le ped�as que te dibujara a los Founding Fathers de Estados Unidos y todos eran racialmente diversos.

# Desarrollo de Herramientas Open Source

00:59:36 - Es dif�cil encontrar el balance. Bueno, tenemos una comunidad, y tambi�n los invito a participar en donde estamos construyendo algunas herramientas open source, por ejemplo, un modelo del RAC para el Diario Oficial de la Federaci�n. Estamos ahorita penetrando en ese proyecto. Algunos ejemplos de c�digo que les mostr�, un canal de Discord que apenas est� empezando, entonces en realidad est� ahorita muy callado, pero hay otros por fuera. 

01:00:02 - Ah, por ejemplo, hasta este de Jogging FACE tiene, ah, no se ve, tiene un canal de Discord, y ese s� tiene much�sima gente que est� interactuando sobre c�mo construir soluciones con Open Source y con inteligencia artificial. Este, y ese s� buscan hogar, Johnny FACE, Discord. Los va a salir en... creo que ser�a todo por ahorita. 

# Preguntas y Respuestas sobre Inteligencia Artificial

01:00:33 - �Tienen preguntas? Esperar para qu� tal, pero a ver si me cambio, me cambio tambi�n. Ah�, �me escuchas mejor? S�, o K. Estuvo este Joaqu�n, pues estuvo padr�simo, la verdad. O sea, demasiada informaci�n. La forma en que la concentraste toda se me hizo muy, muy padre. Yo creo que es un video que pueden... que bueno, que lo grabamos para que despu�s lo puedan volver a ver, �no? 

01:01:12 - Y s� que ahora llevan trabajando con ella en clases anteriores o por su cuenta. O en catones, no s�, ahorita ya est�n pensando c�mo lo van a integrar. Creo que fue un gran momento tener ahorita la sanci�n para que empiecen a ver d�nde m�s o c�mo lo pueden integrar, qu� opciones hay. 

01:01:31 - Y bueno, yo s� quiero abrir un poco, si tienes tanto tiempo Joaqu�n, para preguntas. Si tienes alguna pregunta, alg�n comentario, dudas, no s�. Creo que si tienes unos minutos, Joaqu�n, estar�a muy padre escuchar a los alumnos, a ver sus impresiones y tambi�n a todos los que est�n aqu� presentes, a los que estamos conectados. 

01:02:00 - A ver si adelante, Felipe, si quieres hacer tu pregunta porque el micr�fono del sal�n no funciona. No importa. Silva, �qu� piensa usted que va a ser el futuro? Por ejemplo, la cantes hace un a�o era como una tecnolog�a super nueva. �Qu� veo ahora que puede ser el pr�ximo? 

01:02:22 - �Habr� ya? Pues mira, por un lado, en la parte de RAC, hoy en d�a todo el mundo habla de agentes, �no? Que, bueno, los estamos desmitificando un poco en la presentaci�n en Rack. S�, hay muchas mejoras que vienen, �no? Una de ellas es ahorita, nada m�s Yamile, pero Jenny tiene este tama�o de contexto de 2,000,000 de caracteres, de tokens. Entonces, muchas veces ya ni necesitas una base de datos, le puedes mandar as�, no m�s toda la informaci�n y que te d� la respuesta. 

01:02:54 - S� que por ah� realmente no es lo m�s factible, pero hoy, porque nada m�s Jenny tiene eso y alg�n otro modelo Open Source que no es f�cil de correr, pero para all� va, �no? Entonces, yo creo que hacia adelante van a seguir aumentando estos tama�os de contexto. Les dir�a que m�s bien ustedes pongan mucha atenci�n a c�mo funciona. 

01:03:19 - Por detr�s, el problema va a seguir siendo el mismo, �no? Como traer informaci�n relevante, aunque t� le puedas pegar 2,000,000 de tokens. Va a ser importante cuando tienes millones de PDF con informaci�n, no la puedes alimentar toda de un jal�n. Justo ahorita que estamos con lo del Diario Oficial de la Federaci�n, una sola edici�n del Diario Oficial es como medio mill�n de tokens, �no? Entonces, con dos ediciones, con cuatro ediciones, y sale una edici�n cada d�a, ya te llenaste el tama�o de contexto. 

01:03:51 - Entonces, la soluci�n es RAC. Las han querido matar muchas veces, pero van a seguir siendo relevantes por un buen rato. Todav�a no. Entonces, simplemente s�, aprendan muy bien por la parte de agentes. Esta parte, Tully de funci�n Colin, y por el lado de Raz, entiendan bien c�mo funciona por detr�s, �no? Porque ah� hay muchas mejoras en Rack. 

01:04:15 - Tambi�n se habla mucho de c�mo mejoran los LSY, c�mo est�n evolucionando constantemente los modelos RAC. Tambi�n el que yo estaba usando hace un a�o, hoy en d�a ya sacaron tres versiones nuevas, sacaron Modern Bird, y sacaron... entonces ah� creo que todav�a es un campo que no ha explotado. No hay modelos de EADS, por ejemplo, nada m�s de espa�ol, que podr�an ser m�s chiquitos y correr todav�a m�s eficientemente. 

01:04:39 - Casi hay nada m�s, casi, casi, o en ingl�s, o en chino, o multilenguaje, que son bien grandotes. Si no tienen tan buena eficiencia, hacer fine-tuning de un modelo de embedding tampoco es complicado y muy poca gente lo hace. Eso s�, puede correr en mi computadora. Un fine-tuning de un modelo en vez de ingl�s, para que sea todav�a m�s eficiente o para que sea nada m�s para espa�ol, por ejemplo, y tener un modelo chiquito que funcione para espa�ol. 

01:05:04 - Entonces, ah� en esa parte de Racks, s� hay mucho, mucha blogspot, �no? Mucho, mucho de d�nde cortar con ganancias que a futuro vienen, como esas que les comento, no fighting modelo, RAC y modelos m�s especializados tambi�n. 

# Reflections and Takeaways

01:05:23 - �O.K.? Buena respuesta. �Alguna otra pregunta o comentario? Veo que hay mucho de qu� hablar. �Qu� es lo que m�s se llevan hoy? O sea, �con qu� de la pl�tica los dej� pensando? �Qu� aprendieron o con qu� se quedan? �Alguien que quiera compartir?

01:05:48 - Yo dir�a que ha habido muchas cosas. Bueno, mensaje a ver si puedes. �Tambi�n pregunto alguna vez? O.K. Hola Joaqu�n, �qu� tal? Muchas gracias. Bueno, yo creo que es muy interesante. Creo que nos habl� un poquito sobre las bases que de repente vemos mucho en Internet, pero que no logramos comprender completamente. Por ejemplo, eso de Rack, todos los nuevos modelos que est�n saliendo. Creo que si yo me llevara algo, ser�a que existen muchos nuevos modelos que salen muy r�pido y que parece que nunca dejan de avanzar.

01:06:23 - Pero yo te dir�a, �cu�l es tu opini�n? Justamente, en esa �rea donde buscamos la innovaci�n y buscamos como mejorar los modelos existentes, �podemos menospreciar el �rea de la seguridad en la inteligencia artificial? No, como que la inteligencia artificial que desarrollamos se asegura. Por ejemplo, he escuchado que en Europa dicen que est�n retrasando mucho el desarrollo de nuevos modelos precisamente por tener mucho control sobre esos modelos. Entonces, no s� cu�l es tu opini�n sobre eso.

01:06:53 - Yo dir�a que primero es importante aprender c�mo funcionan las cosas detr�s. A m� todo este tema de modelos Open Source y dejar de depender solo de los grandes proveedores es crucial. Entender c�mo funciona un sistema RAC, c�mo funcionan otros modelos peque�os de lenguaje y utilizarlos, nos va a habilitar a depender menos de esos proveedores y a entender mejor c�mo asegurar la calidad de las respuestas. Si siempre estamos usando lo que los grandes proveedores nos dan, creo que vamos a perder en el entendimiento de c�mo funcionan esos sistemas.

01:07:44 - S� que, por ejemplo, hay sistemas que te facilitan hacer una integraci�n RAC, y t� solo le mandas tus documentos y le env�as tu consulta a trav�s de una llamada. �PY te devuelve los resultados? Pues ah� tambi�n te est�s perdiendo de ciertas cosas, como hacer el chonqing, de c�mo hacer las consultas, de qu� modelos hay disponibles para hacer estos en Bearings. Entre mejor entiendan las bases de c�mo funcionan estos modelos, m�s podr�n asegurar sus sistemas. Van a tener menos dependencia y m�s libertad.

01:08:30 - Luego de ir cambiando algunos componentes, los invitar�a a leer mucho la documentaci�n para estar al tanto de muchas de estas cosas nuevas. Con�ctense con la comunidad, ya sea con esta de Joaqu�n en Twitter. S� que est� muerto para muchos, pero en el �mbito de inteligencia artificial est� m�s vivo que nunca. Todos los grandes investigadores y muchos de los grandes laboratorios de inteligencia artificial tienen sus cuentas de Twitter, y las personas que lo est�n desarrollando tambi�n las tienen. Est�n todos los d�as compartiendo algo nuevo. A veces te explota la cabeza, pero est� padre ver qu� cosas nuevas hay.

# Closing Remarks and Future Engagement

01:09:17 - Bueno, perfecto. Muchas gracias, Joaqu�n. Un �ltimo comentario, y si no, ya despedimos a Joaqu�n. �Alguien m�s quiere preguntar algo o ya despedimos a nuestro invitado? No, es muy interesante la pl�tica, Joaqu�n. Bueno, pues much�simas gracias de vuelta. Es un gusto poder escucharte y que hayas estado en este espacio. Vamos a ir cont�ndote c�mo va todo esto por ac�.

01:09:49 - Y gracias a �lvaro tambi�n por conectarse. �lvaro, no s� si quieres comentar algo o preguntar algo. No, de momento no. Digo, es bastante interesante el tema que abord� Joaqu�n. Para m� son muchas cosas nuevas, de verdad, muy interesante. Gracias. 

01:10:05 - S�, muchas gracias por este resumen, informaci�n y parte global de c�mo se va moviendo la inteligencia artificial. Pues nada, muchas gracias de vuelta. Gracias a �lvaro. Nos vemos al ratito, a las 11, para que veas las presentaciones de los alumnos. Salen las propuestas. Gracias, Joaqu�n. Nos vemos. �Bye! 

01:10:23 - Y ah� tienes el link para que lo compartas despu�s con los alumnos de la presentaci�n. Ah, s�, les paso la presentaci�n. Ahorita se las subo en Teams y tambi�n subo el video en Teams y te lo paso de vuelta. Dale, gracias. Nos vemos. �Bye, bye! �Bye!

