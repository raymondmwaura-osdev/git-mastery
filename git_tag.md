# `git tag`

Git tag creates a permanent reference to a specific point in your code history. Tags tay locked to one commit forever.

```sh
# List all tags
git tag

# Create a tag for the current commit
git tag v0.1.0

# Create a tag with a message (annotated tag - recommended)
# Annotated tags have metadata: author, date, message
git tag -a v0.1.0 -m "First release"

# Tag a specific commit
git tag v0.1.0 abc123

# Push tag to GitHub
git push origin v0.1.0

# Push all tags
git push origin --tags

# Checkout a specific tag
git checkout v0.1.0

# Delete local tag
git tag -d v0.1.0

# Delete remote tag
git push origin --delete v0.1.0
```
