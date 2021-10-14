# Peplib Generator
![Team Poster](https://github.com/Peldom/Peplib_Generator/blob/main/README_Support/Poster_CSU_CHINA_v2.png)
--------------------------------------------------------------------------------
This is the work of team CSU_CHINA-iDEC:
![Team Logo](https://github.com/Peldom/Peplib_Generator/blob/main/README_Support/Teamlogo.png)
- The one model for peptide genesis
## [`Team wiki`](https://github.com/idec2021/CSU_CHINA)
*under development*   
Expected Available Date: 2021.10.01
## [`iDEC wiki`](http://idec.io)
This program is also a competition work in ***International Directed Evolution Competition***(abbr. into ***iDEC***)
## See you in Sept,2021! We are working on several models...
* representation module | *done*
* evolution module | *done*
* binding module | *developing*
* admet module | *developing*
## Workflow
Target Pocket -> RIF -> Motif -> Binder -> Optimized Binder
* Bidner -> Optimized Binder | *able with Peplib Generator*
* Motif -> Bidner | *developing*
* Target Pocket -> RIF -> Motif  | RifGen/RifDock
* Target Pocket -> Motif | *able with Peplib Generator*
## Dependencies
- [python](https://www.python.org/) v3.7.x
     * [NumPy](http://www.numpy.org/) v1.8 or higher
     * [SciPy](http://www.scipy.org/) v0.13 or higher
     * [nose](http://nose.readthedocs.io/en/latest/) v1.3.7 or higher
     * [pytorch](https://pytorch.org) v1.8 or higher
     * biopython forked version
     * [pyswarms(forked version)](https://github.com/Peldom/pyswarms)
     * [AlphaFold](https://github.com/deepmind/alphafold) v2.0
     * [AlphaFold_Advanced](AlphaFold2_advanced)
     * [PDBan](https://github.com/Maximato/PDBan)
- [CUDA](https://developer.nvidia.com/cuda-toolkit) v 11.2 or higher
- [masif](https://github.com/LPDI-EPFL/masif)
     * [msms](http://mgltools.scripps.edu/downloads)
     * [APBS-1.5-linux64](https://sourceforge.net/projects/apbs/files/apbs/apbs-1.5/)
     * [pdb2pqr-linux-bin64-2.1.1](https://github.com/Electrostatics/pdb2pqr)
     * [pymesh](https://github.com/PyMesh/PyMesh)
     * [tensorflow](https://github.com/tensorflow/tensorflow) v1.9
- C++ libraries 
     * [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page) v3.2 or higher
     * [PyBind11](https://github.com/pybind/pybind11)
- Data Source
     * [2020TIANCHI-ProteinSecondaryStructurePrediction-TOP1](https://github.com/wudejian789/2020TIANCHI-ProteinSecondaryStructurePrediction-TOP1)
     * [propedia](http://bioinfo.dcc.ufmg.br/propedia)
     * [pepbdb](http://huanglab.phys.hust.edu.cn/pepbdb/)
     * [peplife](https://webs.iiitd.edu.in/raghava/peplife/index.php)
     * [peptideatlas](http://www.peptideatlas.org/builds/)
     * [pdbbind](http://www.pdbbind-cn.org/download.php)
     * [THPdb](https://figshare.com/articles/dataset/THPdb_Database_of_FDA_Approved_Peptide_and_Protein_Therapeutics/5198005)
     * [KnotProt2.0](https://knotprot.cent.uw.edu.pl/browse/)
     * [Cybase](http://www.cybase.org.au/index.php)
     * [KNOTTIN database](https://www.dsimb.inserm.fr/KNOTTIN/index.php)
- Hardware(off-line)
     * CPU: x86-64; arm64 based is not supported
     * GPU: NVIDIA® Tesla® P100 or higher, with 16GB+ VRAM
     * RAM: 16 GB or higher
## Open source
Source will be available when paper is published(expected date: 2022.01~2022.06)
