# mbc-node

## How to run MBC-Node

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/mbc9555/mbc.git](https://github.com/mbc9555/mbc.git)
    cd mbc
    ```

2.  **Change the node's IP in the `.env` file:**
    * Open the `.env` file with a text editor.
    * Modify the IP address value NODE_PUBLIC_IP= to match your node's IP address.
    * Save the file.

3.  **Run Docker Compose:**

    ```bash
    docker compose up -d
    ```

4.  **Check the logs:**

    ```bash
    docker compose logs -f --tail 30
    ```


* Ensure that you have Docker and Docker Compose installed on your machine.
* If you encounter any issues running MBC-Node, please check the Docker container logs for errors.
