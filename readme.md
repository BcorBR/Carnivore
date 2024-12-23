# 🌸 Carnivore Game

Welcome to **Carnivore**, a game developed in **assembly language** using the ICMC processor from the University of São Paulo! This README will guide you through setting up the simulator and running the game.

---

## 🎮 About the Game

Carnivore is a retro-style game designed for the ICMC processor. Test your skills and enjoy a unique gaming experience!

---

## 🛠️ Simulator Installation

🛠️ What you need to use the simulator

    Install a recent version of Go (at least 1.13)
    Install Git and a C compiler (on Windows, use MinGW).
    On Debian/Ubuntu-based systems, install libgl1-mesa-dev xorg-dev; on Fedora and Red Hat-based systems, install libX11-devel libXcursor-devel libXrandr-devel libXinerama-devel mesa-libGL-devel libXi-devel libXxf86vm-devel.
    The simulator is in the main directory and it's named simgo
    The simulator's repository is linked on tips, at the end of this README

---

## 🖼️ Processor Architecture

![Processor Architecture](architecture.png)

The image above illustrates the architecture of the ICMC processor, providing an overview of its components and design principles.

---

### 🕹️ Step-by-Step Tutorial

1. Open the simulator (`simgo`).
2. Navigate to the top left corner of the screen and click on **Files**.
3. Select **Open Code MIF**, then choose `carnivore.mif` from the `src` folder.
4. Go to **Files** again in the top left corner.
5. Select **Open Char MIF**, then choose `charmap.mif` from the `src` folder.
6. Start the simulation and enjoy the game!

---

## 📹 Video Demonstration

Watch a video explaining the code and showcasing the game: [Carnivore Game Demonstration](https://www.youtube.com/watch?v=45w06YsUfgE)

---

## 💡 Tips

- Use the `--help` option in the simulator to explore its features.
- Check the [simulator's repository](https://github.com/lucasgpulcinelli/goICMCsim/tree/v1.1) for detailed information.

---

## 📄 License

This project is licensed under the terms specified in the [Carnivore Game] repository.

Enjoy the hunt! 🌱🎯
