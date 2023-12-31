# My 100DaysOfOSS Progress Tracker

## Template for Each Day

- **Project**: [Project Name]
- **Description**: [Briefly describe the project and your goals for the day]
- **Tasks completed**: [List the tasks you completed]
- **Challenges faced**: [Mention any challenges you encountered]
- **Resources used**: [Include any helpful resources or documentation links]
- **OpenSauced Highlight**: [Include a link, screenshot, or both if applicable]

# 100DaysOfOSS Progress Tracker

## Day X (Example)

- **Project**: Sample Blog Website
- **Description**: Set up the project and created a basic homepage layout.
- **Tasks completed**: 
  - Installed Angular CLI and generated a new project.
  - Designed the homepage layout with HTML and CSS.
- **Challenges faced**: Understanding CSS Flexbox for layout design.
- **Resources used**: 
  - Angular CLI documentation (https://angular.io/cli)
  - CSS Flexbox guide on MDN (https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
- **OpenSauced Highlight**: [Include a link, screenshot, or both if applicable]

## Day 1

- **Project**: Sobrecodigo Proyecto Beta
- **Description**: Design login UI/UX layout prototypes.
- **Tasks completed**: 
  - Designed desktop login layout.
  - Designed tablet login layout.
  - Designed mobile login layout.
- **Challenges faced**: Understanding Figma interface. I asked Product Owner how to add an icon so I can finally finish the prototype.
- **OpenSauced Highlight**: [Prototype sample](https://github.com/shartrooper/open-saused-journey/blob/main/assets/login-prototype.jpg)

## Day 2

- **Project**: boxyhq/saas-starter-kit
- **Description**: Make the dashboard sidebar responsive for smaller screens.
- **Tasks completed**: 
  - Can toggle visibility on smaller screens.
  - Will remain visible for screens higher or equal than 1024px.
- **Challenges faced**: This is a Next.js app, therefore the components are server rendered and have not access to browser's API.
I designed a custom hook that takes a ref and a string representing parent's id in order to add an event listener which will handle
binding click events outside of the sidebar container (and close on trigger ).
- **OpenSauced Highlight**: [Ongoing issue discussion](https://github.com/boxyhq/saas-starter-kit/issues/202)

## Day 3
 **Project**: Sobrecodigo Proyecto Beta
- **Description**: Open Mongo DB cluster and setup repo database connection.
- **Tasks completed**: 
  - Opened a cluster, config my IP.
  - Setup Mongo and its ODM mongoose on the Express repo.
  - Configure the environment variables.
- **Challenges faced**: The dev team implemented a PR templated, I had to revert the PR I opened in the remote repo directly and learn 
to use the custom template in VSCode in order to make a proper PR.
- **OpenSauced Highlight**: [Merged commit](https://github.com/Sobrecodigo/sc-proyecto-beta-backend/commit/de8ffd9c313741163e1f98b37f8a57fb8a541771)

## Day 4

- **Project**: boxyhq/saas-starter-kit
- **Description**: Fix dashboard sidebar z-index
- **Tasks completed**: 
  - Removed z-index tailwind class after toggle hiding the sidebar.
- **Challenges faced**: n/a. 
- **OpenSauced Highlight**: [Ongoing issue discussion](https://github.com/boxyhq/saas-starter-kit/issues/202)

## Day 5
 **Project**: Sobrecodigo Proyecto Beta
- **Description**: Entity MV feature
- **Tasks completed**: 
  - write Controller code.
  - write Model code.
  - write Service code.
- **Challenges faced**: ...
- **OpenSauced Highlight**: [PR](https://github.com/Sobrecodigo/sc-proyecto-beta-backend/pull/3)

## Day 6
 **Project**: Sobrecodigo Proyecto Beta
- **Description**: Add response formatter
- **Tasks completed**: 
  - add utility function to format the JSON response.
- **Challenges faced**: ...
- **OpenSauced Highlight**: [PR](https://github.com/Sobrecodigo/sc-proyecto-beta-backend/pull/4)

## Day 7
 **Project**: Sobrecodigo Proyecto Beta
- **Description**: Add error middleware
- **Tasks completed**: 
  - refactor response types into another file and add an error handler defined as middleware for some general errors.
- **Challenges faced**: ...
- **OpenSauced Highlight**: [PR](https://github.com/Sobrecodigo/sc-proyecto-beta-backend/pull/5)

## Day 8
- **Project**: boxyhq/saas-starter-kit
- **Description**: Review Svix webhook implementation
- **Tasks completed**: 
  - Test implemented webhook events: member.created, member.deleted, invitation.created and invitation.deleted.
- **Challenges faced**: Reading the documentation and understanding the purpose of adding webhooks on a web application.
- **OpenSauced Highlight**: [Ongoing issue discussion](https://github.com/boxyhq/saas-starter-kit/issues/419)

## Day 9
- **Project**: boxyhq/saas-starter-kit
- **Description**: Improve Type Safety
- **Tasks completed**: 
  - Test implemented webhook events: member.created, member.deleted, invitation.created and invitation.deleted.
- **Challenges faced**:
- **OpenSauced Highlight**: [PR](https://github.com/boxyhq/saas-starter-kit/pull/493)

## Day 10
- **Project**: boxyhq/saas-starter-kit
- **Description**: Fixes for audit logs error message and pricing section keys
- **Tasks completed**: 
  - fix list items keys in defaultLanding component.
  - fix error display caused by undefined audit log tokens.
- **Challenges faced**:
- **OpenSauced Highlight**: [PR](https://github.com/boxyhq/saas-starter-kit/pull/513)

## Day 11
- **Project**: boxyhq/saas-starter-kit
- **Description**: Fix/update user session name
- **Tasks completed**: 
  - userSession user's name is updated after changing it in options.
- **Challenges faced**:
- **OpenSauced Highlight**: [PR](https://github.com/boxyhq/saas-starter-kit/pull/526)

## Day 12
- **Project**: boxyhq/saas-starter-kit
- **Description**: Open issue.
- **Tasks completed**: 
  - Explain issue about Authenticated users being able to access landing page.
- **Challenges faced**:
- **OpenSauced Highlight**: [ISSUE](https://github.com/boxyhq/saas-starter-kit/issues/535)

## Day 13

- **Project**: Sobrecodigo Proyecto Beta
- **Description**: Code Account module.
- **Tasks completed**: 
  - Coded account controller.
  - Coded account service.
  - Coded account model.
- **Challenges faced**: Refactoring the error handling which was incomplete aswell.

## Day 14

- **Project**: Sobrecodigo Proyecto Beta
- **Description**: Code Authentication module.
- **Tasks completed**: 
  - Coded auth controller.
  - Coded jwt verification middleware.
- **Challenges faced**:
- **OpenSauced Highlight**: [PR](https://github.com/Sobrecodigo/sc-proyecto-beta-backend/pull/7)
