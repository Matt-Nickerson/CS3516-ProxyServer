### Proxy Server ###

Student: Matthew Nickerson
Project: Project 2
Class: CS3516

## How to Run the Server

1. Open a terminal or command prompt in the project directory.

2. **Run the proxy server** with the following command:
   ```
   python "proxy server_skeleton code.py" <SERVER_IP>
   ```
   
   Replace `<SERVER_IP>` with the IP address where the proxy should listen. Common options:
   - `127.0.0.1` – Listen on localhost only (for local testing)
   
   You should see the output: `Ready to serve...`

### Testing the Proxy Server

Once the server is running, you can test it using a web browser or command-line tools:

#### Option 1: Using a Browser
1. Use the proxy at `http://<SERVER_IP>:8888`
2. Go to a web page (e.g., `http://<SERVER_IP>:8888/baidu.com`)
3. The proxy will fetch the page and cache it locally
4. Clear browser data and search again once cached, terminal will display `Read from cache`

### Server Details

- **Port:** 8888 (fixed in the code)
- **Protocol:** HTTP/1.0
- **Caching:** The proxy caches requested pages locally in the current directory




