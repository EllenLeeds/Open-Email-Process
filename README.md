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

##### Segmentation ***!Important***
---
- Define segmentation early
- Use `Master Suppression Bucket`
- Use `Master US Suppression` and `Master EU Suppression` accordingly
- When possible, create dynamic lists using SalesForce (if you need help, see Justin Hart)

######- List Creation
- On Import
	- Spot check list in Excel / Google Sheets / Numbers / Libre Office / etc. If there are any obvious discrepancies, re-pull the list, or contact the list provider for assistance.
	- Import list into Pardot
	- Add to campaign using proper naming convention
	- Select `Import Prospects And Add To List`
	- Naming Convention: `(Localization + Segmentation) + (Year + Month) + (Campaign Name) + (type)`
		-  ex. `US Extra Invites  - 201611 - Toast To Tahoe - List`



##### Sending
---
- When possible, schedule email in advance.
- Before sending, generate and share final proof with key team members.

	> Jeff, Liam, Barry, Jane, Jen, Justin, `(Key team members, ex: Member Care, Sales, etc) `

##### Completion Actions ***!Important - All Mailings***
---
- On Unsubscribe
	- Change Prospect Custom Field Value - `Lead Status` --> *Dead*
	- Change Prospect Custom Field Value - `Dead To Pardot` --> *True*

##### Drip Campaign ***!Important - Only Build Through Pardot Engagement Studio***
---
- Naming Convention: `Localization + Drip Campaign + (Year + Month)`
