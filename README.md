# Interactive IDA Plugin List

This is a comprehensive list of plugins for [IDA Pro](https://hex-rays.com/products/ida-pro/) that is more _interactive_, that is, it can be sorted and filtered to help with finding plugins of interest. It also has extra metadata like the language the plugin is written in, when the plugin was last updated, and an attempt at putting plugins into categories.

The dynamic version is hosted on [GitHub Pages](https://vmallet.github.io/ida-plugins). Below you can still find a standard, static version of the list.

**[Go to interactive list](https://vmallet.github.io/ida-plugins)**

## Contribute!

Any contribution is welcome one way or another. If you know of a plugin that could be added, or data in the list that could be updated, missing categories, typos.. please send a PR! If you'd just prefer sending me a message or an email that's fine too, my email should be pretty easy to find on GitHub.

## Plugins (see [interactive version](https://vmallet.github.io/ida-plugins))
401 plugins
* [3DSX Loader](https://github.com/0xEBFE/3DSX-IDA-PRO-Loader): IDA PRO Loader for 3DSX files<br>
_Updated: 2021 12 26 &nbsp;&nbsp; Language: Python_

* [aarch64-sysreg-ida](https://github.com/TrungNguyen1909/aarch64-sysreg-ida): IDA plugin to show ARM MSRs nicely.<br>
_Updated: 2022 02 11 &nbsp;&nbsp; Language: Python_

* [abyss](https://github.com/patois/abyss): Postprocess Hexrays Decompiler Output<br>
_Updated: 2022 01 30 &nbsp;&nbsp; Language: Python_

* [ActionScript 3](https://github.com/KasperskyLab/ActionScript3): An ActionScript 3 processor module and Flash debugger plugin.<br>
_Updated: 2018 10 05 &nbsp;&nbsp; Language: Python_

* [Adobe Flash disassembler](https://hex-rays.com/contests/2009/SWF/ReadMe.txt): The 2 plugins present in this archive will enable IDA to parse SWF files, load all SWF tags as segments for fast search and retrieval, parse all tags that can potentially contain ActionScript2 code, discover all such code(a dedicated processor module has been written for it) and even name the event functions acording to event handled in it (eg. OnInitialize). [Download](https://hex-rays.com/contests/2009/SWF/swf.zip)<br>
_Language: C++_

* [alleycat](https://github.com/devttys0/ida/tree/master/plugins/alleycat): 
  *  Finds paths to a given code block inside a function
  *  Finds paths between two or more functions
  *  Generates interactive call graphs
  *  Fully scriptable<br>
_Updated: 2021 06 02 &nbsp;&nbsp; Language: Python_

* [AlphaGolang](https://github.com/SentineLabs/AlphaGolang): IDApython Scripts for Analyzing Golang Binaries.<br>
_Updated: 2022 05 17 &nbsp;&nbsp; Language: Python_

* [AMIE](https://github.com/NeatMonster/AMIE): A Minimalist Instruction Extender. AMIE is a Python rework of FRIEND that focuses solely on the ARM architecture (only AArch32 and AArch64 are supported). It is both lightweight and dependency-free, and provides the most relevant and up-to-date information about the ARM system registers and instructions.<br>
_Updated: 2019 10 27 &nbsp;&nbsp; Language: Python_

* [Amnesia](https://github.com/duo-labs/idapython): Amnesia is an IDAPython module designed to use byte level heuristics to find ARM thumb instructions in undefined bytes in an IDA Pro database. Currently, the heuristics in this module find code in a few different ways. Some instructions identify and define new code by looking for comon byte sequences that correspond to particular ARM opcodes. Other functions in this module define new functions based on sequences of defined instructions.<br>
_Updated: 2018 04 26 &nbsp;&nbsp; Language: Python_

* [Android/Linux vmlinux Loader](https://github.com/nforest/droidimg): vmlinux.py is a python script which can load vmlinux image in both IDA Pro<br>
_Updated: 2020 11 22 &nbsp;&nbsp; Language: Python_

* [Android Debugging](https://github.com/techbliss/ADB_Helper_QT_Super_version): This version have both support for native arm debugging via usb and sdk ADV manager.<br>
_Updated: 2015 04 05 &nbsp;&nbsp; Language: Python_

* [Android Scripts Collection](https://github.com/strazzere/android-scripts): Collection of Android reverse engineering scripts that make my life easier<br>
_Updated: 2020 05 03 &nbsp;&nbsp; Language: Python_

* [Andromeda-payload](https://github.com/0xEBFE/Andromeda-payload): IDAPython script for decryption payload of Andromeda malware.<br>
_Updated: 2013 03 30 &nbsp;&nbsp; Language: Python_

* [APIScout](https://github.com/danielplohmann/apiscout): This project aims at simplifying Windows API import recovery. As input, arbitrary memory dumps for a known environment can be processed (please note: a reference DB has to be built first, using apiscout/db_builder). The output is an ordered list of identified Windows API references with some meta information, and an ApiVector fingerprint. Includes a convenience GUI wrapper for use in IDA.<br>
_Updated: 2022 01 17 &nbsp;&nbsp; Language: Python_

* [AutoRE](https://github.com/a1ext/auto_re): Auto-renaming plugin with tagging support.<br>
_Updated: 2021 08 04 &nbsp;&nbsp; Language: Python_

* [Back 2 The Future](https://github.com/SafeBreach-Labs/Back2TheFuture): Find patterns of vulnerabilities on Windows in order to find 0-day and write exploits of 1-days. We use Microsoft security updates in order to find the patterns.<br>
_Updated: 2021 08 09 &nbsp;&nbsp; Language: Python_

* [bankswitch](https://github.com/patois/bankswitch): Nintendo Entertainment System (NES) bank switcher: plugin for NES ROMs, simulates bank switching/paging.<br>
_Updated: 2018 12 18 &nbsp;&nbsp; Language: C++_

* [BAP IDA Python](https://github.com/binaryanalysisplatform/bap-ida-python): Integrate BAP (Binary Analysis Platform) with IDA, providing functionality such as function info augmentation, taint propagation, BIR attribute tagging, and more.<br>
_Updated: 2020 02 12 &nbsp;&nbsp; Language: Python_

* [Beautify](https://github.com/P4nda0s/IDABeautify): An IDA plugin for making pseudocode better.<br>
_Updated: 2022 02 01 &nbsp;&nbsp; Language: Python_

* [BinAuthor](https://github.com/g4hsean/BinAuthor): Match an author to an unknown binary.<br>
_Updated: 2020 05 04 &nbsp;&nbsp; Language: Python_

* [BinCAT](https://github.com/airbus-seclab/bincat): BinCAT is a static Binary Code Analysis Toolkit, designed to help reverse engineers, directly from IDA.<br>
_Updated: 2022 05 11 &nbsp;&nbsp; Language: Python_

* [BinClone](https://github.com/BinSigma/BinClone): BinClone: detecting code clones in malware [SERE 2014]<br>
_Updated: 2015 04 04 &nbsp;&nbsp; Language: C++_

* [BinDiff](http://www.zynamics.com/bindiff.html): BinDiff by Zynamics (now Google) is a comparison tool for binary files, that assists vulnerability researchers and engineers to quickly find differences and similarities in disassembled code.<br>
_Updated: 2021 06 07_

* [BinExport](https://github.com/google/binexport): Export disassemblies into Protocol Buffers. BinExport is the exporter component of BinDiff. It is a plugin/extension for IDA that exports disassembly data into the Protocol Buffer format that BinDiff requires.<br>
_Updated: 2022 06 03 &nbsp;&nbsp; Language: C++_

* [Binkit](https://github.com/ohjeongwook/binkit/tree/master/src/plugin): Binkit Plugin For IDA. Use this plugin to load diffing result files (*.json)...<br>
_Updated: 2020 10 05 &nbsp;&nbsp; Language: Python_

* [BinNavi](https://github.com/google/binnavi): BinNavi is a binary analysis IDE - an environment that allows users to inspect, navigate, edit, and annotate control-flow-graphs of disassembled code, do the same for the callgraph of the executable, collect and combine execution traces, and generally keep track of analysis results among a group of analysts.<br>
_Updated: 2020 10 23_

* [Bin Sourcerer](https://github.com/BinSigma/BinSourcerer): BinSourcerer (a.k.a RE-Source Online) is an assembly to source code matching framework for binary auditing and malware analysis.<br>
_Updated: 2015 02 04 &nbsp;&nbsp; Language: Python_

* [Bip](https://github.com/synacktiv/bip): Bip is a project which aims to simplify the usage of python for interacting with IDA. Its main goals are to facilitate the usage of python in the interactive console of IDA and the writing of plugins.<br>
_Updated: 2020 09 09 &nbsp;&nbsp; Language: Python_

* [blc: Binary Lifting Contraption](https://github.com/cseagle/blc): Integrate Ghidra's decompiler as an Ida plugin.<br>
_Updated: 2022 05 22 &nbsp;&nbsp; Language: C++_

* [Bootroom Analysis Library](https://github.com/digitalbond/IBAL): IBAL is the IDA Pro Bootrom Analysis Library, which contains a number of useful functions for analyzing embedded ROMs.<br>
_Updated: 2015 02 12 &nbsp;&nbsp; Language: Python_

* [Bosch ME7](https://github.com/AndyWhittaker/IDAProBoschMe7x): Siemens Bosch ME7.x Disassembler Helper for IDA Pro<br>
_Updated: 2018 01 22 &nbsp;&nbsp; Language: C++_

* [BRUTAL IDA](https://github.com/tmr232/BRUTAL-IDA): Block Redo & Undo To Achieve Legacy IDA.<br>
_Updated: 2019 08 01 &nbsp;&nbsp; Language: Python_

* [Capa Explorer](https://github.com/fireeye/capa/tree/master/capa/ida/plugin): Capa explorer is an IDAPython plugin that integrates the FLARE team's open-source framework, capa, with IDA Pro. capa is a framework that uses a well-defined collection of rules to identify capabilities in a program.<br>
_Updated: 2022 06 06 &nbsp;&nbsp; Language: Python_

* [CGC Loader](https://github.com/cseagle/cgc_ldr): IDA Loader for DARPA CGC binaries.<br>
_Updated: 2018 04 09 &nbsp;&nbsp; Language: C++_

* [CGEN](https://github.com/yifanlu/cgen): CGEN with support for generating IDA Pro IDP modules.<br>
_Updated: 2015 12 28 &nbsp;&nbsp; Language: Scheme_

* [Class Informer](http://sourceforge.net/projects/classinformer/): Scans an MSVC 32bit target IDB for vftables with C++ RTTI, and MFC RTCI type data. Places structure defs, names, labels, and comments to make more sense of class vftables ("Virtual Function Table") and make them read easier as an aid to reverse engineering. Creates a list window with found vftables for browsing.<br>
_Updated: 2018 07 14 &nbsp;&nbsp; Language: C++_

* [Classy](https://github.com/RicBent/Classy): Helps users easily manage classes in IDA Pro. Vtables can be generated by selecting a range, functions can be assigned to classes, their signatures can be easily editing and mangled, IDA structs can be assigned, C headers can be generated, probably more.<br>
_Updated: 2022 02 04 &nbsp;&nbsp; Language: Python_

* [cmake-ida](https://github.com/Elemecca/cmake-ida): Build IDA Pro modules with CMake<br>
_Updated: 2018 01 02_

* [codatify](https://github.com/devttys0/ida/tree/master/plugins/codatify): 
  * Defines ASCII strings that IDA's auto analysis missed
  *  Defines functions/code that IDA's auto analysis missed
  *  Converts all undefined bytes in the data segment into DWORDs (thus allowing IDA to resolve function and jump table pointers)<br>
_Updated: 2021 06 02 &nbsp;&nbsp; Language: Python_

* [Codemap](https://github.com/c0demap/codemap): Codemap is a binary analysis tool for "run-trace visualization" provided as IDA plugin.<br>
_Updated: 2016 07 01 &nbsp;&nbsp; Language: Python_

* [collabREate](https://github.com/cseagle/collabREate): collabREate is a plugin for IDA Pro that is designed to provide a collaborative reverse engineering capability for multiple IDA users working on the same binary file.<br>
_Updated: 2021 09 01 &nbsp;&nbsp; Language: C++_

* [CollaRE](https://github.com/Martyx00/CollaRE): Multi-tool reverse engineering collaboration solution. CollareRE is a tool for collaborative reverse engineering that aims to allow teams that do need to use more then one tool during a project to collaborate without the need to share the files on a separate locations.<br>
_Updated: 2022 02 16 &nbsp;&nbsp; Language: Python_

* [COMFinder](https://github.com/howmp/comfinder): IDA plugin for COM.<br>
_Updated: 2020 04 08 &nbsp;&nbsp; Language: Python_

* [Comida](https://github.com/airbus-cert/comida): Comida is a plugin which searches all the references of the GUID COM object (Common Object Model) and deduce the associated type using the Hexrays plugin to improve the readability of the code.<br>
_Updated: 2020 05 13 &nbsp;&nbsp; Language: Python_

* [Condstanta](https://github.com/Accenture/Condstanta): Search for constant values that are used in conditional statements such as if and switch-case or for functions that contain multiple specific constants.<br>
_Updated: 2022 03 29 &nbsp;&nbsp; Language: Python_

* [Continuum](https://github.com/zyantific/continuum): Continuum is an IDA Pro plugin adding multi-binary project support, allowing fast navigation in applications involving many shared libraries.<br>
_Updated: 2016 09 13 &nbsp;&nbsp; Language: Python_

* [Cortex M Firmware](https://github.com/duo-labs/idapython): The Cortex M Firmware module grooms an IDA Pro database containing firmware from an ARM Cortex M microcontroller. This module will annotate the firmware vector table, which contains a number of function pointers. This vector table annotation will cause IDA Pro to perform auto analysis against the functions these pointers point to.<br>
_Updated: 2018 04 26 &nbsp;&nbsp; Language: Python_

* [CrowdDetox](https://github.com/CrowdStrike/CrowdDetox): The CrowdDetox plugin for Hex-Rays automatically removes junk code and variables from Hex-Rays function decompilations.<br>
_Updated: 2021 05 03 &nbsp;&nbsp; Language: C++_

* [CTO: Call Tree Overviewer](https://github.com/herosi/CTO): IDA plugin for creating a simple and efficient function call tree graph. It can also summarize function information such as internal function calls, API calls, static linked library function calls, unresolved indirect function calls, string references, structure member accesses, specific comments.<br>
_Updated: 2021 12 24 &nbsp;&nbsp; Language: Python_

* [D-810](https://github.com/joydo/d810): D-810 is an IDA Pro plugin which can be used to deobfuscate code at decompilation time by modifying IDA Pro microcode.<br>
_Updated: 2021 02 25 &nbsp;&nbsp; Language: Python_

* [Dalvik Header](https://github.com/strazzere/dalvik-header-plugin): This is a simple Dalvik header plugin for IDA Pro<br>
_Updated: 2013 01 22 &nbsp;&nbsp; Language: C++_

* [Data Xref Counter](https://github.com/onethawt/idapyscripts): Enumerates all of the the x-references in a specific segment and counts the frequency of usage. The plugin displays the data in QtTableWidget and lets the user filter and sort the references. You can also export the data to a CSV file.<br>
_Updated: 2015 09 17 &nbsp;&nbsp; Language: Python_

* [DBGHider](https://github.com/iweizime/DBGHider): An IDA plugin aims to hide debugger from processes (Windows).<br>
_Updated: 2018 06 19 &nbsp;&nbsp; Language: Python_

* [DebugAutoPatch](https://github.com/scottmudge/debugautopatch): Patching system improvement plugin for IDA.<br>
_Updated: 2019 09 06 &nbsp;&nbsp; Language: Python_

* [Debugger](https://github.com/cseagle/sk3wldbg): Debugger plugin for IDA Pro backed by the Unicorn Engine<br>
_Updated: 2021 07 26 &nbsp;&nbsp; Language: C++_

* [dec2struct](https://github.com/krystalgamer/dec2struct): Easily setup vtables in IDA using declaration files.<br>
_Updated: 2017 09 06 &nbsp;&nbsp; Language: Python_

* [deREferencing](https://github.com/danigargu/deREferencing): IDA Pro plugin that implements more user-friendly register and stack views.<br>
_Updated: 2021 05 05 &nbsp;&nbsp; Language: Python_

* [Describe Key](https://github.com/vmallet/ida-describekey): Quickly learn what a shortcut does. Describe Key is a very simple IDA Pro plugin: invoke it, press a shortcut, and instantly see what actions are associated with the shortcut. Quick and easy, call it from anywhere in IDA.<br>
_Updated: 2022 04 08 &nbsp;&nbsp; Language: Python_

* [Diaphora](https://github.com/joxeankoret/diaphora): Diaphora (διαφορά, Greek for 'difference') is a program diffing plugin for IDA Pro, similar to Zynamics Bindiff or the FOSS counterparts DarunGrim, TurboDiff, etc... It was released during SyScan 2015.<br>
_Updated: 2021 12 17 &nbsp;&nbsp; Language: Python_

* [Docker IDA](https://github.com/intezer/docker-ida): Run IDA Pro disassembler in Docker containers for automating, scaling and distributing the use of IDAPython scripts.<br>
_Updated: 2017 11 19 &nbsp;&nbsp; Language: Python_

* [dotNIET](https://github.com/synacktiv/dotNIET): Import missing symbols (usually few thousands) which are resolved at runtime by .NET Native compiled binaries. These symbols lie in SharedLibrary.dll and are not exported by this one.<br>
_Updated: 2021 06 30 &nbsp;&nbsp; Language: Python_

* [DOXBox Debugger](https://github.com/wjp/idados): Eric Fry's IDA/DOSBox debugger plugin<br>
_Updated: 2016 02 28 &nbsp;&nbsp; Language: C++_

* [dp701](https://github.com/pr701/dp701): Dark theme for IDA Pro.<br>
_Updated: 2021 09 22_

* [DrGadget](https://github.com/patois/DrGadget): This is an IDAPython plugin for the Interactive Disassembler for all your ROP experimentation needs.<br>
_Updated: 2017 02 02 &nbsp;&nbsp; Language: Python_

* [DriverBuddy](https://github.com/nccgroup/DriverBuddy): DriverBuddy is an IDA Python script to assist with the reverse engineering of Windows kernel drivers.<br>
_Updated: 2018 11 22 &nbsp;&nbsp; Language: Python_

* [DriverBuddyReloaded](https://github.com/VoidSec/DriverBuddyReloaded): Driver Buddy Reloaded is an IDA Pro Python plugin that helps automate some tedious Windows Kernel Drivers reverse engineering tasks.<br>
_Updated: 2022 06 08 &nbsp;&nbsp; Language: Python_

* [Drop](https://github.com/Riscure/DROP-IDA-plugin): An experimental IDA Pro plugin capable of detecting several types of opaque predicates in obfuscated binaries. It leverages the power of the symbolic execution engine angr and its components to reason about the opaqueness of predicates based on their symbolic context.<br>
_Updated: 2017 12 22 &nbsp;&nbsp; Language: Python_

* [dsync](https://github.com/patois/dsync): IDAPython plugin that synchronizes decompiled and disassembled code views.<br>
_Updated: 2021 01 20 &nbsp;&nbsp; Language: Python_

* [dumpDyn](https://github.com/secrary/IDA-scripts/tree/master/dumpDyn): Script which saves comments, names, breakpoints, functions from one execution to another, f a process allocates a dynamic memory using VirtualAlloc, HeapAlloc, new, etc. and continues execution from that address.<br>
_Updated: 2019 02 26 &nbsp;&nbsp; Language: Python_

* [dwarfexport](https://github.com/ALSchwalm/dwarfexport): dwarfexport is an IDA Pro plugin that allows the user to export dwarf debug information. This can then be imported in to gdb and other tools, allowing you to debug using info you have recovered in IDA even when you cannot connect the IDA debugger.<br>
_Updated: 2020 11 18 &nbsp;&nbsp; Language: C++_

* [DWARF Plugin](https://github.com/vrasneur/idadwarf): IDADWARF is an IDA plugin that imports DWARF debugging symbols into an IDA database. [Download](https://hex-rays.com/contests/2009/IDADwarf-0.2/idadwarf-0.2.zip)<br>
_Updated: 2009 11 15 &nbsp;&nbsp; Language: C++_

* [Dynamic Data Resolver](https://github.com/Cisco-Talos/DynDataResolver): A plugin for IDA that aims to make the reverse-engineering of malware easier. Features: Code Flow Trace, Searchable API call logging, Searchable string logging, Resolving dynamic values and auto-commenting.<br>
_Updated: 2020 12 17 &nbsp;&nbsp; Language: Python_

* [Dynamic IDA Enrichment](https://github.com/ynvb/DIE): DIE is an IDA python plugin designed to enrich IDA`s static analysis with dynamic data. This is done using the IDA Debugger API, by placing breakpoints in key locations and saving the current system context once those breakpoints are hit.<br>
_Updated: 2021 05 13 &nbsp;&nbsp; Language: Python_

* [Dynlib](https://github.com/aerosoul94/dynlib): This is an IDA Pro plugin to aid in reverse engineering PS4 user mode elf's by loading the PS4 specific DYNLIBDATA segment.<br>
_Updated: 2017 12 16 &nbsp;&nbsp; Language: C++_

* [EFI Scripts (efitools)](https://github.com/danse-macabre/ida-efitools): Some IDA scripts and tools to assist with reverse engineering EFI executables.<br>
_Updated: 2015 07 13 &nbsp;&nbsp; Language: Python_

* [EFI Scripts (efitools2)](https://github.com/p-state/ida-efitools2): Plugin for extending UEFI reverse engineering capabilities. Based on ida-efitools (EFI Scripts) with a bunch of fixes and new features.<br>
_Updated: 2020 10 19 &nbsp;&nbsp; Language: Python_

* [EFI Scripts (efiutils)](https://github.com/snare/ida-efiutils): Some IDA scripts to assist with reverse engineering EFI executables.<br>
_Updated: 2014 06 17 &nbsp;&nbsp; Language: Python_

* [EFI Swiss Knife](https://github.com/gdbinit/EFISwissKnife): An IDA plugin to improve (U)EFI reversing.<br>
_Updated: 2017 06 13 &nbsp;&nbsp; Language: C++_

* [efiXplorer](https://github.com/binarly-io/efiXplorer): IDA plugin for UEFI firmware analysis and reverse engineering automation.<br>
_Updated: 2022 06 08 &nbsp;&nbsp; Language: C++_

* [epanos](https://github.com/drvink/epanos): ElectroPaint Automatic No-source Object reaSsembler (a MIPS to C decompiler). This is a very dumb MIPS to C static translator.<br>
_Updated: 2014 05 05 &nbsp;&nbsp; Language: Python_

* [EtherAnnotate](https://github.com/inositle/etherannotate_ida): Parses the specialized instruction trace files that are generated using the EtherAnnotate Xen modification (http://github.com/inositle/etherannotate_xen).  From the instruction trace, register values and code coverage of the run-time information are visualized in IDA Pro through instruction comments and line colorations.<br>
_Updated: 2010 05 04 &nbsp;&nbsp; Language: C++_

* [EtherAnnotate IDA Plugin](https://github.com/jeads-sec/etherannotate_ida): Parse EtherAnnotate trace files and markup IDA disassemblies with runtime values.<br>
_Updated: 2010 05 04 &nbsp;&nbsp; Language: Python_

* [etm_displayer](https://github.com/honeybadger1613/etm_displayer): Display the result of perf Coresight ETM tracing.<br>
_Updated: 2018 09 04 &nbsp;&nbsp; Language: Python_

* [Exports+](https://github.com/ax330d/exports-plus): View Exports. The problem is that IDA for some reason sometimes does not show certain names in Exports or does not demangle them. This plugin fixes this problem.<br>
_Updated: 2018 09 21 &nbsp;&nbsp; Language: Python_

* [Extract Macho-O](https://github.com/gdbinit/ExtractMachO): This is a very simple IDA plugin to extract all Mach-O binaries contained anywhere in the disassembly.<br>
_Updated: 2019 05 09 &nbsp;&nbsp; Language: C++_

* [FA](https://github.com/doronz88/fa): FA stands for Firmware Analysis and intended For Humans. FA allows one to easily perform code exploration, symbol searching and other functionality with ease.<br>
_Updated: 2022 04 26 &nbsp;&nbsp; Language: Python_

* [FCatalog](https://github.com/xorpd/fcatalog_client): FCatalog (The functions catalog) is a mechanism for finding similarities between different binary blobs in an efficient manner. It is mostly useful for identifying a new binary blob is somewhat similar to a binary blob that have been encountered before. The client side of FCatalog is an IDA plugin that allows a group of reverse engineers to manage a pool of reversed functions. Whenever a new binary function is encountered, FCatalog can compare it to all the known and previously reversed binary functions.<br>
_Updated: 2016 08 19 &nbsp;&nbsp; Language: Python_

* [Fentanyl](https://github.com/osirislab/Fentanyl): DAPython script that makes patching significantly easier.<br>
_Updated: 2015 10 02 &nbsp;&nbsp; Language: Python_

* [FindCrypt2](https://hex-rays.com/blog/findcrypt2/): Search for constants known to be associated with cryptographic algorithms.<br>
_Updated: 2006 01 30 &nbsp;&nbsp; Language: C++_

* [Findcrypt-yara](https://github.com/polymorf/findcrypt-yara): IDA pro plugin to find crypto constants (and more)<br>
_Updated: 2022 01 05 &nbsp;&nbsp; Language: Python_

* [FindFunc](https://github.com/FelixBer/FindFunc): Advanced Filtering/Finding of Functions. FindFunc is an IDA PRO plugin to find code functions that contain a certain assembly or byte pattern, reference a certain name or string, or conform to various other constraints.<br>
_Updated: 2022 05 10 &nbsp;&nbsp; Language: Python_

* [findrpc](https://github.com/lucasg/findrpc): Ida script to extract RPC interface from binaries.<br>
_Updated: 2022 01 25 &nbsp;&nbsp; Language: Python_

* [FindYara](https://github.com/OALabs/findyara-ida): IDA python plugin to scan binary with Yara rules.<br>
_Updated: 2021 12 28 &nbsp;&nbsp; Language: Python_

* [FingerMatch](https://github.com/jendabenda/fingermatch): IDA plugin for collecting functions, data, types and comments from analysed binaries and fuzzy matching them in another binaries.<br>
_Updated: 2020 12 30 &nbsp;&nbsp; Language: Python_

* [FIRST](https://github.com/Cisco-Talos/FIRST-plugin-ida): Function Identification and Recovery Signature Tool (FIRST) is a plugin for IDA Pro that allows users to automatically search for and apply function metadata (the function name, parameter names, parameter types, comments, etc.) submitted from different IDBs / users. This functionality is similar to IDA's Lumina feature, which was introduced in IDA 7.2, although with FIRST the function metadata server address is configurable and the FIRST server code is open source, which means the user can set up a private metadata server for internal use if desired. A community database is also maintained by Cisco Talos and available to use free-of-charge. FIRST supports IDA 6.9 SP1 and above.<br>
_Updated: 2020 01 31 &nbsp;&nbsp; Language: Python_

* [flare-emu](https://github.com/fireeye/flare-emu): flare-emu marries a supported binary analysis framework, such as IDA Pro or Radare2, with Unicorn’s emulation framework to provide the user with an easy to use and flexible interface for scripting emulation tasks. It is designed to handle all the housekeeping of setting up a flexible and robust emulator for its supported architectures so that you can focus on solving your code analysis problems. Currently, flare-emu supports the x86, x86_64, ARM, and ARM64 architectures.<br>
_Updated: 2021 04 19 &nbsp;&nbsp; Language: Python_

* [FLARE IDA Decompiler Library (FIDL)](https://github.com/fireeye/FIDL): A sane API for IDA Pro's decompiler.<br>
_Updated: 2022 02 08 &nbsp;&nbsp; Language: Python_

* [FLARE Plugins](https://github.com/mandiant/flare-ida): FLARE Team Reversing Repository plugin collection: Shellcode Hashes, Struct Typer, StackStrings, MSDN Annotations, ApplyCalleeType, idb2pat, argtracker, objc2_analyzer, ironstrings, Code Grafter<br>
_Updated: 2022 05 16 &nbsp;&nbsp; Language: Python_

* [FLIRTDB](https://github.com/Maktm/FLIRTDB): A community driven collection of IDA FLIRT signature files.<br>
_Updated: 2020 05 23_

* [FLS Loader](https://github.com/rpw/flsloader): IDA Pro loader module for IFX iPhone baseband firmwares. Based on a universal scatter loader script by roxfan.<br>
_Updated: 2012 04 19 &nbsp;&nbsp; Language: Python_

* [Fluorescence](https://github.com/devttys0/ida/tree/master/plugins/fluorescence): Un/highlights function call instructions<br>
_Updated: 2021 06 02 &nbsp;&nbsp; Language: Python_

* [FRAPL](https://github.com/FriedAppleTeam/FRAPL): FRAPL is a reverse engineering framework created to simplify dynamic instrumentation with Frida.<br>
_Updated: 2016 12 26 &nbsp;&nbsp; Language: Python_

* [Free the debuggers](https://github.com/techbliss/Free_the_Debuggers): Free the ida pro debuggers for all files.<br>
_Updated: 2015 02 07 &nbsp;&nbsp; Language: Python_

* [Frida](https://github.com/techbliss/Frida_For_Ida_Pro): This is plugin for ida pro thar uses the Frida api. Mainly trace functions.<br>
_Updated: 2015 04 05 &nbsp;&nbsp; Language: Python_

* [FRIEND](https://github.com/alexhude/FRIEND): Flexible Register/Instruction Extender aNd Documentation. FRIEND is an IDA plugin created to improve disassembly and bring register/instruction documentation right into IDA View. (see also: AMIE)<br>
_Updated: 2021 07 26 &nbsp;&nbsp; Language: C++_

* [Fugue FDB IDB exporter](https://github.com/fugue-re/fugue-idapro): Fugue database importer and exporter for IDA Pro.<br>
_Updated: 2022 02 14 &nbsp;&nbsp; Language: C++_

* [Funcap](https://github.com/deresz/funcap): This script records function calls (and returns) across an executable using IDA debugger API, along with all the arguments passed. It dumps the info to a text file, and also inserts it into IDA's inline comments. This way, static analysis that usually follows the behavioral runtime analysis when analyzing malware, can be directly fed with runtime info such as decrypted strings returned in function's arguments.<br>
_Updated: 2016 03 04 &nbsp;&nbsp; Language: Python_

* [FuncScanner](https://github.com/patois/FuncScanner): Collects extended function properties from IDA Pro databases. This is especially useful in reverse engineering code that comes with no or little symbolic information, as is often the case with embedded firmware.<br>
_Updated: 2020 12 06 &nbsp;&nbsp; Language: Python_

* [FunctionInliner](https://github.com/cellebrite-labs/FunctionInliner): An IDA plugin that eases reversing of binaries that have been code-size-optimized with function outlining.<br>
_Updated: 2022 05 09 &nbsp;&nbsp; Language: Python_

* [Functions+](https://github.com/ax330d/functions-plus): IDA Pro plugin to make functions tree view. Plugin parses function names and groups them by namespaces.<br>
_Updated: 2021 04 17 &nbsp;&nbsp; Language: Python_

* [Function Tagger](https://github.com/alessandrogario/IDA-Function-Tagger): This IDAPython script tags subroutines according to their use of imported functions<br>
_Updated: 2021 05 26 &nbsp;&nbsp; Language: Python_

* [Gamecube DSP](https://github.com/dolphin-emu/gcdsp-ida): This project adds support for the DSP present in the Gamecube and the Wii to IDA, the Interactive Disassembler [1]. This allows easy analyze of a DSP ucode, handling cross-references, control flow, and so on.<br>
_Updated: 2014 12 13 &nbsp;&nbsp; Language: Python_

* [Gamecube Extension](https://github.com/hyperiris/gekkoPS): This is a Gekko CPU Paired Single extension instructions plug-in for IDA Pro 5.2<br>
_Updated: 2018 04 25 &nbsp;&nbsp; Language: C++_

* [GandCrab String Decryptor](https://github.com/lacike/gandcrab_string_decryptor): IDC script for decrypting strings in the GandCrab v5.1-5.3<br>
_Updated: 2019 04 24 &nbsp;&nbsp; Language: idc_

* [garmin-ida-loader](https://sourceforge.net/projects/garminidaloader/): IDA loader for Garmin firmwares.<br>
_Updated: 2013 05 30 &nbsp;&nbsp; Language: C++_

* [gdbida](https://github.com/comsecuris/gdbida): A visual bridge between a GDB session and IDA Pro's disassembler<br>
_Updated: 2018 04 23 &nbsp;&nbsp; Language: Python_

* [genmc](https://github.com/patois/genmc): Genmc is an IDAPython script/plugin hybrid that displays Hexrays decompiler microcode, which can help in developing microcode plugins.<br>
_Updated: 2021 01 15 &nbsp;&nbsp; Language: Python_

* [genpatch](https://github.com/tkmru/genpatch): Plugin that generates a python script for patching binary from Patched Byte on IDA.<br>
_Updated: 2019 05 04 &nbsp;&nbsp; Language: Python_

* [Geolocator](https://github.com/techbliss/ida_pro_http_ip_geolocator): Lookup (geolocate) IP's and http/https addresses, using google maps, and MaxMind databases.<br>
_Updated: 2019 03 10 &nbsp;&nbsp; Language: Python_

* [GhIDA](https://github.com/Cisco-Talos/GhIDA): GhIDA is an IDA Pro plugin that integrates the Ghidra decompiler in IDA.<br>
_Updated: 2020 12 16 &nbsp;&nbsp; Language: Python_

* [GhidraDec](https://github.com/GregoryMorse/GhidraDec): Ghidra Decompiler Plugin for IDA Pro.<br>
_Updated: 2022 03 15 &nbsp;&nbsp; Language: C++_

* [golang_loader_assist](https://github.com/strazzere/golang_loader_assist): Making GO reversing easier in IDA Pro.<br>
_Updated: 2020 06 22 &nbsp;&nbsp; Language: Python_

* [golang_struct_builder](https://github.com/spigwitmer/golang_struct_builder): Script that auto-generates structs and interfaces from runtime metadata found in golang binaries.<br>
_Updated: 2021 08 22 &nbsp;&nbsp; Language: Python_

* [go_parser](https://github.com/0xjiayu/go_parser): Yet Another Golang binary parser for IDAPro. Inspired by golang_loader_assist and jeb-golang-analyzer, I wrote a more complete Go binaries parsing tool for IDAPro.<br>
_Updated: 2021 07 29 &nbsp;&nbsp; Language: Python_

* [grap](https://github.com/QuoSecGmbH/grap): Define and match graph patterns within binaries. grap takes patterns and binary files, uses a Casptone-based disassembler to obtain the control flow graphs from the binaries, then matches the patterns against them.<br>
_Updated: 2022 05 05 &nbsp;&nbsp; Language: Python_

* [GraphGrabber](https://github.com/tmr232/GraphGrabber): Grab full-resolution images of IDA graphs.<br>
_Updated: 2017 11 20 &nbsp;&nbsp; Language: Python_

* [Graph Slick](https://github.com/lallousx86/GraphSlick): Automated detection of inlined functions. It highlights similar groups of nodes and allows you to group them, simplifying complex functions. The authors provide an accompanying presentation which explains the algorithms behind the plugin and shows sample use cases.<br>
_Updated: 2014 11 20 &nbsp;&nbsp; Language: C++_

* [GUID-Finder](https://github.com/nihilus/guid-finder): Find GUID/UUIDs. The COM side of RE'ing (at least with "dead listing") can be pretty elusive. With this you can at least partially glean what interfaces and classes a target is using.<br>
_Updated: 2016 01 24 &nbsp;&nbsp; Language: Python_

* [HashDB IDA](https://github.com/OALabs/hashdb-ida): Malware string hash lookup plugin for IDA Pro. This plugin connects to the OALABS HashDB Lookup Service.<br>
_Updated: 2022 03 17 &nbsp;&nbsp; Language: Python_

* [HeapViewer](https://github.com/danigargu/heap-viewer): An IDA Pro plugin to examine the heap, focused on exploit development.<br>
_Updated: 2021 07 13 &nbsp;&nbsp; Language: Python_

* [HexCopy](https://github.com/OALabs/hexcopy-ida): IDA plugin for quickly copying disassembly as encoded hex bytes.<br>
_Updated: 2021 10 11 &nbsp;&nbsp; Language: Python_

* [HexExt](https://github.com/chrisps/Hexext): Improve the output of the hexrays decompiler through microcode manipulation.<br>
_Updated: 2019 08 04 &nbsp;&nbsp; Language: C++_

* [Hex-Rays Block Highlighter](https://github.com/vmallet/ida-hex-highlighter): Highlight code blocks in the Hex-Rays decompiler output. In some cases the decompilation output can be quite hairy with lots of nested blocks and it can be hard to follow where one ends and the other begins. This plugin will highlight blocks in a sticky way, allowing one to navigate within the window while keeping the block highlight around.<br>
_Updated: 2022 04 17 &nbsp;&nbsp; Language: Python_

* [HexRays CodeXplorer](https://github.com/REhints/HexRaysCodeXplorer): The Hex-Rays Decompiler plugin for better code navigation in RE process. CodeXplorer automates code REconstruction of C++ applications or modern malware like Stuxnet, Flame, Equation, Animal Farm ...<br>
_Updated: 2022 03 09 &nbsp;&nbsp; Language: C++_

* [HexRaysDeob](https://github.com/RolfRolles/HexRaysDeob): A Hex-Rays microcode API plugin breaking an obfuscating compiler used to create an in-the-wild malware family. The plugin is fully automatic and requires no user intervention; upon installation, the decompilation listings presented to the user will be free of obfuscation.<br>
_Updated: 2019 08 27 &nbsp;&nbsp; Language: C++_

* [HexRaysPyTools](https://github.com/igogo-x86/HexRaysPyTools): Plugin assists in creation classes/structures and detection virtual tables. Best to use with Class Informer plugin, because it helps to automatically get original classes names.<br>
_Updated: 2020 02 15 &nbsp;&nbsp; Language: Python_

* [hexrays_scripts](https://github.com/patois/hexrays_scripts): Various scripts for the Hexrays decompiler (kloppy, shuffle, arachno, IDA coffee, screenrecorder, ricky).<br>
_Updated: 2022 04 07 &nbsp;&nbsp; Language: Python_

* [Hexrays Toolbox](https://github.com/patois/HexraysToolbox): Find code patterns within the Hexrays AST<br>
_Updated: 2021 11 05 &nbsp;&nbsp; Language: Python_

* [HexRays Tools](https://github.com/nihilus/hexrays_tools): 
  * Assist in creation of new structure definitions / virtual calls detection
  * Jump directly to virtual function or structure member definition
  * Gives list of structures with given size, with given offset
  * Finds structures with same "shape" as is used.
  * convert function to __usercall or __userpurge
  * and more....<br>
_Updated: 2016 01 26 &nbsp;&nbsp; Language: Python_

* [hexviewjump](https://github.com/anic/hexviewjump): IDA 7.0 plugins that helps to jump at hexview and extends JumpAsk expression.<br>
_Updated: 2019 02 27 &nbsp;&nbsp; Language: Python_

* [HightLight](https://github.com/RevSpBird/HightLight): A plugin for ida of version 7.2 to help know F5 window codes better.<br>
_Updated: 2019 08 26 &nbsp;&nbsp; Language: C++_

* [HRDEV](https://github.com/ax330d/hrdev): This is an IDA Pro Python plugin to make Hex-Rays Decompiler output bit more attractive. HRDEV plugin retrieves standard decompiler output, parses it with Python Clang bindings, does some magic, and puts back.<br>
_Updated: 2018 09 21 &nbsp;&nbsp; Language: Python_

* [HrDevHelper](https://github.com/patois/HRDevHelper): HexRays decompiler plugin that visualizes the ctree of decompiled functions using IDA's graph engine.<br>
_Updated: 2021 11 04 &nbsp;&nbsp; Language: Python_

* [Hyara](https://github.com/hyuunnn/Hyara): A plugin to create pattern-matching rules. It helps creating rules for the YARA pattern-matching tool direcly in IDA. It includes a simple detection of relocatable bytes in x86 opcodes for improved matching. It also provides a checker feature for testing the rules on the loaded binary.<br>
_Updated: 2021 11 01 &nbsp;&nbsp; Language: Python_

* [IBT](https://github.com/pwnslinger/IBT): IDA Pro Back Tracer - Initial project toward automatic customized protocols structure extraction.<br>
_Updated: 2017 05 01 &nbsp;&nbsp; Language: Python_

* [IDA2Obj](https://github.com/jhftss/IDA2Obj): IDA2Obj is a tool to implement SBI (Static Binary Instrumentation).<br>
_Updated: 2021 09 24 &nbsp;&nbsp; Language: Python_

* [ida2pwntools](https://github.com/anic/ida2pwntools): IDA 7.0 plugins that helps to attach process created by pwntools and debug pwn.<br>
_Updated: 2019 02 27 &nbsp;&nbsp; Language: Python_

* [IDA2SQL](https://github.com/zynamics/ida2sql-plugin-ida): As the name implies this plugin can be used to export information from IDA databases to SQL databases. This allows for further analysis of the collected data: statistical analysis, building graphs, finding similarities between programs, etc.<br>
_Updated: 2012 01 10 &nbsp;&nbsp; Language: Python_

* [IDA 7.x VS2017 Sample Project](https://github.com/patois/ida_vs2017): This is a sample Visual Studio 2017 (Community Edition) project for IDA 7.x plugins on Windows.<br>
_Updated: 2018 05 10 &nbsp;&nbsp; Language: C++_

* [IDA7-SegmentSelect](https://github.com/rcx/IDA7-SegmentSelect): IDA-SegmentSelect library by sirmabus, ported to IDA 7: A memory segment dialog to allow user to select one or more for processing.<br>
_Updated: 2018 01 08 &nbsp;&nbsp; Language: C++_

* [ida-arm-system-highlight](https://github.com/gdelugre/ida-arm-system-highlight): This script will give you the list of ARM system instructions used in your IDA database. This is useful for locating specific low-level pieces of code (setting up the MMU, caches, fault handlers, etc.).<br>
_Updated: 2021 09 28 &nbsp;&nbsp; Language: Python_

* [IDA Autoruns](https://github.com/tmr232/ida-autoruns): IDA-Autoruns is a simple plugin to make a script run automatically every time you open a specific IDB.<br>
_Updated: 2016 02 21 &nbsp;&nbsp; Language: Python_

* [IDA Batch Decompile](https://github.com/tintinweb/ida-batch_decompile): Batch decompile multiple files and their imports with additional annotations (xref, stack var size) to a pseudocode .c file.<br>
_Updated: 2018 07 12 &nbsp;&nbsp; Language: Python_

* [ida bitfields](https://github.com/JustasMasiulis/ida_bitfields): A simple IDA Pro plugin to make bitfields and bitflags in them easier to reason about.<br>
_Updated: 2022 04 24 &nbsp;&nbsp; Language: C++_

* [IDA BPF Processor](https://github.com/bnbdr/ida-bpf-processor): BPF Bytecode Processor for IDA (python). Supports the old BPF bytecode only (no eBPF).<br>
_Updated: 2018 08 27 &nbsp;&nbsp; Language: Python_

* [IDABuddy](https://github.com/tmr232/IDABuddy): IDABuddy is a reverse-engineer's best friend. Designed to be everything Clippy the Office Assistant was, and more!<br>
_Updated: 2017 09 17 &nbsp;&nbsp; Language: Python_

* [IDA C#](https://blog.karatos.in/a?ID=01000-69f2f124-560e-47a5-bb0c-93052d9763af): Scripting IDA with C#, download [here](https://files.cnblogs.com/nnhy/IDACSharp_20100605143116.rar). (All in Chinese).<br>
_Updated: 2010 06 05_

* [IDA cLEMENCy Tools](https://github.com/cseagle/ida_clemency): Tools to work with the cLEMENCy architecture developed by LegitBS for use during the Defcon 25 Capture the Flag event.<br>
_Updated: 2017 07 31 &nbsp;&nbsp; Language: Python_

* [ida-climacros](https://github.com/0xeb/ida-climacros): `ida-climacros` is a productivity plugin that allows you to define macros that will be expanded when interfacing with IDA's command line interpreter (in the output window).<br>
_Updated: 2021 01 05 &nbsp;&nbsp; Language: C++_

* [ida-cmake](https://github.com/0xeb/ida-cmake): This is not an IDA plugin but a CMake project generator for IDA plugins development.<br>
_Updated: 2022 05 27_

* [ida-cmake](https://github.com/zyantific/ida-cmake): CMake build scripts and a Python helper allowing compilation of C++ IDA plugins for Windows, macOS and Linux without much user effort.<br>
_Updated: 2017 09 02_

* [IDA Color Schemer](https://github.com/tmr232/IDAColorSchemer): tool to easily design IDA color schemes outside IDA. This will hopefully allow simplifying & automating the generation of color schemes and help create colorblind-friendly settings.<br>
_Updated: 2019 01 05 &nbsp;&nbsp; Language: Python_

* [IDA Compare](https://github.com/dzzie/IDACompare): IDA disassembly level diffing tool, find patches and modifications between malware variants. Helps you line up functions across two separate disassemblies. See mydoom A/B sample database and video trainer for usage.<br>
_Updated: 2019 05 30 &nbsp;&nbsp; Language: C++_

* [idaConsonance](https://github.com/eugeneching/ida-consonance): Consonance, a dark color scheme for IDA.<br>
_Updated: 2013 02 19_

* [IDACyber](https://github.com/patois/IDACyber): IDACyber is a plugin that visualizes an IDA database's content.<br>
_Updated: 2021 12 17 &nbsp;&nbsp; Language: Python_

* [idadiff](https://github.com/0x00ach/idadiff): IDAPython script to auto-rename subs using the MACHOC algorithm.<br>
_Updated: 2017 05 17 &nbsp;&nbsp; Language: Python_

* [IDA EA](https://github.com/1111joe1111/ida_ea): A set of exploitation/reversing aids for IDA. Provides a context viewer, instruction emulator, heap explorer, trace dumper, GDB integration, Styling<br>
_Updated: 2017 11 28 &nbsp;&nbsp; Language: Python_

* [IDA Embed arch disasm](https://github.com/a1ext/ida-embed-arch-disasm): Allows you to disassemble x86-64 code (like inlined WOW64 one) while you using 32-bit IDA database. This would be helpfull to analyze WOW64 mode switches.<br>
_Updated: 2021 12 27 &nbsp;&nbsp; Language: Python_

* [idaemu](https://github.com/36hours/idaemu): Emulate code in IDA Pro. it is based on unicorn-engine.<br>
_Updated: 2016 12 15 &nbsp;&nbsp; Language: Python_

* [IDA-EVM](https://github.com/crytic/ida-evm): IDA Processor Module for the Ethereum Virtual Machine (EVM).<br>
_Updated: 2022 05 26 &nbsp;&nbsp; Language: Python_

* [IDA Extrapass](http://sourceforge.net/projects/idaextrapassplugin/): An IDA Pro Win32 target clean up plug-in by Sirmabus. It does essentially four cleaning/fixing steps: Convert stray code section values to "unknown", fix missing "align" blocks, fix missing code bytes, and locate and fix missing/undefined functions.<br>
_Updated: 2018 07 13 &nbsp;&nbsp; Language: C++_

* [IDA Eye](http://www.mfmokbel.com/Down/RCE/Documentation.html): Plugin that enables you to perform different operations at the mnemonic level, independent of any particular processor type. These operations are facilitated through a parameterized template, which include the capabilities to de/highlight instructions, gather statistical information about the frequency of each instruction, and search for sequences of mnemonics, among other features.<br>
_Updated: 2018 03 10 &nbsp;&nbsp; Language: C++_

* [IDA-For-Delphi](https://github.com/Coldzer0/IDA-For-Delphi): IDA Python Script to Get All function names from Event Constructor (VCL).<br>
_Updated: 2019 09 20 &nbsp;&nbsp; Language: Python_

* [IDAFrida](https://github.com/P4nda0s/IDAFrida): IDA Frida Plugin for tracing something interesting. Plugin to generate FRIDA script.<br>
_Updated: 2022 03 28 &nbsp;&nbsp; Language: Python_

* [IDAFuzzy](https://github.com/Ga-ryo/IDAFuzzy): IDAFuzzy is fuzzy searching tool for IDA Pro. This tool helps you to find command/function/struct and so on. (a la Mac Spotlight).<br>
_Updated: 2019 12 16 &nbsp;&nbsp; Language: Python_

* [ida_game_elf_loaders (gel)](https://github.com/aerosoul94/ida_gel): A collection of IDA loaders for various game console ELF's: PS3, PSVita, WiiU.<br>
_Updated: 2019 10 03 &nbsp;&nbsp; Language: C++_

* [IDA GCC RTTI](https://github.com/mwl4/ida_gcc_rtti): Class informer plugin for IDA which supports parsing GCC RTTI.<br>
_Updated: 2018 03 04 &nbsp;&nbsp; Language: C++_

* [ida-genesis](https://github.com/zznop/ida-genesis): Suite of IDA scripts for SEGA Genesis ROM hacking. ROM Loader, Branch Table Enumeration.<br>
_Updated: 2020 02 16 &nbsp;&nbsp; Language: Python_

* [IDAGolangHelper](https://github.com/sibears/idagolanghelper): Set of IDA Pro scripts for parsing GoLang types information stored in compiled binary.<br>
_Updated: 2021 06 15 &nbsp;&nbsp; Language: Python_

* [IdaGrabStrings](https://github.com/andreafioraldi/IdaGrabStrings): Search strings in a specified range of addresses and map it to a C struct.<br>
_Updated: 2017 05 12 &nbsp;&nbsp; Language: Python_

* [idahunt](https://github.com/nccgroup/idahunt): idahunt is a framework to analyze binaries with IDA Pro and hunt for things in IDA Pro. It is command line tool to analyse all executable files recursively from a given folder. It executes IDA in the background so you don't have to open manually each file. It supports executing external IDA Python scripts.<br>
_Updated: 2022 01 04 &nbsp;&nbsp; Language: Python_

* [IDA iBoot Loader](https://github.com/matteyeux/ida-iboot-loader): IDA loader for Apple's 64 bits iBoot, SecureROM and AVPBooter.<br>
_Updated: 2021 12 19 &nbsp;&nbsp; Language: Python_

* [idaidle](https://github.com/google/idaidle): idaidle is a plugin for the commercial IDA Pro disassembler that warns users if they leave their instance idling for too long. After a predetermined amount of idle time, the plugin first warns and later then saves the current disassemlby database and closes IDA.<br>
_Updated: 2021 02 17 &nbsp;&nbsp; Language: C++_

* [IDA Images](https://github.com/rr-/ida-images): Image preview plugin for IDA disassembler.<br>
_Updated: 2020 11 07 &nbsp;&nbsp; Language: Python_

* [IDA IPython](https://github.com/james91b/ida_ipython): This is a plugin to embed an IPython kernel in IDA Pro. The Python ecosystem has amazing libraries (and communities) for scientific computing. IPython itself is great for exploratory data analysis. Using tools such as the IPython notebook make it easy to share code and explanations with rich media. IPython makes using IDAPython and interacting with IDA programmatically really fun and easy.<br>
_Updated: 2017 08 05 &nbsp;&nbsp; Language: C++_

* [IdaJava](https://github.com/cblichmann/idajava): Java integration for Hex-Rays IDA Pro. IdaJava is to Java like IDAPython is to Python: write IDA plugins in Java.<br>
_Updated: 2017 02 15 &nbsp;&nbsp; Language: C++_

* [IDA JScript](https://github.com/dzzie/IDA_JScript): Javascript IDE for IDA with Debugger, Syntax highlighting & Intellisense. Write plugins in Javascript.<br>
_Updated: 2022 05 19 &nbsp;&nbsp; Language: C++_

* [ida-kallsyms](https://github.com/mephi42/ida-kallsyms): IDA script for parsing kallsyms.<br>
_Updated: 2020 11 28 &nbsp;&nbsp; Language: Python_

* [IDAKern](https://github.com/NyaMisty/ida_kern): Raw IDA Kernel API for IDAPython: An IDAPython wrapper for IDA Pro's kernel dll.<br>
_Updated: 2022 04 10 &nbsp;&nbsp; Language: Python_

* [ida_kernelcache](https://github.com/bazad/ida_kernelcache): An IDA Toolkit for analyzing iOS kernelcaches.<br>
_Updated: 2018 11 30 &nbsp;&nbsp; Language: Python_

* [ida_kernelcache 7.5](https://github.com/cellebrite-labs/ida_kernelcache): An IDA Toolkit for analyzing iOS kernelcaches. This fork was updated to work on IDA7.5/Python3/iOS 14.0.1.<br>
_Updated: 2020 10 04 &nbsp;&nbsp; Language: Python_

* [IDA Key Checker](https://github.com/pr701/ida_key_checker): IDA Pro key checker tool, check IDA keys from the command line.<br>
_Updated: 2021 09 22 &nbsp;&nbsp; Language: C++_

* [idalink](https://github.com/zardus/idalink): Some glue facilitating remote use of IDA Python API. idalink works by spawning an IDA CLI session in the background (in a detached screen session), and connects to it using RPyC.<br>
_Updated: 2020 07 14 &nbsp;&nbsp; Language: Python_

* [IDAMagicStrings](https://github.com/joxeankoret/idamagicstrings): An IDA Python plugin to extract information from string constants. The current version of the plugin is able to:
  * Display functions to source files relationships (in a tree and in a plain list, a chooser in IDA language).
  * Display guessed function names for functions.
  * Rename functions according to the source code file their belong + address (for example, memory_mgmt_0x401050).
  * Rename functions according to the guessed function name.<br>
_Updated: 2019 11 08 &nbsp;&nbsp; Language: Python_

* [idamagnum](https://github.com/lucasg/idamagnum): A plugin for integrating MagnumDB requests within IDA. MagNumDB is a database that contains about 380,000 items. These items are constants, names, values all extracted from more than 6,000 header files (.h, .hxx, .hpp, .idl, etc.) provided by standard Windows and Visual Studio SDKs and WDKs.<br>
_Updated: 2020 04 10 &nbsp;&nbsp; Language: Python_

* [ida_medigate](https://github.com/medigate-io/ida_medigate): Medigate plugin for c++ reverse engineering and other utils. Two parts:
  * Implementation of C++ classes and polymorphism over IDA
  * A RTTI parser which rebuilds the classes hierarchy.<br>
_Updated: 2021 02 15 &nbsp;&nbsp; Language: Python_

* [IDAMetrics](https://github.com/mxmssh/idametrics): IDA plugins for static software complexity metrics collection. Collects static software complexity metrics for binary executables of x86 architecture.<br>
_Updated: 2018 01 04 &nbsp;&nbsp; Language: Python_

* [IDA Migrator](https://github.com/giladreich/ida_migrator): IDA Migrator plugin makes the job of migrating symbols and type informations from one IDA database instance to another. It will help migrating function names, structures and enums. This comes in handy when:
  * Moving to a newer version of IDA that does better analysis and you don't want to change in the new instance type information or variable names of the decompiled functions.
  * The current idb instance fails to decompile a function or the decompilation looks wrong in comparison to another idb instance of the same binary.
  * Experimenting on another idb instance before making major changes on the current instance.
  * A lightweight easy way of creating small backups of the current work.
  * For w/e reason, the current idb instance you're working on gets corrupted.<br>
_Updated: 2021 05 28 &nbsp;&nbsp; Language: Python_

* [IDA-minsc](https://github.com/arizvisa/ida-minsc): A plugin that assists a user with scripting the IDAPython plugin that is bundled with the disassembler. This plugin groups the different aspects of the IDAPython API into a simpler format which allows a reverse engineer to script different aspects of their work with very little investment.<br>
_Updated: 2022 05 28 &nbsp;&nbsp; Language: Python_

* [ida-netnode](https://github.com/williballenthin/ida-netnode): Humane API for storing and accessing persistent data in IDA Pro databases.<br>
_Updated: 2020 06 29 &nbsp;&nbsp; Language: Python_

* [IDAngr](https://github.com/andreafioraldi/IDAngr): Use angr in the ida debugger generating a state from the current debug session.<br>
_Updated: 2020 07 22 &nbsp;&nbsp; Language: Python_

* [IDA - Nightfall](https://github.com/0xItx/ida_nightfall): A dark color theme for IDA Pro<br>
_Updated: 2019 06 25 &nbsp;&nbsp; Language: Python_

* [IDAObjcTypes](https://github.com/PoomSmart/IDAObjcTypes): A collection of (public and private) types and functions definitions useful for Objective-C binaries analysis.<br>
_Updated: 2022 05 22 &nbsp;&nbsp; Language: Python_

* [idapatch](https://github.com/mrexodia/idapatch): IDA plugin to patch IDA Pro in memory.<br>
_Updated: 2016 09 03 &nbsp;&nbsp; Language: C++_

* [IDA Patcher](https://github.com/iphelix/ida-patcher): IDA Patcher is a plugin for Hex-Ray's IDA Pro disassembler designed to enhance IDA's ability to patch binary files and memory.<br>
_Updated: 2014 09 23 &nbsp;&nbsp; Language: Python_

* [IDA Patchwork](https://bitbucket.org/daniel_plohmann/idapatchwork): Stitching against malware families with IDA Pro (tool for the talk at Spring9, https://spring2014.gdata.de/spring2014/programm.html). In essence, I use a somewhat fixed / refurbished version of PyEmu along IDA to demonstrate deobfuscation of the different patterns found in the malware family Nymaim.<br>
_Updated: 2014 11 04 &nbsp;&nbsp; Language: Python_

* [IDA Pattern Search](https://github.com/david-lazar/IDAPatternSearch): IDAPatternSearch adds a capability of finding functions according to bit-patterns into the well-known IDA Pro disassembler based on Ghidra’s function patterns format.<br>
_Updated: 2021 09 14 &nbsp;&nbsp; Language: Python_

* [IDA P-Code](https://github.com/binarly-io/idapcode): IDA plugin displaying the P-Code for the current function.<br>
_Updated: 2021 07 20 &nbsp;&nbsp; Language: Python_

* [IDA PDB Loader (IPL)](https://github.com/ax330d/ida_pdb_loader): Simple plugin to load PDB symbols. The problem is that sometimes IDA crashes for me when trying to load symbols, so I came up with this quick and dirty alternative.<br>
_Updated: 2018 09 21 &nbsp;&nbsp; Language: Python_

* [IDAPerl](https://github.com/nlitsme/idaperl): Adds perl scripting support to ida.<br>
_Updated: 2016 07 24 &nbsp;&nbsp; Language: C++_

* [IDAPinLogger](https://github.com/wirepair/idapinlogger): Logs instruction hits to a file which can be fed into IDA Pro to highlight which instructions were called.<br>
_Updated: 2013 07 05 &nbsp;&nbsp; Language: C++_

* [IDA Plugin Loader](https://github.com/tmr232/ida-plugin-loader): Random IDA scripts, plugins, example code (some of it may be old and not working anymore).<br>
_Updated: 2019 10 27 &nbsp;&nbsp; Language: Python_

* [idaplugins](https://github.com/patois/idaplugins): Random IDA scripts, plugins, example code (some of it may be old and not working anymore).<br>
_Updated: 2017 02 05 &nbsp;&nbsp; Language: C++_

* [idaplugins](https://github.com/tmr232/ida-plugins): Plugins for IDA: Plugin Proxy, Function Strings, LCA Graph, Autoenum, Autostruct, Function Flow, Quick Copy.<br>
_Updated: 2015 05 31 &nbsp;&nbsp; Language: Python_

* [ida-plugins](https://vmallet.github.io/ida-plugins/): Interactive IDA Plugin List: a great list of plugins for IDA which can be sorted and filtered dynamically to make it easier to find plugins of interest. Worth checking out! :)

* [idapm](https://github.com/tkmru/idapm): idapm is IDA Plugin Manager. It works perfectly on macOS, it probably works on Windows and Linux.<br>
_Updated: 2020 09 05 &nbsp;&nbsp; Language: Python_

* [idapro_m6502](https://github.com/LucienMP/idapro_m6502): Extends existing support in IDA Pro for the m6502 processor family by adding gdb XML support, and step-over and type information support. Aim was to debug NES roms.<br>
_Updated: 2020 11 10 &nbsp;&nbsp; Language: Python_

* [idapro_m68k](https://github.com/LucienMP/idapro_m68k): Extends existing support in IDA for the Motorola m68k processor family by adding gdb step-over and type information support. Enable type information support so you can press "y" on functions and have the parameters propagate inside and back out of the function.<br>
_Updated: 2019 07 14 &nbsp;&nbsp; Language: Python_

* [IDA Pro Translator](https://github.com/kyrus/ida-translator): Assists in decoding arbitrary character sets in an IDA Pro database into Unicode, then automatically invoking a web-based translation service (currently Google Translate) to translate that foreign text into English.<br>
_Updated: 2015 02 09 &nbsp;&nbsp; Language: Python_

* [IDAPyHelper](https://github.com/patois/IDAPyHelper): IDAPyHelper is a script for the Interactive Disassembler that helps writing IDAPython scripts and plugins.<br>
_Updated: 2019 11 23 &nbsp;&nbsp; Language: Python_

* [IDA Python Embedded Toolkit](https://github.com/maddiestone/IDAPythonEmbeddedToolkit): IDAPython scripts for automating analysis of firmware of embedded devices.<br>
_Updated: 2019 08 14 &nbsp;&nbsp; Language: Python_

* [idapython_virtualenv](https://github.com/gaasedelen/idapython_virtualenv): Multiples virtual envs support for IDAPython. Enable Virtualenv or Conda in IDAPython.<br>
_Updated: 2020 11 11 &nbsp;&nbsp; Language: Python_

* [IDARay](https://github.com/SouhailHammou/IDARay-Plugin): IDARay is an IDA Pro plugin that matches the database against multiple YARA files. Maybe your rules are scattered over multiple YARA files or you simply want to match against as much rules as possible, IDARay is here to help.<br>
_Updated: 2018 11 16 &nbsp;&nbsp; Language: Python_

* [IdaRef](https://github.com/nologic/idaref): IDA Pro Full Instruction Reference Plugin - It's like auto-comments but useful.<br>
_Updated: 2021 10 20 &nbsp;&nbsp; Language: Python_

* [IDA Rest](https://github.com/dshikashio/idarest): A simple REST-like API for basic interoperability with IDA Pro.<br>
_Updated: 2015 03 21 &nbsp;&nbsp; Language: Python_

* [IDArling](https://github.com/IDArlingTeam/IDArling/): IDArling is a collaborative reverse engineering plugin for IDA Pro and Hex-Rays. It allows to synchronize in real-time the changes made to a database by multiple users, by connecting together different instances of IDA Pro.<br>
_Updated: 2021 02 17 &nbsp;&nbsp; Language: Python_

* [IDArling (Fork)](https://github.com/fidgetingbits/IDArling): IDArling is a collaborative reverse engineering plugin for IDA Pro and Hex-Rays. This is an actively maintained fork of the now-abandoned IDARling above.<br>
_Updated: 2022 01 10 &nbsp;&nbsp; Language: Python_

* [Idarop](https://github.com/lucasg/idarop): ROP database plugin for IDA: list and store all the ROP gadgets presents within the opened binary. (inspired from idasploiter).<br>
_Updated: 2018 06 05 &nbsp;&nbsp; Language: Python_

* [ida-rpc](https://github.com/offlineJ/ida-rpc): Discord rich presence plugin for IDA Pro 7.0<br>
_Updated: 2019 04 26 &nbsp;&nbsp; Language: C++_

* [IDAscope](https://github.com/danielplohmann/idascope): IDAscope is an IDA Pro extension with the goal to ease the task of (malware) reverse engineering with a current focus on x86 Windows. It consists of multiple tabs, containing functionality to achieve different goals such as fast identification of semantically interesting locations in the analysis target, seamless access to MSDN documentation of Windows API, and finding of potential crypto/compression algorithms.<br>
_Updated: 2020 08 13 &nbsp;&nbsp; Language: Python_

* [idascripts](https://github.com/nlitsme/idascripts): IDC and idapython script collection. enumerators.py contains several iterators.<br>
_Updated: 2019 09 11 &nbsp;&nbsp; Language: Python_

* [ida-scripts](https://github.com/danigargu/ida-scripts): Misc IDA Pro scripts: cyclomatic_complexity, go_stripped_helper.<br>
_Updated: 2016 10 17 &nbsp;&nbsp; Language: Python_

* [ida-scripts (sam-b)](https://github.com/sam-b/ida-scripts): Dumping ground for whatever IDA Pro scripts I write: call_graph, export2neo4j, find_device_name, mem_complexity, most_refs.<br>
_Updated: 2016 10 09 &nbsp;&nbsp; Language: Python_

* [idasec](https://github.com/robindavid/idasec): IDA plugin for reverse-engineering and dynamic interactions with the Binsec platform.<br>
_Updated: 2017 11 19 &nbsp;&nbsp; Language: Python_

* [ida-settings](https://github.com/williballenthin/ida-settings): Fetch and set configuration values from IDAPython scripts.<br>
_Updated: 2020 09 09 &nbsp;&nbsp; Language: Python_

* [idasetup](https://github.com/lucasg/idasetup): Custom setup.py file for IDA plugins.<br>
_Updated: 2017 10 28 &nbsp;&nbsp; Language: Python_

* [IDAShell](https://github.com/namazso/IDAShell): IDAShell is a shell extension for launching IDA from the context menu of executables (Windows).<br>
_Updated: 2021 07 29 &nbsp;&nbsp; Language: C++_

* [IDA Signature Matching Tool](http://sourceforge.net/projects/idasignsrch/): Tool for searching signatures inside files, extremely useful as help in reversing jobs like figuring or having an initial idea of what encryption/compression algorithm is used for a proprietary protocol or file. It can recognize tons of compression, multimedia and encryption algorithms and
many other things like known strings and anti-debugging code which can be also manually added since it's all based on a text signature file read at run-time and easy to modify.<br>
_Updated: 2018 07 13 &nbsp;&nbsp; Language: C++_

* [idasix](https://github.com/nirizr/idasix): IDAPython compatibility library. idasix aims to create a smooth ida development process and allow a single codebase to function with multiple IDA/IDAPython versions.<br>
_Updated: 2018 08 02 &nbsp;&nbsp; Language: Python_

* [IDA Skins](https://github.com/zyantific/IDASkins): Plugin providing advanced skinning support for the Qt version of IDA Pro utilizing Qt stylesheets, similar to CSS.<br>
_Updated: 2019 06 15 &nbsp;&nbsp; Language: Python_

* [IDA Sploiter](https://github.com/iphelix/ida-sploiter): IDA Sploiter is a plugin for Hex-Ray's IDA Pro disassembler designed to enhance IDA's capabilities as an exploit development and vulnerability research tool. Some of the plugin's features include a powerful ROP gadgets search engine, semantic gadget analysis and filtering, interactive ROP chain builder, stack pivot analysis, writable function pointer search, cyclic memory pattern generation and offset analysis, detection of bad characters and memory holes, and many others.<br>
_Updated: 2019 05 13 &nbsp;&nbsp; Language: Python_

* [IDA Stealth](https://github.com/nihilus/idastealth): IDAStealth is a plugin which aims to hide the IDA debugger from most common anti-debugging techniques. The plugin is composed of two files, the plugin itself and a dll which is injected into the debuggee as soon as the debugger attaches to the process. The injected dll actually implements most of the stealth techniques either by hooking system calls or by patching some flags in the remote process.<br>
_Updated: 2014 09 14 &nbsp;&nbsp; Language: C++_

* [IDA StrikeOut](https://github.com/0xeb/ida-strikeout): IDA strike-out: A Hex-Rays decompiler plugin to patch the Ctree (e.g. remove statements).<br>
_Updated: 2021 12 27 &nbsp;&nbsp; Language: C++_

* [IDA StringCluster](https://github.com/Comsecuris/ida_strcluster): This plugin extends IDA Pro's capabilities to display strings within the binary by clustering found strings on a per-function basis.<br>
_Updated: 2018 03 14 &nbsp;&nbsp; Language: Python_

* [IDA-String-Reference-Locator](https://github.com/praydog/IDA-String-Reference-Locator-Plugin): Finds all first occurring string references near another reference.<br>
_Updated: 2021 12 16 &nbsp;&nbsp; Language: C++_

* [IDA Taco](https://github.com/jjo-sec/idataco): Bring Cuckoo Sandbox-generated output into IDA Pro to assist in reverse engineering malware as well as combining some commonly used tools into one UI.<br>
_Updated: 2016 06 14 &nbsp;&nbsp; Language: Python_

* [IDATag](https://github.com/thalium/idatag): Tag explorer for IDA Pro. The plugin leverages IDA as a platform to map, explore, and visualize collected tags. Tags can come from multiple sources such as IDA itself or different other clients.<br>
_Updated: 2019 07 19 &nbsp;&nbsp; Language: C++_

* [IDA Toolbag](https://github.com/aaronportnoy/toolbag): The IDA Toolbag plugin provides many handy features, such as:
  * A 'History' view, that displays functions in the disassembly that you have decided are important, and the relationships between them.
  * A code path-searching tool, that lets you find what functions (or blocks) are forming a path between two locations.
  * Manage and run your IDC/Python scripts
  * Something that's also of considerable importance is that the IDA Toolbag lets you collaborate with other IDA users: one can publish his 'History', or import another user's history & even merge them!
  * See the official documentation for an extensive feature list.<br>
_Updated: 2015 01 30 &nbsp;&nbsp; Language: Python_

* [IDAtropy](https://github.com/danigargu/IDAtropy): IDAtropy is a plugin for Hex-Ray's IDA Pro designed to generate charts of entropy and histograms using the power of idapython and matplotlib.<br>
_Updated: 2021 04 16 &nbsp;&nbsp; Language: Python_

* [IdaVSHelp](https://github.com/andreafioraldi/IdaVSHelp): IDAPython plugin to integrate Visual Studio Help Viewer in IDA Pro >= 6.8<br>
_Updated: 2017 05 13 &nbsp;&nbsp; Language: Python_

* [idawasm](https://github.com/fireeye/idawasm): These IDA Pro plugins add support for loading and disassembling WebAssembly modules.
  * control flow reconstruction and graph mode
  * code and data cross references
  * globals, function parameters, local variables, etc. can be renamed
  * auto-comment hint support<br>
_Updated: 2018 10 04 &nbsp;&nbsp; Language: Python_

* [idawilli](https://github.com/williballenthin/idawilli): IDA Pro resources, scripts, and configurations.<br>
_Updated: 2022 01 21 &nbsp;&nbsp; Language: Python_

* [idax](https://github.com/0xeb/idax): idax is a set of C++ extensions for the IDASDK. These extensions are a work in progress and are not meant to be used in production code yet. As of now, only my personal IDA plugins use idax.<br>
_Updated: 2021 12 27 &nbsp;&nbsp; Language: C++_

* [IDA x64dbgExport](https://github.com/kweatherman/ida_x64dbgexport_plugin): A binary x64dbg debugger export plugin for IDA Pro. A binary plugin version of mrexodia's official Python version (x64dbgida) but only with an export, no 'import' option.<br>
_Updated: 2022 01 15 &nbsp;&nbsp; Language: C++_

* [idaxex](https://github.com/emoose/idaxex): Xbox360/Xenon loader plugin for IDA 7.2+, supporting most known Xbox360/Xenon .XEX executable file formats.<br>
_Updated: 2022 02 18 &nbsp;&nbsp; Language: C++_

* [IDA Xtensa](https://github.com/themadinventor/ida-xtensa): This is a processor plugin for IDA, to support the Xtensa core found in Espressif ESP8266. It does not support other configurations of the Xtensa architecture, but that is probably (hopefully) easy to implement.<br>
_Updated: 2019 08 20 &nbsp;&nbsp; Language: Python_

* [ida_yara](https://github.com/alexander-hanel/ida_yara): A python script that can be used to scan data within in an IDB using Yara.<br>
_Updated: 2018 09 04 &nbsp;&nbsp; Language: Python_

* [ida-yara-processor](https://github.com/bnbdr/ida-yara-processor): Compiled YARA Rules Processor for IDA.<br>
_Updated: 2019 01 22 &nbsp;&nbsp; Language: Python_

* [idb2pat](https://github.com/alexander-pick/idb2pat): IDB to Pat, fixed to work with IDA 6.2. Create patterns for IDA objects.<br>
_Updated: 2011 10 08 &nbsp;&nbsp; Language: C++_

* [idbutil](https://github.com/nlitsme/idbutil): IDBTOOL - Library and tool for reading IDApro databases. (See Python version 'pyidbutil')<br>
_Updated: 2020 11 27 &nbsp;&nbsp; Language: C++_

* [idcinternals](https://github.com/nlitsme/idcinternals): IDA plugin investigating the internal representation of IDC scripts<br>
_Updated: 2020 11 27 &nbsp;&nbsp; Language: C++_

* [idenLib](https://github.com/secrary/IDA-scripts/tree/master/idenLib): Library Function Identification plugin for IDA Pro.<br>
_Updated: 2019 02 26 &nbsp;&nbsp; Language: Python_

* [IFL](https://github.com/hasherezade/ida_ifl): Interactive Functions List is an user-friendly way to navigate between functions and their references.<br>
_Updated: 2022 01 20 &nbsp;&nbsp; Language: Python_

* [ifred](https://github.com/Jinmo/ifred): IDA command palette & more (Ctrl+Shift+P, Ctrl+P).<br>
_Updated: 2022 03 08 &nbsp;&nbsp; Language: C++_

* [IPyIDA](https://github.com/eset/ipyida): PyIDA is a python-only solution to use a IPython console in the context of IDA Pro. It spawns an IPython kernel that you can connect to with `ipython console --existing` in your shell or by opening a *QT Console* window in IDA Pro with `<Shift-.>`<br>
_Updated: 2022 04 23 &nbsp;&nbsp; Language: Python_

* [J.A.R.V.I.S.](https://github.com/carlosgprado/JARVIS): Just Another ReVersIng Suite: a small bughunting suite comprising three elements: a fuzzer, a tracer based on INTEL PIN, a plugin for IDA Pro thought to assist you with the most common reversing tasks. It integrates with the tracer.<br>
_Updated: 2018 10 19 &nbsp;&nbsp; Language: Python_

* [JNIDA](https://github.com/applicazza/JNIDA): Helps to rename JNI native methods and restore their C signatures<br>
_Updated: 2019 11 18 &nbsp;&nbsp; Language: Python_

* [Kam1n0](https://github.com/McGill-DMaS/Kam1n0-Plugin-IDA-Pro): Kam1n0 is a scalable system that supports assembly code clone search. It allows a user to first index a (large) collection of binaries, and then search for the code clones of a given target function or binary file. Kam1n0 tries to solve the efficient subgraph search problem (i.e. graph isomorphism problem) for assembly functions.<br>
_Updated: 2022 02 13 &nbsp;&nbsp; Language: Python_

* [Karta](https://github.com/CheckPointSW/Karta): "Karta" (Russian for "Map") is a source code assisted fast binary matching plugin for IDA. Karta identifies and matches open-sourced libraries in a given binary using a unique technique that enables it to support huge binaries (> 200,000 functions) with almost no impact on the overall performance.<br>
_Updated: 2022 03 15 &nbsp;&nbsp; Language: Python_

* [Keypatch](https://github.com/keystone-engine/keypatch): A multi-architeture assembler for IDA. Keypatch allows you enter assembly instructions to directly patch the binary under analysis. Powered by [Keystone engine](http://keystone-engine.org).<br>
_Updated: 2021 02 18 &nbsp;&nbsp; Language: Python_

* [Labeless](https://github.com/a1ext/labeless): Labeless is a plugin system for dynamic, seamless and realtime synchronization between IDA Database and Olly. Labels, function names and global variables synchronization is supported.
Labeless provides easy to use dynamic dumping tool, which supports automatic on-the-fly imports fixing as well as convenient tool for IDA-Olly Python scripting synergy.<br>
_Updated: 2022 03 25 &nbsp;&nbsp; Language: C++_

* [LazyIDA](https://github.com/L4ys/LazyIDA): LazyIDA lets you perform many tasks simply and quickly (e.g., remove function return type in Hex-Rays, convert data into different formats, scan for format string vulnerabilities and a variety of shortcuts)<br>
_Updated: 2022 02 25 &nbsp;&nbsp; Language: Python_

* [Lighthouse](https://github.com/gaasedelen/lighthouse): Lighthouse is a Code Coverage Plugin for IDA Pro. The plugin leverages IDA as a platform to map, explore, and visualize externally collected code coverage data when symbols or source may not be available for a given binary.<br>
_Updated: 2022 02 17 &nbsp;&nbsp; Language: Python_

* [LLVMAnalyzer](https://github.com/cbwang505/llvmanalyzer): Based on a retdec open source decompiler tool and on the LLVM compiler architecture, the author integrates the klee symbolic execution tool, and dynamically simulates the decompiled llvm ir (intermediate instruction set) operation through the Symbolic Execution engine. (Chinese).<br>
_Updated: 2022 04 06 &nbsp;&nbsp; Language: C++_

* [LoadProcConfig](https://github.com/alexhude/LoadProcConfig): LoadProcConfig is an IDA plugin to load processor configuration files.<br>
_Updated: 2017 09 21 &nbsp;&nbsp; Language: C++_

* [Localxrefs](https://github.com/devttys0/ida/tree/master/plugins/localxrefs): Finds references to any selected text from within the current function.<br>
_Updated: 2021 06 02 &nbsp;&nbsp; Language: Python_

* [Lucid](https://github.com/gaasedelen/lucid): Lucid is a developer-oriented IDA Pro plugin for exploring the Hex-Rays microcode. It was designed to provide a seamless, interactive experience for studying microcode transformations in the decompiler pipeline.<br>
_Updated: 2020 09 15 &nbsp;&nbsp; Language: Python_

* [Lumen](https://github.com/naim94a/lumen): A private Lumina server for IDA Pro written in Rust.<br>
_Updated: 2022 01 21 &nbsp;&nbsp; Language: rs_

* [MadNES](https://github.com/patois/MadNES): This plugin exports IDA names to FCEUXD SP symbols. These can be loaded by FCEUXD SP to allow symbolic debugging.<br>
_Updated: 2012 09 12 &nbsp;&nbsp; Language: C++_

* [MazeWalker](https://github.com/0xPhoeniX/MazeWalker): Toolkit for enriching and speeding up static malware analysis. MazeWalker’s goal is to reduce malware analysis time by automating runtime data collection and better visualization eventually helping a researcher to concentrate on static analysis and less on its dynamic part.<br>
_Updated: 2022 01 16 &nbsp;&nbsp; Language: Python_

* [Memory Loader](https://github.com/SentineLabs/Memloader): IDA loader that allows loading malicious buffers to IDA without writing them to the disk.
  * UrlLoader - loads files from a URL.
  * MemZipLoader - loads files to encrypted / plain zip file.
  * So far only windows supported.<br>
_Updated: 2021 03 26 &nbsp;&nbsp; Language: C++_

* [MicroAVX](https://github.com/gaasedelen/microavx): An AVX Lifter for the Hex-Rays Decompiler. It adds partial support for a number of common instructions from Intel's Advanced Vector Extensions (AVX). This plugin demonstrates how the Hex-Rays microcode can be used to lift and decompile new or previously unsupported instructions.<br>
_Updated: 2020 07 22 &nbsp;&nbsp; Language: Python_

* [mIDA](https://github.com/tenable/mida): MIDL Decompiler for IDA. Extracts RPC interfaces and recreates the associated IDL file. mIDA supports inline, interpreted and fully interpreted server stubs.<br>
_Updated: 2018 07 05 &nbsp;&nbsp; Language: C++_

* [MILF](https://github.com/carlosgprado/milf): An IDA Pro swiss army knife (with a sexy name!) MILF is an IDA Pro plugin which automates several typical tasks in a RE session.<br>
_Updated: 2013 03 15 &nbsp;&nbsp; Language: Python_

* [mipsAudit](https://github.com/giantbranch/mipsAudit): Static scan script, assembly audit helper script (IDA MIPS静态扫描脚本，汇编审计辅助脚本).<br>
_Updated: 2021 11 25 &nbsp;&nbsp; Language: Python_

* [mipslocalvars](https://github.com/devttys0/ida/tree/master/plugins/mipslocalvars): Names stack variables used by the compiler for storing registers on the stack, simplifying stack data analysis (MIPS only).<br>
_Updated: 2021 06 02 &nbsp;&nbsp; Language: Python_

* [mipsrop](https://github.com/devttys0/ida/tree/master/plugins/mipsrop): 
  * Allows you to search for suitable ROP gadgets in MIPS executable code
  * Built-in methods to search for common ROP gadgets.<br>
_Updated: 2021 06 02 &nbsp;&nbsp; Language: Python_

* [mkYARA IDA Plugin](https://github.com/fox-it/mkYARA): IDA plugin to easily create YARA signatures with mkYARA.<br>
_Updated: 2019 12 16 &nbsp;&nbsp; Language: Python_

* [MrsPicky](https://github.com/patois/mrspicky): An IDAPython decompiler script that helps auditing calls to the memcpy() and memmove() functions.<br>
_Updated: 2019 12 18 &nbsp;&nbsp; Language: Python_

* [msdnGrab](https://github.com/eugeneching/msdn-grab): Allows a user to grab documentation from online MSDN for a given function name in IDA, and import the documentation as a repeatable comment for that function. Handles queries for the Win32 API and C/C++.<br>
_Updated: 2012 07 22 &nbsp;&nbsp; Language: Python_

* [MSDN Helper](https://github.com/yaseralnajjar/IDA-MSDN-helper): This tool will help you to get to Offline MSDN help while using IDA Pro.<br>
_Updated: 2016 09 05_

* [MSDN IDA Pro Plugin](https://github.com/zynamics/msdn-plugin-ida): Imports MSDN documentation into IDA Pro (by zynamics).<br>
_Updated: 2012 01 10 &nbsp;&nbsp; Language: Python_

* [msp430emu](https://github.com/cseagle/msp430emu): An msp430 emulator plugin for Ida Pro.<br>
_Updated: 2019 03 22 &nbsp;&nbsp; Language: C++_

* [MyNav](https://code.google.com/p/mynav/): MyNav is a plugin for IDA Pro to help reverse engineers in the most typical task like discovering what functions are responsible of some specifical tasks, finding paths between "interesting" functions and data entry points.<br>
_Updated: 2010 09 03 &nbsp;&nbsp; Language: C++_

* [nao](https://github.com/tkmru/nao): nao (no-meaning assembly omitter) is dead code eliminator plugin for IDA pro.<br>
_Updated: 2021 05 05 &nbsp;&nbsp; Language: Python_

* [NDSLdr](https://github.com/patois/NDSLdr): Nintendo DS ROM loader module for IDA Pro.<br>
_Updated: 2017 02 05 &nbsp;&nbsp; Language: C++_

* [NECromancer](https://github.com/patois/NECromancer): IDA Pro V850 Processor Module Extension.<br>
_Updated: 2018 05 08 &nbsp;&nbsp; Language: Python_

* [nesdbg](https://github.com/patois/nesdbg): Failed attempt in creating an IDA Pro debugger plugin for NES ROMs<br>
_Updated: 2018 12 18 &nbsp;&nbsp; Language: C++_

* [NES Loader](https://github.com/patois/nesldr): Nintendo Entertainment System (NES) ROM loader module for IDA Pro.<br>
_Updated: 2020 02 26 &nbsp;&nbsp; Language: C++_

* [NES Loader (py)](https://github.com/Jinmo/nesldr-py): Nintendo Entertainment System (NES) ROM loader module for IDA Pro (Python port for IDA 7.x).<br>
_Updated: 2021 07 15 &nbsp;&nbsp; Language: Python_

* [NIOS2](https://github.com/ptresearch/nios2): An IDA Pro processor module for Altera Nios II Classic/Gen2 microprocessor architecture.<br>
_Updated: 2018 09 24 &nbsp;&nbsp; Language: Python_

* [nmips](https://github.com/0rganizers/nmips): IDA plugin to enable nanoMIPS processor support. This is not limited to simple disassembly, but fully supports decompilation and even fixes up the stack in certain functions using custom microcode optimizers. It also supports relocations and automatic ELF detection (even though the UI might not show it, it kinda works). Debugging also works thanks to GDB and it also does some other stuff, such as automatic switch detections.<br>
_Updated: 2021 09 15 &nbsp;&nbsp; Language: Python_

* [NoVmpy](https://github.com/wallds/NoVmpy): Proof of Concept, IDA integration of a static devirtualizer for VMProtect x64 3.x. powered by VTIL.<br>
_Updated: 2022 05 20 &nbsp;&nbsp; Language: Python_

* [NSIS Reversing Suite](https://github.com/isra17/nrs/): NRS is a set of Python libraries used to unpack and analysis NSIS installer's data. It also feature an IDA plugin used to disassembly the NSIS Script of an installer.<br>
_Updated: 2018 05 19 &nbsp;&nbsp; Language: Python_

* [obfDetect](https://github.com/mcdulltii/obfDetect): A plugin to automatically detect obfuscated code and state machines in binaries.<br>
_Updated: 2022 04 29 &nbsp;&nbsp; Language: Python_

* [Obpo: Obfuscated Binary Pseudocode Optimizer](https://github.com/obpo-project/obpo-plugin): Obpo is a microcode-based hex-rays optimizer, uses techniques such as static-program-analysis, dataflow-tracking, concolic-execution to rebuild the obfuscated control flow (such as: OLLVM).<br>
_Updated: 2022 05 01 &nbsp;&nbsp; Language: Python_

* [oldidc](https://github.com/joxeankoret/oldidc): IDA Python's idc.py <= 7.3 compatibility module.<br>
_Updated: 2019 10 11 &nbsp;&nbsp; Language: Python_

* [Optimice](https://code.google.com/p/optimice/): This plugin enables you to remove some common obfuscations and rewrite code to a new segment. Currently supported optimizations are: Dead code removal, JMP merging, JCC opaque predicate removal, Pattern based deobfuscations<br>
_Updated: 2012 08 05 &nbsp;&nbsp; Language: Python_

* [Oregami](https://github.com/shemesh999/oregami): A plugin analyzing the current function to find the usage frame of registers. Oregami eases the work when tracking the use of a register within a function, by limiting the search to occurrences related to the one currently highlighted instead of the whole function. It also allows localized renaming of the registers, and batch type giving to multiple opcodes using the registers.<br>
_Updated: 2020 04 06 &nbsp;&nbsp; Language: Python_

* [Package Manager](https://github.com/Jinmo/idapkg): Packages for IDA Pro (written in python but supports all).<br>
_Updated: 2021 01 04 &nbsp;&nbsp; Language: Python_

* [PacXplorer](https://github.com/cellebrite-labs/PacXplorer): IDA plugin to find code cross references to virtual functions using PAC codes in ARM64e binaries.<br>
_Updated: 2022 03 16 &nbsp;&nbsp; Language: Python_

* [patchdiff2](https://github.com/filcab/patchdiff2): IDA binary differ.<br>
_Updated: 2015 04 09 &nbsp;&nbsp; Language: C++_

* [Patching](https://github.com/gaasedelen/patching): Interactive Binary Patching for IDA Pro. This project extends the popular IDA Pro disassembler to create a more robust interactive binary patching workflow designed for rapid iteration.<br>
_Updated: 2022 02 10 &nbsp;&nbsp; Language: Python_

* [PE Tree](https://github.com/blackberry/pe_tree): Python module for viewing Portable Executable (PE) files in a tree-view using pefile and PyQt5.<br>
_Updated: 2021 05 17 &nbsp;&nbsp; Language: Python_

* [Pigaios](https://github.com/joxeankoret/pigaios): Pigaios ('πηγαίος', Greek for 'source' as in 'source code') is a tool for diffing/matching source codes directly against binaries.<br>
_Updated: 2018 12 17 &nbsp;&nbsp; Language: Python_

* [Plus22](https://github.com/v0s/plus22): Plus22 transforms x86_64 executables to be processed with 32-bit version of Hex-Rays Decompiler.<br>
_Updated: 2015 01 11 &nbsp;&nbsp; Language: PHP_

* [Plympton](https://github.com/rogwfu/plympton): A gem to read program disassembly from a YAML dump. The YAML dump is generated from an IDA Pro python script. This script is included along with this Gem (func.py)<br>
_Updated: 2014 11 25 &nbsp;&nbsp; Language: Python_

* [Pomidor](https://github.com/iphelix/ida-pomidor): IDA Pomidor is a plugin for Hex-Ray's IDA Pro disassembler that will help you retain concentration and productivity during long reversing sessions by encouraging you to take breaks.<br>
_Updated: 2014 09 23 &nbsp;&nbsp; Language: Python_

* [Ponce](https://github.com/illera88/Ponce): Taint analysis and symbolic execution over binaries in an easy and intuitive fashion.<br>
_Updated: 2022 04 25 &nbsp;&nbsp; Language: C++_

* [Prefix](https://github.com/gaasedelen/prefix): Prefix is a small function prefixing plugin for IDA Pro. The plugin augments IDA's function renaming capabilities by adding a handful of convenient prefixing actions to relevant right click menus.<br>
_Updated: 2020 04 24 &nbsp;&nbsp; Language: Python_

* [Processor changer](https://github.com/techbliss/Processor-Changer): Change processor without restarting IDA.<br>
_Updated: 2014 08 11 &nbsp;&nbsp; Language: Python_

* [PSIDA](https://github.com/soggysec/psida): PSIDA is a collection of useful Python scripts for IDA. At this point, PSIDA focuses on collaborative reverse engineering in two models.<br>
_Updated: 2018 08 03 &nbsp;&nbsp; Language: Python_

* [pwndbg](https://github.com/pwndbg/pwndbg): GDB plug-in that makes debugging with GDB suck less, with a focus on features needed by low-level software developers, hardware hackers, reverse-engineers and exploit developers. NOTE: IDA integration through small XMLRPC server.<br>
_Updated: 2022 05 24 &nbsp;&nbsp; Language: Python_

* [pyhexraysdeob](https://github.com/idapython/pyhexraysdeob): A port of Rolf Rolles' HexRaysDeob to Python.<br>
_Updated: 2019 10 15 &nbsp;&nbsp; Language: Python_

* [pyidbutil](https://github.com/nlitsme/pyidbutil): IDBTOOL - Library and tool for reading IDApro databases. (See C++ version 'idbutil').<br>
_Updated: 2022 05 01 &nbsp;&nbsp; Language: Python_

* [pytest-idapro](https://github.com/nirizr/pytest-idapro): A pytest module for The Interactive Disassembler and IDAPython; Record and Replay IDAPython API, execute inside IDA or use mockups of IDAPython API.<br>
_Updated: 2018 11 03 &nbsp;&nbsp; Language: Python_

* [Python Editor](https://github.com/techbliss/Python_editor): Python editor based IDA Pro. The plugin helps python devs with scripting and running python scripts, and creating them. IT have many functions, code recognition and more.<br>
_Updated: 2020 12 25 &nbsp;&nbsp; Language: Python_

* [python-idb](https://github.com/williballenthin/python-idb): not an IDA Pro plugin but allows to open IDA databases (`*.idb` and `*.i64`) and run a simple subset of IDAPython API on top of them, without the IDA Pro itself.<br>
_Updated: 2021 08 06 &nbsp;&nbsp; Language: Python_

* [qb-sync](https://github.com/quarkslab/qb-sync): qb-sync is an open source tool to add some helpful glue between IDA Pro and Windbg. Its core feature is to dynamically synchronize IDA's graph windows with Windbg's position.<br>
_Updated: 2015 07 13 &nbsp;&nbsp; Language: Python_

* [QScripts](https://github.com/0xeb/ida-qscripts): An IDA scripting productivity plugin. With this plugin, you will be able to easily write and test scripts using your favorite editor. `ida-qscripts` will automatically detect changes to your script or one of its dependencies and automatically reload them and re-execute your script.<br>
_Updated: 2022 05 31 &nbsp;&nbsp; Language: C++_

* [Qualcomm Loader](https://github.com/daxgr/qcom-mbn-ida-loader): IDA loader plugin for Qualcomm Bootloader Stages<br>
_Updated: 2014 01 23 &nbsp;&nbsp; Language: C++_

* [quicksec](https://github.com/coldheat/quicksec): IDAPython script for quick vulnerability analysis.<br>
_Updated: 2014 05 10 &nbsp;&nbsp; Language: Python_

* [Rebased Comment](https://github.com/naim94a/rebasedcomment): Rebase comments when you rebase your IDA database, by searching for hexadecimal numbers that are within range of your program's segments, and fixing your comments after every rebase.<br>
_Updated: 2020 04 06 &nbsp;&nbsp; Language: Python_

* [Recompiler](https://github.com/bastkerg/Recomp): IDA recompiler, no docs no help.<br>
_Updated: 2014 12 08 &nbsp;&nbsp; Language: Python_

* [RECON2017](https://github.com/tmr232/RECon2017): RECON 2017 IDA skin & color scheme<br>
_Updated: 2017 06 16 &nbsp;&nbsp; Language: Python_

* [Reef](https://github.com/darx0r/Reef): IDAPython plugin for finding Xrefs from a function.<br>
_Updated: 2016 07 14 &nbsp;&nbsp; Language: Python_

* [RefHUnter](https://github.com/eternalklaus/RefHunter): User-friendly reference finder in IDA. RefHunter provides a summary of references for a function, which includes more information than the built-in “Function calls” widget.<br>
_Updated: 2021 10 01 &nbsp;&nbsp; Language: Python_

* [REmatch](https://github.com/nirizr/rematch): REmatch, a complete binary diffing framework that works by revealing and identifying previously reverse engineered similar functions and migrating documentation and annotations to current IDB.<br>
_Updated: 2018 11 28 &nbsp;&nbsp; Language: Python_

* [REobjc](https://github.com/duo-labs/idapython): REobjc is an IDAPython module designed to make proper cross references between calling functions and called functions in Objective-C methods. The current form of the module supports X64, and will be updated to also support ARM in the future.<br>
_Updated: 2018 04 26 &nbsp;&nbsp; Language: Python_

* [RePEconstruct](https://github.com/davidkorczynski/repeconstruct): RePEconstruct is a tool for automatically unpacking binaries and rebuild the binaries in a manner well-suited for further analysis, specially focused on further manual analysis in IDA pro.<br>
_Updated: 2016 10 28_

* [RE Plugins](https://github.com/dzzie/RE_Plugins): Misc reverse engineering plugins released over the year: IDA_Jscript, IDA_JScript_w_DukDbg, IDASrvr, IDASRVR2, uGrapher, IdaVbScript, IdaUdpBridge, Wingraph32, gleegraph.<br>
_Updated: 2020 10 27 &nbsp;&nbsp; Language: C++_

* [REProgram](https://github.com/jkoppel/REProgram): A way of making almost-arbitrary changes to an executable when run under a debugger -- even changes that don't fit.<br>
_Updated: 2011 12 27 &nbsp;&nbsp; Language: C++_

* [resourcer](https://github.com/cseagle/resourcer): PE file resource enumeration plugin for IDA.<br>
_Updated: 2019 06 19 &nbsp;&nbsp; Language: C++_

* [retdec](https://github.com/avast/retdec-idaplugin): IDA plugin for retdec - a retargetable machine-code decompiler based on LLVM.<br>
_Updated: 2020 08 18 &nbsp;&nbsp; Language: C++_

* [ret-sync](https://github.com/bootleg/ret-sync): ret-sync stands for Reverse-Engineering Tools synchronization. It's a set of plugins that help to synchronize a debugging session (WinDbg/GDB/LLDB/OllyDbg2/x64dbg) with IDA disassembler. The underlying idea is simple: take the best from both worlds (static and dynamic analysis).<br>
_Updated: 2022 05 01 &nbsp;&nbsp; Language: Python_

* [REtypedef](https://github.com/zyantific/REtypedef): REtypedef is an IDA PRO plugin that allows defining custom substitutions for function names. It comes with a default ruleset providing substitutions for many common STL types.<br>
_Updated: 2015 01 03 &nbsp;&nbsp; Language: C++_

* [rizzo](https://github.com/devttys0/ida/tree/master/plugins/rizzo): Identifies and re-names functions between two or more IDBs based on:
  * Formal signatures (i.e., exact function signatures)
  * References to unique string
  * References to unique constants
  * Fuzzy signatures (i.e., similar function signatures)
  * Call graphs (e.g., identification by association)<br>
_Updated: 2021 06 02 &nbsp;&nbsp; Language: Python_

* [RTTI Parser](https://github.com/MlsDmitry/better-rtti-parser): IDA script to parse RTTI information in executable.<br>
_Updated: 2022 04 28 &nbsp;&nbsp; Language: Python_

* [Samsung S4 Rom Loader](https://github.com/cycad/mbn_loader): IDA Pro Loader Plugin for Samsung Galaxy S4 ROMs

* [Sark](https://github.com/tmr232/Sark/): Sark, (named after the notorious Tron villain,) is an object-oriented scripting layer written on top of IDAPython. Sark is easy to use and provides tools for writing advanced scripts and plugins.<br>
_Updated: 2022 03 18 &nbsp;&nbsp; Language: Python_

* [ScatterBee_Analysis](https://github.com/PwCUK-CTO/ScatterBee_Analysis): IDA scripts to aid analysis of files obfuscated with ScatterBee.<br>
_Updated: 2021 12 08 &nbsp;&nbsp; Language: Python_

* [ScratchABit](https://github.com/pfalcon/ScratchABit): ScratchABit is an interactive incremental disassembler with data/control flow analysis capabilities. ScratchABit is dedicated to the efforts of the OpenSource reverse engineering community (reverse engineering to produce OpenSource drivers/firmware for hardware not properly supported by vendors).<br>
_Updated: 2020 11 25_

* [Screen recorder](https://github.com/techbliss/Ida_Pro_Screen_Recorder): IDA Pro Qt Plugin for recording reversing sessions.<br>
_Updated: 2016 07 27 &nbsp;&nbsp; Language: Python_

* [Sega Genesis/Megadrive Tools 2](https://github.com/lab313ru/smd_ida_tools2): Special IDA Pro tools for the Sega Genesis/Megadrive romhackers. Updated to at least IDA 7.5<br>
_Updated: 2021 06 25 &nbsp;&nbsp; Language: C++_

* [ShannonRE](https://github.com/Comsecuris/shannonRE/tree/master/idapython): Helpful scripts for various tasks performed during reverse engineering the Shannon Baseband with the goal to exploit the Samsung Galaxy S6.<br>
_Updated: 2016 08 02 &nbsp;&nbsp; Language: Python_

* [Sig Maker](https://github.com/ajkhoury/SigMaker-x64): Can create sigs automatically and has a wide variety of functions.<br>
_Updated: 2021 07 28 &nbsp;&nbsp; Language: C++_

* [SigMakerEx](https://github.com/kweatherman/sigmakerex): Enhanced IDA Pro signature generator plugin.<br>
_Updated: 2022 02 16 &nbsp;&nbsp; Language: C++_

* [SimplifyGraph](https://github.com/fireeye/SimplifyGraph): An IDA Pro plugin to assist with complex graphs.<br>
_Updated: 2018 01 29 &nbsp;&nbsp; Language: C++_

* [Simulator](https://github.com/nihilus/IDASimulator): IDASimulator is a plugin that extends IDA's conditional breakpoint support, making it easy to augment / replace complex executable code inside a debugged process with Python code.<br>
_Updated: 2014 09 02 &nbsp;&nbsp; Language: Python_

* [Sk3wlDbg](https://github.com/cseagle/sk3wldbg): Debugger plugin for IDA Pro. Front end for using the Unicorn Engine to emulate machine code that you are viewing with IDA.<br>
_Updated: 2021 07 26 &nbsp;&nbsp; Language: C++_

* [SmartDec Plugin](https://github.com/smartdec/smartdec/tree/master/src/ida-plugin): SmartDec integration for IDA. SmartDec is a native code to C/C++ decompiler.<br>
_Updated: 2015 05 06 &nbsp;&nbsp; Language: C++_

* [SmartJump](https://github.com/PwCUK-CTO/SmartJump): IDA Pro plugin to enhance the JumpAsk 'g' keyboard shortcut.<br>
_Updated: 2020 09 14 &nbsp;&nbsp; Language: Python_

* [Snippet Detector](https://github.com/zaironne/SnippetDetector): Snippet Detector is an IDA Python scripts project used to detect snippets from 32bit disassembled files. snippet is the word used to identify a generic sequence of instructions (at the moment a snippet is indeed a defined function). The aim of the tool is to collect many disassembled snippets inside a database for the detection process.<br>
_Updated: 2015 04 24 &nbsp;&nbsp; Language: Python_

* [Snowman Decompiler](https://github.com/yegord/snowman): Snowman is a native code to C/C++ decompiler. Standalone and IDA Plugin. [Source Code](https://github.com/yegord/snowman)<br>
_Updated: 2021 06 21 &nbsp;&nbsp; Language: C++_

* [Splode](https://github.com/zachriggle/ida-splode): Augmenting Static Reverse Engineering with Dynamic Analysis and Instrumentation<br>
_Updated: 2014 10 10 &nbsp;&nbsp; Language: C++_

* [spu3dbg](https://github.com/revel8n/spu3dbg): Ida Pro debugger module for the anergistic SPU emulator.<br>
_Updated: 2016 03 28 &nbsp;&nbsp; Language: C++_

* [Stadeo](https://github.com/eset/stadeo): Stadeo is a set of tools primarily developed to facilitate analysis of Stantinko, which is a botnet performing click fraud, ad injection, social network fraud, password stealing attacks and cryptomining, using IDA.<br>
_Updated: 2021 11 08 &nbsp;&nbsp; Language: Python_

* [Stingray](https://github.com/darx0r/Stingray): Stingray is an IDAPython plugin for finding function strings. The search is from the current position onwards in the current function. It can do it recursively also with configurable search depth. The results order is the natural order of strings in the BFS search graph.<br>
_Updated: 2021 03 19 &nbsp;&nbsp; Language: Python_

* [Structure Dump](http://www.openrce.org/downloads/details/227/Structure_Dump): StructDump is an IDA plugin, allowing you to export IDA types into high-level language definitions. Currently, C++ is supported.<br>
_Updated: 2007 04 05 &nbsp;&nbsp; Language: C++_

* [Styler](https://github.com/techbliss/IDA-Styler): Small Plugin to change the style of Ida Pro.<br>
_Updated: 2014 07 25 &nbsp;&nbsp; Language: Python_

* [SusanRTTI](https://github.com/nccgroup/SusanRTTI): Another RTTI Parsing IDA plugin (GCC/MSVC).<br>
_Updated: 2020 11 02 &nbsp;&nbsp; Language: Python_

* [Swift Demangle](https://github.com/gsingh93/ida-swift-demangle): Demangle Swift function names. It currently only works for ELF files.<br>
_Updated: 2016 04 23 &nbsp;&nbsp; Language: Python_

* [syms2elf](https://github.com/danigargu/syms2elf): A plugin for IDA Pro and radare2 to export the symbols recognized to the ELF symbol table.<br>
_Updated: 2021 11 17 &nbsp;&nbsp; Language: Python_

* [doelf](https://github.com/antonpasm/doelf): A plugin for IDA Pro to export the symbols recognized to the ELF symbol table. It can create an ELF with debug information from any dump file.<br>
_Updated: 2022 05 31 &nbsp;&nbsp; Language: Python_

* [SyncReven](https://github.com/riskeco/SyncReven): Reven integration plugin: synchronize the Axion current analysis window with some code opened in IDA.<br>
_Updated: 2021 09 15 &nbsp;&nbsp; Language: Python_

* [Synergy](https://github.com/CubicaLabs/IDASynergy): A combination of an IDAPython Plugin and a control version system that result in a new reverse engineering collaborative addon for IDA Pro. By http://cubicalabs.com/<br>
_Updated: 2015 01 28 &nbsp;&nbsp; Language: Python_

* [Tarkus](https://github.com/tmr232/Tarkus): Tarkus is a plugin manager for IDA Pro, modelled after Python's pip.<br>
_Updated: 2015 08 13 &nbsp;&nbsp; Language: Python_

* [Tenet](https://github.com/gaasedelen/tenet): A Trace Explorer for Reverse Engineers. Provide more natural, human controls for navigating execution traces against a given binary.<br>
_Updated: 2021 09 14 &nbsp;&nbsp; Language: Python_

* [TurboDiff](http://www.coresecurity.com/corelabs-research/open-source-tools/turbodiff): Turbodiff is a binary diffing tool developed as an IDA plugin. It discovers and analyzes differences between the functions of two binaries.<br>
_Updated: 2011 12 13 &nbsp;&nbsp; Language: C++_

* [UEFI_RETool](https://github.com/yeggor/UEFI_RETool/tree/master/ida_plugin): IDA Plugin for UEFI firmware analysis. This plugin allows you to automatically analyse the input UEFI images, as well as search for dependencies between UEFI images in firmware.<br>
_Updated: 2021 08 03 &nbsp;&nbsp; Language: Python_

* [uEmu](https://github.com/alexhude/uEmu): uEmu is a tiny cute emulator plugin for IDA based on unicorn engine. Supports following architectures out of the box: x86, x64, ARM, ARM64, MIPS, MIPS64<br>
_Updated: 2021 10 13 &nbsp;&nbsp; Language: Python_

* [unity_metadata_loader](https://github.com/nevermoe/unity_metadata_loader): Load strings and method/class names in global-metadata.dat to IDA.<br>
_Updated: 2018 07 18 &nbsp;&nbsp; Language: Python_

* [Virtuailor](https://github.com/0xgalz/Virtuailor): Virtuailor is an IDAPython tool that reconstructs vtables for C++ code written for intel architechture and both 32bit and 64bit code.<br>
_Updated: 2020 06 06 &nbsp;&nbsp; Language: Python_

* [VirusBattle](https://github.com/axmat/virusbattle-ida-plugin): The plugin is an integration of Virus Battle API to the well known IDA Disassembler. Virusbattle is a web service that analyses malware and other binaries with a variety of advanced static and dynamic analyses.<br>
_Updated: 2015 05 26 &nbsp;&nbsp; Language: Python_

* [VMAttack](https://github.com/anatolikalysch/VMAttack): Static and dynamic virtualization-based packed analysis and deobfuscation.<br>
_Updated: 2017 11 30 &nbsp;&nbsp; Language: Python_

* [Void](https://github.com/dove-zp/ida.plugin.void): A 'No Operation' Generator. Creates NOP'd areas though simple convenient actions to relevant right click menus.<br>
_Updated: 2022 04 08 &nbsp;&nbsp; Language: Python_

* [VTBL](https://github.com/nektra/vtbl-ida-pro-plugin): VTBL is an IDA script which identifies all the virtual tables found in any module of a native process. The virtual tables can be related to a COM or a C++ class.<br>
_Updated: 2013 03 27 &nbsp;&nbsp; Language: C++_

* [VT-IDA Plugin](https://github.com/VirusTotal/vt-ida-plugin): This is the official VirusTotal plugin for Hex-Rays IDA Pro. This plugin integrates functionality from VirusTotal web services into the IDA Pro's user interface.<br>
_Updated: 2020 10 05 &nbsp;&nbsp; Language: Python_

* [VulFi](https://github.com/Accenture/VulFi): The VulFi (Vulnerability Finder) tool is a plugin to IDA Pro which can be used to assist during bug hunting in binaries. Its main objective is to provide a single view with all cross-references to the most interesting functions (such as strcpy, sprintf, system, etc.).<br>
_Updated: 2022 04 11 &nbsp;&nbsp; Language: Python_

* [WakaTime](https://github.com/es3n1n/ida-wakatime-py): WakaTime integration for IDA Pro: time tracking plugin showing the time you spend using IDA.<br>
_Updated: 2022 05 18 &nbsp;&nbsp; Language: Python_

* [wilhelm](https://github.com/zerotypic/wilhelm): Alternative API for IDA and Hex-Rays. wilhelm is an API for working with IDA, and in particular the Hex-Rays decompiler. It aims to wrap around the existing SDK's API, plus provide additional features and concepts that make reverse engineering easier.<br>
_Updated: 2022 02 03 &nbsp;&nbsp; Language: Python_

* [Win32 LST to Inline Assembly](https://github.com/binrapt/ida): Python script which extracts procedures from IDA Win32 LST files and converts them to correctly dynamically linked compilable Visual C++ inline assembly.<br>
_Updated: 2009 07 10 &nbsp;&nbsp; Language: Python_

* [Windows Driver Plugin](https://github.com/FSecureLABS/win_driver_plugin): A tool to help when dealing with Windows IOCTL codes or reversing Windows drivers.<br>
_Updated: 2018 08 22 &nbsp;&nbsp; Language: Python_

* [WinIOCtlDecoder](https://github.com/tandasat/WinIoCtlDecoder): An IDA Pro plugin which decodes a Windows Device I/O control code into DeviceType, FunctionCode, AccessType and MethodType.<br>
_Updated: 2015 06 02 &nbsp;&nbsp; Language: Python_

* [WWCD](https://github.com/sektioneins/wwcd): What Would Capstone Decode - IDA plugin that implements a Capstone powered IDA view.<br>
_Updated: 2016 11 29 &nbsp;&nbsp; Language: C++_

* [x64dbgida](https://github.com/x64dbg/x64dbgida): Official x64dbg plugin for IDA Pro.<br>
_Updated: 2022 04 24 &nbsp;&nbsp; Language: Python_

* [X86Emu](https://github.com/cseagle/x86emu): Embedded x86 emulator for Ida Pro. Its purpose is to allow a reverse engineer the chance to step through x86 code while reverse engineering a binary. The plugin can help you step through any x86 binary from any platform. For Windows binaries, many common library calls are trapped and emulated by the emulator, allowing for a higher fidelity emulation. I find it particularly useful for stepping through obfuscated code as it automatically reorganizes an IDA disassembly based on actual code paths.<br>
_Updated: 2020 10 13 &nbsp;&nbsp; Language: C++_

* [xdeobf](https://github.com/teapotd/xdeobf): Experimental deobfuscation plugin for IDA 7.2. It aims to reverse control flow flattening transformation that I encountered (probably a variation of obfuscator-llvm).<br>
_Updated: 2020 03 24 &nbsp;&nbsp; Language: C++_

* [Xex Loader for IDA 6.6](http://xorloser.com/blog/?p=395): This adds the ability to load xex files into IDA directly without having to first process them in any way. It processes the xex file as much as possible while loading to minimise the work required by the user to get it to a state fit for reversing.<br>
_Updated: 2013 09 23_

* [xray](https://github.com/patois/xray): Hexrays decompiler plugin that colorizes and filters the decompiler's output based on regular expressions<br>
_Updated: 2022 01 29 &nbsp;&nbsp; Language: Python_

* [YaCo](https://github.com/DGA-MI-SSI/YaCo): Collaborative Reverse-Engineering for IDA. When enabled, an unlimited number of users can work simultaneously on the same binary. Any modification done by any user is synchronized through git version control. It has been initially released at [SSTIC 2017](https://www.sstic.org/2017/presentation/YaCo/)<br>
_Updated: 2018 11 14 &nbsp;&nbsp; Language: Python_

* [Yagi](https://github.com/airbus-cert/Yagi): Yet Another Ghidra Integration for IDA. Yagi intends to include the wonderful Ghidra decompiler into both IDA pro and IDA Free.<br>
_Updated: 2021 12 20 &nbsp;&nbsp; Language: C++_



## Credits

The original list of 200 plugins came from
[onethawt](https://github.com/onethawt)'s excellent
[idaplugins-list](https://github.com/onethawt/idaplugins-list). His and
other contributors' work was essential in putting together this
interactive list.


## Authors

* Vincent Mallet ([vmallet](https://github.com/vmallet))
