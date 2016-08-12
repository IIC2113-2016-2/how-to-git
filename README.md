
# how-to-git

[Git] es un sistema distribuido de control de versiones,
utilizado principalmente para el desarrollo de software.  
Actualmente, Git es usado por grandes organizaciones,
tanto en proyectos de [código abierto](https://github.com/explore)
como en [softwares comerciales](https://enterprise.github.com/home).

## ¿Para qué?

Existen diversas razones para usar Git.
Por ejemplo, esta herramienta permite,
- llevar un registro de múltiples versiones de un archivo,
- colaborar con otros desarolladores en un mismo proyecto,
- ver cuánto ha trabajado cada uno: quién, dónde y cuándo,
- experimentar con alguna nueva funcionalidad,
- revisar el historial de cierto código,
- seguir _bugs_, analizando qué fue lo que rompió tu código.

Es altamente probable que ya estés familiarizado con los comandos básicos:
_clone_, _status_, _add_, _commit_, _push_, _pull_.  
Sin embargo, Git nos ofrece **mucho** más que eso.

## ¿Dónde partir?

No vale la pena reinventar la rueda en este tema.
Hay decenas de tutoriales de Git dando vuelta en las _interwebs_.  
Pero mira, en la siguiente lista, hemos recopilado los tres _mejores*_,
ordenados de menor a mayor profundidad.

- [**Try Git**](https://try.github.io)  
  El _clásico_ tutorial interactivo de Git creado por Code School.  
  No debería tomar más de una hora, siendo un buen punto de inicio.

- [**Ry's Git Tutorial**](http://rypress.com/tutorials/git/index)  
  Un excelente tutorial escrito desde un punto de vista práctico.  
  Además, las explicaciones están acompañadas de ilustrativos diagramas.

- [**Pro Git**](https://git-scm.com/book/en/v2)  
  Espera, ¿quieres saber todavía más? :grinning:  
  Aquí tienes el libro _oficial_ para aprender _todo_ acerca de Git:
  desde lo más básico hasta las técnicas más avanzadas.

Y finalmente, una mención honrosa para...

- [**Explain Git with D3**](http://onlywei.github.io/explain-git-with-d3)  
  Un brillante trabajo que explica visualmente qué ocurre al ejecutar
  algunos comandos de Git. Me saco el sombrero. :tophat:

## Buenas prácticas

Mantener cierta consistencia en un equipo de muchas personas,
aunque inicialmente pueda parecer una pérdida de tiempo,
será de enorme ayuda en el mediano-largo plazo.  
A continuación, entregamos algunos consejos de utilidad.

- **Escribir buenos mensajes**  
  Pero... ¿qué es un buen mensaje?
  Esta pequeña [guía] intenta ofrecer una respuesta.&lt;/advertising&gt;

- **Realizar _commits_ atómicos**  
  La idea es hacer un _cambio lógico_ por cada _commit_.
  Elaborar _commits_ pequeños permite entenderlos fácilmente,
  pudiendo, por ejemplo, revertirlos en caso de que sea necesario.

- **No hacer _commits_ a medio camino**  
  Por el punto anterior, aunque hayas terminado tu jornada laboral,
  hacer un _commit_ al final del día no es una buena idea.
  Asimismo, si debes cambiar de _branch_ (e.g. para hacer un _hotfix_),
  no caigas en la tentación de hacer un _commit_ apurado.
  En ese caso, `git stash` es un buen aliado.

- **Ponerse de acuerdo en un _workflow_**  
  Existe una gran variedad de _[workflows]_ en Git.
  Sin embargo, elegir el _flujo_ adecuado depende del tamaño del proyecto,
  de las preferencias del equipo, de las metodologías de _deployment_,
  entre otros criterios.  
  Finalmente, lo importante es llegar a un consenso
  para que todo el equipo esté en la misma sintonía.

## gitflow

[_gitflow_](http://nvie.com/posts/a-successful-git-branching-model)
es una metodología de _branching_ para Git diseñada por Vincent Driessen.

_To be continued..._

## Referencias

[_Git Best Practices_](
https://www.git-tower.com/learn/git/ebook/command-line/appendix/best-practices)
— Git Tower

---

\*_mejores_, según criterios que no serán revelados en esta guía.

[/]:# (Referencias implícitas)

[git]:       https://en.wikipedia.org/wiki/Git_(software)
[guía]:      https://gist.github.com/nkawasg/f96a2f0bfe1e059d589d6a2190a2ac81
[workflows]: https://www.atlassian.com/git/tutorials/comparing-workflows
