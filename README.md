# Scores-A-web-based-Scoreboard

- Proposal
  -A web application that shows up to date sports(Baseball, Hockey, etc..) score cards. 

- Technologies
  - Framework
    - Django(?)
      - Django's base templating system isn't the best, consider using Jinja2
        http://jinja.pocoo.org/docs/dev/
      - Django might be too big for our needs. Probably use one of the following options
    - AngularJS(?)
      - 2-way Data binding
      - Plugins
      - Built for 1-page sites
    - EmberJS(?)
      - Convention over configuration
        - means less code
      - Mock APIs for testing
        
  - Database
    - SQLite
    
  - Deployment
    - Server
      - Amazon Web Services
    - Database Management
      - MySQL/PostgresQL(?)

- APIs Used
  - (?)

- Some Specs (informal)
  - Data Retrieval
    - Team data (i.e - names, logos...)
    - Upcoming Matches
    - Past matches
    - Live scores
  - Authentication & Security (OAuth(?))
    - Save favorite teams
    - Other preferences(?)
  - Model
    - Teams
    - Matches
    - Leagues
    - ORM(?)
  - Controller
    - View flow handling
  - Views
    - Templating and style
    
- eature Specifications
  
(?) - Up for discussion/should be researched
