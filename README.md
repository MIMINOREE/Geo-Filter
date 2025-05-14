# Geo-Filter

Geo-Filter is a Windows PowerShell-based tool with a simple graphical interface to manage outbound firewall rules based on imported IPs or CIDR ranges.

## Features

- **Import**: Load a `.txt` file with a list of IP addresses or CIDR ranges to block via Windows Firewall.
- **Enable**: Enable all rules created with the name `BLOCK *`.
- **Disable**: Disable all rules created with the name `BLOCK *`.
- **Remove**: Delete all rules created with the name `BLOCK *`.
- **Check**: Opens the Windows Firewall console and prompts you an instruction to manually click on **"Outbound Rules"**.

## Video
- https://youtu.be/CQfLD59Ch0o
  
## How to Use

1. **Download**
   - Go to the [Releases](https://github.com/MIMINOREE/Geo-Filter/releases) page.
   - Download & Extract:
     - `Geo-Filter.zip`

2. **Run the Tool**
   - **Once extracted**:
     - Right-click Geo-Filter.exe, then choose **Run as Administrator**.
       
4. **How to use**
   - **Import**: Select your IP list file to create a new outbound blocking rule.
   - **Enable**: Reactivate all existing `BLOCK` rules.
   - **Disable**: Temporarily disable those rules.
   - **Remove**: Delete all `BLOCK` rules.
   - **Check**: Opens the firewall UI and prompts you to click **"Outbound Rules"** manually.



**ADDITIONAL NOTE**
- You can manually create a .txt file with IPs or CIDR ranges to block. Each entry should be on a new line.
