# react-redux-and-async-code
async code with redux and advanced topics such as side effects

# fat reducers vs fat components vs fat actions

where should our logic go? if we have a weak backend:

- prefer reducers

if the code is synchronous such as data transformation

avoid action creators or components

- prefer action creators or components

if there is any kind of asychronous code or http requests, mutable code
do not use reducers

also remember not to mutate the state directly inside any component, only inside the reducers


