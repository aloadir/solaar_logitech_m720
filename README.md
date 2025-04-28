# Logitech M720 Mouse Rules for Solaar

This repository provides a set of custom rules for configuring the Logitech M720 mouse using [Solaar](https://pwr-solaar.github.io/Solaar/).

> **Solaar** is a Linux manager for many Logitech keyboards, mice, and trackpads that connect wirelessly via a USB Unifying, Bolt, Lightspeed, or Nano receiver; via a USB cable; or via Bluetooth.

These rules aim to emulate the behavior of the **Multiplatform Gesture Button** as implemented in Logitech’s software for Windows.  
You can see a demonstration of the gesture functionality in this [video](https://www.youtube.com/watch?v=E7YjQ01gacE).

---

## Installation

1. Download the `rules.yaml` file from this repository.
2. Replace your existing `rules.yaml` file (typically located at `~/.config/solaar/rules.yaml`) with the downloaded file.
3. Open Solaar. The new rules will appear automatically in the **Rule Editor**.

> **Note:** You can also configure the rules manually by copying the settings shown in the provided images.

---

## Functionality Overview

### Zoom In and Zoom Out
- The first two rules configure the left and right tilt actions of the scroll wheel to perform **Zoom In** and **Zoom Out**, respectively.

### Multiplatform Gesture Button Setup
- The next three sections configure the three side buttons on the mouse to act as **Multiplatform Gesture Buttons**.

### Forward Button Configuration
- When the **Forward** button is released, Solaar checks the direction of the mouse movement and triggers a corresponding action:
  - **Up, Down, Left, Right** movements each trigger a different action.
  - If no movement is detected, a **default action** is executed.

### Back Button and Bottom Button Configuration
- The **Back** button and the **lowest side button** are configured similarly to the Forward button, supporting gesture-based actions.

---

## References

- [Solaar Official Website](https://pwr-solaar.github.io/Solaar/)
- [Multiplatform Gesture Button Demonstration](https://www.youtube.com/watch?v=E7YjQ01gacE)

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

Special thanks to the Solaar development team for providing an excellent tool for Linux users!
