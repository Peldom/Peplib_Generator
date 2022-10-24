# Peplib Generator

![Team Poster](https://github.com/Peldom/Peplib_Generator/blob/main/README_Support/Poster_CSU_CHINA_v2.png)

--------------------------------------------------------------------------------
This is the work of team CSU_CHINA-iDEC:

![Team Logo](https://github.com/Peldom/Peplib_Generator/blob/main/README_Support/Teamlogo.png)

- The one model for peptide genesis
  
## [`Team wiki`](https://idec2021.github.io/CSU_CHINA/idec/home.html)

## [`iDEC wiki`](http://idec.io)

This program is also a team-competition work in ***International Directed Evolution Competition***(abbr. into ***iDEC***)

## Pre-Print

[Peplib Generator: In silico directed evolution and de novo generation for
peptide drug powered by AlphaFold2](https://arxiv.idec.io/article/000004/) || [Supplementary Data](https://arxiv.idec.io/pdf/a000004.01.pdf)  
Other work-related paper will be listed later

## Workflow

Due to job adjustment, our work has been modified and integrated into a new pipeline for high-throughput in silico generation and screening:

- Rif sampling: by [RifGen](https://github.com/LongxingCao/rifdock_v4.2)/our sampling scripts(unreleased yet)
- Scaffold generation: WeFold(unreleased yet)
- Scaffold filtering: Molpacker(unreleased yet)
- Sequence design: [FastDesign](https://www.rosettacommons.org/docs/latest/scripting_documentation/RosettaScripts/Movers/movers_pages/FastDesignMover)/**ProteinMPNN special edition** edited from [ProteinMPNN](https://github.com/dauparas/ProteinMPNN)
- Sequence Filtering: **AlphaFold2-turbo**(from **Peplib Generator** edited from [AlphaFold2](https://github.com/lucidrains/alphafold2), unreleased yet)

It takes 10-15 days to generate ideal 20k-100k sequences & structures.

## Hardware Dependencies

- Hardware(supported SLURM)
     * CPU: >=1000 * x86-64 cores; arm64 based is not supported
     * GPU: >=10 * NVIDIA® Tesla® P100 or higher, with 16GB+ VRAM
     * RAM: 15 GB each GPU core, 4GB each CPU core
     * ROM: 500GB or higher

