# 🎮 TicTacToe con IA usando Minimax 🤖

![TicTacToe Game](https://raw.githubusercontent.com/GoldHood/TicTacToe-Minimax-AI/refs/heads/main/TicTacToe.gif)

¡Bienvenido al clásico juego de **TicTacToe** (Tres en Raya) con un giro moderno! Este proyecto implementa una **IA invencible** que utiliza el algoritmo **Minimax con poda alfa-beta** para tomar decisiones óptimas, creando una experiencia desafiante para el jugador humano.

## 📋 Descripción

Este proyecto es una implementación de TicTacToe en Python que permite al jugador humano competir contra una IA avanzada. La IA analiza cada movimiento posible utilizando el algoritmo Minimax, lo que la convierte en una oponente formidable. El juego también presenta una interfaz interactiva utilizando `ipywidgets` para mejorar la experiencia de usuario.

## 🚀 Características

- **IA avanzada con Minimax**: La IA utiliza el algoritmo Minimax optimizado con poda alfa-beta para tomar decisiones óptimas.
- **Interfaz interactiva**: Usa `ipywidgets` para una experiencia de juego visual en Jupyter Notebook.
- **Nivel de dificultad**: La IA está diseñada para no perder, por lo que siempre desafía al jugador humano a su máximo nivel.
- **Visualización en tiempo real**: Observa cómo la IA toma decisiones y juega en tiempo real.
- **Demo en GIF**: Visualiza la jugabilidad con un GIF demostrativo al inicio de este README.

## 🛠️ Tecnologías Utilizadas

- **Python**: Lenguaje principal del proyecto.
- **Jupyter Notebook**: Entorno interactivo para ejecutar el juego.
- **ipywidgets**: Librería para crear la interfaz interactiva.
- **Algoritmo Minimax con Poda Alfa-Beta**: Estrategia de IA para tomar decisiones óptimas en cada movimiento.

## 📂 Estructura del Proyecto

- **TicTacToe_MinMaxIA.ipynb**: Código principal del juego y lógica de la IA.
- **TicTacToe.gif**: GIF demostrativo del juego.

## 🎮 Cómo Jugar

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/GoldHood/TicTacToe-Minimax-AI.git
   cd TicTacToe-Minimax-AI
   ```

2. **Instala las dependencias necesarias**:
   - Asegúrate de tener `ipywidgets` instalado. Puedes instalarlo usando:
     ```bash
     pip install ipywidgets
     ```

3. **Ejecuta el Jupyter Notebook**:
   - Abre Jupyter Notebook y ejecuta `TicTacToe_MinMaxIA.ipynb`.
   - El juego se cargará, y podrás jugar directamente contra la IA en la interfaz.

4. **Comienza a jugar**:
   - Selecciona tus movimientos en el tablero interactivo.
   - Observa cómo la IA responde en tiempo real y desafíala a ganarle.

## 📈 Algoritmo Minimax

El algoritmo **Minimax con poda alfa-beta** es una técnica de inteligencia artificial para juegos de estrategia. Evalúa todos los posibles movimientos y toma la decisión óptima para maximizar sus posibilidades de ganar o empatar.

- **Minimax**: Este algoritmo explora todas las jugadas posibles, maximizando las ganancias para la IA y minimizando las del oponente.
- **Poda alfa-beta**: Optimización que permite ignorar ramas del árbol de decisiones, reduciendo el tiempo de cálculo y mejorando la eficiencia.

## 📚 Explicación del Código Principal

- **Clase `TicTacToe`**: La clase principal que implementa el juego.
  - **`__init__`**: Inicializa el tablero y configura al jugador actual como 'X' (el jugador humano).
  - **`create_board`**: Crea la interfaz del tablero utilizando `ipywidgets`, donde cada celda es un botón.
  - **`on_button_click`**: Define el comportamiento al hacer clic en un botón del tablero, permitiendo al jugador humano hacer su movimiento y luego llamando a la IA.
  - **`ai_move`**: Lógica del movimiento de la IA. Usa el algoritmo Minimax con poda alfa-beta para encontrar el mejor movimiento posible.
  - **`minimax`**: Implementación del algoritmo Minimax que evalúa cada movimiento posible para determinar la mejor jugada para la IA.
  - **`get_winner`**: Verifica si hay un ganador en el tablero.
  - **`end_game` y `reset_game`**: Finaliza el juego y permite reiniciar para volver a jugar.

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar la IA o la interfaz, no dudes en hacer un fork y enviar un pull request.

## 📬 Contáctame

Si quieres discutir más sobre el proyecto, aprender juntos o colaborar en nuevas ideas, no dudes en contactarme. Estoy siempre abierto a nuevos conocimientos y mejoras. 

- **Nombre**: Martin Verastegui
- **Correo**: [martin.verastegui@gmail.com](mailto:martin.verastegui@gmail.com)
- **GitHub**: [GoldHood](https://github.com/GoldHood)

¡Hagamos crecer juntos nuestras habilidades y llevemos nuestros proyectos al siguiente nivel! 💡🚀

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para obtener más detalles.

---

### 🎉 ¡Desafía a la IA y disfruta del juego clásico de TicTacToe reinventado! 🏆
