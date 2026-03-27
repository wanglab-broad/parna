
This code helps you scan the torsion parameters by QM calculations. You can also directly download our calculated parameters from Zenodo.

The `sugar_epsilon_zeta_angle.py` file used the pretrained AIMNET model to accelerate the QM calculations. You may have to download the pretrained model from.

Note: This part is computaionally heavy.

```bash
python chi_sugar_angle.py  --mol_name <residue_name> --file <mol.sdf>  --charge <charge>
# if the sugar pucker ring is locked, use `--constrain-sugar` option.
```


