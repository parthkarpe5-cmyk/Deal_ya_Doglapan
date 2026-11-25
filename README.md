# Deal ya Doglapan?
  
The DSC x AWS Club workshop trains and evaluates classifiers on 1,000 simulated startup pitches. The notebook includes the data, preprocessing, training, held-out evaluation, and an interactive pitch dashboard.

## Run the workshop

On Windows, run `setup_workshop.bat` before class with internet access. Once it prints WORKSHOP READY, use `setup_workshop.bat --open` to open JupyterLab. In Colab, upload `Deal_ya_Doglapan_Workshop(1).ipynb` and run the cells in order. The CSV in `data/` is an inspectable copy of the embedded dataset.

## Dashboard

Open `site/index.html` directly for an offline demo. Stage 5 of the notebook generates `simulated_pitch_dashboard.html`. After retraining, copy the generated HTML to `site/index.html` to update the hosted version.

For Vercel, deploy the `main` branch with Root Directory `site`, Framework Preset **Other**, and no build command. This directory contains the static site entry point.
