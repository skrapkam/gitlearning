# Learning Git for my 99time 

## Notes 

### There's no branch in newly created repos 

- Must specify Master branch in first push 
- Use `git push -u origin master` instead of `git push origin master` as the former will record `origin/master` as a remote tracking branch, and will enable the next push to automatically push master to `origin/master`.
- [Read more](https://stackoverflow.com/questions/17096311/why-do-i-need-to-explicitly-push-a-new-branch/17096880#170968800)

### `git stash`
Useful for switching context and working on something else, especially when mid-way through  a code change and aren't ready to commit. 

### Undoing changes 
- Git doesn't have a traditional 'undo' system like word processing tools
    - Refrain from mapping Git operations to any traditional 'undo' mental model
    - Helpful metaphor is to think of Git as a timeline where commits are a snapshot of time 
        - "Undoing" would mean moving back in time 
- `git log` to get a list of latst commits 


### HEAD 