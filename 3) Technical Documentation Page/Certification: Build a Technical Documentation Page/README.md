1.Como usuario, quiero poder ver un elemento principal con un id correspondiente a "main-doc", que contenga el contenido principal de la página (documentación técnica).

2.Dentro del elemento #main-doc, como usuario, quiero poder ver varios elementos section con una clase de main-section. Deben haber al menos cinco.

3.Como usuario, quiero que el primer elemento dentro de cada .main-section sea un elemento header, que contenga texto que describa el tema de esa sección.Deben haber al menos cinco.

4.Cada elemento section con la clase main-section también debe tener un id que corresponda al texto de cada header contenido en él. Cualquier espacio debe ser reemplazado por guiones bajos (por ejemplo, la sección que contiene el encabezado "JavaScript y Java" debe tener un id correspondiente a "JavaScript_and_Java").

5. Los elementos .main-section deben contener al menos diez elementos p en total (no cada uno).

6.Los elementos .main-section deben contener al menos cinco elementos code en total (no cada uno).

7.Los elementos .main-section deben contener al menos cinco elementos li en total (no cada uno).

8.Como usuario, quiero poder ver un elemento nav con un id correspondiente a "navbar".

9.El elemento navbar debe contener un elemento header que contenga texto que describa el tema de la documentación técnica.

10.Además, el navbar debe contener elementos link (a) con la clase de nav-link. Debe haber uno por cada elemento con la clase main-section.

11.El elemento header en #navbar debe estar antes que cualquier elemento link (a) en el navbar.

12.Cada elemento con la clase nav-link debe contener texto que corresponda al texto del encabezado dentro de cada sección (por ejemplo, si tiene una sección/encabezado "Hola Mundo", su navbar debe tener un elemento que contenga el texto "Hola Mundo").

13.Cuando haga clic en un elemento del navbar, la página debe navegar a la sección correspondiente del elemento #main-doc (por ejemplo, si hace clic en un elemento .nav-link que contiene el texto "Hola Mundo", la página navegará a un elemento section con ese id y contiene el encabezado correspondiente).

14.En dispositivos de tamaño regular (laptops, computadoras de escritorio), el elemento con id = "navbar" debe mostrarse en el lado izquierdo de la pantalla y siempre debe ser visible para el usuario.

15.La documentación técnica debe usar al menos una media query.



1.You can see a main element with a corresponding id="main-doc", which contains the page's main content (technical documentation)

2.Within the #main-doc element, you can see several section elements, each with a class of main-section. There should be a minimum of five

3.The first element within each .main-section should be a header element, which contains text that describes the topic of that section.

4.Each section element with the class of main-section should also have an id that corresponds with the text of each header contained within it. Any spaces should be replaced with underscores (e.g. The section that contains the header "JavaScript and Java" should have a corresponding id="JavaScript_and_Java")

5.The .main-section elements should contain at least ten p elements total (not each)

6.The .main-section elements should contain at least five code elements total (not each)

7.The .main-section elements should contain at least five li items total (not each)

8.You can see a nav element with a corresponding id="navbar"

9.The navbar element should contain one header element which contains text that describes the topic of the technical documentation

10.Additionally, the navbar should contain link (a) elements with the class of nav-link. There should be one for every element with the class main-section

11.The header element in the #navbar must come before any link (a) elements in the navbar

12.Each element with the class of nav-link should contain text that corresponds to the header text within each section (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world")

13.When you click on a navbar element, the page should navigate to the corresponding section of the #main-doc element (e.g. If you click on a .nav-link element that contains the text "Hello world", the page navigates to a section element with that id, and contains the corresponding header)

14.On regular sized devices (laptops, desktops), the element with id="navbar" should be shown on the left side of the screen and should always be visible to the user

15.Your technical documentation should use at least one media query

Fulfill the user stories and pass all the tests below to complete this project. Give it your own personal style. Happy Coding!

