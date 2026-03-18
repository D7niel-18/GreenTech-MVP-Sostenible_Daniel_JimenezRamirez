# GreenTech-MVP-Sostenible_Daniel_JimenezRamirez
- Autor: Daniel Jimenez Ramirez
- Profesor: Willman Acosta
- Actividad: AEE_GreenTech. UD04
# Problemas encontrados
Este informe analizamos la refactorización del código fuente de la web del proyecto Salvemos el Planeta. Que trata de querer reducir la obsolescencia programada y a reducir el carbono embebido en el desarrollo de software. A través de ciertas comprobaciones en el HTML y CSS. He identificado dependencias innecesarias (Boostrap), scripts y malas prácticas que aumentan el consumo energético. Las soluciones propuestas reducen el peso de la página, eliminan dependencias no utilizadas y alargan la legibilidad del código.
# Soluciones
He eliminado por la parte de HTML todas las dependecias de Boostrap ya que eran innecesarias para lo que sea pedia y se ha podido solucionar haciendo un CSS donde colocar los estilos que previamente estaban colocados en el HTML, tambien se ha refactorizado el codigo y renombrado las clases de algunas partes del código, he eliminado cuatros scripts que se cargaban pero no eran necesarios para el funcionamiento de la web, el footer se generaba con un script de JavaScript cuando podriamos hacer con HTML y de una manera más sencilla. En la parte del archivo CSS he añadido comentarios para legilibidad del código y he quitado la parte !important que se encarga de hacer que tenga prioridad normalmente se suele usar cuando tenemos una dependecia como Boostrap para que ese estilo tenga prioridad, al haber eliminado Boostrap ya esto no es necesario.
# Conclusiones 
La refactorización del código de esta pagina no es solo algo estetico si no tambien algo que afecta al medioambiente. Con algunos ajustes hemos conseguido que la pagina cargue mas rapida, el servidor pueda trabajar de una manera mas desahogada lo que se convierte en menos calor y eso significa menos consumo electrico.
# Tecnologias usadas y editor
- HTML y CSS
- Visual Studio Code
