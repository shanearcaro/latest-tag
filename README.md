# Latest-Tag

Very simple github actions script that keeps a latest tag synced with the latest commit on the main branch.

The idea is to use the latest tag as a version for a github workflow:
```yml
uses: example@latest
```

This script will delete the latest tag, if it exists, and recreate the tag on the latest commit.