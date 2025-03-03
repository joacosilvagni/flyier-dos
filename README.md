# Flyier DoS Tool
<img width="405" alt="Captura1" src="https://github.com/user-attachments/assets/714e4fd2-cb42-4c08-8a77-ff565eeaafbe" />

Flyier is a Python-based Denial of Service (DoS) tool designed to flood a target server with HTTP requests, ultimately overwhelming its resources and causing service disruptions. It employs a combination of threading and asynchronous programming using the aiohttp library, which allows for high concurrency and efficient handling of multiple requests.

Upon running the tool, the user is prompted to provide a URL, and the script starts sending continuous HTTP requests to that URL, attempting to flood the server with traffic. Flyier also handles different operating systems, clearing the terminal window for a cleaner user interface.

The tool uses Python’s asyncio and aiohttp libraries to make asynchronous GET requests to the target server, repeatedly hitting it with traffic. The responses are logged, including status codes for each request. In case of any server unresponsiveness, the tool outputs a message indicating that the server is down.

Additionally, Flyier includes a graphical banner and warning against using the tool for illegal purposes, aligning with ethical concerns related to DoS attacks.

Key Features:

Asynchronous HTTP request handling for high efficiency.
Multithreaded operation for maximizing concurrent requests.
Simple command-line interface.
Banner and message to prevent illegal usage.
Usage Warning: Flyier is a tool intended for educational purposes and should not be used for unauthorized attacks on systems, which is illegal and unethical. Always use such tools in controlled environments and with explicit permission from the target system owner.
