# 🚀 Essential Git Bash Commands Cheat Sheet

## 📂 Basic Navigation

| Command | Description | Example | Tips |
|---------|-------------|---------|------|
| `pwd` | Print current directory path | `pwd` → `/c/Users/Name` | Always know your location |
| `ls` | List directory contents | `ls -l` | Use `-l` for details, `-t` to sort by time |
| `ls -a` | Show hidden files | `ls -a` | Reveals `.git`, `.env` files |

## 📁 Directory Operations

| Command | Description | Example | Tips |
|---------|-------------|---------|------|
| `cd` | Change directory | `cd Projects` | `cd ..` goes up one level |
| `mkdir` | Create directory | `mkdir -p src/{main,test}` | Creates nested folders |
| `rmdir` | Remove empty directory | `rmdir empty_folder` | Safer than `rm -r` |

## 📄 File Operations

| Command | Description | Example | Tips |
|---------|-------------|---------|------|
| `touch` | Create file | `touch index.html` | Updates timestamp if exists |
| `echo` | Create/file content | `echo "Hi" > file.txt` | `>>` appends, `>` overwrites |
| `cat` | Show file content | `cat config.yml` | `cat > file` creates with input |
| `mv` | Move/rename | `mv old.txt new.txt` | Also moves between directories |

## 🗑️ Deletion Commands

| Command | Description | Example | Warning |
|---------|-------------|---------|---------|
| `rm` | Remove file | `rm temp.txt` | Permanent deletion |
| `rm -r` | Remove directory | `rm -r node_modules/` | Deletes recursively |
| `rm -f` | Force delete | `rm -f *.log` | No confirmation |

## 🔍 Search & Inspection

| Command | Description | Example | Options |
|---------|-------------|---------|---------|
| `find` | Find files | `find . -name "*.js"` | `-size +1M`, `-mtime -7` |
| `grep` | Search text | `grep "error" logs.txt` | `-i` case-insensitive, `-r` recursive |

## 🛠️ Utility Commands

| Command | Description | Shortcut | Tip |
|---------|-------------|----------|-----|
| `clear` | Clear screen | `Ctrl+L` | Keeps history |
| `history` | Command history | `!23` | Re-run 23rd command |
| `code .` | Open in VS Code | - | Requires VS Code |

## ⚡ Power User Tips

### Wildcards
```bash
*.txt       # All text files
project-??  # Files like project-01
[A-Z]*      # Uppercase starting files