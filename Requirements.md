# Requirements

1. As a user I want to log into my account.
- create login and logout page (use mock data)
- (non functional) configure token authentication
- (non functional) create proper code structure

2. As a user I want to add new travel idea.
Travel idea contains information about:
- name of the idea (like: 'City Break in Budapest', 'East Euro Trip')
- destination (country, city, place - works like hashtags)
- estimated time of travel (days, weeks)
- some picure(s) from free api should be loaded and presented

3. As a user I want to manage administration settings of my account:
- language of the interface
- number of visible travel ideas per page
- color theme

4. As a user I want to put travel location as autocompletable field
- use some existing free API

5. As a user I want login via gmail account to the app

6. As a user I want to have option to choose my language of interface
- as for now only polish and english

7. I would like to integrate login procedure with gmail and facebook account.

--------- Backlog ----------
- In other iterations more non mandatory information (security note, attractinos, cost of living [$, $$, $$$]) could be loaded.
- I want to move ideas to show priority board (at the beginning it can be simple list)
- As a user I want to see all destinations from trip catalogue (?): trip (name, country, etc)
- As a user I want to see list of my selected destination
- As a user I want to change priorities of my destinations
- As a user I want to see list of all my trips
- As a uset I want to read about destination and: add it to my prio list, mark as already done

--------- Hints ------------
- Use lazy loading