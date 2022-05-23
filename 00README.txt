
ADRV9361-z705 BSP README
========================

Please clone this git repo to <plx_project_base>/project-spec
  $> git clone --branch FOO_BAR git@github.com:jeremymc526/adrv9361-z7035-projspec.git

TODO - Can the FPGA code be a subgit of this repo?   Or does it belong somewhere else ? 

Double check that the kernel git tree is pointing to our internal mirror of the
Analog Devices git tree.

  $> cd ..
  $> petalinux-config

"Linux Components Selection" --> "linux-kernel (remote)"
"Remote linux-kernel settings -->" [git://github.com/zainar/linux_analogdev.git;protocol=https]
"Remote linux-kernel git TAG/Commit ID" --> adrv9361_2021_R1

Exit!

Continue building PetaLinux 2019.1 as normal.
  

