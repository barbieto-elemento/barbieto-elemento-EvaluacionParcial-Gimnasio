# PowerFit (App de Rutinas Fitness)
## Descripción de la app

PowerFit es una aplicación enfocada en la presentación visual de una rutina de entrenamiento fitness.
La pantalla muestra una imagen referencial del entrenamiento, el nombre de la rutina, una breve descripción, un campo de entrada para registrar la cantidad a adquirir, un widget de valoración mediante estrellas, y dos botones de acción: Comprar y Agregar al carrito.

Este proyecto prioriza el diseño UI (alineación, jerarquía visual, proporciones, tipografía y distribución de elementos) utilizando una estructura clara, funcional y centrada en la experiencia del usuario.

<img width="689" height="1078" alt="image" src="https://github.com/user-attachments/assets/3bc4c38b-b639-4edb-b4b1-56ec2cd2edeb" />

Explicación breve:
La vista final presenta una estructura limpia y centrada, donde la imagen superior sirve como elemento visual principal. El título destaca mediante tipografía en negrita, seguido de una descripción secundaria. Los elementos interactivos (RatingBar, input y botones) están organizados de forma vertical, permitiendo una navegación intuitiva y una interacción rápida por parte del usuario.

## Imagen de la plantilla blanca (base de construcción)

<img width="829" height="1023" alt="image" src="https://github.com/user-attachments/assets/3bea5e24-b956-4259-9fef-1b23c84c4bb3" />

Explicación:
La plantilla blanca representa la estructura inicial del diseño sin estilos avanzados. Se utiliza para definir la disposición de los elementos principales (imagen, textos, widget, input y botones), asegurando una correcta alineación y jerarquía antes de aplicar mejoras visuales.

## Imagen de la maqueta de la app

<img width="829" height="1023" alt="image" src="https://github.com/user-attachments/assets/5ba29015-fcab-478e-ad3d-67601e39d4e4" />

Explicación breve:
La maqueta representa el diseño conceptual de la aplicación, donde se definen proporciones, distribución de elementos y estructura general. Sirve como guía visual para el desarrollo del layout final en Android Studio.

## Elementos incluidos (Imagen, Texto, Input, Widget, Botones) + atributos usados y sustento
### 1) Imagen

Elemento usado: ImageView
Atributos aplicados:
android:src="@drawable/fitness": carga la imagen desde los recursos del proyecto.
android:scaleType="centerCrop": asegura que la imagen se ajuste sin deformarse.
android:layout_width="180dp" / android:layout_height="180dp": tamaño uniforme.
android:contentDescription: mejora la accesibilidad.

<img width="881" height="1017" alt="image" src="https://github.com/user-attachments/assets/7ed900a2-ce34-4d22-8fcd-6510686192bc" />

### Sustento:
La imagen cumple la función de atraer visualmente al usuario y representar el producto (rutina fitness), generando una mejor experiencia visual.

### 2) Texto

Elementos usados: TextView (Título y descripción)
Atributos aplicados:
Título
android:textSize="20sp"
android:textStyle="bold"
android:gravity="center"
Descripción
android:textSize="16sp"
android:gravity="center"
android:layout_marginBottom="10dp"

<img width="819" height="1024" alt="image" src="https://github.com/user-attachments/assets/631141a9-7c9f-46ac-9a04-11e638bcad60" />

### Sustento:
Se aplica jerarquía visual mediante tamaño y estilo. El título destaca como elemento principal, mientras que la descripción complementa la información.

### 3) Input

Elemento usado: EditText (Cantidad a comprar)
Atributos aplicados:
android:hint="Cantidad a comprar": guía para el usuario.
android:inputType="number": restringe la entrada a valores numéricos.
android:layout_width="match_parent": ocupa todo el ancho disponible.

<img width="870" height="1019" alt="image" src="https://github.com/user-attachments/assets/93b97bf4-88e2-44ab-83c3-069d05f4b2ea" />

### Sustento:
Permite la interacción directa del usuario, facilitando el ingreso de datos necesarios para la compra.

### 4) Widget

Elemento usado: RatingBar
Atributos aplicados:
android:numStars="5": escala de valoración estándar.
android:stepSize="1": permite valores enteros.
android:layout_marginBottom="10dp"

<img width="820" height="1014" alt="image" src="https://github.com/user-attachments/assets/98b80291-04ea-4a4c-b251-ba33f59f8c41" />

### Sustento:
El widget permite al usuario visualizar y/o asignar una valoración a la rutina, mejorando la interacción y percepción del contenido.

### 5) Botones

Elemento usado: Button
Atributos aplicados:
android:text="Comprar" y android:text="Agregar al carrito": acciones claras.
android:layout_width="200dp": tamaño uniforme.
android:layout_marginBottom="10dp": separación visual.

<img width="814" height="1025" alt="image" src="https://github.com/user-attachments/assets/bf1fe809-18bd-4e59-9b7f-e249d9f54480" />

### Sustento:
Los botones representan las acciones principales del usuario dentro de la app. Su ubicación y tamaño facilitan la interacción rápida.

## CONCLUSIÓN
La aplicación PowerFit cumple con los principios básicos de diseño de interfaces en Android, integrando correctamente componentes visuales e interactivos. Se logra una interfaz clara, ordenada y funcional, donde cada elemento cumple un propósito específico dentro de la experiencia del usuario.
