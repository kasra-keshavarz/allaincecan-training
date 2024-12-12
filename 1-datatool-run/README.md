# Run `datatool`

To run `datatool`, we can follow:

```console
foo@narval-compute-node:~$ cd $HOME/github-repos/datatool/
foo@narval-compute-node:~$ ./extract-dataset.sh  \
  --dataset=rdrsv2.1  \
  --dataset-dir=$HOME/scratch/alliancecan-training-data/meteorological-data/rdrsv2.1/ \
  --output-dir=$HOME/scratch/alliancecan-training-data/modelling/1-outputs/datatool-outputs/ \
  --start-date="1985-01-01" \
  --end-date="1985-01-31" \
  --shape-file=$HOME/scratch/alliancecan-training-data/modelling/0-geofabric/bow-at-calgary-geofabric/bcalgary_subbasins.shp \
  --prefix=bow_at_calgary_ \
  --cluster=$HOME/github-repos/allaincecan-training/1-datatool-run/drac-narval.json \
  --variable=RDRS_v2.1_A_PR0_SFC,RDRS_v2.1_P_FB_SFC,RDRS_v2.1_P_FI_SFC,RDRS_v2.1_P_HU_09944,RDRS_v2.1_P_TT_09944,RDRS_v2.1_P_UVC_09944,RDRS_v2.1_P_P0_SFC;
```


