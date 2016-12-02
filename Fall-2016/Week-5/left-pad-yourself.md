# Left Pad
#### Week 5 {Foundation Challenge}

### Assignment
Left-pad is a controversial module that [broke](http://www.theregister.co.uk/2016/03/23/npm_left_pad_chaos/) half of the internet, and lead to funny articles such as [1](https://news.ycombinator.com/item?id=11350651) [2](https://medium.com/friendship-dot-js/i-peeked-into-my-node-modules-directory-and-you-wont-believe-what-happened-next-b89f63d21558) and others. 

Your assignment is to replicate either the left-pad module or the right-pad module and you will publish to NPM. Of course you will write your own code for each.

Your module will add empty padding to a string, either left or right you choose. It should work like so:

```javascript
left_pad('foo', 4)
// => "    foo" 
```

### Tips
- A string is essentially an array of characters or chars. So you can simple loop through a string and add the extra blank spaces as required.
- When naming this make it creative as opposed to something simple and boring such as left_pad
- Make sure your the name of your module matches everywhere (i.e. github repo, package.json, etc.)

### Requirements & Goals
**Level 3: Minimum Requirement = Passing = #junior-dev**<br />
**Level ≥ 4: Awesome level = Mastery = #senior-dev**

##### Level 1*
- [ ] *created basic module*
- [ ] *available on github*

##### Level 2*
- [ ] *published on npm*

##### Level 3*
- [ ] *github repo has descriptive readme.md* For help in this take a look at other [repo's](https://github.com/stevemao/left-pad). 
Your readme.md should contain how to install it, and example usage cases. You should be using [markdown features](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) such as syntax coloring.

##### Level 4
- [ ] *uses ES6 conventions* [1](https://github.com/airbnb/javascript) [2](https://webapplog.com/es6/)

##### Level 5
- [ ] *it is unit tested and fully covered* [1](https://blog.risingstack.com/node-hero-node-js-unit-testing-tutorial/)

### Submission
In order to meet level 3 requirements your code should be available both in github, and npm. We'll check on Friday using [Students.md](https://github.com/CodeRGV/boot/blob/master/Fall-2016/Students.md) so if your github username isn't up then we won't be able to grade you and give you feedback.
