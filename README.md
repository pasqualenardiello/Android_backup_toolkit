# Android_backup_toolkit
"A series of bash script to optimize android devices backups"

This is a set of bash compatible scripts designed to interact with TWRP recovery and its "adb backup" feature.

Right now the set is composed of two main scripts and other two auxiliary scripts.

The "backup" script is the main interface during the backup operation while the "mngmode" script is a secondary script for managing and checking the existent backups.

The "infoprovider" and the "rmchck" scripts are used in background in order to retrive additional informations from devices and to keep order in the folders structure.
