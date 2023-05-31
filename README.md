Create a custom hook that takes a url and options.
Use the useState() hook to initialize the response, error and abort state variables.
Use the useEffect() hook to asynchronously call fetch() and update the state variables accordingly.
Create and use an AbortController to allow aborting the request. Use it to cancel the request when the component unmounts.
Return an object containing the response, error and abort state variables.
