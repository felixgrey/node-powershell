# invoke()

Runs the commands currently in the shell object pipeline.

#### Returns

[Promise] - A promise that resolves with the output of all the commands that were in the pipeline before the call to this function, or rejects with an error.    

#### Example

```javascript
ps.invoke().then(output => {}).catch(err => {});
```