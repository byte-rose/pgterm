# pgterm

**pgterm** is a terminal-based interface (TUI) for PostgreSQL, written in Go. It allows you to connect to a PostgreSQL database, run queries, and browse tables directly from your terminal.

## Demo 

https://github.com/user-attachments/assets/ec57d812-7039-48fc-8eb9-59f01084b05e

## Features

- **Connection Manager**: Easily connect to any PostgreSQL database.
- **Table Browser**: View list of tables in the database.
- **SQL Query Editor**: Write and execute SQL queries.
- **Result Viewer**: View query results in a formatted table.
- **Keyboard Navigation**: Efficient keybindings for quick navigation.

## Shortcuts

| Key Binding         | Action               |
| ------------------- | -------------------- |
| `Alt` + `q`         | Focus Query Input    |
| `Alt` + `r`         | Focus Results View   |
| `Alt` + `t`         | Focus Tables List    |
| `Alt` + `Enter`     | Execute Query        |
| `Tab` / `Shift+Tab` | Navigate Up and Down |

## Installation

You can install `pgterm` directly using `go install`:

```bash
go install github.com/nabsk911/pgterm@latest
```

Make sure your `GOPATH` bin directory is in your system `PATH`.

## Usage

Run the application:

```bash
pgterm
```

