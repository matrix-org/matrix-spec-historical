This repository contains copies of the Matrix specification from before
v1.0. They are hosted online at https://spec.matrix.org/historical.

# Deployment notes

```
curl -L https://github.com/matrix-org/matrix-spec-historical/archive/refs/heads/main.tar.gz | tar -xvz
rm -r historical.bak
mv historical historical.bak
mv matrix-spec-historical-main historical
```
