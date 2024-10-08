
# Port Scanner

This is a simple port scanner script written in Python. It scans a specified host for open ports within a given range.

## Usage

1. Clone the repository:

    ```sh
    git clone https://github.com/MoneKEE/port-scanner.git
    cd port-scanner
    ```

2. Run the script:

    ```sh
    python port_scanner.py
    ```

3. Enter the host to be scanned when prompted.

## How it works

- The script prompts the user to enter the host to be scanned.
- It resolves the IP address of the host.
- It scans ports from 50 to 8999 to check if they are open.
- For each open port, it prints the port number.
- It prints the total time taken for the scan.

## Dependencies

- Python 3.x

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
