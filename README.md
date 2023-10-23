Notebook is a web application that replicates the functionality of Google Keep. Built with React and styled using Material-UI, this project allows users to create, edit, and organize notes with a user-friendly interface. 

#**Components and Features:**

1. **Form Component:**
   - The "Form" component allows users to create new notes. Users can enter a title and content for each note.
   - When a user inputs data and adds a note, it is displayed in the "Notes" section.
   - If the title and content are not empty, the note is added to the list of active notes.

2. **Archive Component:**
   - The "Archive" component displays notes that users have archived.
   - Users can choose to either unarchive or delete these archived notes.
   - Unarchiving a note moves it back to the "Notes" section.
   - Deleting an archived note permanently removes it from the application.

3. **DeleteNote Component:**
   - The "DeleteNote" component displays notes that users have marked for deletion.
   - Users can either restore these deleted notes or remove them permanently.
   - Restoring a deleted note moves it back to the "Notes" section.
   - Permanently removing a note means it is lost forever.

4. **EmptyNotes Component:**
   - The "EmptyNotes" component serves as a user-friendly notification for when a section is empty.
   - It displays a lightbulb icon and a message, such as "Notes you add appear here."
     
   ![image](https://github.com/SpatikaP/Notebook/assets/79979665/feaee95b-9c0f-4273-9a1d-20f94145eefc)

5. **NavList Component:**
   - The "NavList" component provides a sidebar menu for easy navigation between sections.
   - Users can switch between "Notes," "Archives," and "Trash."
   - Each section has an associated icon for visual recognition.

6. **SwipeDrawer Component:**
   - The "SwipeDrawer" component manages the layout of the application.
   - It includes a header bar and a sidebar menu for navigation.
   - Users can toggle the visibility of the sidebar by clicking on a menu icon in the header.

7. **DataProvider Component:**
   - The "DataProvider" component serves as a context provider, managing the application's state.
   - It maintains three separate arrays for notes, archived notes, and deleted notes.
   - The context provided by "DataContext" allows components to access and update these arrays.

 
   ![image](https://github.com/SpatikaP/Notebook/assets/79979665/f1ca6190-3dac-41d9-b847-6ed4d660e867)



#**Functionality:**

- Users can create notes by entering a title and content.
- Notes can be archived to keep them separate from the active notes.
- Archived notes can be unarchived to bring them back to the active notes or deleted.
- Deleted notes are moved to the trash section and can be restored or permanently removed.
- The sidebar menu provides easy navigation between different sections of the application.

**Styling and Responsiveness:**

- Material-UI is used for styling, which results in a visually appealing and responsive design.
- The project includes various Material-UI components like cards, icons, and styled containers to create a clean and modern interface.

This project effectively manages the state of notes and offers various features for note organization and management. It is a practical example for learning React, Material-UI for styling, and state management within a web application. Users can efficiently create, organize, and manage their notes through this user-friendly and responsive interface.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
