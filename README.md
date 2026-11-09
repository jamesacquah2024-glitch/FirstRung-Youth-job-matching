# FirstRung-Youth-job-matching
Source code and project files for my app.
# FirstRung: Youth Job Matching

FirstRung is a single-page web app that helps young people find jobs that fit their skills. You enter what you can do, and the app ranks open jobs by how well they match. It also shows which skills you are missing and how to build them.

## Features

- **Find jobs:** Enter your first name, education level, location, preferred job type, whether you can travel, and your skills. Every job gets a match score out of 100.
- **Match labels:** Each job is marked as a Strong match (70+), Possible match (45 to 69), or Stretch (below 45).
- **Skill gaps:** Results show the skills you have, the ones you are missing, and a tip for closing the first gap.
- **Related skills:** Related skills count part-way, so "Sales" helps with "Customer service".
- **Post a job:** Employers can add a job with a title, company, location, minimum education, job type, pay, required and nice-to-have skills, and a remote option.
- **Save jobs:** Mark jobs you like as saved.
- **Accessible and mobile friendly:** Keyboard-friendly controls, light and dark mode, and a layout that adapts to phone screens.

## How the Matching Works

| Part | Points |
|------|--------|
| Required skills you have | 50 |
| Nice-to-have skills | 15 |
| Location, or remote work | 15 |
| Education level | 10 |
| Job type you asked for | 10 |

## Built With

HTML (single-file web app)

## How to Run

1. Download or clone this repository.
2. Open `FirstRung – Youth job matching.html` in any web browser.

## Project Files

- `FirstRung – Youth job matching.html`: the complete app
- `FirstRung – Youth job matching.md`: project notes
- `README.md`: this file

## Limitations

This is a demo. Jobs and saved items are kept in the browser only and disappear when the page is refreshed. A real version would connect the job list to a database.

## Author

James Acquah
