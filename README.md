# Awesome-CI-CD-Automation

# 1. Replace the awesome link
sed -i '' 's|https://github.com/sindresorhus/awesome|https://github.com/ishandutta2007/Awesome-Awesome-Awesome|g' README.md
# (drop the '' on Linux)

# 2. Verify the replacement
grep -c "sindresorhus/awesome" README.md        # expect 0
grep -c "ishandutta2007/Awesome-Awesome-Awesome" README.md   # expect >0

# 3. Append the Support section (paste the block above, or use a heredoc)
cat >> README.md << 'EOF'

---

## 🙏 Support

Thank you for checking out **Awesome Chatbot Development Platform**! ...
EOF

# 4. Stage, commit, push
git add README.md
git commit -m "docs: replace awesome link, add Support section with sponsor CTA"
git push
