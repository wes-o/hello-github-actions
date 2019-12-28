# Github-Actions-Notes

## Structure 
- the action itself
- a workflow that uses action(s)

> A workflow can contain many actions, or combine jobs. Jobs combine steps. -> Jobs can run Actions.

> Each action has a purpose. (files referenced in actions are in separate directories)

### Types of Actions
- container actions
> Docker container actions allow environment to be packaged with the GitHub Actions code

_can only execute in the GitHub-Hosted Linux environment_
- Javascript actions
> decouples the actions from environment allowing faster execution 

_creates dependency management responsibility to maintain_

