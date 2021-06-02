# Changes since 2021-05-19

## Changes in Algorithm

- [#6253](https://github.com/AliceO2Group/AliceO2/pull/6253) 2021-06-02: Drop o2::byte by [@ktf](https://github.com/ktf)
## Changes in Analysis

- [#6220](https://github.com/AliceO2Group/AliceO2/pull/6220) 2021-05-21: Event selection adapted to Run2 and Run3 MC by [@ekryshen](https://github.com/ekryshen)
- [#6232](https://github.com/AliceO2Group/AliceO2/pull/6232) 2021-05-22: Do not use printf by [@ktf](https://github.com/ktf)
- [#6225](https://github.com/AliceO2Group/AliceO2/pull/6225) 2021-05-25: DPL Analysis: Handle unassigned (-1) index in grouping by [@aalkin](https://github.com/aalkin)
- [#6237](https://github.com/AliceO2Group/AliceO2/pull/6237) 2021-05-25: Fixes in doxygen: by [@ihrivnac](https://github.com/ihrivnac)
- [#6254](https://github.com/AliceO2Group/AliceO2/pull/6254) 2021-05-27: Avoid tuple in analysis task by [@ktf](https://github.com/ktf)
- [#6255](https://github.com/AliceO2Group/AliceO2/pull/6255) 2021-05-28: PWGHF: Fix track selection in index skimming by [@vkucera](https://github.com/vkucera)
- [#6266](https://github.com/AliceO2Group/AliceO2/pull/6266) 2021-05-30: Add flag to check if a track has TOF by [@njacazio](https://github.com/njacazio)
- [#6271](https://github.com/AliceO2Group/AliceO2/pull/6271) 2021-05-30: PWGHF: Switch MC on by default by [@vkucera](https://github.com/vkucera)
- [#6260](https://github.com/AliceO2Group/AliceO2/pull/6260) 2021-05-30: support unassigned indices by [@jgrosseo](https://github.com/jgrosseo)
- [#6289](https://github.com/AliceO2Group/AliceO2/pull/6289) 2021-06-01: DPL: avoid dependency on boost for trivial stuff by [@ktf](https://github.com/ktf)
- [#6302](https://github.com/AliceO2Group/AliceO2/pull/6302) 2021-06-02: DPL Analysis: avoid instantiating HistFactory functions for each TU by [@mario-krueger](https://github.com/mario-krueger)
- [#6301](https://github.com/AliceO2Group/AliceO2/pull/6301) 2021-06-02: DPL Analysis: fix AnalysisTask test after renaming data model table by [@aalkin](https://github.com/aalkin)
- [#6273](https://github.com/AliceO2Group/AliceO2/pull/6273) 2021-06-02: Fixing typo in VarManager by [@mcoquet642](https://github.com/mcoquet642)
- [#6284](https://github.com/AliceO2Group/AliceO2/pull/6284) 2021-06-02: documentation of data model. renaming unassigned tracks table by [@jgrosseo](https://github.com/jgrosseo)
## Changes in Common

- [#6211](https://github.com/AliceO2Group/AliceO2/pull/6211) 2021-05-20: DPL: use Resource Manager to optimize shared memory usage by [@ktf](https://github.com/ktf)
- [#6222](https://github.com/AliceO2Group/AliceO2/pull/6222) 2021-05-31: dcs-config-proxy and sample consumer workflow by [@shahor02](https://github.com/shahor02)
- [#6274](https://github.com/AliceO2Group/AliceO2/pull/6274) 2021-06-02: Avoid inclusion of Vc/Vc in RandomRing by [@sawenzel](https://github.com/sawenzel)
## Changes in DataFormats

- [#6228](https://github.com/AliceO2Group/AliceO2/pull/6228) 2021-05-21: missing includes to compile with gcc11 by [@wiechula](https://github.com/wiechula)
- [#6236](https://github.com/AliceO2Group/AliceO2/pull/6236) 2021-05-24: BadChannelsMap renamed by [@peressounko](https://github.com/peressounko)
- [#6242](https://github.com/AliceO2Group/AliceO2/pull/6242) 2021-05-26: [TRD] remove tabs and trailing whitespaces by [@martenole](https://github.com/martenole)
- [#6247](https://github.com/AliceO2Group/AliceO2/pull/6247) 2021-05-28: Headers: remove unneeded traits by [@ktf](https://github.com/ktf)
- [#6222](https://github.com/AliceO2Group/AliceO2/pull/6222) 2021-05-31: dcs-config-proxy and sample consumer workflow by [@shahor02](https://github.com/shahor02)
- [#6300](https://github.com/AliceO2Group/AliceO2/pull/6300) 2021-06-02: Add back cerrno by [@ktf](https://github.com/ktf)
- [#6253](https://github.com/AliceO2Group/AliceO2/pull/6253) 2021-06-02: Drop o2::byte by [@ktf](https://github.com/ktf)
## Changes in Detectors

- [#6210](https://github.com/AliceO2Group/AliceO2/pull/6210) 2021-05-19: Fix for a typo in FT0 RecPointReaderSpec (from N.Burmasov) by [@shahor02](https://github.com/shahor02)
- [#6205](https://github.com/AliceO2Group/AliceO2/pull/6205) 2021-05-19: [MFT] Marking reconstructed tracks on the MC AOD table by [@rpezzi](https://github.com/rpezzi)
- [#6207](https://github.com/AliceO2Group/AliceO2/pull/6207) 2021-05-20: [MCH] prepare setup for run3 by [@pillot](https://github.com/pillot)
- [#6206](https://github.com/AliceO2Group/AliceO2/pull/6206) 2021-05-20: minor fixes in TPC CalArray and TPC/qc PID by [@tklemenz](https://github.com/tklemenz)
- [#6228](https://github.com/AliceO2Group/AliceO2/pull/6228) 2021-05-21: missing includes to compile with gcc11 by [@wiechula](https://github.com/wiechula)
- [#6229](https://github.com/AliceO2Group/AliceO2/pull/6229) 2021-05-22: GPU: Option renaming, and grouping of TRD and TPC options by [@davidrohr](https://github.com/davidrohr)
- [#6233](https://github.com/AliceO2Group/AliceO2/pull/6233) 2021-05-23: Suppress leftover PHOSCalib directory [fix for PR6187] by [@shahor02](https://github.com/shahor02)
- [#6234](https://github.com/AliceO2Group/AliceO2/pull/6234) 2021-05-23: fix in CCDB populator documentation by [@shahor02](https://github.com/shahor02)
- [#6236](https://github.com/AliceO2Group/AliceO2/pull/6236) 2021-05-24: BadChannelsMap renamed by [@peressounko](https://github.com/peressounko)
- [#6237](https://github.com/AliceO2Group/AliceO2/pull/6237) 2021-05-25: Fixes in doxygen: by [@ihrivnac](https://github.com/ihrivnac)
- [#6242](https://github.com/AliceO2Group/AliceO2/pull/6242) 2021-05-26: [TRD] remove tabs and trailing whitespaces by [@martenole](https://github.com/martenole)
- [#6262](https://github.com/AliceO2Group/AliceO2/pull/6262) 2021-05-27: More fixes in doxygen: by [@ihrivnac](https://github.com/ihrivnac)
- [#6230](https://github.com/AliceO2Group/AliceO2/pull/6230) 2021-05-28: MFT Noise calibration by [@mcoquet642](https://github.com/mcoquet642)
- [#6272](https://github.com/AliceO2Group/AliceO2/pull/6272) 2021-05-31: RawFileWriter can handle empty HBF fillers of >8KB by [@shahor02](https://github.com/shahor02)
- [#6222](https://github.com/AliceO2Group/AliceO2/pull/6222) 2021-05-31: dcs-config-proxy and sample consumer workflow by [@shahor02](https://github.com/shahor02)
- [#6279](https://github.com/AliceO2Group/AliceO2/pull/6279) 2021-06-01: Treat FLUKA_VMC like a real plugin by [@sawenzel](https://github.com/sawenzel)
- [#6267](https://github.com/AliceO2Group/AliceO2/pull/6267) 2021-06-01: [MCH] use configurable parameters for MCH tracking by [@pillot](https://github.com/pillot)
- [#6274](https://github.com/AliceO2Group/AliceO2/pull/6274) 2021-06-02: Avoid inclusion of Vc/Vc in RandomRing by [@sawenzel](https://github.com/sawenzel)
- [#6253](https://github.com/AliceO2Group/AliceO2/pull/6253) 2021-06-02: Drop o2::byte by [@ktf](https://github.com/ktf)
- [#6298](https://github.com/AliceO2Group/AliceO2/pull/6298) 2021-06-02: Fix in requesting FT0 data for PVertex validation by [@shahor02](https://github.com/shahor02)
- [#6263](https://github.com/AliceO2Group/AliceO2/pull/6263) 2021-06-02: pythia8 generator flag will start empty pythia8 config, make sure you… by [@preghenella](https://github.com/preghenella)
## Changes in Examples

- [#6221](https://github.com/AliceO2Group/AliceO2/pull/6221) 2021-05-21: o2-sim: Improve communication between primary server and transport wo… by [@sawenzel](https://github.com/sawenzel)
- [#6263](https://github.com/AliceO2Group/AliceO2/pull/6263) 2021-06-02: pythia8 generator flag will start empty pythia8 config, make sure you… by [@preghenella](https://github.com/preghenella)
## Changes in Framework

- [#6215](https://github.com/AliceO2Group/AliceO2/pull/6215) 2021-05-20: DPL: hotfix for resource manager by [@ktf](https://github.com/ktf)
- [#6211](https://github.com/AliceO2Group/AliceO2/pull/6211) 2021-05-20: DPL: use Resource Manager to optimize shared memory usage by [@ktf](https://github.com/ktf)
- [#6208](https://github.com/AliceO2Group/AliceO2/pull/6208) 2021-05-20: Dropping old / obsolete / unmaintained code by [@ktf](https://github.com/ktf)
- [#6212](https://github.com/AliceO2Group/AliceO2/pull/6212) 2021-05-21: DPL: add test for ability to create transport by [@ktf](https://github.com/ktf)
- [#6218](https://github.com/AliceO2Group/AliceO2/pull/6218) 2021-05-21: DPL: properly handle SIGTERM by [@ktf](https://github.com/ktf)
- [#6228](https://github.com/AliceO2Group/AliceO2/pull/6228) 2021-05-21: missing includes to compile with gcc11 by [@wiechula](https://github.com/wiechula)
- [#6225](https://github.com/AliceO2Group/AliceO2/pull/6225) 2021-05-25: DPL Analysis: Handle unassigned (-1) index in grouping by [@aalkin](https://github.com/aalkin)
- [#6238](https://github.com/AliceO2Group/AliceO2/pull/6238) 2021-05-25: DPL Analysis: Update histogram registry spec to make it more distinguishable by [@saganatt](https://github.com/saganatt)
- [#6241](https://github.com/AliceO2Group/AliceO2/pull/6241) 2021-05-26: Fix parsing for InputSpec with DataOrigin only by [@shahor02](https://github.com/shahor02)
- [#6254](https://github.com/AliceO2Group/AliceO2/pull/6254) 2021-05-27: Avoid tuple in analysis task by [@ktf](https://github.com/ktf)
- [#6256](https://github.com/AliceO2Group/AliceO2/pull/6256) 2021-05-27: DPL: improve workflow validation by [@ktf](https://github.com/ktf)
- [#6217](https://github.com/AliceO2Group/AliceO2/pull/6217) 2021-05-28: DPL Analysis: send the size of the tables as metric by [@ktf](https://github.com/ktf)
- [#6240](https://github.com/AliceO2Group/AliceO2/pull/6240) 2021-05-28: DPL: improve shared memory handling in AOD by [@ktf](https://github.com/ktf)
- [#6268](https://github.com/AliceO2Group/AliceO2/pull/6268) 2021-05-29: DPL: rationalise parent-child communication by [@ktf](https://github.com/ktf)
- [#6266](https://github.com/AliceO2Group/AliceO2/pull/6266) 2021-05-30: Add flag to check if a track has TOF by [@njacazio](https://github.com/njacazio)
- [#6276](https://github.com/AliceO2Group/AliceO2/pull/6276) 2021-05-31: DPL DDS: use id rather than name for task id by [@ktf](https://github.com/ktf)
- [#6222](https://github.com/AliceO2Group/AliceO2/pull/6222) 2021-05-31: dcs-config-proxy and sample consumer workflow by [@shahor02](https://github.com/shahor02)
- [#6289](https://github.com/AliceO2Group/AliceO2/pull/6289) 2021-06-01: DPL: avoid dependency on boost for trivial stuff by [@ktf](https://github.com/ktf)
- [#6283](https://github.com/AliceO2Group/AliceO2/pull/6283) 2021-06-01: DPL: cleanup AODReaderHelpers.cxx by [@ktf](https://github.com/ktf)
- [#6290](https://github.com/AliceO2Group/AliceO2/pull/6290) 2021-06-01: DPL: reduce template instanciation by [@ktf](https://github.com/ktf)
- [#6302](https://github.com/AliceO2Group/AliceO2/pull/6302) 2021-06-02: DPL Analysis: avoid instantiating HistFactory functions for each TU by [@mario-krueger](https://github.com/mario-krueger)
- [#6301](https://github.com/AliceO2Group/AliceO2/pull/6301) 2021-06-02: DPL Analysis: fix AnalysisTask test after renaming data model table by [@aalkin](https://github.com/aalkin)
- [#6253](https://github.com/AliceO2Group/AliceO2/pull/6253) 2021-06-02: Drop o2::byte by [@ktf](https://github.com/ktf)
- [#6284](https://github.com/AliceO2Group/AliceO2/pull/6284) 2021-06-02: documentation of data model. renaming unassigned tracks table by [@jgrosseo](https://github.com/jgrosseo)
## Changes in Generators

- [#6263](https://github.com/AliceO2Group/AliceO2/pull/6263) 2021-06-02: pythia8 generator flag will start empty pythia8 config, make sure you… by [@preghenella](https://github.com/preghenella)
## Changes in Steer

- [#6239](https://github.com/AliceO2Group/AliceO2/pull/6239) 2021-05-25: Fix: QED interaction sampler was using default BC scheme by [@shahor02](https://github.com/shahor02)
## Changes in Utilities

- [#6208](https://github.com/AliceO2Group/AliceO2/pull/6208) 2021-05-20: Dropping old / obsolete / unmaintained code by [@ktf](https://github.com/ktf)
- [#6245](https://github.com/AliceO2Group/AliceO2/pull/6245) 2021-05-26: Grep logfile always as ascii file not as binary in jobutils.sh by [@davidrohr](https://github.com/davidrohr)
- [#6253](https://github.com/AliceO2Group/AliceO2/pull/6253) 2021-06-02: Drop o2::byte by [@ktf](https://github.com/ktf)
