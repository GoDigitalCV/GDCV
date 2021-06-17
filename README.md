# GoDigitalCV

## About

V 0.0.2

### Built With

#### Backend Stack

- Flask
- sqlalchemy
- Python3

#### Frontend Stack

- Javascript
- Bootstrap
- HTML/CSS

### Installation

1. Clone the repo `git clone https://github.com/GoDigitalCV/GDCV.git`
2. Enter Directory `cd GDCV`
3. Install all packages `pip install -r requirements.txt`
4. Remove site.db file to start fresh database `rm resume/site.db`
5. Setup Env Variables:
   - Create file .env inside folder resume
   - Add the following
     ```
     MAIL_USERNAME="{{ your gmail username }}"
     PASSWORD="{{ your password }}"
     ```
6. Run webserver `python3 app.py `
7. Run the program and go to localhost:5000

## Contributing

When contributing to this repository, please first discuss the change you wish
to make via issue, email, or any other method with the owners of this repository
before making a change.

1. Ensure any install or build dependencies are removed before the end of the
   layer when doing a build.
2. Update the README.md with details of changes to the interface, this includes
   new environment variables, exposed ports, useful file locations and container
   parameters.
3. Associate each Pull Request with the required issue number
4. Write clear and meaningful commit messages.
5. If you report a bug please provide steps to reproduce the bug.
6. In case of changing the backend routes please submit an updated routes
   documentation for the same.

## TO-DO

### Front-End

- [ ] Fix home page video (not displayed, index.html)
- [x] Add front-end design
- [ ] Add CV css design
- [ ] Layout footer not displaying
- [ ] Social sharing buttons

### Back-End

- [x] Create master page template (extend layout.html)
- [ ] Fix pdf download bug
- [ ] Deploy to Heroku for testing
- [ ] Develop video application
- [ ] Multiple Cv templates
- [ ] Clean development branches
- [ ] squash SQLALCHEMY_TRACK_MODIFICATIONS overheads

## Ideas

- [ ] Build from Linkedin profile

## Screenshots

- Add Your Details <img
  src="https://github.com/GoDigitalCV/GDCV/blob/master/images/projects.png">

- Update your Details <img
  src="https://github.com/GoDigitalCV/GDCV/blob/master/images/Update.png">

- Delete Details <img
  src="https://github.com/GoDigitalCV/GDCV/blob/master/images/delete.png">
