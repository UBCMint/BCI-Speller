We use Docker to run `snakemake`.

```
sudo docker pull quay.io/biocontainers/snakemake@sha256:5b10f1e7efd065d29b95327eb79e760334dfc022c071b8fd555d4f84e6469395
sudo docker run --name snakemake -it -p 80:8080 -d quay.io/biocontainers/snakemake@sha256:5b10f1e7efd065d29b95327eb79e760334dfc022c071b8fd555d4f84e6469395
sudo docker attach snakemake
```
