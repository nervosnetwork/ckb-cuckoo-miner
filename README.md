# ckb-cuckoo-miner
A cuckoo miner for avx2 CPUs, avx512 CPUs and Nvidia GPUs.

## How to build
By default, GPU miner is not built, you can build GPU miner with this parameters:
```
cargo build --release --features gpu
```
Cuda is essential to build and run GPU miners.

## How to use
1. Modify `ckb-miner.toml` in this repo and copy it to your working directory. You can specify the CPUs and GPUs you want to use.

2. Copy `ckb-miner` (you can build it yourself or download it) to your working directory.

3. run the miner

```
./ckb-miner
```

