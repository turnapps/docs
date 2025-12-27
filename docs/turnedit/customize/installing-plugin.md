# Installing plugin
#### This guide explains how to manually install plugins for TurnEdit. This process is consistent across all versions of TurnEdit.
> [!IMPORTANT]
> Security Requirement: The sha256.txt file is mandatory for all plugins to ensure integrity and prevent unauthorized modifications.

> [!IMPORTANT]
> Plugins must be .NET assembly.

## 01.Prepare Plugin Files
Plugins are typically distributed as `.zip` files. Extract the zip file to a temporary location. You should find at least the following two files:
- `YourPluginName.dll` (The actual plugin file)
- `sha256.txt` (Checksum file for security)
## 02.Locate Installation Directory
Open the folder where TurnEdit.exe is installed. You will find two essential folders:  
TurnEdit/  
├── TurnEdit.exe  
├── plugins/ (Place DLLs here)  
└── checksums/ (Place TXT files here)  
## 03.Deploy Files
Move the extracted files to their respective directories. **The checksum file must match the plugin's filename**.  

| Original File | Destination and Renaming |
| --- | --- |
| `Example.dll` | `/plugins/Example.dll` |
| `sha256.txt` | `/checksums/Example-sha256.txt` |

## 04.Restart TurnEdit
Restart TurnEdit to apply the changes. The software will verify the `.dll` against the `sha256.txt` in the checksums folder before loading.
