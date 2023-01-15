# Contribute to this repository

## How to choose the event 🧐

This repo is to be a community-curated list of Hungarian tech conferences. So, before adding a new event, please be sure:

- make sure it is a tech conference and it is not already listed.

- make sure that is a conference (not a meetup, hackaton, etc.)

- make sure that the event is happenign in Hungary (either in Hungarian or in a foreing language).

## Prepare the contribution ✍️

Fork this project to your github account and create the file inside the `_conferences/` directory.

The file should be named the conference name and year with an `.md` extension (for example, `road-to-aws-conf-2023.md`).

## File format 📄

The contents of the file should use the following template:

`name`: the name of the conference, avoid adding the location of the event in the name, the location will be displayed next to the name of the conference.

`website`: the website of the conference, avoid to link to signup pages (Eventbrite, Meetup, etc...) instead try to find the official event website, to allow users to find more information about the event.

`location`: the location of the conference (`<city>, <country>`, `Online` or both)

`online`: if the conference is online (`true` or `false`)

`lang`: the language of the conference (`Magyar`, `English` or `Magyar & English`)

`date_start`: the start date of the conference (`YYYY-MM-DD`)

`date_end`: the end date of the conference (`YYYY-MM-DD`)

`cfp_start`: the start date of the call for papers (`YYYY-MM-DD`)

`cfp_end`: the end date of the call for papers (`YYYY-MM-DD`)

`cfp_site`: the website of the call for papers (`https://roadtoaws.com/contact/`)

Example:

```markdown
---
name: "Road to AWS Conf"
website: https://roadtoaws.com/
location: Budapest, Hungary
online: true
lang: English

date_start: 2023-04-01
date_end:   2023-04-01

cfp_start: 2022-04-01
cfp_end:   2022-04-01
cfp_site:  https://roadtoaws.com/contact/
---
```

## Create a pull request 📌

Before push, please verify that the file is correctly formatted ([try to run the project](/README.md#running-locally) on you local machine).

There are no convention for the commit message, but it is recommended to use the following format: `"Add <conference name> <year>"`.

Then commit the changes, push the code and create a pull request.
