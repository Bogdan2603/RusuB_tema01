# RusuB_tema01

OpenGL este un API utilizat pentru randarea graficii 2D și 3D, fiind folosit pe scară largă în aplicații interactive precum jocurile video și simulările. Este open-source, cross-platform și poate fi folosit cu diverse limbaje de programare (C, C++,C#, Python, etc.). De asemenea, are versiuni derivate precum OpenGL ES (pentru dispozitive mobile) și WebGL (pentru browser). Vulkan este o alternativă modernă, optimizată pentru performanță.

Puncte Tari

1. Cross-Platform: OpenGL funcționează pe diverse sisteme de operare și dispozitive, oferind flexibilitate dezvoltatorilor.

2. Open Source: Fiind open-source, OpenGL permite comunității să contribuie la dezvoltarea sa.

3. Suport pentru mai multe limbaje: API-ul poate fi utilizat cu mai multe limbaje de programare, extinzând accesibilitatea.

4. Implementări derivate: OpenGL ES și WebGL oferă funcționalități similare pe platforme mai mici, precum telefoanele mobile și browserele.

5. Shadere programabile: După versiunea 3.1, OpenGL permite personalizarea etapelor de randare grafică prin shadere.

Puncte Slabe

1. Curba de învățare abruptă: OpenGL este dificil de învățat, mai ales pentru începători.

2. Performanță: OpenGL poate fi mai lent decât alte API-uri moderne, precum Vulkan sau DirectX 12.

3. Compatibilitatea cu Apple: OpenGL nu este pe deplin compatibil cu platformele Apple, care favorizează Metal.

4. Pipeline-ul grafic: Pipeline-ul fix anterior versiunii 3.1 este mai limitat comparativ cu cel programabil.

Modelul de Automat cu Stări Finite

OpenGL poate fi văzut ca un automat cu stări finite, în care fiecare acțiune grafică modifică starea curentă a sistemului. Schimbările de stare afectează modul în care scenele sunt randate, iar fiecare pas al pipeline-ului grafic modifică rezultatul final. Acest model oferă control asupra randării, dar poate complica dezvoltarea aplicațiilor grafice dacă stările nu sunt gestionate corect.
