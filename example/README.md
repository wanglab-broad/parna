# Example

This folder contains examples of how to use the `parna` package to model and parameterize RNA molecules. Each subfolder contains a specific example with its own README file that explains how to run the scripts and what the expected output is.

# The examples include:
- `00.generate_charge`: This example shows how to generate charges for non-canonical nucleotides.
- `01.extract_backbone`: This example demonstrates how to extract the backbone of an RNA molecule. This is for the cutomized modeling of chemically modified nucleotides based on a given RNA structure.
- `02.build_structure`: This example shows how to construct a customized oligonucleotide from a extracted backbone.
- `03.generate_fep_topology`: This example shows how to prepare the FEP simulations. This example requires `amberti` package.
- `04.parameterize`: This example shows how to parameterize a new nucleotide. We also provided the parameters of structures shown in the paper in the Zenodo repo. The output of parameterization is a `.yaml` file. 
- `05.modify_topology`: This example shows how to modify an Amber topology file based on a `.yaml` parameter file.