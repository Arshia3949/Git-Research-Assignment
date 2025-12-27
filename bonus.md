cat <<EOF > bonus.md
In this bonus task, I successfully managed the repository locally by first using 'git clone' to copy it to my machine. I then created this 'bonus.md' file and documented the essential commands used throughout the project—including 'git add', 'git commit', and 'git push'—to demonstrate a complete local-to-remote version control workflow.
EOF

git add bonus.md
git commit -m "Complete bonus task Option A"
git push origin main
