# Amber-99SB-DISP
Amber 99SB-DISP forcefield
---
## DESCRIPTION
This is a molecular dynamics force field for both folded and disordered protein states developped by Robustelli P. et al.

Files created for 'Interactions et mécanismes d'assemblage des protéines et des peptides' Team, I2BC CNRS UMR 9198.

## Installation

### Installation & usage from sources

1. Clone this repo `git clone https://github.com/jcarvaill/Amber-99SB-DISP` in your molecular dynamic simulation preparation directory.
2. To use this forcefield with tleap (AmberTools)
      `tleap -f leap/leaprc.ff14SB-disp.redq -I leap`
      
## Licence
This program is under the GNU GPLv3 licence, which means that anyone who 
distributes this code or a derivative work has to make the source available under 
the same terms, and also provides an express grant of patent rights from 
contributors to users.

## Citation
If you use our code for research, please cite this paper:
```text
@article{robustelli2018a99sb-disp,
  title={Developing a molecular dynamics force field for both folded and disordered protein states},
  author={Robustelli P., Piana S., Shaw DE.},
  journal={Proc Natl Acad Sci U S A.  DOI:10.1073/pnas.1800690115},
  year={2018}
}
```
