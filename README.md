# Dokku Static Buildpack using Nginx

Two things to make this work:

1. Add an empty `.servestatic` file in your project root
2. Create an `.env` file in your project containing this:

```
BUILDPACK_URL="https://github.com/ruudud/static-buildpack.git"
```

Added nginx directives:
 - types_hash_max_size 2048;

