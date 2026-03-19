# Dockerfile-Advance-Demo

# Build bloated
docker build -f Dockerfile.bloated -t app:bloated .

# Build optimized
docker build -f Dockerfile.optimized -t app:optimized .

# Check size
docker images
