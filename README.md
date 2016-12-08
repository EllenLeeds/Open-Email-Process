# open_email_process

## Contribution Rules
Please see [Contribution.md](/CONTRIBUTING.md)

## Table of Contents
- [Process](/process/)
	- [Campaign](/process/campaign.md)
	- [Segmentation](/process/segmentation.md)
		- [List Creation](/process/segmentation.md)
	- [Published Template](/process/template.md)
	- [Draft](/process/draft.md)
  	- [Text Version](/process/template.md)
	- [Sending](/process/sending.md)
	- [Completion Actions](/process/completion_action.md)
	- [Drip Campaign](/process/drip.md)

## Process

##### Campaign
---
- Naming Convention: `(Localization + Segmentation) + (Year + Month) + (Campaign Name)`
	- ex. `US - Prospect - 201611 - Destination: Tahoe`
	- ex. `EU Members - 201611 - EU Newsletter`
- Campaign should include email template, and email draft.

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

We have three master Dynamic lists in Pardot. For future segmentation lists involving Prospects or Opportunities, please create them by duplicating US - 201612 - Prospects - All Open or US - 201612 - Opportunities and adding a new Dynamic Rule.

- US - 201612 - Prospects - All Open
- US - 201612 - Prospects - All Open - Previous 12 Months
- US - 201612 - Opportunities 

###### Existing Segmentation Lists
San Diego
- US - 201612 - Prospects - Dest SD
- US - 201612 - Prospects - Home SD
- US - 201612 - Opportunities - Dest SD
- US - 201612 - Opportunities - Home SD

Palm Springs
- US - 201612 - Prospects - Dest Palm Springs
- US - 201612 - Prospects - Home Palm Springs
- US - 201612 - Opportunities - Dest Palm Springs
- US - 201612 - Opportunities - Home Palm Springs

Napa
- US - 201612 - Prospects - Dest Napa
- US - 201612 - Prospects - Home Napa
- US - 201612 - Opportunities - Dest Napa
- US - 201612 - Opportunities - Home Napa

Monterey
- US - 201612 - Prospects - Dest Monterey
- US - 201612 - Prospects - Home Monterey
- US - 201612 - Opportunities - Dest Monterey
- US - 201612 - Opportunities - Home Monterey

Tahoe
- US - 201612 - Prospects - Dest Tahoe / Truckee
- US - 201612 - Prospects - Dest Tahoe / Truckee
- US - 201612 - Opportunities - Dest Tahoe / Truckee
- US - 201612 - Opportunities - Home Tahoe / Truckee

Mammoth
- US - 201612 - Prospects - Dest Mammoth
- US - 201612 - Prospects - Home Mammoth
- US - 201612 - Opportunities - Dest Mammoth
- US - 201612 - Opportunities - Home Mammoth

Santa Barbara
- US - 201612 - Prospects - Dest Santa Barbara
- US - 201612 - Prospects - Home Santa Barbara
- US - 201612 - Opportunities - Dest Santa Barbara
- US - 201612 - Opportunities - Home Santa Barbara

San Jose
- US - 201612 - Prospects - Dest San Jose
- US - 201612 - Prospects - Home San Jose
- US - 201612 - Opportunities - Dest San Jose
- US - 201612 - Opportunities - Home San Jose

San Carlos
- US - 201612 - Prospects - Dest San Carlos
- US - 201612 - Prospects - Home San Carlos
- US - 201612 - Opportunities - Dest San Carlos
- US - 201612 - Opportunities - Home San Carlos

Oakland
- US - 201612 - Prospects - Dest Oakland
- US - 201612 - Prospects - Home Oakland
- US - 201612 - Opportunities - Dest Oakland
- US - 201612 - Opportunities - Home Oakland

Hawthorne
- US - 201612 - Prospects - Dest Hawthorne
- US - 201612 - Prospects - Home Hawthorne
- US - 201612 - Opportunities - Dest Hawthorne
- US - 201612 - Opportunities - Home Hawthorne

Burbank
- US - 201612 - Prospects - Dest Burbank
- US - 201612 - Prospects - Home Burbank
- US - 201612 - Opportunities - Dest Burbank
- US - 201612 - Opportunities - Home Burbank


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

###### Text Version ***!Important***
---
	- Update early, update often.
		- Seriously, don't forget this!
		- Affects any user who can not render the HTML email
	- Before sending, do one final check. Then check it again.

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
