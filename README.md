
# Tutorial For Using WC ntuples

Created for the September 2024 MicroBooNE Analysis Workshop at the University of Minnesota.

## Getting Started

```
git clone https://github.com/leehagaman/wc_ntuple_tutorial
cd wc_ntuple_tutorial
pip install requirements.txt # or install any imports that error with conda/pip
source run_1_download_script.sh YOUR_FNAL_USERNAME # needs a valid token from kinit first
```

`tutorial.ipynb` walks through some examples and explanations about these root files.

`tutorial_multiple_runs.ipynb` shows examples with runs 1-3, including correctly normalizing by POT. To use these, run `source runs_123_download_script.sh YOUR_FNAL_USERNAME`

