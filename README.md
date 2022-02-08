# midi2tab_Deconvolutions
Transcribing guitar tabs from MIDI input.

## Environment setup
create conda environment:
conda env create -f guitar_tab.yml

save conda environment, if you make changes (caution: remove os and cuda-related dependencies!):
conda env export -n guitar_tab -f guitar_tab.yml --no-builds

## Before you run
Create folder structure (todo, with python script)
Before running again, make sure folders are empty (reset with python script)

Run in the following order:
reset_files_structure.py (only the first time)
run_00_make_events.py
run_01_make_pianoroll_tab.py
run_01_make_random_pr_tab.py

train_*.py
make_*.py

