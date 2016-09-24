# Guidelines Checklist

## The Format of Review

To review a js library, we need to check several things:

- Project's GitHub page
- GitHub Issues & Collaboration
- Git usage
- Code

More info on [JS Police](http://jspolice.com), especially this [post](http://jspolice.com/post/13-secrets-to-coding-awesome-js-plugins-not-like-a-jerk/). :tada::tada::tada:

### GitHub Page / Docs:

- Is there a description in the top?
- Is there a link to a project's website?
- Does the Readme display a nice typography rhythm in terms of titles and subtitles?
- Does the Readme contain a short description of what the library does?
- Does the Readme contain documentation about the API?
- Does the Readme contain code examples with the documentation of methods?
- Does the Readme specify guidelines for contributing?
- Does the Readme specify the license?
- Are there Releases?
- Are the Releases well documented?
- Travis or other CI?
- Are there demos?
- Is there a diagram explaining the code structure?
- Was the project updated recently?

### Issues & Collaboration

- Are there many issues?
- Are they swiftly responded to?
- Are the issues labeled?
- Number of contributors?

### Git

- Are commits atomic?
- Are there a lot of nonsense commit messages?
- Are there feature branches?
- Release branches, hotfix?
- Number of stars, forks and watches?

### The Code

- Is there a package.json?
- Is there a bower.json, if applicable?
- Are packages up to date?
- Is there .jshint, .eslint or some other linting tool?
- Is there a dist folder or equivalent?
- Is there a minified version of the library?
- Is there a module bundler?
- Is there a task runner?
- Are there tests? (unit, e2e)
- Is code consistently formated?
- Does code follow a style guide?
- Are there meaningful comments?
- Is there a config / options object
- Does the code depend on any external libraries?
- Does it play well with other libraries? (overriding _ or $, noConflict method)
- Does it use OO js?
- Are there any design patterns used?
- Do CSS class names refer to the function in the page (img-caption), and not form (bold-red) or content (pink-elephant)?
- Correctness - Does the code do everything it claims?
- Complexity -Does it accomplish its goals in a straightforward way?
- Consistency - Does it achieve its goals consistently?
- Maintainability - Could the code be easily extended by another member of the team with a reasonable level of effort?
- Scalability - Is the code written in such a way that it would work for both 100 users and 10,000? Is it optimized?
- Style - Does the code adhere to a particular style guide (preferably one agreed upon by the team if the project is collaborative)?