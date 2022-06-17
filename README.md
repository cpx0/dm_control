# DeepMind Control Suite

## 環境構築

### chmod +x <file>
```bash
chmod +x docker/build.sh
chmod +x docker/Dockerfile
chmod +x launch.sh
```

### Build: Docker Image 'dm_control:1.1'

```bash
cd docker
. build.sh
```

### Run: Docker Container 

```bash
cd ..
. launch.sh <container_name> <image_tag>
```
