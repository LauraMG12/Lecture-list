# This project aims to test your skills in user interaction handling, state management, data filtering, and code structuring.

We are a multinational book publishing company. We want to offer our audience a way to view our catalog and save the books they are interested in to a reading list.

To achieve this, we want to develop a web application that allows users to view available books and create a reading list. Please keep in mind:

- We are unsure if the framework we use now will be final, but we want to reuse as much code as possible.
- The application should be user-friendly and visually appealing.
- We have 80% of users coming from desktop browsers.

Use the `books.json` file to get book data. You can add more books if you wish, as long as they follow the same structure.

## Functionality

[] 1. **Display Available Books**: The application should display a list of available books that the user can review.
[] 2. **Create Reading List**: Users must be able to create a reading list from the available books. The UI should clearly indicate which books are in the reading list and which are not. It should also be possible to move a book from the reading list to the available list.
[] 3. **Filter Books by Genre**: Users should be able to filter the list of available books by genre, and a counter with the number of available books, the number of books in the reading list, and the number of available books in the selected genre should be displayed.
[] 4. **State Synchronization**: There must be global state synchronization that reflects the number of books in the reading list and the number of books still available. If a book is moved from available to reading list, both counts should be updated accordingly.
[] 5. **Data Persistence**: The application should persist reading list data in the browser's local storage. Upon page reload, the reading list should remain.
[] 6. **Tabs Synchronization**: If the user opens the application in two different tabs, changes made in one tab should be reflected in the other without the need for a backend.
[] 7. **Deployment**: The application should be deployed on a free hosting service (Netlify, Vercel, Firebase, etc.) and accessible through a public URL. Indicate the URL in the README.
[] 8. **Testing**: The application must have AT LEAST one test. Create the test that you consider most important for your application.
[] 9. Implement a search functionality in the list of available books.
[] 10. Add a new filter to filter books by the number of pages.
[] 11. Allow reordering of books in the reading list by priority.
[] 12. Make your design responsive.

## Code Tips

1. **Code Structure**: The code should be well-organized and easy to read.
2. **HTML Semantics**: HTML should be semantic and accessible.
3. **Team Thinking**: Prepare your project with the idea that anyone on your team may need to work on it in the future (scripts in package.json, minimal documentation in README, code comments if necessary, etc.).
4. **Code Formatting**: Ensure your code is consistently formatted. You can use Prettier or any other tool you prefer.
5. **Production-Ready**: Make sure your application is ready for production. Minimize code, optimize images, etc.

Good luck, and have fun coding!

#####################################################################################################################################

# Vue 3 + TypeScript + Vite

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support For `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
   1. Run `Extensions: Show Built-in Extensions` from VSCode's command palette
   2. Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.
   #   L e c t u r e - l i s t 
    
    
