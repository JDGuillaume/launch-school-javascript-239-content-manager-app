# Contact Manager App

## Specification

For this project, I've been tasked with replicating the application at
http://devsaran.github.io/contact-manager-backbone/ and extending it to include a tagging feature.

The tagging feature should allow you to:

- Create tags when you add or edit a contact.
- Click a tag and display all contacts with that tag.

The original project uses the following libraries and APIs:

- [Backbone.js](https://backbonejs.org/)
- [Bootstrap](https://getbootstrap.com/)
- [Handlebars](https://handlebarsjs.com/)
- [LocalStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
- [RequireJS](https://requirejs.org/)

For this project, Launch School has provided us with an API server with built-in documentation.

## Method

1. Focused on understanding the requirements of the task.
2. Familiarized myself with the website, its features, and available states.
3. Began isolating different portions of the HTML into individual components and identifying which elements would
   benefit form Handlebars templating.
   - Base HTML
   - Add Contact and Search
   - Existing Contact Cards (List Items)
   - Form
   - Search Output for No Matching Contacts
   - No Contacts
4. Began creating Handlebars templates.
   - Add Contact and Search
   - Existing Contact Cards (List Items)
   - Form
   - Search Output for No Matching Contacts
   - No Contacts
5. Moved to [Model-View-Controller (MVC) Architecture](https://www.taniarascia.com/javascript-mvc-todo-app/)
   - Created Model and API behavior
     - Verified via console that behavior was working as intended.
   - Created Views
   - Created Event Handlers
   - Wired Up Model and View via Controller
6. Continued to build out desired functionality.
   - Rendered various views.
     - Worked to limit unnecessary data fetching.
   - Added console.log for success on given actions.
   - Added prompt for deletion.
   - Added tag de-duplication and form validation.
   - Improved UI for tag rendering and selection.
   - Implemented search functionality.
