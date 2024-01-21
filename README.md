# Awesome DB Papers

> These papers need to be revisited.
> More read papers will be added when I get time.

## Distributed Transaction Papers [Read]
- [Google Spanner Paper](https://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf) - Distributed `Strict Serializable Transaction` using True Time
- [Caliv - Dist Txn](https://www.cs.umd.edu/~abadi/papers/calvin-sigmod12.pdf) -  sequencing layer, scheduling layer, pre-determined order
- [HLC eBay - Session Guarantees with Raft and HLC ‘19](https://arxiv.org/pdf/1808.05698.pdf) - Session Consistency
- [Percolator - TiKV](https://tikv.org/deep-dive/distributed-transaction/percolator/) - 2PC, Ts oracle

## Disaggregated Shared Memory for Databases [Read]
- [PolarDB Serverless: BTree](https://users.cs.utah.edu/~lifeifei/papers/polardbserverless-sigmod21.pdf) - RDMA, PolarDB Txn Flow, Page Array
- [FORD - Hash Index](https://www.usenix.org/conference/fast22/presentation/zhang-ming) - One Sided RDMA, Dist OCC Txn, HitchHiked Locking
- [Sherman - BTree Index](https://arxiv.org/abs/2112.07320): HW features, Classic CC, XLOCK to resolve W-W conflict, Lock-free search with version to resolve R/W conflict
- [RACE - Extendable HashIndex](https://www.usenix.org/conference/atc21/presentation/zuo): Lock free remote CC, Pilaf Cuckoo Hashing


## Misc Papers [Read]
- [Elkan's Kmeans](https://cdn.aaai.org/ICML/2003/ICML03-022.pdf) - Fast `Kmeans` Algorithm using Triangle Inequality Property
- [A method for implementing Lock-Free shared Data Structures](https://dl.acm.org/doi/pdf/10.1145/165231.165265) - Coordination Technique, Caching Algo
