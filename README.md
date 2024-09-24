# FroggerProcess 🐸🚗

[![License](https://img.shields.io/github/license/Gabrielebandino/FroggerProcess)](LICENSE)
[![Contributors](https://img.shields.io/github/contributors/Gabrielebandino/FroggerProcess)](https://github.com/Gabrielebandino/FroggerProcess/graphs/contributors)
[![Issues](https://img.shields.io/github/issues/Gabrielebandino/FroggerProcess)](https://github.com/Gabrielebandino/FroggerProcess/issues)

Welcome to **FroggerProcess**, a terminal-based implementation of *Frogger* built in C using the **ncurses** library. This project simulates a multi-agent system where each entity (logs, enemies, projectiles, etc.) is represented as a separate process, providing an introduction to concurrent programming via process management.

## 🚀 Features

- **Process-based Simulation**: Each game element (frog, logs, cars, projectiles) runs as an independent process.
- **Graphics via ncurses**: Uses the ncurses library to render game elements in the terminal.
- **Real-time Interaction**: Control the frog and navigate through dynamically moving obstacles.
- **Simple Inter-Process Communication**: Coordinates multiple processes without the use of threads.

## 🛠️ Technologies

- **Programming Language**: C
- **Graphics**: ncurses for rendering game elements.
- **Process Management**: Fork and exec system calls for spawning and managing game elements.
- **Inter-Process Communication**: Shared memory or signals (depending on implementation).
