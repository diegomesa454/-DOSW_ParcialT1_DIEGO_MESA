# -DOSW_ParcialT1_DIEGO_MESA
# -requerimientos
funcionales:1.permitir al estudiante solicitar tutorias
 2. confirmar las tuturias 
 3.validar las materias
# . no funcionales: 1 ser responsive
 2: respetar los colores de ingenieria de sistemas 
# . - historia de usuario:como estudiante quiero solicitar tutorias para poder aprender mas sobre mi materia
# . - historia de usuario: como profesor quiero confirmar mis tutorias para que mis estudiantes puedan organizar su tiempo 
[diagrama de caso de uso]
(docs/uml/diagrama_de_caso_de_uso.png)
# . - patrones de diseño
# . -factory method -creacional
vamos a usar este patron de diseño para poder crear un objeto que me permita  solicitar las tutorias
# .- observator -estructural
vamosa a usar este patron de diseño para que una vez confirmada la tutoria envia un mensaje automaticamente al profesor y al estudiante
# . - diagrama de clases
(docs/uml/diagrama_de_clases.png)
# . - justificacion 
estamos usando dos principios de solid el open/closed porque nuestro proyecto queda abierto para añadir nuevas funcionalidades o cosas por el estilo y single responsability porque notifyne solo tiene la tarea de enviar el mensaje al profesor y al estudiante apenas confirme la tutoria.
