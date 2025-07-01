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
![image](https://github.com/user-attachments/assets/c83bbc45-8608-43f0-bd45-4d05d36c6b88)

### Forward Button Configuration
- When the **Forward** button is released, Solaar checks the direction of the mouse movement and triggers a corresponding action:
  - **Up, Down, Left, Right** movements each trigger a different action, "Print", "Escape", Control + f, Control + l + h, respectively.
  - If no movement is detected, a **default action** is executed. In this case, the action is press the key combo Control + f.
![image](https://github.com/user-attachments/assets/9e31b96c-7f28-4fdb-b37d-672786f8d365)

### Back Button and Bottom Button Configuration
- The **Back** button and the **lowest side button** are configured similarly to the Forward button, supporting gesture-based actions.
![image](https://github.com/user-attachments/assets/fb7ed436-fd7c-42b2-a282-f1eab54e07e8)

![image](https://github.com/user-attachments/assets/92832375-5324-4526-9d7f-0cfe55cbbd14)

---

## References

- [Solaar Official Website](https://pwr-solaar.github.io/Solaar/)
- [Multiplatform Gesture Button Demonstration](https://www.youtube.com/watch?v=E7YjQ01gacE)

---

## Acknowledgments

Special thanks to the Solaar development team for providing an excellent tool for Linux users!
