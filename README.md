# SuperPAL

Data, Code and Model for the paper "[SuperPAL: Supervised Proposition ALignment for Multi-Document Summarization and Derivative Sub-Tasks](https://arxiv.org/abs/2009.00590)".

You can try [SuperPAL aligner demo](https://nlp.biu.ac.il/~ernstor1/SuperPAL_IU/) for a sense.

Predicted alignments of MultiNews and CNN/DailyMail train and val datasets can be found [here](https://drive.google.com/drive/folders/1JnRrdbENzBLpbae5ZIKmil1fuZhm2toc?usp=sharing).

To generate derived datasets (salience, clustering and generation) use:
```
  python createSubDatasets.py -alignments_path <ALIGNMENTS_PATH>  -out_dir_path <OUT_DIR_PATH>
```
