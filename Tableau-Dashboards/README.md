Contact Center Data Analysis - Tableau Dashboard

About Dataset

The dataset represents healthcare contact center operations, capturing call-level interactions related to claims, enrollment, benefits, prior authorization, billing, and system access.

 > It includes operational, quality, and performance metrics such as wait time, handle time, SLA targets, call outcomes, first call resolution, escalation, and abandonment.

 > The data spans multiple months, enabling trend analysis, peak-hour identification, and operational planning.

 > Calls are segmented by queue, call reason, member type, and channel, allowing targeted analysis across different business functions.

 > The dataset is designed to mirror real-world healthcare contact center systems while   remaining HIPAA-safe and non-identifiable.



Tableau Public Link
https://public.tableau.com/views/ContactCenterPerformance_17688507181890/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


<img width="1050" height="832" alt="image" src="https://github.com/user-attachments/assets/046b0167-37f5-46d1-9ec0-57ab0976333f" />

<img width="1043" height="832" alt="image" src="https://github.com/user-attachments/assets/0ef444ee-0c9c-40d9-936d-68b5c6e15142" />

Link to Dashboard

https://public.tableau.com/views/ContactCenterPerformance_17688507181890/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Data Dictionary

Average time a member waits before their call is answered. This is a core access-to-care KPI.

	Average Speed of Answer (ASA) = AVG([wait_time_sec])

SLA Met Flag = IF [wait_time_sec] <= [sla_target_sec] THEN 1 ELSE 0 END

SLA Compliance % = AVG([SLA Met Flag])

This measures the percentage of calls answered within the defined SLA threshold, which directly reflects service quality and operational performance.

First Call Resolution (FCR %)

	FCR measures how effectively member issues are resolved on the first contact, which is a key quality 	and efficiency indicator.

  FCR Flag= IF [first_call_resolution] = "Yes" THEN 1 ELSE 0 END
FCR %= AVG([FCR Flag])

Abandonment Flag = IF [call_outcome] = "Abandoned" THEN 1 ELSE 0 END

Abandonment Rate % = AVG([Abandonment Flag])
Abandonment Rate is the percentage of calls where members hang up before their call is answered by an agent.

Escalation Rate % = AVG([escalated_flag])
Escalation Rate measures the percentage of calls that could not be resolved by the first-level agent and required additional support.

<img width="1817" height="598" alt="image" src="https://github.com/user-attachments/assets/622b5a3a-e481-41c7-a9b9-cd8c4aa59c20" />




<img width="2885" height="891" alt="image" src="https://github.com/user-attachments/assets/0164eb9a-e405-4828-b96f-fbcadb647dfb" />
