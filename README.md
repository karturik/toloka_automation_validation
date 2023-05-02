## VALIDATION SCRIPTS SAMPLES
___
### Scripts for automating project validation on Yandex-Toloka

> Reject set
> 
> Download and sort set's attachment (allow validator to select, which attachment download, which will be rejected and for what reasons)
> 
> Send message to toloker with reject reasons and errors on different languages
> 
> Give toloker skills
> 
> Save set data to DB, checks if the set has been downloaded before and what it's status

### Structure:
- script
- working_excel

Working_excel is a file, where validator can past assignment_id or assignment link, select, which attachment download, which reject and for what reasons
Reject reasons select by them numbers, then reasons past to message and send to tolokers.
Toloker get errors to correct and skill for retrying.

Excel_sample image:

![alt text](https://github.com/karturik/toloka_automation_validation/blob/main/excel_sample.png?raw=true)

Toloker's message sample:

![alt text](https://github.com/karturik/toloka_automation_validation/blob/main/message_sample.png?raw=true)