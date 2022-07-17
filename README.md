# ELKO Living System on Home Assistant
This is a custom setup file for ELKO Living System products on Home Assistant. This is just a custom file to include the norwegian and swedish products of ELKO Living System. 
The IHC products are not all the same as ELKO. You need to use the IHC Controller integration on Home Assistant, with this custom file. 

All credit to dingusdk for the integration that makes this possible. 

## Installation
1. Install the IHC integration on your Home Assistant (https://github.com/dingusdk/haihc-betatest.git)
2. Copy the ihc_auto_setup.yaml and replace it with the corresponding file from the IHC Controller integration on your Home Assistant. (config/custom components/ihc)
3. Restart Home Assistant
4. Customize