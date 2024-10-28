```
(base) lhvu@realtimeaidoe:~/bio/bwa-mem2-prebuilt$ pwd
/home/lhvu/bio/bwa-mem2-prebuilt
(base) lhvu@realtimeaidoe:~/bio/bwa-mem2-prebuilt$ bwa-mem2 index ../minimap2/test/
MT-human.fa  MT-orang.fa  q2.fa        q-inv.fa     t2.fa        t2.fa.amb    t2.fa.ann    t2.fa.bwt    t2.fa.pac    t2.fa.sa     t-inv.fa
(base) lhvu@realtimeaidoe:~/bio/bwa-mem2-prebuilt$ bwa-mem2 index ../minimap2/test/t2.fa
Looking to launch executable "/home/lhvu/bio/bwa-mem2-prebuilt/bwa-mem2-2.2.1_x64-linux/bwa-mem2.avx2", simd = .avx2
Launching executable "/home/lhvu/bio/bwa-mem2-prebuilt/bwa-mem2-2.2.1_x64-linux/bwa-mem2.avx2"
[bwa_index] Pack FASTA... 0.00 sec
* Entering FMI_search
init ticks = 527880
ref seq len = 148
binary seq ticks = 70456
build suffix-array ticks = 110936
ref_seq_len = 148
count = 0, 40, 74, 108, 148
BWT[88] = 4
CP_SHIFT = 6, CP_MASK = 63
sizeof CP_OCC = 64
pos: 19, ref_seq_len__: 18
max_occ_ind = 2
build fm-index ticks = 487960
Total time taken: 0.0021
```
