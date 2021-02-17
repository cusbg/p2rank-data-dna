# P2Rank-DNA datasets

Data and results of P2Rank applied to protein-DNA sites detection
as presented in the bachelor thesis of Petra Gajdošová (see the docs).

The results were obtained running

```
./prank.sh traineval -c config -t ../p2rank-data-dna/distance_5.0/train_chains.ds -e ../p2rank-data-dna/distance_5.0/eval_chains.ds  -out_subdir FasterForest2/distance_5.0/model -surface_additional_cutoff 3.2
```

Most of the parameters are stored in the [config](config.groovy) file.

The surface cutoffs were based on the distance threshold using the default solvent radius (solvent_radius = 1.8). Specifically:
- distance 4.0 -> cutoff 2.2
- distance 4.5 -> cutoff 2.7
- distance 5.0 -> cutoff 3.2
- distance 5.5 -> cutoff 3.7
- distance 6.0 -> cutoff 4.2





