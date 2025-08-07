<h1>ETL Development: Logging and Monitoring</h1>


<h2>Overview</h2>
Implemented logging and monitoring techniques in Talend, both implicitly and explicitly, to track job execution, capture errors, and improve ETL maintainability.
<br />


<h2>Key Highlights</h2>

- **Explicit Logging:** Added logging components into the job design manually, using `tStatCatcher`, `tLogCatcher` (with `tWarn` and `tDie`), `tFlowMeterCatcher` & `tFlowMeter`, and `tAssertCatcher` & `tAssert` to capture job statistics, data flow metrics, and assertion checks.

- **Implicit Logging:** Configured the Stats & Logs options within job settings by checking boxes for Use statistics (`tStatCatcher`), Use logs (`tLogCatcher`), and Use volumetrics (`tFlowMeterCatcher`). Directed log outputs to the console and to files by defining paths, names, and formats for automated job monitoring.


<h2>Skills </h2>

Talend Open Studio, Logging & Monitoring, Error Handling, ETL Job Auditing, ETL Performance Tracking.

<h2>Documentation:</h2>

<p align="center">
Explicit Logging - Job Designer Workflow <br/>
<img src="https://github.com/user-attachments/assets/74bde713-4485-4d94-832f-756434afc90e" height="80%" width="80%" alt="Schema Handling"/>
<br />
<br />
Explicit & Implicit Logging - Output Files  <br/>
<img src="https://github.com/user-attachments/assets/d7efc4f4-85f0-4575-8dd3-e1d410c0bff8" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Logging Output - Console View <br/>
<img src="https://github.com/user-attachments/assets/e30def2c-dc16-4b33-ad69-938bf870e8e5" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Implicit Logging - Configuration Setup  <br/>
<img src="https://github.com/user-attachments/assets/d0656ee4-f252-4d72-9d7c-001a051c2cbb" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
