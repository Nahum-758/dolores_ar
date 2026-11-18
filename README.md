# dolores_ar

# Ángel Nahúm
El ciclo TDD de siempre
🔴 ROJO: escribe la prueba (debe FALLAR)
Escribes la prueba; falla.
🟢 VERDE: el código mínimo para pasar
Código mínimo para que pase.
🔵 REFACTOR: ordena sin romper nada

Ronda 1 · ¿A qué distancia está? (Haversine)
🔴 ROJO: escribe la prueba (debe FALLAR)
<img width="824" height="340" alt="image" src="https://github.com/user-attachments/assets/2f527630-7761-4b32-879c-00bba68de6c5" />
<img width="824" height="172" alt="image" src="https://github.com/user-attachments/assets/f2210242-1997-4e9b-9f2c-fd6ef9d92aec" />

Ciclo 1.2 · 🟢VERDE
<img width="444" height="104" alt="image" src="https://github.com/user-attachments/assets/408c6743-382a-4a5e-afcc-c7779ae28a59" />

🔵 REFACTOR: ordena sin romper nada
Ejecuta flutter test: las 4 pruebas de distancia pasan. Observa que Coordenada y las matemáticas viven en dominio/ y no importan NADA de Flutter.
🏆 RETO PARA TI
Agrega una prueba: la distancia entre la Parroquia y la Plaza Principal del catálogo (después de la Ronda 3) debe estar entre 30 y 120 m. ¿Tiene sentido para ti caminando? Sí, ya que de manera geográfica de Dolores Hidalgo, la Parroquia de Nuestra Señora de los Dolores se encuentra justo frente al Jardín Principal
<img width="444" height="90" alt="image" src="https://github.com/user-attachments/assets/2ef1cecf-9565-4fb6-9d4a-72d450ef7eff" />

Ronda 2 · ¿Hacia dónde queda? Rumbo y ángulos
Ciclo 2.1 · 🔴 ROJO
<img width="601" height="220" alt="image" src="https://github.com/user-attachments/assets/3c52dec0-ea48-4db8-8d21-acaf2bde92d4" />
<img width="601" height="126" alt="image" src="https://github.com/user-attachments/assets/b178b2a2-334e-451a-adad-1af937ed0066" />

Ciclo 2.2 · 🟢 VERDE
 <img width="598" height="123" alt="image" src="https://github.com/user-attachments/assets/886087f0-3b8a-4739-abd1-1a59520d391a" />

🔵 REFACTOR: ordena sin romper nada
Ejecuta flutter test. Las pruebas de cruce por el norte son las que justifican todo este capítulo: si alguna vez alguien "simplifica" suavizarAngulo y reintroduce el error, la prueba lo atrapa.
🏆 RETO PARA TI
Agrega una prueba que verifique que suavizarAngulo nunca devuelve un valor fuera de 0-360, probando con ángulos negativos y mayores que 360.
 <img width="598" height="123" alt="image" src="https://github.com/user-attachments/assets/072ba24a-18a0-4d16-981a-0236c8f4480d" />

Ronda 3 · De ángulo a pantalla: el campo de visión
Ciclo 3.1 · 🔴 ROJO
 <img width="567" height="235" alt="image" src="https://github.com/user-attachments/assets/ee4d05ec-ab42-40dc-b40e-76f728c1d485" />
 <img width="569" height="118" alt="image" src="https://github.com/user-attachments/assets/7b98f1dc-26f9-4f1f-ad93-b10a1636a685" />


Ciclo 3.2 · 🟢 VERDE
 <img width="606" height="114" alt="image" src="https://github.com/user-attachments/assets/a4f2977f-feba-4768-bdb1-cc19f1c34d65" />


Ronda 4 · El motor de realidad aumentada
Ciclo 4.1 · 🔴 ROJO
 <img width="825" height="274" alt="image" src="https://github.com/user-attachments/assets/3748ebf3-b6a5-4f7a-ba49-0513ffffde89" />
<img width="825" height="178" alt="image" src="https://github.com/user-attachments/assets/cce41992-4e49-484d-8950-b7ddec39c5ee" />

Ciclo 4.2 · 🟢 VERDE
$ flutter test
 <img width="390" height="96" alt="image" src="https://github.com/user-attachments/assets/84a439d3-5fe8-4a5f-bc78-ab984ef7cb28" />

🔵 REFACTOR: ordena sin romper nada
El motor es una función pura: mismas entradas, mismas salidas, sin efectos secundarios. Las funciones puras son las más fáciles de probar, de entender y de reutilizar.
🏆 RETO PARA TI
Agrega al motor un parámetro "categorias" que filtre los lugares (por ejemplo, mostrar solo museos). Escribe primero la prueba.
 <img width="391" height="122" alt="image" src="https://github.com/user-attachments/assets/0859f7f5-c9af-489e-89f8-482bc7350158" />

Ronda 5 · El pasaporte turístico (gamificación)
Ciclo 5.1 · 🔴 ROJO
<img width="424" height="281" alt="image" src="https://github.com/user-attachments/assets/8fd66a54-5de2-431e-a2f0-bdbbf554eb0c" />
<img width="528" height="114" alt="image" src="https://github.com/user-attachments/assets/c6b265d8-1cd0-4c25-9886-7d655640423a" />

Ciclo 5.2 · 🟢 VERDE
<img width="666" height="128" alt="image" src="https://github.com/user-attachments/assets/6b142c3a-0d0d-4d20-9abf-d8d51de78169" />
 

Ronda 6 · Fuentes de datos y el ViewModel
Ciclo 6.1 · 🔴 ROJO: el ViewModel
 <img width="715" height="265" alt="image" src="https://github.com/user-attachments/assets/715c99d1-164b-4cd7-aaca-8debe5c6693e" />
  <img width="715" height="154" alt="image" src="https://github.com/user-attachments/assets/6d23b78c-6e0b-4c61-930e-477de6c93f82" />

Ciclo 6.2 · 🟢 VERDE
$ flutter test
<img width="395" height="120" alt="image" src="https://github.com/user-attachments/assets/4a4defc5-eb1d-4f6e-b92d-66353343cc72" />
