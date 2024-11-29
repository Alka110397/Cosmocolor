# Cosmocolor Test

- Enfoque:
  Aplicación de prueba que muestra un listado de elementos en una vista desplazable, el cual podras obtener más información al seleccionar el elemento.

## Tabla de Contenidos

- [Características](#características)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Desafíos](#desafiós)

## Características

- Pantalla Principal:
  - Obtiene datos de la API JSONPlaceholder https://jsonplaceholder.typicode.com/photos.
  - Muestra una lista de información (título, id, albumId) en una vista desplazable.
- Pantalla de Detalles:
  - Cuando un usuario toca un elemento navega a una pantalla de detalles.
  - Muestra información detallada del elemento en esta pantalla.
- Navegación:
  - Utilización de react-navigation.
- Estilización:
  - Contiene estilos básicos para que la aplicación sea visualmente atractiva y fácil de usar.
- Gestión de Estado:
  - Utilización de los hooks useState y useEffect de React para la gestión de estado y datos.
- Extra:
  - Indicador de "Cargando..." mientras se obtienen los datos.
  - La aplicación es adaptable a diferentes tamaños de pantalla.

## Requisitos

- Node 23.3.0
- React Native CLI 0.76

## Instalación

Instrucciones sobre cómo instalar el proyecto:

1. Clona el repositorio:

   ```bash
   git clone https://github.com/Alka110397/Cosmocolor.git

   ```

2. Instala dependencias:

   ```bash
   npm install

   ```

3. Instala pods (solo iOS):

   ```bash
   cd ios
   bundle install
   bundle exec pod install

   ```

4. Ejecuta el proyecto:
   ```bash
   npm start
   ```

## Desafíos

1. La API proporcionada no contaba con muchos datos para manipular.

#### Solucion

Utilize algunos metodos de Javascript para obtener distintos datos.

2. No cuento con dispositivo físico Android.

#### Solucion

Utilize emuladores para realizar las pruebas necesarias.

![Simulator Screenshot - iPhone 16 Plus - 2024-11-29 at 03 28 33](https://github.com/user-attachments/assets/9835a78b-791c-4567-815c-47af435edf30)
![Simulator Screenshot - iPhone 16 Plus - 2024-11-29 at 03 28 17](https://github.com/user-attachments/assets/cf51d6a8-32ff-4f9f-9aa0-41bcb16304cd)
![Simulator Screenshot - iPhone 16 Plus - 2024-11-29 at 03 28 12](https://github.com/user-attachments/assets/8ff572bd-206d-4037-9986-5ceecd0bec37)



