## Manifesto - Technical Assignment
##### By Robert Bourne, Web developer and job candidate.
### Installation
1. Clone this git repo
2. For ease of use I have chosen to use lando as a docker-based local development environment, the configuration is stored in the codebase. Assuming lando has been configured correctly, run `lando start` from the project root.
3. To import the composer dependencies (such as contributed modules), run `lando composer install` from the project root.
4. Import the configuration stored in `/config/sync` by running `lando drush cim -y`
5. You may need to clear caches, to do this run `lando drush cr`
6. Visit the local Drupal site in a browser - [Manifesto Technical Assignment](http://manifesto-technical-assignment.lndo.site/user/login). 

### Technical tasks
1. **Editorial Experience** - *Client needs to be able to build the Article content type’s content by adding one or more of the below components. Client needs the ability to move components up and down in the content and the ability to add a component multiple times.*
    1. 
2. **Editorial Experience / Permissions:** - *If current editor role is not administrator, Article form Title field must have the description “Lorem ipsum dolor sit amet, consectetur adipiscing elit.“. Description shouldn’t appear for administrators.*
    1. 
3. **Remote API:** - *Client needs the ability to fetch current weather for provided postcode from ABC service. This is needed across different components of the website, the client hasn’t specified where yet. The candidate can either use a real service providing this if the candidate know any, mock-up the service output by HTTP fetching a json stored in the docroot or even skip the HTTP call completely and just return a weather value. Expected values is one of ‘sunny’, ‘cloudy’ or ‘rainy’.*
    1. 
4. **Drupal Backend/Theming:** - *Article must have Postcode field, where editor can set the London area the article is about. On the front end the Postcode displays right below the title. Also after the article’s content a weather widget is displayed, showing the weather for the article postcode pulling the data from the service described above.*
    1. 
5. **“I Feel Good” wildcard:** - *Remember: Weather in London changes quickly! Quicker than Drupal’s cache sometime... does the solution above consider it?*
    1. 

##### Any questions feel free to contact me on <robertbourne86@gmail.com>

