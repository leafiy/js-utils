```bash
git tag --list '2.0.0-*' | xargs -I % echo "git tag -d %; git push --delete origin %" | sh
```