# TheBGAcademy
The first 2 years of BGA have been testing the water on how we should run in the future.

## Aims
This new website, for launch prior to BGA25, will enable help realise those goals by allowing for:

- Blog posting - RSS
- Signup via Google / email
    - Allowing us to collect only Demographic information and contact information to better serve the bioinformatics community.
    - This allows us to better move with the aims of groups like Justice, Equity, Diversity, and Inclusion Committee (J.E.D.I Commitee) of the EBP.
- Through these signups, attendees will be able to signup for specific sessions and allow us to run a second instance of that session
- Keep a database of sessions, years, software versions, protocols, e.t.c to enable a true ToolNote system
    - ToolNotes would be sessions which could release along side a paper to show off the tool in a more tutorial based manner or for students to gain a better understanding of said tool.

## Tech Stack
- Python3.10 + Django - 5.1
    - Chosen due to the wide adoption of Python, and bug fixes and updates are more doable that if I went with a rust based system.

- PostgreSQL
    - Popular and very scalable

- Docker
    - It's Docker, containerisation is very important for this kind of project in my opinion.