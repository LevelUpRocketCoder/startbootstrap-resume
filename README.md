
<!DOCTYPE html>
<html lang="en">
    <head>
        {% load static %}
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
        <meta name="description" content="" />
        <meta name="author" content="" />
        <title>Resume - Start Bootstrap Theme</title>
        <link rel="icon" type="image/x-icon" href="assets/img/favicon.ico" />
        <!-- Font Awesome icons (free version)-->
        <script src="https://use.fontawesome.com/releases/v6.3.0/js/all.js" crossorigin="anonymous"></script>
        <!-- Google fonts-->
        <link href="https://fonts.googleapis.com/css?family=Saira+Extra+Condensed:500,700" rel="stylesheet" type="text/css" />
        <link href="https://fonts.googleapis.com/css?family=Muli:400,400i,800,800i" rel="stylesheet" type="text/css" />
        <!-- Core theme CSS (includes Bootstrap)-->
        <link href="{% static 'css/styles.css' %}" rel="stylesheet" />
    </head>

    <body id="page-top">
        <!-- Navigation-->
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top" id="sideNav">
            <a class="navbar-brand js-scroll-trigger" href="#page-top">
                <span class="d-block d-lg-none">JULIO SILVAr</span>
                <span class="d-none d-lg-block"><img class="img-fluid img-profile rounded-circle mx-big mb-2" src="{% static 'assets/img/foto.jpg'%}" alt="..." /></span>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>
            <div class="collapse navbar-collapse" id="navbarResponsive">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#experience">Experience</a></li>
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#education">Education</a></li>
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#skills">Skills</a></li>
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#interests">Interests</a></li>
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#awards">Awards</a></li>
                </ul>
            </div>
        </nav>
        <!-- Page Content-->
        <div class="container-fluid p-0">
            <!-- About-->
            <section class="resume-section" id="about">
                <div class="resume-section-content">
                    <h1 class="mb-0">
                      <html>
<head>
    <title>Perfiles Profesionales</title>
</head>
<body>
    <h1>Perfiles Profesionales</h1>
    {% if object_list %}
        <ul>
            {% for perfil in object_list %}
            <li>
                <p>No hay perfiles profesionales registrados.</p>
                <strong>Nombres:</strong> {{ perfil.nombres }} <br>
                <strong>Apellidos:</strong> {{ perfil.apellidos }} <br>
                <strong>Email:</strong> {{ perfil.email }} <br>
                <strong>Carrera:</strong> {{ perfil.carrera }} <br>
                <strong>Celular:</strong> {{ perfil.celular }} <br>
            </li>
            {% endfor %}
        </ul>
    {% else %}
    <strong>Nombres:</strong> {{ perfil.nombres }} <br>
    <strong>Apellidos:</strong> {{ perfil.apellidos }} <br>
    <strong>Email:</strong> {{ perfil.email }} <br>
    <strong>Carrera:</strong> {{ perfil.carrera }} <br>
    <strong>Celular:</strong> {{ perfil.celular }} <br>
    {% endif %}
</body>
</html>  
                        <span class="text-primary">Julio Cesar Silva Fuertes</span>
                    </h1>
                    <div class="subheading mb-5">
                        126 Alto Pampahasi · La Paz, CO 0000 · (+591) 63187353 ·
                        <a href="mailto:name@email.com">juliosilva18888@gmail.com</a>
                    </div>
                    <p class="lead mb-5">I am experienced in leveraging agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition.</p>
                    <div class="social-icons">
                        <a class="social-icon" href="#!"><i class="fab fa-linkedin-in"></i></a>
                        <a class="social-icon" href="https://github.com/StartBootstrap/startbootstrap-resume/compare/master...LevelUpRocketCoder:startbootstrap-resume:master"><i class="fab fa-github"></i></a>
                        <a class="social-icon" href="https://x.com/Dax1083385?t=7UQExSSMClTe1VBnpIoi6w&s=09"><i class="fab fa-twitter"></i></a>
                        <a class="social-icon" href="https://www.facebook.com/profile.php?id=100093090667452"><i class="fab fa-facebook-f"></i></a>
                    </div>
                </div>
            </section>
            <hr class="m-0" />
            <!-- Experience-->
            <section class="resume-section" id="experience">
                <div class="resume-section-content">
                    <h2 class="mb-5">Experiencia</h2>
                    <div class="d-flex flex-column flex-md-row justify-content-between mb-5">
                        <div class="flex-grow-1">
                            <h3 class="mb-0">Auxiliar Web Developer</h3>
                            <div class="subheading mb-3">Web Solutions</div>
                            <p>Mi búsqueda de la excelencia se refleja en mi deseo constante de aprender y desarrollarme. He aprovechado cada oportunidad para familiarizarme con nuevas tecnologías y herramientas para mantenerme al día con las últimas tendencias en desarrollo web. Mi experiencia con soluciones web no sólo fortaleció mis habilidades técnicas, sino que también me permitió crecer profesionalmente y desarrollar una pasión más profunda por crear soluciones web innovadoras y de alta calidad.</p>
                        </div>
                        <div class="flex-shrink-0"><span class="text-primary">Septiembre 2020 - Presente</span></div>
                    </div>
                    <div class="d-flex flex-column flex-md-row justify-content-between mb-5">
                        <div class="flex-grow-1">
                            <h3 class="mb-0">Diseñador Grafico</h3>
                            <div class="subheading mb-3">Mejo aplicacion de Diseño</div>
                            <p>Mi compromiso con la excelencia se refleja en mi atención meticulosa a los detalles y mi capacidad para cumplir con los plazos de entrega ajustados. He demostrado habilidades sólidas en la gestión del tiempo y la organización, lo que me ha permitido manejar múltiples proyectos simultáneamente sin comprometer la calidad del trabajo.</p>
                        </div>
                        <div class="flex-shrink-0"><span class="text-primary">December 2019 - Marzo 2021</span></div>
                    </div>
                    <div class="d-flex flex-column flex-md-row justify-content-between mb-5">
                        <div class="flex-grow-1">
                            <h3 class="mb-0">Capacitacion de Microsoft Office</h3>
                            <div class="subheading mb-3">Manejo de programas Office</div>
                            <p>Mi compromiso con la excelencia se refleja en mi atención personalizada a las necesidades individuales de mis usuarios y mi capacidad para adaptar la capacitación a los niveles y objetivos específicos de cada grupo. Recibí comentarios positivos de los participantes sobre mi paciencia, claridad y capacidad para hacer que el aprendizaje fuera accesible y relevante.</p>
                        </div>
                        <div class="flex-shrink-0"><span class="text-primary">Enero 2023 - Febrero 2023</span></div>
                    </div>
                    <div class="d-flex flex-column flex-md-row justify-content-between">
                        <div class="flex-grow-1">
                            <h3 class="mb-0">Web Design Intern</h3>
                            <div class="subheading mb-3">Shout! Media Productions</div>
                            <p>Durante mi pasantía participé en resolución de problemas y recuperación de código, superando desafíos técnicos con perseverancia y creatividad. El trabajo en equipo me ha enseñado la importancia de la comunicación y colaboración efectivas para lograr objetivos comunes y entregar proyectos de alta calidad a tiempo.</p>
                        </div>
                        <div class="flex-shrink-0"><span class="text-primary">Marzo 2024 - Agosto 2024</span></div>
                    </div>
                </div>
            </section>
            <hr class="m-0" />
            <!-- Education-->
            <section class="resume-section" id="education">
                <div class="resume-section-content">
                    <h2 class="mb-5">Education</h2>
                    <div class="d-flex flex-column flex-md-row justify-content-between mb-5">
                        <div class="flex-grow-1">
                            <h3 class="mb-0">Universidad Salesiana de Bolivia</h3>
                            <div class="subheading mb-3">Lic. INGENERIA EN SISTEMAS</div>
                            <div>Programacion  - Aplicaciones y paginas web Track</div>
                            <p>GPA: 78</p>
                        </div>
                        <div class="flex-shrink-0"><span class="text-primary">Febrero 2022 - Diciembre 2025</span></div>
                    </div>
                    <div class="d-flex flex-column flex-md-row justify-content-between">
                        <div class="flex-grow-1">
                            <h3 class="mb-0">UNIDAD EDUCATIVA ELISA DE BALLIVIAN</h3>
                            <div class="subheading mb-3">Humastica y Psicologia </div>
                            <p>Promedio: 70 </p>
                        </div>
                        <div class="flex-shrink-0"><span class="text-primary">Febrero 2007 - Diciembre 2019</span></div>
                    </div>
                </div>
            </section>
            <hr class="m-0" />
            <!-- Skills-->
            <section class="resume-section" id="skills">
                <div class="resume-section-content">
                    <h2 class="mb-5">Skills</h2>
                    <div class="subheading mb-3">Programming Languages & Tools</div>
                    <ul class="list-inline dev-icons">
                        <li class="list-inline-item"><i class="fab fa-python"></i></li>
                        <li class="list-inline-item"><i class="fab fa-java"></i></li>
                    </ul>
                    <div class="subheading mb-3">Workflow</div>
                    <ul class="fa-ul mb-0">
                        <li>
                            <span class="fa-li"><i class="fas fa-check"></i></span>
                            Mobile-First, Responsive Design
                        </li>
                        <li>
                            <span class="fa-li"><i class="fas fa-check"></i></span>
                            Cross Browser Testing & Debugging
                        </li>
                        <li>
                            <span class="fa-li"><i class="fas fa-check"></i></span>
                            Cross Functional Teams
                        </li>
                        <li>
                            <span class="fa-li"><i class="fas fa-check"></i></span>
                            Agile Development & Scrum
                        </li>
                    </ul>
                </div>
            </section>
            <hr class="m-0" />
            <!-- Interests-->
            <section class="resume-section" id="interests">
                <div class="resume-section-content">
                    <h2 class="mb-5">Interests</h2>
                    <p>Fuera del mundo tecnológico, tengo muchos otros intereses que me inspiran y enriquecen mi creatividad. Algunos de ellos son:.</p>
                    <p class="mb-0"> - Arte y Diseño: Disfruto explorando diversas formas de expresión artística, desde pintura hasta ilustración digital.</p>
                    <p class="mb-1"> - Música: La música es una gran fuente de inspiración para mí. Disfruto tocar la guitarra y experimentar con la producción musical en mi tiempo libre.</p>
                    <p class="mb-1"> - Literatura: Soy lector y disfruto de una variedad de géneros literarios, desde ciencia ficción hasta poesía. Me encanta perderme en historias y descubrir nuevas ideas a través de la escritura.</p>
                </div>
            </section>
            <hr class="m-0" />
            <!-- Awards-->
            <section class="resume-section" id="awards">
                <div class="resume-section-content">
                    <h2 class="mb-5">Awards & Certifications</h2>
                    <ul class="fa-ul mb-0">
                        <li>
                            <span class="fa-li"><i class="fas fa-trophy text-warning"></i></span>
                            Certificacion en Microsoft
                        </li>
                        <li>
                            <span class="fa-li"><i class="fas fa-trophy text-warning"></i></span>
                            Pasantia en Gustosi de un año
                        </li>
                        <li>
                        </li>
                        <li>
                        </li>
                        <li>
                        </li>
                        <li>
                        <li>
                        </li>
                    </ul>
                </div>
            </section>
        </div>
        <!-- Bootstrap core JS-->
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>
        <!-- Core theme JS-->
        <script src="{% static 'js/scripts.js' %}"></script>
    </body>
</html>
