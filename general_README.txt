# ===========================================================================
# Copyright (C) 2016 IEEE SIGHT/HIC-Ottawa
# (https://github.com/IEEE-Humanitarian/general)
#
# The general folder has files related to IEEE's Humanitarian and Development
# Open Source repository, including licenses to use under IEEE's
# Open Source Humanitarian Engineering Licensing Protocol (OS-HELP).
#
# The contents of this file are subject to the terms of the Creative
# Commons BY-SA License, v. 4.0. If a copy of the CC BY-SA
# was not distributed with this folder contents, you can obtain one
# at http://creativecommons.org/licenses/by-sa/4.0/.
# ---------------------------------------------------------------------------
#  $Author: alfredo.herrera@ieee.org$
#  $Date: 11-February-2016$
#  $Name: alfredoh1234$
# ===========================================================================

Repository directory structure:  
a) All projects in repositiry shall have a directory structure as shown below.
b) Each directory shall have a text file describing its contents, named "<dir-name>_README.txt"
c) Directory structure represents activity area(s) for work/structure and may include:

[design]      only contains folders and design_README.txt
-> [bin]      executables, scripts, toolchain/CAD
-> [doc]      specifications, requirements, references
-> [1_model]  for example, octave files
-> [2_mech]   for example, FreeCAD, 3D printer (stl) files
-> [3_elechw] for example, Qucs files
-> [4_pcb]    for exmaple, KiCAD files
-> [5_sw-app] for exampel, C/C++, Java, PERL, Python files
-> [sys-int]  system bring-up, integration, verification 
-> [misc]     miscelaneous

[project] project files, budget, risk & issue record...
-> [legal] license files, license template(s), patent references, certification report, etc
-> [peer-review] release process, templates, reference files

# ===========================================================================
# Change History
# ---------------------------------------------------------------------------
#  $Revision: 0.1 $
#  $Log: Initial release$
#
# ===========================================================================