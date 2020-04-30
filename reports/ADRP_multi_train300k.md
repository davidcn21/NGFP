# Comparing Testing MSE with baseline model


| target                  |       nfp |       cfp |
|--------------------------|-----------|-----------|
| avg top-200 score mean   | 7.86823   | 7.04068   |
| avg top-200 score recall | 0.0729545 | 0.0356818 |
| avg spearman corr.       | 0.331202  | 0.0556998 |

averages
target             | baseline test-loss (mse) | NFP test-loss (mse) |
|------------------|--------------------------|---------------------|
|ADRP_pocket1      | 0.42                     | 0.3608              |
|ADRP_pocket12     | 0.39                     | 0.3558              |
|ADRP_pocket13     | 0.57                     | 0.5267              |
|ADRP-ADPR_pocket1 | 0.69                     | 0.6180              |
|ADRP-ADPR_pocket5 | 0.31                     | 0.2624              |

### Notes
#### For reproducibility
`Namespace(batch_size=32, datafile='../dataset/covid19/xuefeng/ADRP_merged.csv', define_split    =None, delimiter=',', epochs=50, fp_method='nfp', lr=0.001, multiclass=True, output_dir='../ou    tput/', runs=3, sample=None, split_seed=7, target_name='ADRP', use_tqdm=False)`

#### Train-validation-test Split Signature
sha256: `195c6b92b450f6898ca21189ab937061ddbdcf52060131949358ef83d63e80c6`
