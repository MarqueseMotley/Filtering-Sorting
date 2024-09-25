# Filtering and Sorting Protection Status Logs for Critical Systems
ProtectionStatus: This is the table you're querying, likely containing data related to security or protection statuses of various systems.<img width="1193" alt="Screenshot 2024-09-25 at 9 55 00 AM" src="https://github.com/user-attachments/assets/22236128-a493-4a31-9af2-dd0019048d5e">

| where: This is the filter condition, which limits the results based on the given criteria.
Computer contains "DC01.na.contosohotels.com": This part specifies that the query should only return rows where the Computer field includes the text "DC01.na.contosohotels.com". The contains operator checks if the string you're searching for is present in the Computer field.
<img width="1196" alt="Screenshot 2024-09-25 at 11 12 13 AM" src="https://github.com/user-attachments/assets/3c19e656-5229-4fae-9e02-a689fd75c8a5">

When you add | sort by TimeGenerated to the query, it sorts the results by the TimeGenerated column
<img width="1196" alt="Screenshot 2024-09-25 at 11 19 57 AM" src="https://github.com/user-attachments/assets/aef7ed4d-dfca-4769-8159-e60d28eca6d9">

This query is useful when you're trying to investigate or monitor protection or security-related events for a particular machine (DC01) and you want to see the latest logs or events first.
