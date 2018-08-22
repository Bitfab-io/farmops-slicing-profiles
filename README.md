# Bitfab farm slicing profiles

## How to export printing profiles from the Slic3r GUI to the repo

1. Open Slic3r Prusa Edition
2. Export config bundle
3. Open the `.ini` file with a text editor
4. Remove the unnecessary profiles
	* Remove Prusa print, printer and filament profiles
	* Remove test profiles
	* Remove profiles with Octoprint API keys
5. Upload the profile to the repo. File name `bfc_Slic3r_config_bundle.ini`
6. Done

## How to import printing profiles in the Slic3r GUI

1. Open Slic3r Prusa Edition
2. Go to `File > Load config bundle`
3. Load `bfc_Slic3r_config_bundle.ini`
4. Done.