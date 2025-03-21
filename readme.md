# Detection Engineering using Elastic Security

This repository demonstrates a detection engineering project using **Elastic Security**. The focus is on creating a detection rule to identify traffic generated by **Nmap** and **Nikto** tools.

## Files in this Repository:
- **`kql_query.kql`**: The custom KQL query used to detect Nmap and Nikto traffic.
- **`rules_export.ndjson`**: The exported detection rule in **ndjson** format for import into Elastic.
- **`logs_filtered.csv`**: Exported logs from **Elastic Security** in CSV format for analysis.
- **`/screenshots`**: Folder containing screenshots of the attack, rule creation, and alerts.
- **`attack_analysis.md`**: Detailed analysis of the attack, detection rule creation, and findings. Please check this file for step-by-step instructions.

## How to Use:
1. **Review `attack_analysis.md`**: This file contains a step-by-step breakdown of the attack, rule creation process, and the analysis conducted.
2. **KQL Query (`kql_query.kql`)**: The query used to filter Nmap and Nikto user-agent traffic.
3. **Detection Rule (`rules_export.ndjson`)**: The detection rule file, which can be imported into Elastic.
4. **Logs (`logs_filtered.csv`)**: Analyze the exported logs from Elastic using CSV format.
5. **Screenshots**: View the folder for screenshots documenting the process and analysis.

## Notes:
- This project demonstrates the ability to detect malicious traffic and configure detection rules using Elastic.
- The analysis file contains more details on the attack, how the detection rule was written, and how alerts were triggered.


---


