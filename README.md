# NewsAPP

![NewsAPP](assets/NewsAPP.png)

NewsAPP is a simple news reader application written in Rust using the Egui framework and the NewsAPI.


## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Running the Application](#running-the-application)
- [Special Instructions for Arch Linux](#special-instructions-for-arch-linux)

## Features

- Fetches news headlines from a variety of sources.
- Displays headlines in a user-friendly interface.
- Allows users to follow links to read more about a news story.

## Getting Started

### Prerequisites

- **Rust Compiler**: If you haven't already, you'll need to install the Rust compiler. You can do this by following the instructions on the [official Rust website](https://www.rust-lang.org/tools/install).

### Installation

- **Clone the repository**: Clone the NewsAPP repository to your local machine by running the following command in your terminal:

    ```bash
    git clone https://github.com/Sri-dhar/NewsAPP.git
    ```

## Running the Application

- **Run the application**: Navigate into the cloned directory and run the application using Cargo, Rust's package manager. Run the following commands in your terminal:

    ```bash
    cd NewsAPP
    cargo run
    ```

After following these steps, the NewsAPP should be running on your local machine.

## Special Instructions for Arch Linux

If you are using an Arch-based distribution and have the Wayland display manager running, use the following command instead of "cargo run":

    ```bash
    WINIT_UNIX_BACKEND=x11 cargo run
    ```