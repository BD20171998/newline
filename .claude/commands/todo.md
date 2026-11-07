# Find TODOs Command

Search the whole repository for lines that contain “TODO” (case‑insensitive) and show the file path with line numbers:

!grep -Rin --exclude-dir=node_modules --exclude-dir=.git "TODO" .
