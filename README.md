# open_email_process

## Contribution Rules
Please see [Contribution.md](/CONTRIBUTING.md)

## Process

##### Campaign
---
- Naming Convention: `(Localization + Segmentation) + (Year + Month) + (Campaign Name)`
	- ex. `US - Prospect - 201611 - Destination: Tahoe`
	- ex. `EU Members - 201611 - EU Newsletter`
- Campaign should include email template, and email draft.

##### Published Template
---
- Naming Convention: `(Localization + Segmentation) + (Year + Month) + (Campaign Name) + (type)`
	- ex. `US Prospect - 201611 - Destination: Tahoe - Template`
	- ex. `EU Members - 201611 - EU Newsletter - Template`

##### Draft
---
- Naming Convention: `(Localization + Segmentation) + (Year + Month) + (Campaign Name) + (type)`
	-  ex. `US Lead - 201611 - Destination: Tahoe`
- If sending a follow up, append `Follow Up` to the end of the title.
	- ex. `US Lead - 201611 - Destination: Tahoe - Follow Up`
	- ex. `EU Members - 201611 - EU Newsletter`

##### Text Version ***!Important***
---
- Update early, update often.
	- Seriously, don't forget this!
	- Affects any user who can not render the HTML email
- Before sending, do one final check. Then check it again. 

##### Segmentation
---
***!Important*** - Please avoid using any lists that predate December 2016. New lists must adhere to naming conventions. When possible, make the list Dynamic so it stays up-to-date.
---
- Define segmentation early
- Use `Master Suppression Bucket`
- Use `Master US Suppression` and `Master EU Suppression` accordingly

> ######- List Creation
> - On Import
>	- Spot check list in Excel / Google Sheets / Numbers / Libre Office / etc. If there are any obvious discrepancies, re-pull the list, or contact the list provider for assistance.
>	- Import list into Pardot
>	- Add to campaign using proper naming convention
>	- Select `Import Prospects And Add To List`
>	- Naming Convention: `(Localization) + (Year + Month) + (Segmentation) + (Details)`
>		-  ex. `US - 201612 - Prospects - All Open`

We have three new Dynamic lists in Pardot. For future segmentation lists involving Prospects or Opportunities, please create them by duplicating US - 201612 - Prospects - All Open or US - 201612 - Opportunities and adding a new Dynamic Rule.

- US - 201612 - Prospects - All Open
- US - 201612 - Prospects - All Open - Previous 12 Months
- US - 201612 - Opportunities 


##### Sending
---
- When possible, schedule email in advance.
- Before sending, generate and share final proof with key team members.

	> Liam, Barry, Jane, Simon, Jori `(Key team members, ex: Member Care, Sales, etc) `

- Before sending, double and triple check the text-version of HTMl emails.

##### Completion Actions ***!Important - All Mailings***
---
- On Unsubscribe
	- Change Prospect Custom Field Value - `Lead Status` --> *Dead*
	- Change Prospect Custom Field Value - `Dead To Pardot` --> *True*

##### Drip Campaign ***!Important - Only Build Through Pardot Engagement Studio***
---
- Naming Convention: `Localization + Drip Campaign + (Year + Month)`
