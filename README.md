
# Tutorial For Using WC ntuples

Created for the September 2024 MicroBooNE Analysis Workshop at the University of Minnesota, and updated for the October 2025 MicroBooNE Analysis workshop at the Illinois Institute of Technology.

## Getting Started

```
git clone https://github.com/leehagaman/wc_ntuple_tutorial
cd wc_ntuple_tutorial

# downloading an example 4.5 GB run 4c SURPRISE NC pi0 overlay file
# you can find more SURPRISE files here: https://docs.google.com/spreadsheets/d/1RUiX2M6zoob9R0YWPLummHzmX5UeLLEtS-7ZU-x2gA4/edit?gid=450838812#gid=450838812
kinit -f <YOUR_USERNAME>@FNAL.GOV
scp <YOUR_USERNAME>@uboonegpvm01.fnal.gov:/exp/uboone/data/uboonepro/MCC9.10/run4c_full_samples/wc_processed/BNB/checkout_MCC9.10_Run4c4d5_v10_04_07_13_BNB_NCpi0_overlay_surprise_reco2_hist_4c.root data
```

`tutorial.ipynb` walks through some examples and explanations about these root files.

## More Detailed Tutorial Including Data/MC Comparisons

This version of the tutorial focuses on SURPRISE files, including newer WC spacepoints and PMT information. These files are larger, so we only download one for this tutorial. For a more detailed previous tutorial which loads all file types and included higher-level outputs like efficiencies and histograms, see https://github.com/leehagaman/wc_ntuple_tutorial/tree/d9afd57988188bb9c64595765cbb42fe27169985

## More Documentation

Currently a work in progress: https://www.overleaf.com/project/67d87eaafc48747c1cc92b42
