
```bash

sequence_component_file=component.json
oligo_pdb_complex=oligo_without_protein.pdb
backbone_complex=backbone.lib
output_oligo_dir_complex=oligo_protein

python build_structure.py --sequence-components $sequence_component_file \
                             --oligo-pdb $oligo_pdb_complex \
                             --backbone $backbone_complex \
                             --output-dir $output_oligo_dir_complex
```

Please modify the data folder path such as `lib` in the script. To use a parameterized `lib`, please download the files from Zenodo deposite.
