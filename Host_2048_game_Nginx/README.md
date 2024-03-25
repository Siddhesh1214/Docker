# 2048
A small clone of [1024](https://play.google.com/store/apps/details?id=com.veewo.a1024), based on [Saming's 2048](http://saming.fr/p/2048/) (also a clone).

Made just for fun. [Play it here!](http://gabrielecirulli.github.io/2048/)

The official app can also be found on the [Play Store](https://play.google.com/store/apps/details?id=com.gabrielecirulli.app2048) and [App Store!](https://itunes.apple.com/us/app/2048-by-gabriele-cirulli/id868076805)


### Screenshot

<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/1175750/8614312/280e5dc2-26f1-11e5-9f1f-5891c3ca8b26.png" alt="Screenshot"/>
</p>

That screenshot is fake, by the way. I never reached 2048 :smile:

## Contributing
Changes and improvements are more than welcome! Feel free to fork and open a pull request. Please make your changes in a specific branch and request to pull into `master`! If you can, please make sure the game fully works before sending the PR, as that will help speed up the process.

---
# Hosted 2048 Game with Docker and Nginx

Welcome to the Dockerized version of the classic 2048 game! This repository provides everything you need to quickly deploy the game using Docker and Nginx.

### About the Game
2048 is a popular single-player sliding block puzzle game. The objective is to slide numbered tiles on a grid to combine them and create a tile with the number 2048.

### Prerequisites

Before you start, ensure you have Docker installed on your machine. If not, you can install it by following the instructions in the [official Docker documentation](https://docs.docker.com/get-docker/).

### Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/Siddhesh1214/Docker.git
    ```

2. Navigate to the `Nginx/2048` directory:

    ```bash
    cd Docker/Nginx/2048
    ```

3. Build the Docker image:

    ```bash
    docker build -t 2048-game .
    ```

4. Run the Docker container:

    ```bash
    docker run -d -p 80:80 2048-game
    ```

5. Access the game in your web browser:

    ```
    http://localhost
    ```

### How to Play

2048 is a single-player sliding block puzzle game. The objective is to slide numbered tiles on a grid to combine them and create a tile with the number 2048. Use the arrow keys to move the tiles in the respective direction.
