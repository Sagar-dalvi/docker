continuation of Docker commands and concepts, including some advanced commands and use cases.

### Advanced Docker Commands

#### **docker inspect [CONTAINER/IMAGE]**
- **Purpose**: Provides detailed information about a container or image in JSON format.
- **Example**:
  ```bash
  docker inspect my_container
  ```
- **Output**: Detailed JSON output about the container’s configuration, state, and more.

#### **docker stats**
- **Purpose**: Shows real-time statistics for running containers, including CPU, memory usage, and network I/O.
- **Example**:
  ```bash
  docker stats
  ```
- **Output**: Displays live data on container performance.

#### **docker diff [CONTAINER]**
- **Purpose**: Shows changes made to the filesystem of a container since it was started.
- **Example**:
  ```bash
  docker diff my_container
  ```
- **Output**: Lists added, modified, and deleted files in the container.

#### **docker history [IMAGE]**
- **Purpose**: Shows the history of an image, including the commands used to create it.
- **Example**:
  ```bash
  docker history my_image
  ```
- **Output**: Displays layers of the image along with creation time and command.

#### **docker volume create [VOLUME_NAME]**
- **Purpose**: Creates a new Docker volume.
- **Example**:
  ```bash
  docker volume create my_volume
  ```
- **Output**: Creates a volume named `my_volume`.

#### **docker volume rm [VOLUME_NAME]**
- **Purpose**: Removes a Docker volume.
- **Example**:
  ```bash
  docker volume rm my_volume
  ```
- **Output**: Removes the volume named `my_volume`.

#### **docker network create [NETWORK_NAME]**
- **Purpose**: Creates a new Docker network.
- **Example**:
  ```bash
  docker network create my_network
  ```
- **Output**: Creates a network named `my_network`.

#### **docker network rm [NETWORK_NAME]**
- **Purpose**: Removes a Docker network.
- **Example**:
  ```bash
  docker network rm my_network
  ```
- **Output**: Removes the network named `my_network`.

#### **docker-compose logs**
- **Purpose**: Displays logs from services defined in a Docker Compose file.
- **Example**:
  ```bash
  docker-compose logs
  ```
- **Output**: Shows logs from all services in the Docker Compose setup.

#### **docker-compose exec [SERVICE] [COMMAND]**
- **Purpose**: Executes a command in a running container for a specific service.
- **Example**:
  ```bash
  docker-compose exec web /bin/bash
  ```
- **Output**: Opens a bash shell inside the container of the `web` service.

#### **docker-compose build**
- **Purpose**: Builds or rebuilds services defined in a Docker Compose file.
- **Example**:
  ```bash
  docker-compose build
  ```
- **Output**: Builds the images for services defined in the `docker-compose.yml` file.

#### **docker-compose up --build**
- **Purpose**: Starts services and rebuilds images if changes are detected.
- **Example**:
  ```bash
  docker-compose up --build
  ```
- **Output**: Starts the services and rebuilds images if necessary.

### Docker Command Summary with Examples

1. **`docker inspect [CONTAINER/IMAGE]`**
   - Get detailed information about a container or image.
   - Example: `docker inspect my_container`

2. **`docker stats`**
   - View real-time statistics of running containers.
   - Example: `docker stats`

3. **`docker diff [CONTAINER]`**
   - See changes made to the filesystem of a container.
   - Example: `docker diff my_container`

4. **`docker history [IMAGE]`**
   - View the history of an image.
   - Example: `docker history my_image`

5. **`docker volume create [VOLUME_NAME]`**
   - Create a new volume.
   - Example: `docker volume create my_volume`

6. **`docker volume rm [VOLUME_NAME]`**
   - Remove a volume.
   - Example: `docker volume rm my_volume`

7. **`docker network create [NETWORK_NAME]`**
   - Create a new network.
   - Example: `docker network create my_network`

8. **`docker network rm [NETWORK_NAME]`**
   - Remove a network.
   - Example: `docker network rm my_network`

9. **`docker-compose logs`**
   - View logs for services in Docker Compose.
   - Example: `docker-compose logs`

10. **`docker-compose exec [SERVICE] [COMMAND]`**
    - Execute a command in a specific service container.
    - Example: `docker-compose exec web /bin/bash`

11. **`docker-compose build`**
    - Build or rebuild services defined in Docker Compose.
    - Example: `docker-compose build`

12. **`docker-compose up --build`**
    - Start services and rebuild images if necessary.
    - Example: `docker-compose up --build`

These commands cover a wide range of Docker functionalities, 
from managing containers and images to working with Docker Compose and handling volumes and networks.
