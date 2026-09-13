# anthropic-mcp-sever-client
MCP architecture and how it shifts tool definition and execution burden from server to specialized MCP servers
- MCP's transport-agnostic communication system and the message types used between clients and servers
- Explore the complete request-response flow from user queries through MCP clients to external services and back to Claude
- Build MCP servers using the Python SDK with decorators to define tools instead of writing JSON schemas manually
- Implement document management functionality with tools for reading and editing documents using Field descriptions and type hints
- Use the built-in MCP Server Inspector to test and debug your server functionality in a browser-based interface
- Define resources for exposing read-only data, including both direct resources with static URIs and templated resources with parameters
- Implement resource reading functionality in clients with proper MIME type handling for JSON and text content
- Build prompts that provide pre-crafted, high-quality instructions for common workflows like document formatting
- Understand when to use each MCP primitive: tools (model-controlled), resources (app-controlled), and prompts (user-controlled)
- Examine practical integration patterns including autocomplete functionality and context injection for AI conversations
