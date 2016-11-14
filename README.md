# open_email_process

## Contribution Rules
Please see [Contribution.md](/CONTRIBUTING.md)

## Process

##### Campaign
- Naming Convention: `(Campaign Name) + (Month) + (Year)`
	- ex. `Destination: Tahoe - November, 2016`
- Campaign should include email template, and email draft.

##### Published Template
- Naming Convention: `(Campaign Name) + (Month) + (Year) + (type)`
	-  ex. `Destination: Tahoe - November, 2016 - Template`

##### Draft
- Naming Convention: `(Campaign Name) + (Month) + (Year) + (type)`
	-  ex. `Destination: Tahoe - November, 2016 - Email`

##### Segmentation
- Define segmentation early
- Use `Master Suppression Bucket`
- Use `Master US Suppression` and `Master EU Suppression` accordingly
- When possible, create dynamic lists using SalesForce (if you need help, see Justin Hart)

##### Sending
- When possible, schedule email in advance.
- Before sending, generate and share final proof with key team members.

	> Jeff, Liam, Barry, Jane, Jen, Justin, `(Key team members, ex: Member Care, Sales, etc) `

##### Completion Actions ***!Important - All Mailings***
- Change Prospect Custom Field Value - `Lead Status` --> *Dead*
- Change Prospect Custom Field Value - `Dead To Pardot` --> *True*
