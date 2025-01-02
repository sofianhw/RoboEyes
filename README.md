# RoboEyes Library

RoboEyes is a Python library that creates smoothly animated robot eyes for GUI displays using **Pygame**. It provides configurable eye shapes and various moods and animations, making it ideal for robotics, art installations, and interactive applications.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sofianhw/RoboEyes.git
   ```
2. Install required dependencies:
   ```bash
   pip install pygame
   ```
3. Run:
   ```bash
   python main.py
   ```

---

## API Reference

### General

- **`begin(screen_width, screen_height, max_framerate)`**: Initialize RoboEyes.
- **`update()`**: Update eye animations with frame rate limiting.
- **`drawEyes()`**: Draw eyes without frame rate limiting.

### Configurations

- **`setWidth(left, right)`**: Set width of eyes.
- **`setHeight(left, right)`**: Set height of eyes.
- **`setBorderradius(left, right)`**: Set border radius.
- **`setSpacebetween(space)`**: Adjust spacing between eyes.
- **`setCyclops(on_off)`**: Toggle single-eye mode.

### Expressions and Animations

- **`setMood(mood)`**: Set mood (`HAPPY`, `TIRED`, `ANGRY`, `DEFAULT`).
- **`anim_confused()`**: Confused animation.
- **`anim_laugh()`**: Laughing animation.
- **`blink(left=1, right=1)`**: Blink one or both eyes.

### Macro Animators

- **`setAutoblinker(on_off, interval, variation)`**: Random blinking.
- **`setIdleMode(on_off, interval, variation)`**: Random repositioning.

---

## License

This project is licensed under the **GNU General Public License (GPL)**.

---

## Credits

The RoboEyes library is inspired by the [FluxGarage RoboEyes project](https://github.com/FluxGarage/RoboEyes/) by FluxGarage. Special thanks for the original work that inspired this project.