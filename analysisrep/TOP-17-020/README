# Setup: 
## Higgs Combine tool at CMSSW_7_4_7

# Declare:
## TOP_EFT_Models_search_NLO.py is for model
## datacard directory contains datacard for different process, the path of input file need to be adjusted 
## input directory contains the histograms

#Usage:
##copy TOP_EFT_Models_search_NLO.py to CMSSW_7_4_7/bin/slc6_amd64_gcc491
##change the input root file path in datacard file 
##use "text2workspace.py input_card_name -o output_ws_name -P TOP_EFT_Models_search_NLO:yourModelName" to produce the workspace
##use "combine -M MultiDimFit workSpace.root -m 125.7 -n obs_scan --algo=grid" to do likelihood scan for observed
##use "combine -M MultiDimFit workSpace.root -m 125.7 -n obs_scan --algo=grid -t -1 --expectSignal=0" to do likelihood scan for expected
