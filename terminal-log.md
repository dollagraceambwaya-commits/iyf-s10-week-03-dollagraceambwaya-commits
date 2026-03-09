## Commands Used:
- `mkdir my-project` - Created main project directory
- `mkdir -p my-project/src` - Created src directory
- `touch my-project/README.md` - Created README file
- `rm -v ./my-project/src/contact.html - Shows confirmation of deletion

# Show command history
ls -la
grep -r "button" ./my-project/src/
find . -name "*contact.html"
rm -v ./my-project/src/contact.html
echo "button" >> contact.html
grep -r "button" ./src/
grep -r "button" ./my-project/src/
cat contact.html
grep "button" contact.html
history 10

## Assignment Answers

1. How many HTML files? 2
2. Which files contain "contact"? terminal-log.md, contact.html
3. How many lines in CSS? 4
4. Last 10 commands?  7  grep -r "contact" .
    8  sed i '8s/<hi>/<h1>/' contact.html
    9  sed -i '8s/<hi>/<h1>/' contact.html
   10  grep "contact" .
   11  grep -r "contact" .
   12  grep -r -i "contact" .
   13  touch styles.css
   14  cat >> styles.css <<EOF
h1 {
font-family: Arial, sans-serif;
font-size: 16px;
}
EOF

   15  wc -l styles.css
   16  history 10