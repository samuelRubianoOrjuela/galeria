# TALLER GALERIA



#### ¿Que funciones cumplen las siguientes propiedades?

- **"transition" :**  

  Esta permite controlar una transición en el momento en el que un elemento HTML cambia. Su sintaxis es:  " transition:  propiedad   duracion   funcion-de-temporizacion   [retardo]; "

  ej:

  ```css
  transition: transform 0.3s ease-in-out;
  ```

- **"filter" :**

  Agrega un filtro en el cual tenemos opciones de cambiar elementos como el brillo y la opacidad de un elemento determinado. Su sintaxis es:  " filter:  aplicacion(); "

  ej:

  ```css
  .elemento {
      filter: opacity(0.9);
  }
  ```

- **"transform" :**

  Con esta propiedad, se puede realizar una variedad de cambios visuales en un elemento, como trasladarlo (moverlo), rotarlo, escalarlo y sesgarlo. Su sintaxis es:  " transform:  valor(); "

  ej:

  ```css
  .elemento {
      transform: scale(1.04);
  }
  ```

- **"grid-auto-flow: dense" :**

  Controla cómo se colocan los elementos en el grid cuando no hay suficientes columnas o filas para acomodar todos los elementos. Su sintaxis es:  " grid-auto-flow:  valor(); "

  ej:

  ```css
  .elemento {
      grid-auto-flow: dense;
  }
  ```

- **"minmax()" :**

  Esta función permite establecer un rango flexible entre un valor mínimo y un valor máximo en las dimensiones de una cuadrícula (grid) o de un elemento en una cuadrícula. Su sintaxis es:  " minmax(minimum, maximum); "

  ej:

  ```css
  .elemento {
      propiedad: minmax(200px, 500px);
  }
  ```

- **"Media Query" :**

  Es una técnica en CSS que permite aplicar estilos diferentes a un documento HTML basándose en características específicas del dispositivo que está siendo utilizado para visualizar la página. Su sintaxis es:  " @media tipo-de-medio y (condición) { Reglas de estilo para el tipo de medio y la condición } "

  ej:

  ```css
  @media (min-width: 600px) {
    .wide {
        grid-column: span 2;
    }
    .tall {
        grid-row:span 2;
    }
  }
  ```

- **"min-width" :**

  Es una función que permite establecer ancho minimo para un elemento HTML. Su sintaxis es:  " min-width: valor "

  ej:

  ```css
  .elemento {
    min-width: 600px;
  }
  ```

- **"span" :**

  Indica que el elemento seleccionado debería extenderse a través de n columnas o filas en la cuadrícula. Su sintaxis es:  " grid: span valor; "

  ej:

  ```css
  .elemento {
    grid-column: span 2;
  }
  ```

- **"background-size: cover;" :**

  La propiedad background-size: cover; en CSS se utiliza para controlar el tamaño de una imagen de fondo de manera que cubra completamente el área del contenedor, sin distorsionar la relación de aspecto de la imagen y asegurándose de que toda el área del contenedor esté cubierta por la imagen. Su sintaxis es:  " background-size: cover; "

  ej:

  ```css
  .elemento {
    background-size: cover;
  }
  ```

- **"background-position: center;" :**

  La propiedad background-position: center; en CSS se utiliza para definir la posición del fondo de un elemento en relación con su contenedor. En este caso específico, center indica que la imagen de fondo debe centrarse tanto horizontal como verticalmente dentro del contenedor. Su sintaxis es:  " background-position: center; "

  ej:

  ```css
  .elemento {
    background-position: center;
  }
  ```

- **"background-repeat: no-repeat;" :**

  La propiedad background-repeat: no-repeat; en CSS se utiliza para especificar cómo se debe repetir una imagen de fondo dentro de un elemento. En este caso, no-repeat indica que la imagen de fondo no debe repetirse, y se mostrará solo una vez en el área del contenedor. Su sintaxis es:  " background-repeat: no-repeat; "

  ej:

  ```css
  .elemento {
    background-repeat: no-repeat;
  }
  ```