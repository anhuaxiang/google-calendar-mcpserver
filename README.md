# Google Calendar MCP


```json

{
  "mcpServers": {
    "google-calendar": {
      "env": {
        "GOOGLE_ACCESS_TOKEN": "GOOGLE_ACCESS_TOKEN",
        "GOOGLE_REFRESH_TOKEN": "GOOGLE_REFRESH_TOKEN",
        "GOOGLE_CLIENT_ID": "GOOGLE_CLIENT_ID",
        "GOOGLE_CLIENT_SECRET": "GOOGLE_CLIENT_SECRET"
      },
      "command": "uvx",
      "args": [
        "google-calendar-mcpserver"
      ]
    }
  }
}
```