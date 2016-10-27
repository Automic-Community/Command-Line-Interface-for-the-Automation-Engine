*Command Line Interface for the Automation Engine*
=============


Powerful CLI Tool for CRUD operations on AE Objects
http://github.com/Automic-Community/Command-Line-Interface-for-the-Automation-Engine

<!-- List of attached files -->
Contents of Solution Package:

						
								*CLI_ReadMe.pdf
								
						


Documenation and Instructions
---

<p>The latest version of the Command Line Binaries is always available at the following link:</p>
<p>https://github.com/brendanSapience/UC4-Automic-AE-CLI-Binary-Repository</p>
<p>The documentation can be found on the same page.</p>
<p>Any request for additional features is welcome! Feel free to make suggestions on the github page directly.</p>
<p>&nbsp;</p>
<p>Features currently available:</p>
<pre style="box-sizing: border-box; font-family: Consolas, 'Liberation Mono', Menlo, Courier, monospace; font-size: 13.6px; margin-top: 0px; font-stretch: normal; line-height: 1.45; word-wrap: normal; padding: 16px; overflow: auto; background-color: #f7f7f7; border-radius: 3px; color: #333333; margin-bottom: 0px !important;"><code style="box-sizing: border-box; font-family: Consolas, 'Liberation Mono', Menlo, Courier, monospace; font-size: 13.6px; padding: 0px; margin: 0px; background: transparent; border-radius: 3px; word-break: normal; border: 0px; display: inline; overflow: visible; line-height: inherit; word-wrap: normal;">**## OBJECT Specific CLI Binaries:**

    * CALE_Update.jar: Update / import CALE Objects from JSON files. 
    * AGENTS_Management.jar: Manage Agents from Client 0 (assign to other clients, delete, etc.) (ex: allow all clients to use Agent WIN01 for Execution)
    * HOSTGROUPS_Management.jar: Manage Hostgroups (add agents, run simulations, remove agents, etc.)
    * CHANGES_Show.jar:     Display content of Audit Trail with filters (needs to be activated in Client 0 first)   
    * CONN_Update.jar:  Update CONN Objects (including RA CONN such as SOAP or REST CONNs)
    * JOBS_RA_Update.jar:   Update RA Jobs (SOAP, REST, FTP, etc.)
    * JSCH_Update.jar:  Update SCHED Objects
    * LOGIN_Update.jar: Update LOGIN Objects
    * STORAGE_Update.jar:   Update STORAGE Objects (only v11.2 and up)
    * TASKS_Operations.jar: Handle Operations on Activities Window (Deactivate all "Completed" tasks, restart aborted JOBS tasks with title matching ".*DEV.*")
    * USER_Update.jar:  Update USER Objects
    * VARA_SQL_Update.jar:  Update SQL VARA Objects
    * VARA_SQLI_Update.jar: Update SQLI VARA Objects
    * VARA_STATIC_Update.jar: Update STATIC &amp; XML VARA Objects (XML VARA is a subtype of STATIC)
    * VARA_Update.jar:  Update General Properties of VARA Objects
    * JOBF_Update.jar:      Update JOBF Objects. (ex: change the pattern for Destination File in all JOBF objects at once)
    * JOBP_Update.jar:      Update JOBP Objects. (ex: update all task names for all Workflows at once)
    * JOBS_SQL_Update.jar:  Update JOBS_SQL Objects (ex: modify the Database Connection name in all JOBS_SQL containing "*SQL1*" in their name)
    * JOBS_Update.jar:      Update JOBS Objects (ex: modify the name of a variable in all JOBS containing "*ABC*" in their title)

**## GENERAL CLI Binaries:**

    * OBJECTS_Delete.jar: Delete Objects of any type. (with regular expressions...)
    * OBJECTS_Create.jar: Create Objects of any type. (ex: create 200 JOBS Objects)
    * OBJECTS_Duplicate.jar: Duplicate Objects of any type. (ex: duplicate all objects matching name "*AB*PROD*" to "*AB*DEV*" at once)
    * OBJECTS_Export_Import.jar: Import &amp; Export Objects and dependencies (v11.2 and up)
    * OBJECTS_Execute.jar: Execute now or schedule later (executable) Objects. (ex: run now all JOBP matching name "*DEV*JOBP*")
    * OBJECTS_Move.jar: Move Objects of any type anywhere (within the same client) (ex: move all objects matching "*PROD*ABC*" to Folder "SANDBOX")
    * OBJECTS_Rename.jar: Rename Objects of any type (ex: rename objects with title matching ".*Legacy.*" from "*ALPHA*" to "*BETA*")
    * UTIL_ClientAudit.jar: Extract an Audit Report on Specific Client Usage (ex: number of active objects defined, etc.) 
    * UTIL_EnvironmentAudit.jar: Extract Environment Wide Usage Report (ex: number of clients defined, etc.)
    * UTIL_SystemOverview_Show.jar: Extract Content of the System Overview into a parsable format (JSON)</code></pre>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

Copyright and License
---

Solutions, Templates, Actions and other content available on the Automic Marketplace subject to the Automic [Developers Distribution License] (https://marketplace.automic.com/developers-distribution-license) as well as the Automic Community [Terms of Service] (https://marketplace.automic.com/community-terms-of-service).
Automic does not support, maintain or warrant any content submitted by the Automic-Community.



Questions or Need Help? 
---
Any questions or comments? Converse with your fellow Users in the [Automic Community] (https://community.automic.com).