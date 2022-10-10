# SQL Developer Reports 

SQL Developer reports for Oracle database version 12c+ tuning and more.

## Installation
1. Go to https://github.com/masked-devops/sql-developer-reports
2. Code -> Download ZIP -> Unzip the file locally.
3. Open SQL Developer.
4. View -> Reports
5. Right click on User Defined Reports -> Open Report... -> Select the masked-devops.sql-developer-reports.xml file

Link to the video <>

The database user needs the select_catalog_role privilege to run the reports.
    
    --Local User
    create user sqd identified by sqd;
    grant connect,select_catalog_role to sqd;

    --Common User
    create user c##_sqd identified by sqd container=all;
    grant connect,select_catalog_role to c##_sqd container=all;

## Documentation

* Masked-Devops Session History
  
    Workload report on V$ACTIVE_SESSION_HISTORY and DBA_HIST_ACTIVE_SESS_HISTORY
    
    Link to the documentaton [Masked-Devops Session History](doc/Masked-Devops-Session-History.md)
    <img src="doc/img/Masked-Devops-SessionHistory/2022-09-25.png" width="600" height="300">

* Masked-Devops SQL History
  
    Workload report on V$ACTIVE_SESSION_HISTORY and DBA_HIST_ACTIVE_SESS_HISTORY 
    <img src="doc/img/Masked-Devops-SessionHistory/2022-09-25.png" width="600" height="300">

* [Masked-Devops AWR reports](doc/Masked-Devops-AWR-Reports.md)
    
    Create AWR/ASH/ADDM reports files.
    Link to the documentaton 
    [Masked-Devops Session History](doc/Masked-Devops-Session-History.md)
    <img src="doc/img/Masked-Devops-AWRreports/Masked-Devops.AWR.Reports3.png" width="600" height="300">

* Masked-Devops AWR reports Time Model
    
    Time model chart with View AWR/ASH/ADDM reports.
    <img src="doc/img/Masked-Devops-AWRreportsTimeModel/Masked-Devops.AWR.Reports.TimeModel.png" width="600" height="300">

* Masked Devops Session Browser
    Browse Oracle sessions 
* Masked Devops CPU
  
    Workload report on V$ACTIVE_SESSION_HISTORY and DBA_HIST_ACTIVE_SESS_HISTORY 
    <img src="doc/img/Masked-Devops-SessionHistory/2022-09-25.png" width="600" height="300">

* Masked Devops I/O
  
    Workload report on V$ACTIVE_SESSION_HISTORY and DBA_HIST_ACTIVE_SESS_HISTORY 
    <img src="doc/img/Masked-Devops-SessionHistory/2022-09-25.png" width="600" height="300">

* Masked-Devops Read Alert Log
  
    Workload report on V$ACTIVE_SESSION_HISTORY and DBA_HIST_ACTIVE_SESS_HISTORY 
    <img src="doc/img/Masked-Devops-SessionHistory/2022-09-25.png" width="600" height="300">


* Masked-Devops Read Trace File

* Masked Devops AWR Sysstat

