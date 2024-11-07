Install

sudo apt install nvidia-cuda-toolkit


Make

nvcc -Iinclude -rdc=true -o cacachavecuda src/sha256_cuda.cu src/ripemd160_cuda.cu src/bitcoin_address.cu -lsecp256k1
