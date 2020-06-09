# Rosetta clips

Personal cheatsheet and quick copy-paste scripts for [Rosetta](https://rosettacommons.org/).

## Useful flags

Reference:

(1) Lemmon, G.; Meiler, J. RosettaLigand Docking with Flexible XML Protocols. Methods Mol Biol 2012, 819, 143–155. https://doi.org/10.1007/978-1-61779-465-0_10.

- Specifying database
    - \-in:path:database <path_to_rosetta_db>
- Input structures
    - \-in:file:s \<PDB1> \<PDB2> ...
    - \-in:file:list <pdbfiles_linedelimit.list>
- Ligand parameter files
    - \-in:file:extra_res_fa \<PARAM1> \<PARAM2> ...
    - \-in:file:extra_res_path \<dir_to_params_file>
- Process control
    - parser:protocol <xml_file>
    - packing: <ex1|ex2>
- Output control
    - \-out:nstruct <n>
    - \-out:path:all <path>