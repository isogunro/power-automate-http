# How to send email from no-reply

Body:
```json
{
  "properties":{
    "To": {
            "results":["@{triggerOutputs()?['body/WorkEmail/Email']}"]
          },
    "Subject":"Welcome to the firm @{triggerOutputs()?['body/Employee_x0020_First_x0020_Name']}",
    "Body":"Your <b>onboarding information</b> <br /><br />
            DO NOT REPLY TO THIE EMAIL! THIS MAILBOX IS NOT MONITORED."
  }
}
```
# IMAGE
![image](https://user-images.githubusercontent.com/19296277/174641496-e70e051f-2903-4613-ade2-30fd107a2620.png)
