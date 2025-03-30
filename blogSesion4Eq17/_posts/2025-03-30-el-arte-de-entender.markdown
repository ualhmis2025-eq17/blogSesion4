---
layout: post
title:  "El arte de entender en la era de la infoxicación"
date:   2025-03-30 9:23:29 +0100
categories: jekyll update
---

# Autor: [Ismael]({{site.baseurl}}/members/Ismael)

# El arte de entender en la era de la infoxicación.

# 🧠 La importancia de entender  

Son muchas las razones por las que merece la pena esmerarse en intentar entender las cosas 🤔💡. Tenemos razones puramente intelectuales 📚, más asociadas a la filosofía que a cuestiones prácticas 🏛️.  

Como podría decir Platón, las ideas son perfectas ✨ y por sí solas su mera existencia justifica todo intelecto que intente entenderlas 🧠. Sin embargo, es muy evidente que el mundo en el que vivimos es claramente aristotélico 🌍, antítesis de las ideas platónicas.  

<img src="{{ site.baseurl }}/images/aristotPlat.jpg" alt="Aristóteles VS Platón" style="display: block; margin-left: auto; margin-right: auto;">

Como tal, toda afirmación, todo saber, todo en general debe tener un propósito y una razón de ser para que merezca la pena 🎯, razones prácticas, que sirvan en la vida real ⚙️.  

---

# 🤖 Inteligencia artificial y el problema de la inmediatez  

En la era de la inteligencia artificial 🤖, no solo los informáticos han derivado en un estado de pereza más absoluto que antes 😴, sino que en general, todos los estudiantes 🎓 e incluso profesionales de campos intelectuales (no físicos) se han intoxicado de la información instantánea 📲 y están dejando de lado la bendición del entendimiento 🧩.  

Muchos jóvenes de diversas ingenierías de la UAL utilizan inteligencias ya comerciales y mainstream como ChatGPT no como una fuente útil, sino como autoridad 🔗.  

<img src="{{ site.baseurl }}/images/ChatGPT.png" alt="Estupidez Natural" style="display: block; margin-left: auto; margin-right: auto;">

---

# 🎥 Un referente en la divulgación matemática  

Una de las personas por las que más admiración tengo es el Traductor de Ingeniería 🎥, un ingeniero argentino 🇦🇷 que sube vídeos divulgatorios principalmente de Matemáticas ➕➗, aunque también tiene vídeos de física 🔬 e ingeniería en general.  

  <div style="position: relative; text-align: center; z-index: -1;">
    <img src="{{ site.baseurl }}/images/elTraductor.jpg" alt="El Traductor de Ingeniería" width="100px">
    <p>El Traductor de Ingeniería</p>
  </div>

Su canal gira en torno a un concepto clave: entender 🤯. Cuando estaba en Bachillerato lo seguía y apliqué esta filosofía, lo que me hizo enamorarme de las Matemáticas ❤️📐 como nunca antes.  

Cuando las matemáticas eran reglas incuestionables 🚫, las aborrecía 😖. Cuando empecé a entenderlas, pude ver su belleza 🎨.  

---

# 👨‍💻 El dilema del informático: ¿para qué entender?  

Podría incluso parecer que nosotros no estamos necesariamente dentro del barco 🚢 de "entender las cosas". Al fin y al cabo, somos informáticos 👨‍💻👩‍💻, ¿no? ¿Para qué necesito entender cómo funciona mi Sistema Operativo 🖥️ si solo tengo que "programar" 💻?  

Quizás tú no pienses eso, pero muchas personas sí 🤷. Esto se debe a que la informática ha sido democratizada en internet 🌐 y ha sufrido una disrupción artificial de la ingeniería y el método ingenieril 🛠️.  

No es algo malo, ya que ha permitido a muchas personas entrar en el sector sin la necesidad de ir a la Universidad 🏫, lo cual es perfectamente viable ✅, pero las aísla del pensamiento crítico y analítico 🧐 que debería tener un ingeniero.  

---

# 🐧 Problemas técnicos en Linux y el pensamiento crítico  

Y no estoy hablando de supuestos 🚨. Tengo un ejemplo reciente que me pasó a mí mismo 📖.  

Estaba intentando trabajar con Tesseract 👀, un motor de reconocimiento de caracteres ópticos desarrollado por Google en Python 🐍. Para este fin, existe el Wrapper pytesseract 🔄.  

Como utilizo **Linux 🐧**, mi IDE, Visual Studio Code, está instalado como un **Flatpak 📦**. Puede que no tenga mucha relevancia ahora mismo, pero la tiene.  

Flatpak intenta aislar las aplicaciones entre sí y entre el sistema 🔒, algo similar a lo que ocurre en Android 📱 (basado en **Linux 🐧**, recordemos que **Linux 🐧** es solo el kernel).  

Como tal, la ventaja de Flatpak es similar a los entornos virtuales de Python 🛑🐍: evita los conflictos entre librerías 📚 y los infiernos de dependencias 🔥 al estar todo incluido. Pero también comparte sus desventajas: es más pesado ⚖️ y dificulta la comunicación entre módulos que necesitan compartir archivos 🗂️.  

Este era el caso de mi ejemplo, ya que pytesseract necesita la localización del binario Tesseract ⚙️, que en mi caso estaba en una carpeta de mi Sistema Operativo 📂.  

Como **Visual Studio Code estaba instalado como Flatpak**, todas las instancias de bash generadas estaban "virtualizadas" 🧳 y tenían acceso restringido al sistema 🚫.  

Intenté ejecutar código Python con pytesseract y siempre lanzaba el mismo error ⚠️ en tiempo de ejecución ⏳: no podía encontrar el binario 🔍, aunque revisé muchas veces que el binario estaba incluido en el `$PATH` del bash que ejecutaba Visual Studio Code 🚀.  

Finalmente, cuando probé en una terminal real, el intérprete de Python funcionaba sin problemas 🎉. Ahí fue cuando me di cuenta de que el problema era culpa de Flatpak 📦, y después de tanto tiempo perdido ⌛, decidí trabajar directamente en una terminal real 💻.  

---

# 🔎 La importancia de preguntarse "¿Por qué?"  

Mi proceso de resolución del problema hubiera sido mejor si me hubiera preguntado: **"¿Por qué?"** ❓  

Aquí es donde entra el arte del saber 🎭. Si me lo pregunté, pero no indagué lo suficiente 🔍.  

Como siempre, probé primero las causas más sencillas y probables 🎯, pero lejos de seguir preguntándome, simplemente fui divagando sin rumbo 🏞️ hasta que encontré la solución 💡.  

Si hubiera dado rienda suelta a mi inquietud y ansias de saber por qué 🤯, el problema se habría resuelto más fácilmente.  

En vez de moverme por instinto y por interminables búsquedas de Google 🌍 y chats con ChatGPT 🤖, debería haber priorizado el razonamiento estructurado.  

---

# ✅ Conclusión: herramientas útiles, pero no lo son todo  

Estas últimas herramientas son útiles, sí ✅, pero **no lo son todo** 🚫.  

Nos pueden dar información útil 📖, pero lo más importante es **entender en cada momento lo que uno está haciendo** 🔄.  

En este caso, estaba, en cierta manera, **infoxicado con un problema trivial** 🌀.  
