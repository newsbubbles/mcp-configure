# MCP Servers Configurator

This project is a simple, web‑based configuration tool for setting up and managing your MCP server entries. It provides an intuitive, mobile‑first interface where you can easily add servers, specify commands, arguments, and environment variables, and instantly view the resulting JSON configuration.

## Live Demo

Check out the live version on GitHub Pages:  
[https://newsbubbles.github.io/mcp-configure/](https://newsbubbles.github.io/mcp-configure/)

## How to Use

1. **Add a Server:**  
   Click the **Add Server** button to create a new MCP server configuration entry.

2. **Configure the Server:**  
   - **Server Key:** Enter a unique identifier for your server.  
   - **Command:** Specify the command that should be executed.  
   - **Arguments:** Click **Add Argument** to insert one or more command arguments.  
   - **Environment Variables:** Click **Add Env Variable** to add environment variable key‑value pairs (optional).

3. **View JSON Configuration:**  
   The JSON output updates in real time as you configure your servers. It displays a well‑formatted JSON with a top‑level `mcpServers` object mapping each server key to its configuration.

4. **Copy the JSON:**  
   When you're ready, click the **Copy JSON** button to copy the entire configuration to your clipboard.

## Project Structure

- **index.html:** Contains the complete HTML, CSS, and JavaScript code for the configurator.
- **README.md:** This file, with instructions and an overview of the project.

## License

This project is open source and available under the [MIT License](LICENSE).
