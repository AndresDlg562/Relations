# Introducci�n y Presentaci�n de Joaqu�n Bravo

00:00:01 - Alumnos de sexto semestre y tesistas de tequila en el campus Monterrey. 

00:00:11 - Gracias, �lvaro, por conectarte. Tambi�n quiero darle la bienvenida a Joaqu�n Bravo. Joaqu�n Bravo es programador con 20 a�os de experiencia. Trabaj� en su propio despacho de software durante 10 a�os, desarrollando soluciones con Drupal para peri�dicos, revistas y universidades. Tambi�n ayud� a organizar conferencias de c�digo abierto en Latinoam�rica, lo cual es muy padre. Despu�s estuvo 6 a�os en Wayland, donde empez� como Tellez y termin� como director de innovaci�n. Actualmente trabaja en Vicks, desarrollando soluciones de all�. Es un experto en el �rea, y me da mucho gusto que podamos tenerlo aqu�, en este espacio, en el sal�n, compartiendo sus conocimientos con nosotros. Joaqu�n, muchas gracias. Bienvenido.

00:00:53 - Gracias, Elvia, por invitarme otra vez a estar aqu�. El semestre pasado, Joaqu�n nos acompa�� tambi�n en el sal�n. Gracias por volver a repetirlo, Joaqu�n. Con mucho gusto. 

00:01:09 - Pueden ver mi pantalla. �Sabes? Perd� la conexi�n un poco. D�jame volver a conectar mientras muevo la computadora. Ha estado fallando. 

00:01:23 - �Me escuchan? Bueno, s�, te escuchamos. Si quieren irse conectando por Teams, tambi�n pueden hacerlo, por si no logro conectar aqu� la pantalla. Solo necesito que todos en mi otra llamada se mantengan en silencio para que no se vicie el micr�fono. 

00:01:37 - �Ah, s�? Pero s� se pueden desmontar en cualquier momento si tienen dudas, con toda confianza. 

00:01:44 - Hola, buenos d�as. 

00:02:14 - Hola, hola. No creo que aprend�. Ah� est�, ya estamos. Ahora, s�, d�jame ver si conecta mi laptop. Hola, hola. 

00:02:47 - S�, no. Ya hab�a funcionado, pero mientras mov�a la computadora, como que dej� de funcionar. Siento que est� fallando, m�s bien es el cable de HDMI, �no? A veces hay que revisar el audio para ver a d�nde se est� mandando. 

00:03:21 - S�, pero no hay problema. Ni siquiera est� recibiendo la se�al. No, no, no puedo acceder. Pero creo que s� te escuchamos. No s� si alcanzan a escuchar hasta atr�s. 

00:03:34 - S�, s�, y nos conectamos por Teams. Entonces, adelante, Joaqu�n. Ustedes me dicen. 

# Desarrollo de Soluciones con Inteligencia Artificial

00:03:39 - Bueno, esta presentaci�n es como una introducci�n a c�mo desarrollar soluciones con inteligencia artificial. Hay un t�rmino que est� muy de moda, que es el de ingenieros de IA, que creo que es una combinaci�n de cosas que ustedes ya saben y que est�n aprendiendo como ingenieros en sistemas, m�s algunas otras cosas. 

00:04:00 - Es un poquito de lo que vamos a estar hablando, pero siempre tenemos que estar muy enfocados en construir soluciones, no tanto en la tecnolog�a, sino al final en el producto que queremos hacer. 

00:04:19 - �Ya me present� Elvia? Entonces, soy ingeniero, y s�, es un poquito diferente a otros roles ya establecidos en la industria, como un data scientist o un machine learning engineer. En el sentido de que, por ejemplo, un engineer no est� construyendo o desarrollando nuevos modelos, ni siquiera est� haciendo reentrenamiento de modelos existentes. 

00:04:46 - No requiere, al menos para esta parte de construir soluciones con inteligencia artificial, de teor�a muy avanzada sobre inteligencia artificial, redes neuronales o matem�ticas. No se enfoca en ese estilo, sino simplemente en conocer muy bien los modelos y las herramientas que se pueden utilizar para crear soluciones aumentadas, en ingl�s, con inteligencia artificial. 

00:05:18 - Mucho de esta presentaci�n, adem�s, ya hay, o sea, como el t�rmino est� muy de moda, a lo mejor ya han visto esta p�gina de Roach, que es muy buena, y justo acaban de estrenar este nuevo de Einer, que trae muchos t�rminos y buenos links para profundizar m�s. 

00:05:38 - A grandes rasgos, podemos decir que cuando vamos a construir este tipo de soluciones, vamos a tener ciertos binding blocks, ciertas piezas de lego que vamos a usar para construir estas soluciones. La primera, muy obvia, es esta herramienta, que es como ChatGPT, que nos vino a revolucionar toda esta industria y acelerar todo por ah� a finales del 2022. 

00:06:06 - Esa es una herramienta, los prompts, que es la manera en la que vamos a estar interactuando principalmente con estos elementos. El conocimiento que pueden obtener estos elementos no es solo el que ya tienen porque ya fueron entrenados por alguien m�s, sino el que les vamos a dar nosotros de nuestros usuarios y de nuestra tecnolog�a para mejorar la aplicaci�n. 

00:06:29 - Tambi�n hay integraciones con otros servicios, y vamos a ver que hay muchos otros modelos de los que podemos servir. No todos son modelos de lenguaje. Hay muchos otros modelos que, como ingenieros, es muy bueno conocerlos para no centrarnos �nicamente en matar mosquitos a escopetazos. 

00:06:57 - Adem�s, es importante saber c�mo implementar algo de integraci�n continua y despliegue continuo en nuestras soluciones para que sean robustas y funcionen bien en producci�n. Esto tambi�n est� basado en otra presentaci�n interesante de Look March�n, que se titula "Todos podemos ser ingenieros". Esto se basa en el conocimiento que ya tienen. Es decir, si ustedes ya saben lenguajes de programaci�n, librer�as, bases de datos e integraciones con servicios, ya tienen mucho de lo que se necesita.

# Componentes y Evaluaci�n de Modelos de IA

00:07:28 - Ahora, vamos a ver algunos de estos componentes, estas piezas del ecosistema. La primera, la m�s importante, es donde vamos a pasar m�s tiempo, en la parte de LLMs. Tenemos que escoger entre dos grandes grupos: los LLMs en la nube y los LLMs de c�digo abierto. En realidad, esa l�nea es un poco difusa, pero es �til para entender mejor las variaciones que vamos a ver entre los LLMs disponibles para nosotros. Estas variaciones vienen dadas por la calidad del modelo, es decir, qu� tan buenas respuestas da y qu� tanto conocimiento tiene.

00:08:11 - Otro aspecto importante es el tama�o del contexto, o "context window", que es fundamental conocer. Tambi�n debemos considerar el precio: cu�nto nos va a costar hospedarlo, ya sea en nuestros propios equipos o usando un servicio en la nube. Hay muchas maneras de evaluar esto, y hay muchos recursos disponibles, como tablas y gr�ficos en donde podemos ver c�mo est�n evaluados los diferentes modelos. 

00:08:44 - Por ejemplo, hay un sitio llamado artificialanalysis.ai donde siempre est�n comparando modelos de inteligencia artificial. Se puede hacer un "drill down" de las pruebas que est�n realizando. Actualmente, no est� actualizado con el �ltimo modelo que sali� esta semana, que es el Claude 3.7. De hecho, s� est� disponible, y lo actualizan muy r�pido.

00:09:18 - En cuanto a la velocidad de respuesta, esto tambi�n es importante a considerar dependiendo del tipo de aplicaci�n que estemos usando. Por ejemplo, en la parte superior de las evaluaciones est� el modelo "Owned Mini". El precio tambi�n es un factor a tener en cuenta. Muchos modelos tienen una opci�n gratuita, pero cuando quieres lanzar algo en producci�n, esa opci�n probablemente no ser� suficiente, y el precio comenzar� a ser importante.

00:10:08 - Algo m�s que quer�a mencionar sobre el precio es que estas son evaluaciones de otros modelos, y conviene familiarizarse con algunas de ellas. Aqu�, por ejemplo, explican exactamente qu� evaluaci�n est�n usando, como la de Nigma, el Multi Challenge o la de Visual Understanding. Dependiendo del tipo de soluci�n que queremos hacer, si tiene mucho de visual, tal vez nos convenga usar Gemini en lugar de otro modelo.

00:10:34 - Esta otra opci�n es un repositorio de GitHub donde se puede ver c�mo est� hecho este sitio, lstats.stats.com. Ellos traen una historia de c�mo han ido evolucionando algunos modelos con el tiempo. Podemos ver c�mo han ido subiendo en sus puntuaciones. En la parte superior, podemos ver a Brock y OpenAI, mientras que m�s abajo est� Mistral, que es una empresa francesa. Ellos tienen m�s evaluaciones sobre cu�l es el mejor para c�digo y razonamiento.

# Introducci�n a Modelos de Lenguaje y Tama�o de Contexto

00:11:22 - El tama�o del contexto ya lo mencionamos brevemente, pero el campe�n indiscutible en este momento es el modelo de Google, que tiene un tama�o de contexto de 2,000,000 de tokens. Cuando necesitamos enviar mucha informaci�n, este modelo ser� de las mejores opciones, junto con otros factores como el precio y la velocidad.

00:12:19 - Parece que ya logr� conectar el sal�n. D�jame cambiar la bocina un segundo. �Me escuchan bien? Hola, hola, �me escuchan? S�, los escuchamos.

00:12:39 - Muy bien, esta es otra gr�fica que creo que es de las �ltimas que les quer�a mostrar. La pongo ahorita; est� comparando otra vez el score, ahora contra el precio. Entonces, est� nuevamente a la hora de que vamos a salir. A producci�n va a ser muy relevante, �no? Mientras m�s para ac�, mejor calidad de las respuestas, y mientras m�s arriba son, m�s caros, �no? Entonces, estos que est�n abajo, pues tienen un s�per precio. La versi�n mini tambi�n tiene muy buen precio, y Claud Sweet, pues es un poquito m�s caro, pero tambi�n ahorita es el que tiene la corona del que entiende la mejor calidad de respuestas. 

00:13:22 - Incluso este de Sonnet, este de Claud, en la parte de c�digo es s�per relevante, ya que tiene una calificaci�n muy por encima de muchos otros modelos. Estaba escuchando de parte de la comunidad que desarrolla este tipo de soluciones que est�n impresionados, �no?, de la calidad. Adem�s, esto es porque junto con el nuevo modelo, liberaron un software Open Source que puedes usar en tu computadora para ayudarte a codificar, que es como una gente, �no?, del c�digo. 

00:13:58 - Entonces, eso lo hace a�n m�s relevante. Hablamos hasta ahorita casi de puros modelos hospedados en la nube. Si se fijan, por ah� hab�a algunos Open Source. De hecho, por ejemplo, de Ipsec lo puedes, lo Torres, normalmente en la nube, porque de hecho correrlo en Python en tu propia computadora no es tan f�cil. Para empezar, por el tama�o del modelo, que es un modelo muy grande, no como los modelos de Lama, que hay versiones m�s chiquitas. S�, es enorme y no es factible correrlo; m�s que versiones ya muy reducidas que no tienen la misma calidad de respuestas.

# Privacidad y Soberan�a en Modelos Open Source

00:14:32 - �Entonces estamos hablando de Claud models? Ahora, �por qu� querr�a uno usar o por qu� considerar de cualquier manera modelos Open Source? Bueno, hay varias razones muy buenas. La primera que luego sale y que pesa mucho es la privacidad de la informaci�n. Si vamos a estar tratando con datos privados de nuestra empresa que no quieren que se est�n mandando a proveedores terceros, entonces la �nica opci�n que queda es correr modelos Open Source, que puedes correr en tus propios equipos, en tus propios servidores, en tu propia LAN. As� evitas cualquier problema de privacidad o de seguridad de la informaci�n.

00:15:16 - Muchas veces, el Gobierno de Estados Unidos, por ejemplo, tiene ese tipo de pol�ticas. Seguramente muchos bancos y muchos clientes van a tener ese tipo de restricciones, a pesar de que muchos Claud providers, como el mismo OpenAI, Concha, GPT, Claud, todos ellos te dicen que si est�s usando la versi�n free, pues nada es gratis en esta vida. Al usarlo gratis, lo que te est�n cobrando es que van a usar los datos que t� les mandes para seguir entrenando sus modelos. Cuando pagas por sus APIs, ellos te dicen que no, que en la licencia, justo por pagar por sus APIs, ya no van a usar esos datos para entrenar sus modelos. Pero a�n con eso, con esa promesa, no hay nada que te la asegure. Con esa promesa de los proveedores cloud, de todas formas, muchos clientes optan por no utilizar estos modelos y m�s bien pulsar modelos que puedas correr en tu propia computadora, en tus propios servidores.

00:16:15 - Entonces, la privacidad de la informaci�n es muy importante. Muy relacionado a ese t�rmino est� la parte de soberan�a, no soberan�a de la informaci�n y de la tecnolog�a. Ah� podemos ver, por ejemplo, c�mo famosamente Estados Unidos, en su Gobierno, no va a querer que usen modelos chinos. Los chinos seguramente tambi�n tienen restricciones similares en donde, por nada del mundo, van a estar usando modelos gringos. Los europeos invierten tambi�n fuertemente en modelos propios, como esta compa��a de Mistral. Israel tiene sus propios modelos, y as�. Esta parte de soberan�a de la informaci�n es no depender de fuerzas externas, tener control sobre la tecnolog�a y la informaci�n que manejas, es un concepto muy importante. 

00:17:01 - No solo aplica a pa�ses, tambi�n puede aplicar a empresas. Esto est� muy relacionado con la privacidad, pero la soberan�a tambi�n te puede orientar a usar modelos Open Source, que adem�s van a tener m�s transparencia. Puedes tener m�s confianza en ellos, porque si tienes alguna duda de por qu� se est� comportando de cierta manera, los puedes ver. No son Open Source y, por eso, al ser abiertos, puedes ver c�mo es que las respuestas se est�n generando de cierta manera. 

00:17:31 - Algo que hay que mencionar es qu� tan Open Source realmente es el modelo, �no? �Qu� tan abierto realmente es? Porque hay tres cosas que pueden abrir. Una cosa es abrir los pesos del modelo, que es como quien dice que puedas usar el ejecutable, el bajarte el punto exe y usarlo. Eso depende de la licencia que le pongan, y muchas licencias de estos modelos son licencias abiertas, que puedes usar para lo que gustes. Algunas tienen licencias no comerciales. Algunos de estos modelos los puedes usar, pero para usos m�s bien educativos, acad�micos o de investigaci�n, pero no para uso comercial. Hay que revisar la licencia, pero eso de liberar los pesos es, es, es como liberarte una estable. No, realmente no hay una transparencia sobre c�mo funciona el modelo.

00:18:22 - Algunos liberan tambi�n el dataset, que es lo m�s raro; en realidad, muy poco liberal en el dataset, pero s� hay algunos datasets libres que puedes ver, o pueden liberar el c�digo. El c�digo necesario tambi�n para, ya sea que usaron para entrenarlo o el que se usa para correrlo, �no? Y bueno, dentro de estos niveles de transparencia es donde vas a ir ganando confianza tambi�n en el modelo. Con esta transparencia y con esto que podemos ver del modelo, de c�mo funciona, pues tambi�n nos permite customizarlo de mejor manera. Es m�s f�cil customizar modelos Open Source, que puedes bajar el modelo y entrenarlo en tu propio equipo, que hacer este tipo de customizaciones contra modelos como los de OpenAI y otros proveedores.

00:19:14 - Siempre se habla primero de OpenAI porque es el primero y es de donde muchos se est�n copiando muchas de estas buenas pr�cticas. Te ofrece de manera de hacer fine-tuning de su modelo, pero es dif�cil, es costoso y te est�s atando a ese modelo. Mientras que si lo haces con un modelo Open Source, tienes un poco m�s de libertad hacia donde moverte. Te est�s dejando de depender de un proveedor externo.

# Ventajas de Usar Modelos Open Source

00:19:45 - Finalmente, otra parte que se menciona aqu� es usar Open Source para ahorrarnos dinero. Bueno, con todo lo que han sido abaratados los costos. Les mostraba yo esta tablita anterior, donde los m�s baratos realmente son OpenAI con GPT-3.5, que es s�per barato. Claude de Anthropic tampoco es tan caro. A Jiminy, no s� por qu�, pero es barat�simo; realmente es rid�culo lo que cuesta el token. Entonces, a veces no tanto, vamos a ahorrar en el costo. S�, pueden ser mucho m�s eficientes algunos de estos modelos en la nube, pero est� tambi�n este componente en donde un modelo Open Source puede llegar a correr incluso en tu computadora.

00:20:28 - Hay modelos Open Source que puedo correr en mi computadora personal, en una MacBook Pro, por ejemplo, o en una computadora que tenga estos �ltimos chips que est� sacando Intel o AMD, que tienen soporte para inteligencia artificial. Con cierto RAM, pueden correr en esos, o incluso en celulares. En el edge, le llaman. Hay modelos tan peque�os que pueden correr tambi�n ya en tu celular o en dispositivos peque�os como Raspberry Pi, por ejemplo. Entonces, ciertamente puede haber tambi�n un ahorro en costos, puesto que no est�s necesitando ni siquiera correrlo en un equipo que ya tienes.

00:21:06 - Aqu� tambi�n puede haber cierto ahorro a la ecolog�a. Adem�s, estos modelos, como se sabe, c�mo funcionan los modelos Open Source, son los que han avanzado mucho m�s en esta parte de la eficiencia y del ahorro en qu� tan caro es correrlos. Son los que han empujado 100% a que bajen los precios tan dram�ticamente los modelos en la nube. Entonces, s� vale la pena considerar eso tambi�n.

# Evaluaci�n de Modelos Open Source

00:21:38 - Entrando ya a evaluaciones de modelos Open Source, est� este, por ejemplo, el leaderboard de Hugging Face. Para estos screenshots, solo list� los proveedores oficiales como para alistar aqu� los m�s famosos, justo para que salga. Por ejemplo, cuenta que es un modelo chino, de los mejores modelos que puedes correr justo en hardware relativamente que no necesitas un supercomputador. Est� Mistral, este modelo europeo que les llamaba la AMA, obviamente de Meta. 

00:22:08 - Entonces, estos modelos los podemos ver en este listado. Hay otros filtros en donde si dices t�: "Oye, �cu�l puedo correr en un consumer device? �No? �En una PC? �Cu�l puedo correr en un celular?" Y si se fijan, lo que baja principalmente es el n�mero de par�metros. Estos modelos cuentan con 72 billones de par�metros. Vic tiene 600 billones de par�metros. En realidad, no es factible correrlo m�s que en un supercomputador. 

00:22:33 - Estos modelos, para que puedan correr en computadoras personales, tienen 3.5. Esta es la versi�n a 3 billones de par�metros, a 6 billones de par�metros, y corren en una computadora personal. 

00:22:49 - Si nos vamos a los que son para edge, no tengo aqu� abierta la ventana, pero seguramente nos van a salir modelos de un bill�n de par�metros, m�ximo dos billones de par�metros. Y esos s� que son modelos que podr�s correr tambi�n hasta en tu celular muchas veces. Ah, hay por ah�, creo que el link lo ten�a por ac�, donde lo dej�. 

00:23:12 - Ah, s�, este. Bueno, tambi�n la pregunta que luego sale es porque no sale de ipsec, �no? En estos s�, si es de los m�s chidos Open Source, pues bueno, ah� cierta especulaci�n. En el mismo foro, Foro de Joaqu�n FACE, en donde, seguramente una parte es porque es un modelo de 600 billones de par�metros. Es grand�simo y los modelos que salen en esa tabla llegan hasta 140,000,000 de par�metros. O tal vez tambi�n porque dic todav�a no corre con la librer�a de Transformers, que es una de las librer�as Open Source m�s usadas. 

00:23:44 - �Sino es que la m�s usada para correr este tipo de modelos, no? Bueno, entonces, si tenemos alguna de estas caracter�sticas que nos dice, creo que un modelo Open Source ser�a una buena idea. �C�mo los corremos? 

# Implementaci�n y Ejecuci�n de Modelos Locales

00:24:01 - Lo m�s sencillo y por donde les dir�a que comenzar es por este software de O Lama. Por detr�s, usa la m�s P o otro proyecto en C++ que corre. No puede correr en GPU, pero tambi�n corre en CPU, es decir, no necesitas una super tarjeta gr�fica para correr O Lama o para correr algunos de estos modelos. Entonces, esa es la manera m�s sencilla. Es como el Docker de los L Tnes. Yo lo tengo instalado en mi computadora, tengo varios modelos ah� y es muy eficiente. 

00:24:28 - Yolanda, despu�s tambi�n lo podr�as correr en producci�n en alg�n servidor Linux. Podr�as correr O Lama y estar corriendo ah� tus modelos ya para sistemas en producci�n. Correrlo tal cual sobre Python tambi�n es una opci�n porque permite ciertas optimizaciones que tal vez O Lama no soporta para CUDA. Por ejemplo, hay un proyecto que se llama BLM que es muy eficiente para servir a millones de clientes, desde Python o para la Mac. 

00:25:01 - Hay cierto c�digo de Python que utiliza bien los procesadores de Mac optimizados para inteligencia artificial, espec�ficamente la arquitectura MLX, que O Lama hoy en d�a no lo soporta. Hay un ticket abierto por ah�, pero no han agregado esa funcionalidad. Entonces, hay ciertos casos en donde conviene correr este c�digo de Python. 

00:25:27 - Ah, o si est�. Nada m�s probando, hay uno que se llama El Estudio. Este no es Open Source, O Lama s� es Open Source. El Estudio no es Open Source, pero tambi�n si quieren jugar con modelos en su computadora, esta es una buena soluci�n que s� corre esta arquitectura de MLX con Python en la mano. Entonces, tambi�n vale la pena considerarlo para jugar, no para producci�n. 

00:25:53 - Y hay algunos estimadores de qu� tanto RAM necesitar�as para correr un modelo de manera local en tu computadora. Por ejemplo, aqu� te est� diciendo que tengo un modelo de 25,000,000 de billones de par�metros que est� cuantizado. Cuantizado es una palabra que usan para decir que los modelos normalmente est�n basados en arreglos de vectores que tienen 16 bits y luego le reducen el n�mero de bits en cada uno de esos vectores para reducir el tama�o del modelo. 

00:26:25 - Sigue teniendo 25,000,000 de par�metros, pero en n�meros m�s chiquitos que los hacen m�s eficientes. Si bien pierden, claro, bastante de la calidad en la respuesta, no toda. O sea, no se vuelven tontos, pero no tienen la misma calidad en las respuestas. Entonces, un modelo de estos de 25 billones de par�metros cuantizado a cuatro bits se estima que pudiera correr, por ejemplo, con una computadora que tenga 16 GB de RAM. 

00:26:50 - As� que podemos ver que si bajamos los n�meros de par�metros a algo m�s chiquito, por ejemplo, yo tengo 8 gigas de RAM. �Puedo correr? Tal vez hasta 9 billones de par�metros con una cuantizaci�n de cuatro bits. Este fue el primero que encontr� en Internet. Hay otras calculadoras, ya no me gust� esta, que no pude m�s bien modificar yo los par�metros y que me diga el RAM. 

00:27:20 - �El RAM te dice cu�l modelo estima que vas a poder correr? Hay m�s, hay m�s calculadoras y nos da una idea general. Esta computadora que tengo yo aqu� tiene 36 gigas en RAM. Entonces, puedo poner modelos m�s grandes. 

# Integrating Large and Small Models

00:27:36 - Finalmente, esta frase que me gusta mucho de este comercial: �por qu� no los dos? Acaban de anunciar tambi�n esta semana un proyecto en colaboraci�n, me parece que es la Universidad de Stanford, junto con Obama, en donde est�n haciendo proyectos en los que corren, por un lado, un modelo muy grande, remoto, como ChatGPT o como Claude, junto con modelos chiquitos locales de 8,000,000 de par�metros como O Lama. 

00:28:08 - Juntos pueden resolver problemas a una fracci�n del costo que si se lo mandaras nada m�s al modelo grande. El costo de resolver el problema es muy, muy alto, y la calidad de la respuesta es la mejor. Pero si usas esta combinaci�n de un modelo grandote orquestando muchos modelos chiquitos para cosas m�s sencillas, obtienes una muy buena calidad de respuesta a una fracci�n del costo.

00:28:37 - Entonces, este tipo de soluciones para algunos problemas, obviamente, no funciona para todo. Es un nicho muy espec�fico de problemas, por lo que vale la pena investigar este tipo de soluciones. No solo se trata de usar ambos modelos, sino que algo m�s que les dir�a es que intenten desacoplar, de todas formas, al principio que est�n desarrollando una soluci�n. Desacoplar no significa casarse por completo con alg�n modelo, puesto que este est� evolucionando constantemente. Es bueno usar librer�as; hay libros para empezar. La mayor�a de muchos de los proveedores soportan el mismo API que OpenAI.

00:29:21 - Por ejemplo, el mismo cliente que est�s usando en Python o en JavaScript de OpenAI para conectarte a la API, si le cambias el servidor y en vez de apuntar a OpenAI, apuntas a tu local host corriendo, va a funcionar. Entonces, hay mucha interoperabilidad. Por un principio, conviene no casarse tanto con un modelo espec�fico. Me gust� much�simo la idea de no casarse con el API de OpenAI, sino usar herramientas que te atraigan un poquito.

00:29:49 - OpenAI y su cliente son una de estas herramientas. Otras en Python son algunas librer�as como Little Lem, que es una sola librer�a con la que te conectas a todos los que quieras. Esta librer�a soporta much�simos proveedores. Hay otra de un compa�ero llamado Andrew en G, que es famoso porque tiene un sitio de "AI for Everyone" y ofrecen cursos gratuitos de inteligencia artificial. Su equipo liber� una librer�a que se llama AI Suite. Tambi�n hay ejemplos de esa librer�a que es multi.

00:30:23 - En JavaScript, tambi�n hay librer�as como Lem 10. Ross tiene las suyas. Hay otra de una persona llamada Jason Lee que se llama Instructor, que es muy interesante. Esa misma librer�a tiene soporte para Python, TypeScript, PHP, Ruby, Elixir, y seguramente con distintos niveles de soporte. En realidad, Python casi siempre es lo m�s importante en este tipo de soluciones. En segundo lugar, dir�a que JavaScript es relevante.

00:30:50 - Una opini�n que tengo, que puede ser un poco controversial, es que siento que es mejor evitar, al menos en un principio, o sobre todo ustedes que est�n aprendiendo a desarrollar este tipo de soluciones, librer�as grand�simas que tratan de abarcarlo todo, como LangChain o como LlamaIndex. Se convierten en una capa de abstracci�n tan grande que te conviertes m�s en un ingeniero de LangChain o de LlamaIndex y en realidad no aprendes el detalle fino de algunos de los componentes de estas soluciones. 

00:31:30 - El lenguaje es un componente muy importante que puede tener su propia capa de abstracci�n, pero hay muchas otras partes de estas soluciones. Son bloques de Lego que les comentaba. Si todo lo est�s usando con LangChain, creo que al final m�s bien te va a limitar, adem�s de que tiene su propia curva de aprendizaje muy grande. Esa es mi opini�n personal, y es una opini�n muy compartida tambi�n en algunos foros.

# Knowledge Management in AI Solutions

00:31:53 - Ahora, pasemos al siguiente bloque de Lego, que es el conocimiento. Bueno, los modelos ya tienen conocimiento, pero �c�mo doy conocimiento que ellos no tienen porque es propio de mi compa��a, de mi organizaci�n? Lo m�s normal es, por un lado, pensar en el fine-tuning. Pero el fine-tuning es muy caro. En realidad, la soluci�n por defecto que m�s se usa es aumentar justo el conocimiento que ya tiene, haciendo copy-paste, como quien dice, en el prompt de la informaci�n a la que tiene acceso el modelo para lograr hacer esto. 

00:32:35 - Para ello, necesitamos una base de datos. Esta es una presentaci�n m�s larga que tengo, nada m�s con un resumen de sistemas RAG, en donde normalmente tienes dos pasos. Por un lado, en tu base de datos, tienes toda la informaci�n que t� tengas de tu compa��a, que bien puede ser las �rdenes de compra, documentos en PDF o lo que sea. La indexas para que pueda ser buscada cuando el usuario est� interactuando.

00:33:12 - En un primer momento, indexas toda esta informaci�n para las b�squedas, y cuando el usuario est� interactuando, ya sea haciendo una pregunta directamente en un chat o interactuando con alg�n filtro, vas a poder convertir esa interacci�n del usuario en un vector o algo que puedas buscar f�cilmente en esta base de datos que tienes de toda tu informaci�n. As�, puedes traerte el contenido relevante de la base de datos y envi�rselo al usuario para dar una respuesta.

00:33:47 - Este tipo de soluciones RAG son s�per t�picas. En aprender m�s o menos c�mo funciona, �no? Pero a grandes rasgos, estos son todos sus componentes. No es una base de datos de vectores que bien puede ser el mismo PostgreSQL. Ya manejan Esquivel Light, MySQL; son bases de datos que soportan tambi�n b�squeda de vectores. 

00:34:08 - �O hay bases de datos especializadas? Pero si ya est�n usando alguna base de datos de estas no relacionales, les dir�a que simplemente le agreguen este componente de vectores. Si quieren usar una base de datos especializada como Chroma, hay muchas opciones; tambi�n lo pueden hacer, �no? Este componente de b�squeda es la parte importante, ya que pueden hacer b�squedas de texto normales. Full text search, que tiene sus propios �ndices para full text search en MySQL. Lo mismo ocurre con otras bases de datos, o lo pueden combinar con estas b�squedas de vectores para hacer b�squedas no tanto basadas en los keywords, sino en el sentido de lo que est�s buscando en la aplicaci�n. 

00:34:56 - Y eso, entonces, ya ese conocimiento que t� ten�as en la base de datos se lo vas dando al LLM conforme el usuario lo necesita para poder ir produciendo respuestas. Eso es, a grandes rasgos, c�mo funciona una soluci�n RAG. Este es un prompt, uno de los componentes que mencionamos. Tambi�n estos Lego blocks son los prompts. Este es un producto t�pico para una soluci�n RAG, �no? En donde, tal cual, ya hiciste la pregunta del usuario. 

00:35:25 - Lleg� la pregunta del usuario, hiciste una b�squeda en la base de datos y te trajiste documentos relevantes que le vas a dar al LLM en el prompt. Entonces, al front, casi casi le pones casi literal el contexto y le pones todos los documentos que te trajiste de la base de datos. Los puedes poner formateados en JSON o en XML, o si es puro texto, pues simplemente copypaste del contexto. Luego, unas instrucciones t�picas de un programa de RAG son: "Utiliza este contexto para contestar la pregunta. Si la respuesta no est� en el contexto, di que no sabes". 

00:36:01 - Y ah� est�s un poquito, tambi�n evitando las alucinaciones, y lo hago con mi padre de la pregunta, �no? Y esto es un solo plan que le mand� a Salem y ya te va a dar una respuesta basada en tu conocimiento. Entonces, si se fijan, esto es algo en realidad bastante sencillo. 

# Data Integration and Structuring Outputs

00:36:17 - Otro componente que mencionamos son las integraciones. Para hacer estas integraciones, como esta misma, no lo estamos integrando con nuestra base de datos. Hay que pensar en dos cosas. Por una parte, tenemos que estructurar el output que nos genera para poder hacer estas integraciones. Muchas veces necesitamos que la respuesta que venga del LLM, ya junto con el input del usuario, etc�tera, venga formateada de cierta manera que nosotros la podamos usar en nuestro sistema. 

00:36:48 - No nada m�s para un chat. Un chat es lo primero que pensamos cuando estamos hablando de soluciones aumentadas por LLMs o por inteligencia artificial. Pero no, no nada m�s con los chats. Si queremos otro tipo de cosas, por ejemplo, podemos extraer informaci�n de los inputs del usuario, de un texto o de una imagen. 

00:37:08 - �Podr�amos sacar, por ejemplo, de un recibo que nos est� dando el usuario? Podemos sacar los line items, cada �tem, cu�nto cuesta y el total. De una foto que era dif�cil de parchear, el LLM nos ayuda a obtener un JSON con esta informaci�n. O si tenemos recetas de cocina, un recetario, y lo escaneamos, podemos pedirle a un LLM que nos vaya dando de cada receta el nombre de la receta, una lista de ingredientes en formato JSON y las instrucciones de c�mo prepararlo. 

00:37:39 - Entonces, estamos de contenido no estructurado, sacando contenido estructurado que podemos utilizar de distintas maneras en nuestra aplicaci�n. O le damos un CSV, un PDF que tiene tablas, a lo mejor informaci�n financiera, y queremos que esa tabla nos la convierta en un CSV para poderlo usar en nuestra aplicaci�n de cierta manera. Esto es un uso muy t�pico de este tipo de soluciones, estos modelos en donde de contenido no estructurado estamos sacando contenido ya �til para nuestras aplicaciones. 

00:38:11 - Ya se hizo, nosotros podemos operarlo dentro de nuestro sistema. Podemos acceder a cierto campo y mostrarlo en cierta parte de nuestra interfaz. Entonces, como se hace mucho de esto, puede ser en el mismo prompt. En el mismo prompt, por favor, quiero que des la instrucci�n de que el output venga de esta manera y le das un ejemplo de c�mo quieres formateado el output. Esta es una manera, o hay librer�as que te facilitan esto. Tambi�n OpenAI tiene su formato para hacer estructural, para que te devuelva JSON y lo mandas de cierta manera en su API. 

00:38:51 - Lo mismo con Jenny. Tienes algunos ejemplos muy buenos aqu�, justo para, por ejemplo, extraer las recetas, �no? �Y c�mo logras que te mande? As� es, eso que les comentaba: el nombre de la receta, los ingredientes, las instrucciones. Vienen ejemplos de c�mo lograrlo. Casi todos los ejemplos en realidad que est�n mostrando son como este, c�mo obtener el clima, me parece. No les voy a EH.

00:39:15 - Hola, Ma. Si usan la librer�a de Obama o Llama, tambi�n tiene facilidades para intentar obligar a los QL Tnes que us� la AMA para que te manden output estructurado en alg�n formato espec�fico, como JSON. Cuando te vas a esa funcionalidad, hay ciertos modelos que puedo usar y otros que no. Entonces, tambi�n hay foros en donde dicen: "Oigan, estoy usando la AMA, pero no me funciona bien con tal modelo para producir JSON". Ah, es que te recomiendo usar este otro, no esta librer�a que les mencion� antes de Instructor. Este es un c�digo de Instructor, nada m�s. As�, muy r�pido, para ver c�mo funcionar�a.

00:39:51 - Algo as� est�n usando un modelo cloud que es de coger, pero si le cambias de aqu� a en vez de usar coger a usar OpenAI, es el mismo c�digo. Entonces, simplemente le dices, "from coger" o "from OpenAI", le mandas el cliente, le mandas tu prompt y le dices qu� modelo quieres usar. Le mandas, a lo mejor, un pedazo de texto en donde alguien te est� diciendo: "Ah, pues tengo 25 a�os y t� quieres extraer el nombre de la persona y su edad". Entonces, parchear esto con un retweet, �s�? Pues cambia constantemente, �no? 

00:40:24 - Entonces, para nosotros, programarlo tradicionalmente ser�a dif�cil extraer ese tipo de datos. Para LM es muy sencillo, �no? Entonces, m�s bien defines en Instructor una clase de los campos que necesitas extraer y es lo que mandas. Respondes, modelas y esto te va a hacer m�s o menos lo que necesita OpenAI o lo que necesitan distintas librer�as para hacer esa estructura. Al final, ya vamos a tener un objeto que tiene esos campos parcheados.

# Integrating Functions with Language Models

00:40:55 - Este es un ejemplo muy peque�o usando Instructor, no para hacer todo, sino para hacer integraciones. Es una de las cosas que necesitas. Otra muy importante es funci�n Collins, o Tool, que es otro nombre con el que se le conoce a estas funcionalidades. En el ambiente OpenAI, Cloud Mining o Llama, tambi�n tienen tus PS para c�mo hacer que los LM mismos. 

00:41:21 - Ac� nosotros estamos m�s bien de la respuesta del LM. La vamos a usar para nosotros insertar algo en la base de datos, pero nosotros en nuestro c�digo que escribimos no. Mientras que en funci�n Collins le vamos a decir al LM qu� funciones tiene disponibles para que �l decida si las quiere llamar o no, en base a las instrucciones del usuario. Entonces, es un uso un poco diferente, �no? Este es m�s reactivo y no depende de nosotros si se va a llamar la funci�n.

00:41:53 - Los ejemplos tambi�n est�n padres. Casi siempre, casi todos estos ejemplos son acerca del clima, de que el LM responde de acuerdo a las preguntas del usuario. Si tiene que, si tiene una funci�n para obtener el clima actual, este provee al usuario, �no? Bien, las instrucciones. Vamos a ver otra vez un ejemplo muy peque�o con esta otra librer�a que les mencionaba, que se llama E-Suite, que te ayuda a usar, te abstrae un poco la dificultad de hacer esto.

00:42:20 - Funci�n Collins, desde estos elementos, es un ejemplo chiquito, �no? Entonces, defines tu funci�n "Willy Trains" y necesitas mandar la ubicaci�n, �no? De en d�nde est�s y la hora del d�a. En base a eso, t� ya checas alg�n servicio externo o algo que tengas por ah� para devolver una respuesta. 

00:42:45 - Por ejemplo, en este caso, esta es la funci�n que quieres que el LM pueda llamar. Tienes los inputs del usuario que llegan y, por ejemplo, aqu� hay un usuario que est� diciendo en su input: "Yo vivo en San Francisco, �pudieras checar el clima? Planeo hacer un picnic alrededor de las dos". Entonces, a la hora de que usas esta librer�a, simplemente le mandas las herramientas disponibles, las funciones que va a tener el LM para decidir si la va a llamar o no. Le agregas un par�metro de cu�ntas veces puede iterar en estas llamadas para mandar la respuesta final al usuario y listo.

00:43:19 - El LM solito va a llamar tu funci�n y va a crear una respuesta con el output de la funci�n para responder la pregunta del usuario. Otro ejemplo muy t�pico es llamar funciones externas que el LM pueda llamar para checar el clima, checar tu base de datos, insertar nuevos r�cords en la base de datos, leer r�cords de la base de datos, etc�tera.

# Understanding Agents in AI

00:43:46 - Y eso nos lleva un poquito a este buzzword que est� muy de moda hoy en d�a, que es "agentes". Vamos a hablar un poco de agentes. 

00:43:54 - Hubo, esta semana, no, la semana pasada, una conferencia en Nueva York que era el "Engineering Summit", donde, por ejemplo, justo Adri�n habl� mucho de agentes. Alguien defin�a a los agentes; �l es uno de los organizadores de la conferencia. Dec�a que normalmente un agente consiste en tener tu modelo equipado con instrucciones que puede dar el usuario sobre lo que quiere hacer. Hay que definir qu� cosas s� puede hacer y qu� cosas no. Adem�s, hay herramientas o funciones que puede usar para extender las capacidades de este modelo que corre en un runtime. 

00:44:37 - Esta definici�n est� un poco rebuscada, pero es �til. Despu�s sali� una definici�n mucho m�s sencilla, que dir�a que es: un agente es simplemente un modelo que tiene acceso a funciones y herramientas, y que est� corriendo en un loop, en un "while true". Este modelo tiene acceso a ciertas herramientas y las puede usar si lo necesita. Por ejemplo, el agente que liber� Anthropic, y t� puedes ver el c�digo fuente, es bastante m�s completo. Te dice c�mo funciona esta herramienta de Anthropic que todo el mundo am�, c�mo te ayuda a hacer c�digo, y t� le puedes leer el c�digo fuente, te lee todo tu directorio, te puede modificar algunas cosas, agregar comentarios a tu repositorio de Git, etc�tera. 

00:45:33 - Tiene muchos tools disponibles, como un "dispatch agent", que puede correr cosas en el backend, leer archivos de tu l�nea de comandos, editarlos, reemplazar peque�as cosas, etc�tera. No tiene muchas herramientas disponibles que simplemente est�n corriendo en un loop dentro de su c�digo. No es realmente un "while true"; se ejecuta esto y no es m�s que eso, no tiene un servidor externo. En resumen, un agente es un modelo con acceso a funciones que corre en un loop. 

# Testing and Validation in AI Solutions

00:46:10 - Esto es para intentar desmitificar esa palabra. Tiene mucho buzz hoy en d�a, pero no es m�s que eso. �Ya pueden construir ustedes sus propios agentes? Bueno, esto va a ser muy importante, tambi�n la parte de c�mo probar, ya que les est�n ense�ando a ustedes todo acerca de "unit testing", "functional testing" y "automation". Cuando haces soluciones con inteligencia artificial, tambi�n vas a necesitar probarlas. 

00:46:41 - Algunas recomendaciones: obviamente, estas pruebas deben estar corriendo de manera autom�tica, con integraci�n continua, mientras est�n haciendo el c�digo, para que constantemente lo est�n evolucionando. Si cambian el modelo, por ejemplo, si estaban usando Claude 3.5 y sali� el 3.7, se actualizan. Seguramente algunas pruebas se van a romper porque est� cambiando el modelo que est�s corriendo por detr�s. Entonces, correrlas en un loop continuo con tus pruebas va a ser s�per importante. 

00:47:16 - Va a ser muy importante involucrar a "subject matter experts", es el t�rmino, a gente que entienda muy bien el conocimiento de tu aplicaci�n, de qu� se trata, qu� tipo de conocimiento es importante, qu� tipo de respuestas son las que esperamos y que sean ejemplos realmente significativos para que esos ejemplos de uso real de tu aplicaci�n los puedas probar. Es importante tener un set de pruebas que sea significativo. 

00:47:49 - Normalmente es muy famosa esta frase cuando se habla de datos en sistemas: "si le metes basura al sistema, te va a sacar basura". Entonces, es importante que estas pruebas sean buenas. Normalmente vas a estar checando la entrada del sistema de informaci�n. Si est�s usando alg�n sistema para traer informaci�n de tu base de datos para responderle al usuario sobre alguna cosa, algo que puedas probar sin siquiera irte a la parte de LM son tus mecanismos de b�squeda que te est�n regresando los registros de la base de datos que t� esperas que te regresen en los primeros lugares. 

00:48:27 - Es muy sencillo: simplemente haz pruebas de integraci�n de tu base de datos. Cuando llega cierto input del usuario y t� buscas en la base de datos, esperas que el resultado top sea este, porque sabes que ese es el documento relevante. Ah� es donde es muy importante el experto de tu base de datos, que sepa realmente cu�les son las respuestas relevantes que est�s esperando. Eso es muy f�cil de probar; es simplemente un query en la base de datos. 

00:48:58 - �Y cu�les son los resultados que est�s esperando? Conforme a eso, probablemente las pruebas las vas a tener que cambiar cuando cambien los queries de datos, pero te van a dar una idea de si tu sistema se est� rompiendo desde el input de conocimiento que le est�s mandando. 

00:49:12 - Otro tip es que tambi�n el output del modelo, es decir, las respuestas que generas, tienen que ser revisadas. Si se fijan, hay este argumento de temperatura, que te dicen que si le pones una temperatura alta, el modelo es m�s creativo. Lo que est� haciendo es agregarle un elemento aleatorio a las respuestas que genera. Si t� pones esa temperatura en cero, le quitas el elemento aleatorio y a un input te debe devolver siempre el mismo output. 

00:49:46 - Entonces, en tus pruebas del contenido que esperas generar con el modelo, pones la temperatura en cero, env�as un input del usuario y vas a esperar cierta respuesta, �no? Esa puede ser una prueba de integraci�n muy buena y certera. Si modificas algo en tu sistema y se rompe, vas a ver que algo pas� y necesitas modificar algo en el c�digo.

# Exploring Specialized AI Models

00:50:08 - Y bueno, ya casi se nos acaba el tiempo, pero tambi�n creo que es muy importante aprender que est�bamos hablando de modelos de lenguaje, pero hay muchos otros modelos que vale la pena considerar cuando estamos empezando a hacer soluciones aumentadas con inteligencia artificial. La inteligencia artificial no solamente son estos modelos de lenguaje; hay muchos modelos. 

00:50:29 - Voy a mencionar algunos, por ejemplo, modelos m�s especializados. Unos son los modelos de embedding que se usan justamente en estas soluciones. Hay de muchos tipos, algunos son solo para ingl�s o para chino. Hay otros modelos de embedding que son multiling�es o solo de franc�s, o creo que solo de espa�ol. No he visto muchos de esos modelos que te pueden sacar tambi�n cu�l es el vector que define una imagen, no solo un texto, para poder buscar im�genes o videos. Tambi�n hay modelos de embedding que te ayudan a sacar el vector de medios, de una imagen, de un video, de un sonido. 

00:51:08 - As� podemos, desde nuestra base de datos, traernos el contenido relevante. Para eso sirven estos modelos de embedding. Hablando de todos estos ejemplos, la gran diferencia es que son modelos especializados y mucho m�s peque�os que corren de manera m�s eficiente. Normalmente, los modelos de lenguaje, incluso los de c�digo abierto, van a necesitar un servidor potente, probablemente, si quieres respuestas de calidad. Pero estos modelos especializados, por ser m�s peque�os, pueden correr en hardware m�s limitado. 

00:51:36 - Hay algunos de estos modelos de embedding, por ejemplo, que corren en mi Raspberry Pi. Entonces, t� puedes tener tu sistema en producci�n, con la base de datos de vectores ya indexada. Cuando llega una pregunta del usuario, todo est� corriendo en la Raspberry Pi, que est� tomando la pregunta del usuario, convirti�ndola en vectores para comparar y buscar cu�les vectores son los m�s cercanos a esa pregunta. Luego, generas la respuesta con un modelo que est� hospedado en otro lado, no en la Raspberry Pi, pero el modelo de embedding s� puede correr en ella.

00:52:12 - Otros modelos, como los modelos de visi�n, te permiten extraer informaci�n de im�genes. Claro que puedes usar modelos grandes para eso, pero hay otros modelos m�s peque�os, como Mondrian o Small Vision Language Model, que tambi�n te permiten hacer este tipo de cosas, como la detecci�n de un coche en un video, extrayendo marca y modelo. Esto puede estar corriendo con un modelo peque�o, en lugar de un modelo enorme de 600 millones de par�metros; estos modelos son de 2 billones de par�metros y saben correr en dispositivos mucho m�s peque�os. 

00:52:54 - Entonces, vale mucho la pena verlos. Puedes describir im�genes, detectar objetos, extraer informaci�n. Por ejemplo, extraer de un recibo los precios individuales y el total lo puedes hacer con modelos grandes, pero tambi�n con estos modelos peque�os y gratuitos en tu computadora o en tu tel�fono. 

# Applications of AI in Text and Speech Processing

00:53:15 - Otros modelos especializados son para extracci�n de texto, como el OCR, que era el reconocimiento �ptico de caracteres. Convertir un PDF a texto. Hay dos proyectos de c�digo abierto que se usan en otros modelos, como IBM Markup, que si t� le das un PDF, te van a extraer todo el texto, incluso de fotos de documentos, y lo van a formatear en texto. 

00:54:01 - Tambi�n hay modelos de speech to text. Por ejemplo, Whisper, que es un modelo de c�digo abierto que puedes usar para escuchar audio y traducirlo a texto. Esto puede ser muy �til. Justo hicimos unas aplicaciones hace algunos semestres, donde los alumnos ayudaban a practicar ingl�s. Entonces, t� le hablabas a la computadora, extra�a el texto, y ese texto despu�s lo evaluaban con algunos problemas usando un modelo de lenguaje que te dec�a si estaba bien o mal. 

00:54:31 - La calificaci�n te iba evaluando tu nivel de ingl�s o te ayudaba a practicar tu ingl�s. No, y eso es con el modelo speech to text. Por ejemplo, hay un Whisper web, una versi�n de Whisper que corre en el navegador. Entonces, t� puedes directamente en el navegador, sin usar un servidor. Es un modelo m�s peque�o que puede correr en el browser. 

00:54:52 - �Depende de la computadora y de qu� browser, verdad? Y te puede ir extrayendo en el mismo navegador este texto de audios o de archivos, o de la c�mara del video. Tambi�n. Este es un ejemplo de Mondrian, Bustamante extrayendo, y esto de c�mo se usan estos modelos. Es c�digo muy sencillo. 

# Creating Proofs of Concept with Python Libraries

00:55:17 - Finalmente, esto te va a ayudar a crear pruebas de concepto. Hay librer�as en Python muy sencillas para esto. Streamline, Grader�o, Marimo. Aqu� son excelentes librer�as de prototipado en Python. Fast HTML tambi�n es muy bueno si quieres un poco m�s de personalizaci�n. Incluso aqu� hay un c�digo open source hecho por m�, no hay promocion�ndolo, que es justo toda una aplicaci�n sencilla de c�mo extraer texto, hacer b�squedas y luego crear un chat muy sencillo con Fast HTML. 

00:55:54 - Hasta ah� no est� s�per avanzado, pero es un ejemplo completo de c�mo hacer esto en Python. En JavaScript tambi�n se puede hacer mucho de esto y hay algunos workshops por ah� de c�mo funcionan los embeddings. Hay un video que grab� hace poquito, un repositorio y unos slides. 

# Ethical Considerations in AI Development

00:56:13 - Ah, muy importante, consideraciones �ticas. Ustedes que son privilegiados, no simplemente por estudiar en la universidad, digamos en el TEC de Monterrey, y de aprender este tipo de tecnolog�as, no podemos dejar de mencionar qu� es lo que queremos hacer con la inteligencia artificial. Tal cual, como en Spiderman, con gran poder, conlleva gran responsabilidad. Es incre�ble lo c�nicos que son algunas personas. 

00:56:41 - Ahorita que estoy en este espacio, hay quienes dicen que con esto vamos a poder eliminar o cambiar a todo nuestro call center y que sean simplemente algunos agentes. Entonces, nosotros que estamos permitiendo el desarrollo de este tipo de soluciones, �cu�l es nuestro objetivo? �Es realmente reducir la fuerza laboral, ahorrarnos dinero y ganarlo nosotros mismos? �O realmente estamos buscando empoderar, ayudar a que m�s gente tenga acceso a estas tecnolog�as para beneficio de todos? 

00:57:17 - Los invito a que, conforme aprendan de estas tecnolog�as, intenten compartir este conocimiento no solo con sus compa�eros, sino tambi�n con sus pap�s, con sus vecinos, sobre c�mo se usan estas herramientas. Siempre tengan en cuenta para qui�n est�n creando estas soluciones. No es para el beneficio de unos pocos, sino de la manera l�gica y no solo para ustedes o el cliente de Alcatraz. 

00:57:44 - Es muy importante porque es algo muy nuevo que viene a revolucionar nuestra industria. Cuanto menos c�nicos seamos con el tipo de soluciones que desarrollamos, mejor. Hay algunos slides que hablan un poco m�s sobre otros problemas �ticos que est�n imbuidos en los sistemas de lenguaje. 

00:58:03 - �Tienen ciertas tendencias o prejuicios? Casi se pueden mapear. Este modelo es un poco m�s libertario, es m�s autoritario, est� m�s alineado a la derecha o a la izquierda. Los modelos ya traen esos prejuicios. Ya hay ejemplos de las preguntas. Hay papeles completos que vienen desde los datos de entrenamiento o a veces simplemente en el fine-tuning. 

00:58:30 - Eran muy famosos ejemplos de los DEC. Si le preguntaban sobre Tiananmen, no te respond�a, y no es porque los datos no est�n ah�. Luego pod�an hacer trucos de que, ah, resp�ndeme, pero reemplazando las "a" por "1" y las "6" por "1". Y s�, respond�a. �Qu� pas� en Tiananmen? Lo mismo pasa con los modelos americanos. Si t� le preguntas a muchos modelos sobre Donald Trump o sobre alg�n problema pol�tico actual, muy probablemente te da una respuesta muy vaga. 

00:58:59 - Muchas veces no sabemos cu�l es el resultado �ptimo. Si queremos que nuestros modelos reflejen fielmente la realidad, que en nuestra realidad t�pica siempre hay desigualdades, o si queremos que nuestros modelos de lenguaje sean un reflejo del futuro ideal que estamos buscando. Eso muchas veces nos termina disparando en el pie, como esos ejemplos rid�culos que hab�a de Gemini que te mostraba cuando le ped�as que te dibujara a los founding fathers de Estados Unidos y todos eran racialmente diversos. 

# Community Engagement and Open Source Tools

00:59:39 - Es dif�cil encontrar el balance. Bueno, tenemos una comunidad. Tambi�n los invito a que, si quieren participar, estamos construyendo algunas herramientas open source del RAC para el Diario Oficial de la Federaci�n. Estamos ahorita penetrando ese proyecto.

00:59:52 - Algunos ejemplos de c�digo que les mostr�, un canal de Discord que apenas est� empezando, entonces en realidad est� ahorita muy callado, pero hay otros por fuera. Por ejemplo, hasta este de Jogging FACE tiene un canal de Discord, y ese s�, con much�sima gente que est� interactuando sobre c�mo construir soluciones con Open Source e inteligencia artificial. Este s� busca hogar, Johnny FACE, Discord.

# Reflections and Questions

01:00:33 - Creo que ser�a todo por ahorita. Si tienen preguntas, esperen un momento. A ver si me cambio, me cambio tambi�n. Ah�, �me escuchas mejor? S�, o K. Estuvo este Joaqu�n, pues estuvo padr�simo, la verdad. O sea, demasiada informaci�n. La forma en que la concentraste toda se me hizo muy, muy padre.

01:01:08 - Yo creo que es un video que grabamos para que despu�s lo puedan volver a ver. S� que ahora llevan trabajado con ella en clases anteriores o por su cuenta. No s�, ahorita ya est�n pensando c�mo lo van a integrar. Creo que fue un gran momento tener ahorita la sanci�n para que empiecen a ver d�nde m�s o c�mo lo pueden integrar, qu� opciones hay.

01:01:35 - Yo s� quiero abrir un poco, si tienes tiempo, Joaqu�n, para preguntas. Si tienes alguna pregunta o comentario, no s�, creo que si tienes unos minutos, estar�a muy padre escuchar a los alumnos y ver sus impresiones. Tambi�n a todos los que est�n aqu� presentes, a los que estamos conectados.

01:02:00 - A ver si adelante, Felipe, si quieres hacer tu pregunta. Porque el micr�fono del sal�n no funciona. No importa. Silva, �qu� piensas que va a ser el futuro? Por ejemplo, la cantes una hace un a�o era como una tecnolog�a super nueva. �Qu� veo ahora que puede ser el pr�ximo? 

01:02:25 - Pues mira, por un lado, en la parte de RAC, hoy en d�a todo el mundo habla de agentes. Los estamos desmitificando un poco en la presentaci�n en Rack. Hay muchas mejoras que vienen. Una de ellas es que, ahorita, nada m�s Yamile, pero Jenny tiene este tama�o de contexto de 2,000,000 de caracteres, de tokens. Entonces, muchas veces ya ni necesitas una base de datos; le puedes mandar as� toda la informaci�n y que te d� la respuesta.

01:02:54 - S� que por ah� realmente no es lo m�s factible, pero hoy, porque nada m�s Jenny tiene eso y alg�n otro modelo Open Source que no es f�cil de correr, pero para all� va. Yo creo que hacia adelante van a seguir aumentando estos tama�os de contexto. Les dir�a que m�s bien ustedes pongan mucha atenci�n a c�mo funciona por detr�s. El problema va a seguir siendo el mismo: c�mo traer informaci�n relevante, aunque t� le puedas pegar 2,000,000 de tokens.

01:03:27 - �Va a ser importante cuando tienes millones de PDF con informaci�n? No la puedes alimentar toda de un jal�n. Justo ahorita que estamos con lo del Diario Oficial de la Federaci�n, una sola edici�n del Diario Oficial es como medio mill�n de tokens. Entonces, con dos ediciones, con cuatro ediciones, y sale una edici�n cada d�a, ya te llenaste el tama�o de contexto. 

01:03:51 - La soluci�n es RAC. Las han querido matar muchas veces, pero van a seguir siendo relevantes por un buen rato. Entonces, simplemente s�, aprendan muy bien por la parte de agentes. Esta parte, Tully de funci�n Colin, y por el lado de Raz, entiendan bien c�mo funciona por detr�s, porque ah� hay muchas mejoras en Rack. Tambi�n se habla mucho de c�mo mejoran los LSY, c�mo est�n evolucionando constantemente los modelos RAC. 

01:04:21 - El que yo estaba usando hace un a�o, hoy en d�a ya sacaron tres versiones nuevas, sacaron Modern Bird, y entonces ah� creo que todav�a es un campo que no ha explotado. No hay modelos de EADS, por ejemplo, nada m�s de espa�ol, que podr�an ser m�s chiquitos y correr todav�a m�s eficientemente. Casi hay nada m�s, casi casi, o en ingl�s, o en chino, o multilenguaje, que son bien grandes. 

01:04:44 - Si no tienen tan buena eficiencia, hacer fine-tuning de un modelo de embedding tampoco es complicado, y muy poca gente lo hace. Eso s� puede correr en mi computadora. Un fine-tuning de un modelo en vez de ingl�s, para que sea todav�a m�s eficiente o para que sea nada m�s para espa�ol, por ejemplo, y tener un modelo chiquito que funcione para espa�ol. 

01:05:04 - Entonces, en esa parte de Racks, s� hay mucho, mucha blogspot, mucho de d�nde cortar con ganancias que a futuro vienen, como esas que les comento, fine-tuning de modelo, RAC y modelos m�s especializados. 

# Insights on AI Models and Future Directions

01:05:25 - �Alguna otra pregunta o comentario? Veo que hay mucho inter�s. �Con qu� se quedan hoy? �Con qu� de la pl�tica los dej� pensando? �Qu� aprendieron o con qu� se quedan? �Alguien que quiera compartir?

01:05:48 - Yo dir�a que ha habido muchas cosas interesantes. Bueno, mensaje a ver si puedes. �Tambi�n pregunto alguna vez o K? Hola Joaqu�n, �qu� tal? Muchas gracias. Bueno, yo creo que es muy interesante. Creo que nos habl� un poquito sobre las bases que de repente vemos mucho en Internet, pero que no logramos comprender completamente. 

01:06:07 - Por ejemplo, eso de Rack, todos los nuevos modelos que est�n saliendo. Creo que si yo me llevara algo, ser�a que existen muchos nuevos modelos que salen muy r�pido y que parece que nunca dejan de avanzar. Pero yo te dir�a, �cu�l es tu opini�n? Justamente, en esa �rea donde buscamos la innovaci�n y buscamos como decorar los modelos existentes, �podemos menospreciar el �rea de la seguridad en la inteligencia artificial? No, como que la inteligencia artificial que desarrollamos se asegura. Por ejemplo, he escuchado que en Europa dicen que est�n retrasando mucho el desarrollo de nuevos modelos precisamente por tener mucho control sobre esos modelos. 

01:06:50 - Entonces, no s� cu�l es tu opini�n sobre eso. Yo dir�a que primero es importante aprender c�mo funcionan por detr�s. A m� todo este tema de modelos Open Source y dejar de depender de los grandes proveedores, entender c�mo funciona un sistema RAC, c�mo funcionan otros modelos peque�os de lenguaje y estarlos utilizando, nos va a habilitar a depender menos de ellos y a entender mejor c�mo asegurar la calidad de las respuestas. 

01:07:38 - Si siempre estamos usando lo que los grandes proveedores nos dan, creo que vamos a perder justo ah�, en el entendimiento de c�mo funcionan esos sistemas. S� que, por ejemplo, hay sistemas que te facilitan hacer una integraci�n RAC, y t� nada m�s le mandas tus documentos y le mandas tu query a trav�s de una llamada. Te devuelve los resultados, pero ah� tambi�n te est�s perdiendo de ciertas cosas, como hacer el chonqing, de c�mo hacer los queries, de qu� modelos hay disponibles para hacer estos en Bearings. 

01:08:24 - Entre mejor entiendan las bases de c�mo funcionan estos modelos, van a poder asegurar sus sistemas. Van a tener menos dependencia y m�s libertad. Luego de ir cambiando algunos componentes, los invitar�a a leer mucho la documentaci�n para estar al tanto de muchas de estas cosas nuevas. Con�ctense con la comunidad, ya sea con esta de Joaqu�n en Twitter. S� que est� muerto para muchos, pero en el �mbito de inteligencia artificial est� m�s vivo que nunca. Todos los grandes investigadores y muchos de los grandes laboratorios de inteligencia artificial tienen sus cuentas de Twitter, y las personas que lo est�n desarrollando tambi�n las tienen y est�n todos los d�as. 

01:09:13 - �Hay algo nuevo? A veces te explota la cabeza, pero est� padre. 

# Conclusion and Farewell

01:09:17 - Bueno, perfecto. Muchas gracias, Joaqu�n. Un �ltimo comentario, y si no, ya despedimos a Joaqu�n. �Alguien m�s quiere preguntar algo o ya despedimos a nuestro invitado? No, que es muy interesante la pl�tica, Joaqu�n. Bueno, pues much�simas gracias de vuelta. Es un gusto poder escucharte y que hayas estado en este espacio. Vamos a ir cont�ndote c�mo va todo esto por ac�. 

01:09:49 - Gracias a �lvaro tambi�n por conectarse. �lvaro, no s� si quieres comentar algo, preguntar algo. No, de momento no. Digo, fue bastante interesante el tema que abord� Joaqu�n. Para m�, fue muchas cosas nuevas, de verdad, muy interesante. 

01:10:05 - S�, muchas gracias por este resumen de informaci�n y parte global de c�mo se va moviendo la inteligencia artificial. Pues nada, muchas gracias de vuelta. Gracias a �lvaro. Nos vemos al ratito, a las 11, para que veas las presentaciones de los alumnos. Salen las propuestas. 

01:10:23 - Gracias, Joaqu�n. Nos vemos. �Bye! Y ah� tienes el link para que lo compartas despu�s con los alumnos de la presentaci�n. Ah, s�, les paso la presentaci�n. Ahorita se las subo en Teams y subo el video en Teams tambi�n y te lo paso de vuelta. 

01:10:37 - �Dale, gracias! Nos vemos. �Bye, bye!

