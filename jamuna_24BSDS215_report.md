

#Directory and File Structure  
- Created a primary directory named "data_etl" with 12 subdirectories for each month. 
- Added job scripts like "extract_sales_data.py", "transform_customer_data.py", and "load_orders-data.py" into respective month directories.  

#File Operations 
- Moved "transform_customer_data.py" from the "march" directory to the "may" directory to reorganize tasks.
- Renamed "transform_customer_data.py" to "new_transform_customer_data.py" to reflect updated job processes. 

#File Permissions Management  
- Created a sensitive file "sensitive_data_load.sh" for secure job execution. 
- Set permissions ('700') so only authorized users can read, write, and execute. 

#Backup Operations  
- Backed up critical scripts like "sensitive_data_load.sh" into a "backup" directory. 
- Verified the backup's existence using file listing. 

#File and Directory Cleanup
- Deleted an outdated script, 'extract_sales_data.py", no longer in use.
- Removed the empty "march" directory to maintain a clean file structure. 
- Wrote a script to automatically delete all empty directories in "data_etl" after tasks complete. 

#File Sorting and Organization  
- Sorted job files by "modification date" (newest and oldest) using appropriate Linux commands. 
- Sorted files by size to identify the largest ETL scripts for possible optimization. 

#File Compression and Archival 
- Archived the entire 'data_et' directory into a compressed file named 'data_etl_backup.tar.gz'.
- Verified the archive contents to ensure all necessary files were included. 

#System Monitoring  
- Checked "server uptime" to ensure continuous operation for ETL job execution. 
 
#Network Connectivity Verification  
- Tested network connectivity to external sources (e.g., cloud storage, APIs) using a "ping test". 
- Confirmed stable connectivity with no packet loss. 

#Automation for File Generation  
- Automated the creation of 100 sample ETL job files for extraction, transformation, and loading processes using a Bash script. 

#Command History Management  
- Fetched and reviewed the last 20 commands executed on the server. 
- Saved the complete command history for documentation purposes in "jamuna_24BSDS215.md" 
 
#User-Specific Directory Creation  
- Created dedicated directories for users, such as "data_analyst" and "etl_admin". 
- Set permissions to ensure only respective users and admins could access their directories. 

#Summary of Key Maintenance Tasks**  
- Reorganized file structures, set security permissions, backed up key job scripts, cleaned unused files, monitored resources, and automated repetitive tasks.  

#Final Status**  
- "Directories and files' are well-organized, secured, and archived. 
- "Server uptime" and resource usage were verified to ensure optimal performance. 
- All ETL tasks, backups, and cleanups have been completed and document.
