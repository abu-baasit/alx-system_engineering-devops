Summary of the Issue

This documentation highlights an incident that occurred on Monday 12th August 2024, between the hours of 12pm WAT to 3pm WAT. The outage was caused majorly by updating a software to a newest version, which caused a complete outage hindering the users from having access to both website and mobile application. The outage lasted for about 3 hours.

Timeline
 System Administrators and engineers were alerted by monitoring system when several error messages were encountered by users
The team on-call investigated the issue, and identify software update as the major cause thereby crashing the system
The team had to deploy the previous version of the software to ascertain a likely solution
 Roll back to the previous version of the software prompt a healthy system upturn gradually, however bug fixes were required
 The issue was escalated to the engineering team thereby making them swing to action.
 The engineering team detected the bugs and moved on to fix it appropriately.
  After the final fix, the system went back to normal and users gained access to the system.


Root Cause and Resolution

The cause of the outage is majorly due to a bug in the latest version of a software having updated it from a previous version having LTS i.e long term support, thereby causing malfunction and making  it unstable. It disrupts the system and prevented the users from having access to the website and mobile application 

Corrective and Preventive Measures
Software was tested in batches to identify the issue, after which roll back to the previous version was done to bring normalcy.
 Major bug fixes were done on the previous version upon roll back and the newest version were also worked on.
A comprehensive analysis was done to ascertain what led to the malfunction and how to prevent the future occurrence.


This postmortem outlines the cause of the outage and the steps being taken to prevent similar occurrences in the future. The engineering team and system administrative team will collaborate to implement the corrective and preventative measures mentioned above.


