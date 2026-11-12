# ROSE-HEA

Supporting materials for the manuscript:

**Sample-efficient prediction of high-entropy alloy strength
through outcome-aware robust sequential learning**

## Currently available materials

The following archives contain saved numerical results,
analysis notebooks, figures, and tables:

- ROSE_HEA_Sections_5_1_5_2.rar:
  Main predictive comparison and sequential learning curves.

- ROSE_HEA_Section_5_3_Sample_Transfer.rar:
  Predictive value of ROSE-HEA-selected observations
  across conventional regressors.

- ROSE_HEA_Section_5_4_Design_Space.rar:
  Design-space coverage and regional prediction accuracy.

- ROSE_HEA_Section_5_5_Budget_Sensitivity.rar:
  Initial-size and sequential-budget sensitivity.

## How to use

Download and extract the entire archive. Open a terminal in
the extracted folder containing `requirements.txt`, then install
the dependencies:

```bash
python -m pip install -r requirements.txt
```

Open the supplied `.ipynb` file in Jupyter Notebook or JupyterLab
and run its cells from top to bottom. Keep the supplied data files
and folder structure unchanged so the notebook can locate its inputs.

## Implementation availability

The current packages regenerate analyses from saved results;
they do not rerun the model-training and sequential-acquisition
experiments.

The complete implementation is being prepared and will be
added to this repository.
