# oracle_pdb_Ass_2_MUGANAMFURA-Bizimana-Nancy-20251IMA068
Name: Muganamfura Bizimana Nancy Student ID: 20251IMA068
## Task 1: Create a New Pluggable Database
A new Pluggable Database (PDB) was created in Oracle Database 21c using the PDB seed.
## PDB creation command
[Screenshot] (https://github.com/MuganamfuraNancy24/Assignment_2_MUGANAMFURA-Bizimana-Nancy-20251IMA068/blob/188c16d04f111d4458488d30873325a7d77bd6dd/Screenshot%202026-09-21%20082221.png)
## PDB open state
[Screenshot] (https://github.com/MuganamfuraNancy24/Assignment_2_MUGANAMFURA-Bizimana-Nancy-20251IMA068/blob/4dd4183e59bcc18c17c47b09c42b5f0a28f0caa6/Screenshot%202026-09-21%20082221.png)
## User created inside PDB username clearly visible
[Screenshot] https://github.com/MuganamfuraNancy24/Assignment_2_MUGANAMFURA-Bizimana-Nancy-20251IMA068/blob/4cdc08408ff790841592d4fe0f6088b424034337/Screenshot%202026-09-21%20082251.png)
## Task 2: Create and Delete a PDB
A temporary PDB  was created and verified in Oracle Database 21c. After completing the required checks, the PDB was closed and deleted along with its data files. The deletion was then verified successfully.

## PDB creation command + result visible
[Screenshot] (https://github.com/MuganamfuraNancy24/Assignment_2_MUGANAMFURA-Bizimana-Nancy-20251IMA068/blob/95e04cce12b27c37d6e044b49c65d9c5e00ccbca/Screenshot%202026-09-22%20161957.png)
## PDB deletion command + result visible
[Screenshot] (https://github.com/MuganamfuraNancy24/Assignment_2_MUGANAMFURA-Bizimana-Nancy-20251IMA068/blob/ba5f0512575783c0c59cc2a7458af34068bc594f/Screenshot%202026-09-22%20162355.png)
## Task 3: Oracle Enterprise Manager (OEM)
## Clear screenshot of the OEM dashboard



## Oracle Environment Used
Database: Oracle Database 21c
Tool: Oracle SQL Developer / SQL Plus
Operating System: Windows
Database Architecture: Container Database (CDB) with Pluggable Databases (PDBs)
Database User: Administrative user with privileges to create and delete PDBs
## Challenges faced (if any) and how they were solved
### Challenges and Solutions
ORA-65005 file path error: The PDB creation failed because the file path was incorrect. 
Solution: I checked the actual Oracle data-file location and used the correct Windows path.
ORA-65020 PDB already closed: The PDB was already closed when I tried to close it again. 
Solution: I confirmed its status and proceeded to the deletion step.

