# Personal Medication Care – Test Cases

| Test Case ID | Test Case | Input | Expected Result |
|---|---|---|---|
| TC01 | User Registration | Valid username, email and password | User account should be created successfully. |
| TC02 | Invalid Registration | Invalid email address | System should display an error message. |
| TC03 | Add Medicine | Medicine name, dosage and time | Medicine details should be saved successfully. |
| TC04 | Empty Medicine Details | Medicine name and dosage left empty | System should display a validation message. |
| TC05 | Set Medicine Reminder | Select medicine and reminder time | System should send a notification at the scheduled time. |
| TC06 | Mark Medicine as Taken | Select the Taken option | System should record the medicine as Taken. |
| TC07 | Mark Medicine as Missed | Select the Missed option | System should record the medicine as Missed. |
| TC08 | View Medication History | Open medication history | System should display previous medication records. |
| TC09 | Update Medicine Details | Change medicine dosage or reminder time | Updated medicine details should be saved successfully. |
| TC10 | Delete Medicine | Select a medicine and click Delete | Selected medicine should be removed from the active medicine list. |
