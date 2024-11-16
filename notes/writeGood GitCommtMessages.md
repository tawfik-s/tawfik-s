[joelparkerhenderson/git-commit-message: Git commit message: how to write a great git commit message and commit template for version control](https://github.com/joelparkerhenderson/git-commit-message)


## very important
["Good Commit" vs "Your Commit": How to Write a Perfect Git Commit Message | by Victor Timi | in Level Up Coding - Freedium](https://freedium.cfd/https://levelup.gitconnected.com/good-commit-vs-your-commit-how-to-write-a-perfect-git-commit-message-6e96ab6357fa)




# my template is 

## Title
Write a title summarizing what this commit does.
Start with an uppercase imperative verb, such as
Add, Drop, Fix, Refactor, Bump; see ideas below.
Think of your title as akin to an email subject,
 so you don't need to end with a sentence period.
Use 50 char maximum, which is this line's width.
## Summary (Contain Why and Who)


## Tags

We recommend these summary keywords because they use imperative mood, present tense, active voice, and are verbs:

- **Add**: Create a capability e.g. feature, test, dependency.
    
- **Drop**: Delete a capability e.g. feature, test, dependency.
    
- **Fix**: Fix an issue e.g. bug, typo, accident, misstatement.
    
- **Bump**: Increase the version of something e.g. a dependency.
    
- **Make**: Change the build process, or tools, or infrastructure.
    
- **Start**: Begin doing something; e.g. enable a toggle, feature flag, etc.
    
- **Stop**: End doing something; e.g. disable a toggle, feature flag, etc.
    
- **Optimize**: A change that MUST be just about performance, e.g. speed up code.
    
- **Document**: A change that MUST be only in the documentation, e.g. help files.
    
- **Refactor**: A change that MUST be just a refactoring patch
    
- **Reformat**: A change that MUST be just a formatting patch, e.g. change spaces.
    
- **Rearrange**: A change that MUST be just an arranging patch, e.g. change layout.
    
- **Redraw**: A change that MUST be just a drawing patch, e.g. change a graphic, image, icon, etc.
    
- **Reword**: A change that MUST be just a wording patch, e.g. change a comment, label, doc, etc.
    
- **Revise**: A change that MUST be just a revising patch e.g. a change, an alteration, a correction, etc.
    
- **Refit/Refresh/Renew/Reload**: A change that MUST be just a patch e.g. update test data, API keys, etc.


## Authored-By
If the commit is written by multiple people, then use the git trailers
to thank each person as a co-author; various git tools can track this.
```txt
Authored-by: Name <name@example.com>
Co-authored-by: Name <name@example.com>

```
