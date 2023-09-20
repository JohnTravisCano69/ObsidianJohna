Vim es un editor de texto altamente configurable y potente utilizado en sistemas Unix y Linux. Tiene numerosos comandos y combinaciones de teclas para realizar diversas tareas de edición y navegación. Aquí hay una lista de algunos comandos de Vim junto con su significado:

Nota: Los comandos de Vim a menudo se combinan con modificadores y movimientos, por lo que pueden ser más complejos de lo que parece a simple vista. Además, esta lista no es exhaustiva, ya que Vim tiene una amplia gama de comandos.

    Modos:
        i: Entra en el modo de inserción antes del cursor.
        I: Entra en el modo de inserción al principio de la línea.
        a: Entra en el modo de inserción después del cursor.
        A: Entra en el modo de inserción al final de la línea.
        o: Abre una nueva línea debajo y entra en el modo de inserción.
        O: Abre una nueva línea encima y entra en el modo de inserción.
        Esc: Sal de cualquier modo especial y vuelve al modo normal.

    Navegación:
        h, j, k, l: Moverse hacia la izquierda, abajo, arriba y hacia la derecha, respectivamente.
        w, b, e: Avanzar una palabra hacia adelante, hacia atrás o al final, respectivamente.
        gg, G: Ir al principio o al final del archivo.
        0, $: Ir al principio o al final de la línea actual.
        Ctrl-u, Ctrl-d: Desplazarse hacia arriba o hacia abajo por la mitad de la página.

    Edición:
        x: Elimina el carácter bajo el cursor.
        dd: Borra la línea actual.
        yy: Copia la línea actual.
        p, P: Pega el contenido copiado o cortado después o antes del cursor.
        u: Deshace la última acción.
        Ctrl-r: Rehace la última acción.
        :w: Guarda el archivo.
        :q: Sale de Vim.
        :wq o :x: Guarda y sale.

    Buscar y reemplazar:
        /patrón: Busca el patrón en el texto hacia adelante.
        ?patrón: Busca el patrón en el texto hacia atrás.
        n: Va a la siguiente coincidencia de búsqueda.
        N: Va a la coincidencia anterior de búsqueda.
        :%s/patrón/sustitución/g: Reemplaza todas las ocurrencias de patrón con sustitución en todo el archivo.
        :s/patrón/sustitución/g: Reemplaza la primera ocurrencia de patrón con sustitución en la línea actual.

    Ventanas y pestañas:
        :vsp o :vsp nombre_de_archivo: Abre un nuevo panel vertical.
        :sp o :sp nombre_de_archivo: Abre un nuevo panel horizontal.
        Ctrl-w seguido de h, j, k, l: Cambia entre paneles.
        :tabnew o :tabnew nombre_de_archivo: Abre una nueva pestaña.
        gt y gT: Cambia entre pestañas.

    Ayuda:
        :help: Abre la ayuda de Vim.
        :q en la ventana de ayuda: Cierra la ventana de ayuda.

editor de texto opcional para trabajar con [[ssh]]