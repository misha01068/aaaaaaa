#!/bin/bash
FILE="/etc/passwd"
echo "Users with /bin/bash shell:"
grep 'bin/bash' "$FILE" | cut -d: -f1
