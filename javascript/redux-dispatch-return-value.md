# The return value of `store.dispatch`

If you've not applied any middleware to your store, `store.dispatch(action)` will return the action object.

If you have added middleware, the return value can be anything at all, depending on what the middleware returns.

This is useful for async actions that can return a promise that can be `then`'d or `await`'d.
