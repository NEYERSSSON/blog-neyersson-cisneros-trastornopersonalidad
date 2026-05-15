<index html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio Clínica - Mgt. Neyersson Cisneros</title>
    <style>
        :root {
            --primary: #2c3e50; /* Azul Clínico */
            --secondary: #34495e;
            --accent: #3498db;
            --success: #27ae60;
            --warning: #f39c12;
            --purple: #9b59b6;
            --light: #ecf0f1;
            --text: #333;
            --porta: #c00707b7;
        }

        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
            line-height: 1.6; 
            color: var(--text); 
            margin: 0; 
            /* Ajuste de imagen: más pequeña y sutil */
            background: linear-gradient(rgba(255, 255, 255, 0.9), rgba(255, 255, 255, 0.9)), 
                        url('image_76505a.jpg'); 
            background-size: 500px; /* Aquí controlas el tamaño. Prueba con 300px o 500px */
            background-attachment: fixed; /* La imagen se queda quieta al bajar */
            scroll-behavior: smooth; }

            body { 
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
    line-height: 1.6; 
    color: var(--text); 
    margin: 0; 

    /* CÓDIGO PARA LA IMAGEN DE FONDO */
    background-image: linear-gradient(rgba(255, 255, 255, 0.85), rgba(255, 255, 255, 0.85)), 
                      url('trastorno-de-personalidad.jpg'); 
    background-size: cover;       /* Cubre toda la pantalla sin deformarse */
    background-position: center;  /* Centra la imagen */
    background-attachment: fixed; /* La imagen se queda quieta al bajar (Efecto Parallax) */
    
    scroll-behavior: smooth; 
}
  
        /* Ajuste de navegación para que no tape los títulos */
         section { scroll-margin-top: 120px; }
        
            /* Header y Navegación */
        header { background: var(--primary); color: white; padding: 2.5rem; text-align: center; border-bottom: 4px solid var(--accent); }
        
        nav { background: var(--secondary); padding: 15px; position: sticky; top: 0; z-index: 1000; display: flex; justify-content: center; flex-wrap: wrap; gap: 10px; }
        nav a { color: white; padding: 6px 12px; text-decoration: none; font-weight: bold; font-size: 0.85rem; transition: 0.3s; border-radius: 4px; background: rgba(255, 255, 255, 0.453); }
        nav a:hover { background: var(--accent); color: white; }

        .container { max-width: 1150px; margin: 20px auto; padding: 20px; }

        /* Tarjetas Estilo Clínico */
        .card { background: white; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); margin-bottom: 30px; overflow: hidden; border-left: 5px solid var(--accent); }
        .card-header { background: #f8f9fa; padding: 15px 20px; display: flex; justify-content: space-between; align-items: center; border-bottom: 1px solid #ddd; }
        .card-body { padding: 20px; }
        
        .badge { background: var(--success); color: white; padding: 5px 12px; border-radius: 20px; font-size: 0.85rem; font-weight: bold; }
        
        h2, h3 { color: var(--primary); margin-top: 0; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; }
        
        /* Botones e Interactividad */
        .btn { display: inline-block; background: var(--accent); color: white; padding: 10px 18px; border-radius: 5px; text-decoration: none; margin: 5px 0; font-size: 0.9rem; border: none; cursor: pointer; }
        .btn-orange { background: #e67e22; }
        .btn:hover { opacity: 0.9; }

        table { width: 100%; border-collapse: collapse; margin-top: 15px; }
        th, td { padding: 12px; border: 1px solid #ddd; text-align: left; }
        th { background: var(--light); }

        .quiz-box { background: #fdfdfd; border: 1px solid #eee; padding: 20px; border-radius: 10px; margin-top: 10px; }

        footer { text-align: center; padding: 40px; background: var(--primary); color: white; margin-top: 50px; }

        /* Header y Portada Dinámica con Imagen */
        header {
            background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.7)), 
                        url('trastornos-de-la-personalidad.jpg') no-repeat center center;
            background-size: cover; /* Hace que la imagen cubra todo el espacio */
            color: white;
            padding: 5rem 2rem; /* Más espacio arriba y abajo */
            text-align: center;
            border-bottom: 6px solid var(--accent);
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5); /* Sombra para el texto */
        }

        header h1 {
            font-size: 2.8rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: auto;
            background: rgba(44, 62, 80, 0.6); /* Fondo semi-transparente para el texto */
            padding: 5px 15px;
            border-radius: 5px;
            backdrop-filter: blur(2px); /* Efecto de desenfoque */
        }
    </style>
</head>
<body>

<header>
    <div class="header-content">
        <h1>Maestría en Psicología Clínica</h1>
        <div class="'trastornos-de-la-personalidad.jpg'"></div>
        <p>Trastornos de la Personalidad</p>
    </div>
</header>

<div class="container">
    
    <section id="inicio" class="card" style="border-top: 5px solid var(--accent); border-left: none;">
        <div class="card-body" style="text-align: center;">
            <h2>Bienvenida al Portafolio Digital</h2>
            <p style="max-width: 800px; margin: auto; color: #555;">
                "La máscara que llevamos ante el mundo es solo una fracción de nuestra verdadera organización psíquica." 
                Como estudiante de esta maestría, este espacio busca profundizar en lo que hay detrás de cada rostro: 
                desde la herencia biológica hasta los patrones de conducta que definen nuestra identidad.
            </p>
        </div>
    </section>
<div>
<nav>
    <a href="#inicio">Inicio</a>
    <a href="#intro">Introducción</a>
    <a href="#profa">Dra. Aelen</a>
    <a href="#neyersson">Mgt. Neyersson Cisneros</a>
    <a href="#s1">Semana 1</a>
    <a href="#s2">Semana 2</a>
    <a href="#s3">Semana 3</a>
    <a href="#s4">Semana 4</a>
    <a href="#encuestas">Autoevaluación de Conocimientos Clínicos</a>
    <a href="#glosario">Glosario</a>
    <a href="#anexos">Anexos</a>
    <a href="#contacto">Dudas y Tips</a>
</nav></div>
<div>
    <!-- PORTADA / INICIO -->
    <section id="inicio" class="card" style="border-left-color: var(--porta);">
        <div class="card-body" style="text-align: center;">
            <h2>Portafolio Digital de Aprendizaje</h2>
            <p>Un resumen integral de la asignatura Trastornos de la Personalidad.</p>
            <hr style="width: 50%; opacity: 0.2;">
            <p><em>"La personalidad es la organización dinámica, dentro del individuo, de los sistemas psicofísicos que determinan su conducta y su pensamiento característico".</em></p>
        </div>
        </div>
    </section>
    <!-- INTRODUCCIÓN -->
    <section id="intro" class="card" style="border-left-color: var(--success);">
        <div class="card-body">
            <h3>Introducción</h3>
            <p> 📣 Este blog tiene como propósito documentar el proceso de formación en la Maestría de Psicología Clínica, integrando las bases teóricas, metodológicas y prácticas analizadas en cada sesión de clase. Aquí se presentan los entregables, reflexiones y herramientas didácticas desarrolladas.</p>
           <a href="#inicio">🔙</a>
           </div>
    </section>
    <!-- PROFESORA -->
    <section id="profa" class="card" style="border-left-color: var(--warning);">
        <div class="card-body">
            <h3> 👩🏻‍🏫 Docente : Dra. Aelen López</h3>
            <p>Doctora en Ciencias de la Salud y el Comportamiento Humano. Especialista en la investigación de procesos psicológicos y formación clínica de alto nivel.</p>
           <a href="#inicio">🔙</a>
        </div>
    </section>

    <!-- MGT. NEYERSSON CISNEROS -->
    <section id="neyersson" class="card" style="border-left-color: var(--secondary);">
        <div class="card-body">
            <h3> 🙋🏻‍♂️ Alumno : Mgt. Neyersson Cisneros</h3>
            <p>Estudiante de Maestría en Psicología Clínica. Padre de cuatro hijos y profesional comprometido con la aplicación de la tecnología al servicio de la salud mental y la comprensión de los trastornos de la personalidad.</p>
            <div style="background: #f9f9f9; padding: 10px; border-radius: 5px; border-left: 3px solid var(--secondary);">
                <strong>Pensamiento Clínico:</strong> "El estudio de la personalidad nos permite no solo entender al paciente, sino predecir rutas de bienestar".
             <a href="#inicio">🔙</a>
            </div>
        </div>
    </section>

    <!-- SEMANA 1 -->
    <section id="s1" class="card">
        <div class="card-header">
            <h3>📆 Semana 1: Bases - Metodología y Teorías clásicas en el estudio de la personalidad</h3>
            <span class="badge">🏆 90/100</span>
        </div>
        <div class="card-body">
            <div class="grid">
                <div>
                <h4>Contenido</h4>
                    <p> 🧠 El estudio de la personalidad es, quizás, uno de los desafíos más fascinantes y complejos de la psicología clínica. No se trata simplemente de observar cómo se comporta alguien, sino de desentrañar el rompecabezas gigante donde las piezas cambian de forma según el lente teórico con el que se miren.  En este espacio, exploramos el camino que va desde las estructuras más básicas hasta las teorías que han moldeado nuestra comprensión del ser humano:</p>
                    <p> 1. Bases y Metodología: El Cimiento del SerPara entender por qué somos como somos, primero debemos distinguir entre lo que traemos al nacer y lo que el mundo graba en nosotros. Aquí analizamos la Constitución física, el Temperamento innato y el Carácter aprendido. A través de métodos clínicos, correlacionales y experimentales, buscamos no solo describir la personalidad, sino predecir conductas y mejorar la intervención psicológica en el ámbito clínico.</p>
                    <p> 2. Teorías Clásicas: Diferentes Lentes para una Misma VerdadLa historia de la psicología nos ha legado diversas formas de entender la psique:</p>
                    <div>
                    <div>- El enfoque Factorial: Que mide rasgos estables y medibles como la extraversión o el neuroticismo.</div>  
                    <div>- El enfoque Conductual y Cognitivo: Que ve la personalidad como un sistema de hábitos aprendidos y significados construidos.</div>  
                    <div>- El enfoque Humanista: Que apuesta por el potencial de autorrealización y el proyecto individual de cada persona.</div>  
                    <div>- El enfoque Psicoanalítico: Que se sumerge en las profundidades del inconsciente y los conflictos de la infancia para explicar el presente.  Entender estas bases y teorías no es solo un ejercicio académico; es la herramienta fundamental para todo aquel que busca comprender la naturaleza humana en toda su diversidad y complejidad.</div>

                    <a href="CLASE_1.pdf" class="btn">📄 Ver Diapositiva Clase 1</a>
                 <a href="CLASE_2.pdf" class="btn">📄 Ver Diapositiva Clase 2</a>
                </div>
                <div>
                    <h4>Asignaciones</h4>
                    <p>Mapa Mental de determinantes de la personalidad y Esquema Conceptual de enfoques teóricos.</p>
                    </a><a href="NEYERSSON_CISNEROS_UNIDAD 1.pdf" target="_blank" class="btn" style="background: #0dff00ae;">
                    📂 Ver Entregable 1
                    </a>
                </div>
                <div><a href="#inicio">🔙</a></div>
        </div>
    </section>  <!-- SEMANA 2 -->
    <section id="s2" class="card">
        <div class="card-header">
            <h3>📆 Semana 2: Los criterios de normalidady anormalidad en la personalidad / Personalidad y Psicopatología</h3>
            <span class="badge">🏆98/100</span>
            <span class="badge">🏆95/100</span>
        </div>
         <div class="card-body">
          <h4>Contenido</h4>
                <p> 1. ¿Qué define la Normalidad y la Anormalidad? </p>
                <div> La normalidad no es perfección, sino la capacidad de funcionar eficazmente en la vida diaria. Se basa en un continuo donde no existe una línea exacta divisoria.  
                <div>- Criterios de Normalidad: Se caracterizan por la adaptación al entorno, el bienestar subjetivo, la flexibilidad cognitiva y conductual, y un manejo adecuado de las emociones (autocontrol).  
                <div>- Criterios de Anormalidad: Se manifiestan a través de la rigidez, el malestar significativo, el deterioro social y las distorsiones en la percepción de la realidad.</div> 
                <p> 2. Evolución Histórica de la PatologizaciónLa comprensión de la personalidad "desviada" ha tenido una transformación radical: <p> 
                <div>- Siglo XIX (Criminología): Autores como Lombroso vinculaban la anormalidad directamente con el delito y factores biológicos innatos ("delincuente nato"). </div>  
                <div>- Transición a la Psiquiatría: A finales del siglo XIX, las conductas desviadas dejan de verse solo como delitos para entenderse como trastornos mentales con diagnósticos clínicos. . </div>  
                <div>- Enfoque Actual: Hoy prevalece el modelo biopsicosocial, integrando biología, psicología y contexto social, dejando atrás la visión puramente criminalizante.. </div> 
        </div>
                    <a href="CLASE 3.pdf" class="btn">📄 Ver Diapositiva Clase 3</a>
                 <a href="CLASE_4.pdf" class="btn">📄 Ver Diapositiva Clase 4</a>
                 <a href="LISTADO DE TRASTORNOS - grupos - exposiciones de temas.docx.pdf" class="btn">📄 Ver Listas de transtornos y grupos</a>
                </div>
                <div>
                    <h4>Asignaciones</h4>
                    <p> 1. Diferencia entre la Personalidad Normal y Anormal . Observe los videos y luego desarrolle el reporte: 
                        <div style="margin-bottom: 15px;">
                           <a href="https://www.youtube.com/watch?v=eVvJZ0vZ4jg" target="_blank" class="btn" style="background: #FF0000;">
                              🎬 Ver Video 1 : Diferencia entre la Personalidad Normal y Anormal
                          </a>
                           <a href="https://www.youtube.com/watch?v=7IOZeViaXv0" target="_blank" class="btn" style="background: #FF0000;">
                            🎬 Ver Video 2
                             </a><a href="REPORTE_DE_VIDEO_neyersson cisneros.pdf" target="_blank" class="btn" style="background: #0dff00ae;">
                            📂 Ver Enteregable 2
                             </a>
    </div>
                    </p>
                    <p> 2. Lee el artículo de investigación y observa  el video  y  luego desarrolle el protocolo PNI Enlaces: 
    
                   <p>Lee el artículo científico y observa el video asignado para desarrollar el análisis de los puntos Positivos, Negativos e Interesantes (PNI).</p>
    
    <div style="margin: 15px 0; display: flex; flex-wrap: wrap; gap: 10px;">
        <a href="https://www.scielo.cl/scielo.php?script=sci_arttext&pid=S0719-05812016000100001" target="_blank" class="btn" style="background: #2c3e50;">
            🔗 Leer Artículo Personalidad y psicopatología
        </a>
        <a href="https://www.youtube.com/watch?v=gg9o7SBZvpU" target="_blank" class="btn" style="background: #FF0000;">
            🎬 Ver Video: La raíz de los trastornos graves de la personalidad | OTTO KERNBERG
        </a>
            </a><a href="protocolo PNI_ NEYERSSON_CISNEROS.pdf" target="_blank" class="btn" style="background: #0dff00ae;">
                            📂 Ver Enteregable 3
                             </a>
                              <div><a href="#inicio">🔙</a></div>
    </div>
            
         </section> <!-- SEMANA 3-->
          <section id="s3" class="card">
        <div class="card-header">
            <h3>📆 Semana 3: Presentaciones Trastorno de la Personalidad </h3>
            <span class="badge">🏆 100/100</span>
        </div>
         <div class="card-body">
          <h4>Contenido</h4>
                <p> 👥👥 Trastornos en Exposición (Semana del 12 al 16 de mayo)</p>
                <h4><p>Sesión del 12 de mayo</p></h4>
                <div>- Trastorno Paranoide de la Personalidad: Análisis de patrones de desconfianza y suspicacia generalizada hacia los demás.</div>
                <div>- Trastorno Esquizoide de la Personalidad: Estudio del desapego en las relaciones sociales y la restricción de la expresión emocional (incluye la presentación, Mgt. Neyersson Cisneros).</div>
                <div>- Trastorno Esquizotípico de la Personalidad: Evaluación de deficiencias sociales, distorsiones cognitivas y excentricidades del comportamiento.</div>
                <a href="PSICOPATOLOGÍA CLÍNICA Trastorno de la Personalidad Esquizoide Neyer, Akm007, Thelma Figueroa & Equipo Maestría en Psicología Clínica.pdf" class="btn" style="background: #0dff00ae;">📄 Ver Trastorno Esquizoide</a>
                <a href="RTRASTORNO PARANOIDE DE LA PERSONALIDAD.pdf" class="btn" style="background: #ff2f00c9;">📄 Ver Trastorno Paranoide </a>
                 <a href="Trastorno Esquizotipico de la personalidad.pdf" class="btn" style="background: #ffb700;">📄 Ver Trastorno Esquizotípico</a>
                <h4><p> Sesión del 14 de mayo </p></h4>
                <div>- Trastorno Antisocial de la Personalidad: Patrones de desprecio y violación de los derechos de los demás.</div>  
                <div>- Trastorno Límite de la Personalidad (Borderline): Inestabilidad en las relaciones interpersonales, la autoimagen y los afectos, marcada por una notable impulsividad.</div> 
                <div>- Trastorno Histriónico de la Personalidad: Patrón de excesiva emotividad y búsqueda de atención.</div>
                <a href="PSICOPATOLOGÍA CLÍNICA Trastorno de la Personalidad Esquizoide Neyer, Akm007, Thelma Figueroa & Equipo Maestría en Psicología Clínica.pdf" class="btn" style="background: #cc00ffae;">📄 Ver Trastorno Límite</a>
                <a href="RTRASTORNO PARANOIDE DE LA PERSONALIDAD.pdf" class="btn" style="background: #ff00c8b2;">📄 Ver rastorno Antisocial </a>
                 <a href="Trastorno Esquizotipico de la personalidad.pdf" class="btn" style="background: #0026ffc3;">📄 Ver Trastorno Histriónico</a>
            
                    <h4>Asignaciones</h4>
                    <p>Realizar presentación según lo asignado en dicha lista que se adjunta a continuación:</p>
                    <a href="LISTADO DE TRASTORNOS - grupos - exposiciones de temas.docx.pdf" class="btn">🔍 Ver Lista de grupos conformados</a> 
                     <div><a href="#inicio">🔙</a></div>
                    </div>
    </section> <!-- SEMANA 4-->
          <section id="s4" class="card">
        <div class="card-header">
            <h3>📆 Semana 4: Trastornos de personalidad - AVATARES  </h3>
            <span class="badge">🏆 00/100</span>
        </div>
         <div class="card-body">
          <h4>Contenido</h4>
                <p> 🤖 El Rol del Avatar en la Psicología Clínica
El uso de avatares (representaciones digitales del "yo") ha dejado de ser exclusivo de los videojuegos para convertirse en una herramienta terapéutica de vanguardia. 
<div>Su impacto en la salud mental se resume en tres ejes principales: </div>

            <div>🛡️ Desinhibición y Seguridad: Actúa como un filtro emocional que reduce la ansiedad social, permitiendo que el paciente explore su identidad y comunique sentimientos con mayor apertura.
            </div>
            <div>🎭 Efecto Proteus: Los usuarios tienden a adoptar rasgos de personalidad y comportamientos de sus avatares, lo que facilita el ensayo de conductas más funcionales y seguras en la vida real.
            </div>
            <div>🔬 Intervención en Trastornos: Es fundamental en la Terapia de Exposición para fobias y en la Terapia de Avatar para el manejo de alucinaciones auditivas, permitiendo al paciente externalizar y ganar control sobre su sintomatología.
            </div></p>
            <div>
                <p><div>Pensamiento Clínico: "Al personificar un diagnóstico a través de un avatar, transformamos conceptos técnicos del DSM-5 en una experiencia visual humana, facilitando la psicoeducación y eliminando el estigma".</div></p>
            </div>    
                           
                    <h4>Asignaciones</h4>
                    <p>Crea un avatar del trastorno de personalidad de tu agrado, tomando en cuenta los expuestos por sus compañeros de clase.</p>
                    <a href="avatar_neyer.mp4" class="btn" style="background: #0026ffc3;">🦾 Ver ESQUITAR</a> 
                     <div><a href="#inicio">🔙</a></div>
                    </div>

    </section>  <!-- QUIZ -->
   <section id="encuestas" class="card" style="border-left-color: #9b59b6;">
        <div class="card-body">
            <h3>📊 Autoevaluación de Conocimientos Clínicos</h3>
            <p>Responde estas 6 preguntas basadas en las clases de la Dra. Aelen López. Cada acierto suma puntos a tu promedio final.</p>
            
            <div class="quiz-box" style="background: #fdfdfd; padding: 20px; border-radius: 10px; border: 1px solid #eee;">
                <form id="maestriaQuiz">
                    <div class="pregunta" style="margin-bottom: 20px;">
                        <p><strong>1. ¿Qué concepto define la base biológica heredada e inalterable de la personalidad?</strong></p>
                        <input type="radio" name="p1" value="0"> Carácter<br>
                        <input type="radio" name="p1" value="1"> Temperamento<br>
                        <input type="radio" name="p1" value="0"> Personalidad
                    </div>

                    <div class="pregunta" style="margin-bottom: 20px;">
                        <p><strong>2. Según los criterios de normalidad, ¿qué capacidad permite ajustar pensamientos y conductas según la situación?</strong></p>
                        <input type="radio" name="p2" value="0"> Rigidez<br>
                        <input type="radio" name="p2" value="1"> Flexibilidad<br>
                        <input type="radio" name="p2" value="0"> Autocontrol
                    </div>

                    <div class="pregunta" style="margin-bottom: 20px;">
                        <p><strong>3. ¿Qué autor del siglo XIX planteaba la existencia de un "delincuente nato" por rasgos biológicos?</strong></p>
                        <input type="radio" name="p3" value="1"> Cesare Lombroso<br>
                        <input type="radio" name="p3" value="0"> Sigmund Freud<br>
                        <input type="radio" name="p3" value="0"> Otto Kernberg
                    </div>

                    <div class="pregunta" style="margin-bottom: 20px;">
                        <p><strong>4. En el modelo de Kernberg, ¿qué nivel tiene identidad estable y usa defensas maduras (represión)?</strong></p>
                        <input type="radio" name="p4" value="0"> Organización Psicótica<br>
                        <input type="radio" name="p4" value="0"> Organización Límite<br>
                        <input type="radio" name="p4" value="1"> Organización Neurótica
                    </div>

                    <div class="pregunta" style="margin-bottom: 20px;">
                        <p><strong>5. ¿Cuál es el cambio fundamental de la CIE-11 (OMS) respecto a los trastornos de personalidad?</strong></p>
                        <input type="radio" name="p5" value="0"> Crea más categorías fijas<br>
                        <input type="radio" name="p5" value="1"> Adopta un enfoque dimensional y de gravedad<br>
                        <input type="radio" name="p5" value="0"> Elimina el diagnóstico médico
                    </div>

                    <div class="pregunta" style="margin-bottom: 20px;">
                        <p><strong>6. ¿Qué dominio de la CIE-11 se caracteriza por el perfeccionismo extremo y el control rígido?</strong></p>
                        <input type="radio" name="p6" value="1"> Anankastia<br>
                        <input type="radio" name="p6" value="0"> Desinhibición<br>
                        <input type="radio" name="p6" value="0"> Desapego
                    </div>

                    <button type="button" class="btn" style="background: var(--purple);" onclick="validarQuiz()">Finalizar y Ver Promedio</button>
                </form>
                
                <div id="feedbackArea" style="margin-top: 20px; display: none; padding: 15px; border-radius: 8px;">
                    <h4 id="scoreTitle"></h4>
                    <p id="detailsArea"></p>
                </div>
            </div>
             <div><a href="#inicio">🔙</a></div>
        </div>
    </section>

    <script>
    function validarQuiz() {
        const respuestas = {
            p1: { correcta: "1", msg: "Correcto: El temperamento es innato. El carácter es aprendido." },
            p2: { correcta: "1", msg: "Correcto: La flexibilidad es clave para la salud mental." },
            p3: { correcta: "1", msg: "Correcto: Lombroso fue pionero en la criminología biológica." },
            p4: { correcta: "1", msg: "Correcto: El nivel neurótico es el más funcional en el modelo de Kernberg." },
            p5: { correcta: "1", msg: "Correcto: La CIE-11 prioriza la gravedad sobre las etiquetas." },
            p6: { correcta: "1", msg: "Correcto: La anankastia implica una necesidad patológica de orden." }
        };

        let puntos = 0;
        let totalPreguntas = 6;
        let explicaciones = "";

        for (let i = 1; i <= totalPreguntas; i++) {
            const radio = document.querySelector(`input[name="p${i}"]:checked`);
            if (radio) {
                if (radio.value === "1") {
                    puntos++;
                    explicaciones += `<p style="color: green;">✅ Pregunta ${i}: ${respuestas['p'+i].msg}</p>`;
                } else {
                    explicaciones += `<p style="color: red;">❌ Pregunta ${i}: Incorrecto. Revisa el material de la Dra. Aelen sobre este punto.</p>`;
                }
            } else {
                explicaciones += `<p style="color: gray;">⚠️ Pregunta ${i}: No respondida.</p>`;
            }
        }

        const promedio = Math.round((puntos / totalPreguntas) * 100);
        const feedback = document.getElementById("feedbackArea");
        feedback.style.display = "block";
        feedback.style.background = promedio >= 70 ? "#e8f5e9" : "#ffebee";
        
        document.getElementById("scoreTitle").innerText = `Tu Promedio: ${promedio}/100 (${puntos} aciertos)`;
        document.getElementById("detailsArea").innerHTML = explicaciones;
        
        window.location.hash = "encuestas"; // Desplaza la pantalla al resultado
    }
    </script>

    <!-- GLOSARIO -->
    <section id="glosario" class="card">
        <div class="card-body">
            <h3>📖 Glosario Técnico</h3>
            <table>
                <tr>
                    <th>Término</th>
                    <th>Definición Clínica</th>
                </tr>
                <tr>
                    <td><strong>Personalidad</strong></td>
                    <td>Organización dinámica de los sistemas psicofísicos.</td>
                </tr>
                <tr>
                    <td><strong>Rasgo</strong></td>
                    <td>Característica estable que permite predecir la conducta.</td>
                </tr>
                <tr>
                    <td><strong>Locus de Control</strong></td>
                    <td>Grado en que las personas creen que tienen control sobre los eventos.</td>
                </tr>
            </table>
             <div><a href="#inicio">🔙</a></div>
        </div>
    </section>

    <!-- ANEXOS -->
    <section id="anexos" class="card">
        <div class="card-body">
            <h3>📎 Anexos y Recursos</h3>
            <p>Material de apoyo utilizado durante las sesiones de clase.</p>
            <div class="grid">
                <a href="CLINICA__-_PROGRAMAS_DE_TRASTORNOS_DE_LA_PERSONALIDAD.pdf" class="btn">📂 Programa de la Materia</a>
                <a href="CRONOGRAMA_DE_LA_ASIGNATURA.pdf" class="btn">🗓️ Cronograma</a>
                <a href="HORARIO_-_PSICOLOGIA_CLINICA-_ABRIL_Y_MAYO_2026_1.pdf" class="btn"> 🕰️ Horarios </a>
                <a href="DSM_5-TR_EN_ESPAN771OL.pdf" class="btn">📘 DSM-5 </a>
                <a href="Autoevaluacion.doc" class="btn">🤝 Autoevaluación </a>
            </div>
             <div><a href="#inicio">🔙</a></div>
        </div>
    </section>

    <!-- CONTACTO, DUDAS Y TIPS -->
    <section id="contacto" class="card" style="border-left-color: #e67e22; background: #fffcf5;">
        <div class="card-body">
            <h3>💡 Dudas, Tips y Pensamientos</h3>
            <p>¿Tienes dudas sobre los entregables o quieres compartir un tip de estudio?</p>
            <a href="mailto:tu-correo@maestria.com" class="btn btn-orange">📧 Enviar Correo a Neyersson</a>
            
            <div style="margin-top: 20px; padding: 15px; background: white; border-radius: 8px; border: 1px dashed #e67e22;">
                <h4>📌 Tip Clínico</h4>
                <p>Al analizar un trastorno, siempre diferencia lo que es propio del <strong>temperamento</strong> (biología) de lo que ha sido moldeado por el <strong>ambiente</strong> (carácter).</p>
            </div>
             <div><a href="#inicio">🔙</a></div>
        </div>
    </section>

</div>

<footer>
    <p>Mgt. Neyersson Cisneros &copy; 2026 | Maestría en Psicología Clínica</p>
    <p>Trastornos de la Personalidad - Dra. Aelen López</p>
     <div><a href="#inicio">🔙</a></div>
</footer>

<script>
    function checkQuiz() {
        let score = 0;
        const r1 = document.querySelector('input[name="q1"]:checked');
        const r2 = document.querySelector('input[name="q2"]:checked');
        
        if(r1 && r1.value == "1") score++;
        if(r2 && r2.value == "1") score++;
        
        const resultTxt = document.getElementById("quizResult");
        resultTxt.innerText = "Resultado: " + score + " / 2 correctas. ¡Sigue estudiando!";
        resultTxt.style.color = score === 2 ? "var(--success)" : "var(--warning)";
    }
</script>

</body>
</html>
