# Pew

Make/Makefile alternative (Pew/Pewfile)

# Usage

1. Create a Pewfile:

```
touch Pewfile
```

2. Open the created `Pewfile` and describe commands:

```
test:
  - echo "test"
  - echo "second test line"
```

3. Run `pew test`, you should get:

```
test
second test line
```
