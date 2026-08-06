# roadmapsh-basic-dockerfile

## Table of Contents

- [About](#about)
- [Features](#features)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Installation & Usage](#installation--usage)
- [Example Output](#example-output)
- [How It Works](#how-it-works)
- [Error Handling](#error-handling)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Author](#author)
- [License](#license)

## About

A minimal Docker project that builds a container image and prints `Hello, Captain!` when run.

**Project Reference:** [roadmap.sh/projects/basic-dockerfile](https://roadmap.sh/projects/basic-dockerfile)

## Features

- Uses a lightweight Alpine Linux base image.
- Runs a single command when the container starts.
- Produces a predictable message and then exits immediately.

## Project Structure

- `Dockerfile`: Defines the image and the command executed at runtime.
- `README.md`: Explains the project and how to use it.

## Requirements

- Docker installed on your machine.
- A terminal capable of running Docker commands.

## Installation & Usage

### Clone or downlad the repository:

Option A - Clone with Git

```bash
git clone https://github.com/JescAude18/roadmapsh-basic-dockerfile.git
cd roadmapsh-basic-dockerfile
```

Option B - Download ZIP from Github

- Open the repository page: `https://github.com/JescAude18/roadmapsh-basic-dockerfile`
- Click `Code` -> `Download ZIP`
- Extract the archive and move into the project folder:

```bash
cd roadmapsh-basic-dockerfile
```

### Build the image:

```bash
docker build -t roadmapsh-basic-dockerfile -f Dockerfile .
```

### Run the container:

```bash
docker run --rm roadmapsh-basic-dockerfile
```

## Example Output

```text
Hello, Captain!
```

## How It Works

The `Dockerfile` starts from `alpine:latest` and uses `CMD` to run `echo "Hello, Captain!"` when the container launches.

## Error Handling

If Docker is not installed or the daemon is not running, the build or run commands will fail. Make sure Docker is available before trying again.

## Roadmap

- Keep the example as a minimal Docker learning exercise.
- Optionally add more basic Docker examples in the future.

## Contributing

Contributions are welcome. If you improve the example, keep the project minimal and easy to understand.

1. Fork the project
2. Create a branch for your feature (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Author

**Created by**: Jessica MOUSSOUGAN

**Email**: [jessicamoussougan@gmail.com](mailto:jessicamoussougan@gmail.com)

**GitHub**: [@JescAude18](https://github.com/JescAude18)

## License

No license yet.

This project is currently for personal training and learning.