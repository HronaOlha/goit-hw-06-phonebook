# goit-react-hw-06-phonebook

## Task

Refactor the Contact Book application code from `goit-react-hw-04-phonebook` to add state management using the Redux Toolkit library. Let the Redux state look like this.
```javascript
{
   contacts: [],
   filter: ""
}
```
- Create a store with configureStore()
- Use the createSlice() function
- Create actions to save and delete a contact, as well as update a filter
- Connect React components with Redux logic using the react-redux library hooks.
- Use the Redux Persist library to store an array of contacts in local storage
