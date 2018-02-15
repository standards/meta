---
title: Meta
description: Standard to create GitHub Standards
category: user-guide
repository_url: https://github.com/standards/meta
---
[![badge]](https://github.com/Standards/meta/issues/4)

[![Backers on Open Collective](https://opencollective.com/openstandards/backers/badge.svg)](#backers)
 [![Sponsors on Open Collective](https://opencollective.com/openstandards/sponsors/badge.svg)](#sponsors) 

## Goals
The development world inside GitHub is vast and full of wonders, with lots people with different ways to conceive a piece of software. Open Source projects can present a huge challenge on how things should be done across scattered teams where common-knowledge distribution is a huge challenge on its own too.

Every developer comes from different background and can think of a solution in a number of different ways, but in order to be successful there are certain ground rules that should be put in place.

Being able to create something that followed pre-established conventions we can all agree on basically helps us:

* Measure quality in some way
* In case of software development, standards would assist a developer in understanding what a piece of software provides in order to facilitate usage
* Provide an understandable and universally accepted way to collaborate on any type of project
* Promote a healthy way to extend any project when collaboration guidelines are followed
* Bring up to speed new comers to a project being able to ramp up reading applied standards

A project complient with this standard constitutes a standard.

## Definition

### In a README.md file

#### Title, description and category
Basic information should be added to the header of the `README.md` file of your standard to identify it. First of all we have the title of the standard that should be meaningful yet short, then a short description. Lastly a category to help searchability (e.g. the targeted programming language) and the resporitory URL where the standard is located. These need to be in the following form:

```markdown
 ---
 title: Meta
 description: Standard to create GitHub Standards
 category: user-guide
 repository_url: https://github.com/standards/meta
 ---
```
  
#### Goals section
This section should cover why the standard should exist. Always try to include the "A project compliant with this standard..." and examples of the resultant workflow of a compliant project.


#### Definition section 
Which are the specific requirements that should be applied in order to be fully compliant. You can also point out optional requirements with a clear reference of why it is optional. At least there should be one compulsory requirement.

#### Resources section 
Any reference to documentation used to create the standard as well as any appendixes. This is optional as there may not be any resource available to add.

#### Maintainers section
At least two people, with their correspondent email addresses, responsible for maintaining the standard. Also they could officiate as validators if no validator section is included. Refer to the [Learn section] of the Standards homepage to know more about validators job.

#### Validator section (optional)
It can be omitted if the people added as "Maintainers" are the ones responsible of fulfilling validators tasks. Otherwise, same requirements, at least two persons with their correspondent email addresses.

### Other files 
The following files should exist in your repository root or inside a `.github` folder:

#### `ISSUE_TEMPLATE.md` file
With the following content:

```markdown
## What is the purpose of this Issue?
- Request validation (title must be "Validate owner/repo-name vX.Y.Z" being owner/repo the repository location to validate and vX.Y.Z the standard version complied)
- Propose changes
- Propose a new Standard

## Describe the purpose of this Issue a bit further
```

#### `PULL_REQUEST_TEMPLATE.md` 
With the following content:

```markdown
## What is the purpose of this Pull Request?

## Does this Pull Request solve any existent Issue?  
```

## Resources

* [Explore section] of the Standards homepage: Where you can explore all existing standards.
* [Learn section] of the Standards homepage: Information to understand how you can submit a new standard, propose changes to existing ones or request validation for applied standards on your projects.

## Maintainers

1. [@leog](https://github.com/leog)
2. [@tunnckoCore](https://github.com/tunnckoCore)

[Explore section]: https://standards.github.io/explore
[Learn section]: https://standards.github.io/learn
[badge]: https://standards.now.sh/badge/standards/meta/4?cache=1

## Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="graphs/contributors"><img src="https://opencollective.com/openstandards/contributors.svg?width=890&button=false" /></a>


## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/openstandards#backer)]

<a href="https://opencollective.com/openstandards#backers" target="_blank"><img src="https://opencollective.com/openstandards/backers.svg?width=890"></a>


## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/openstandards#sponsor)]

<a href="https://opencollective.com/openstandards/sponsor/0/website" target="_blank"><img src="https://opencollective.com/openstandards/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/openstandards/sponsor/1/website" target="_blank"><img src="https://opencollective.com/openstandards/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/openstandards/sponsor/2/website" target="_blank"><img src="https://opencollective.com/openstandards/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/openstandards/sponsor/3/website" target="_blank"><img src="https://opencollective.com/openstandards/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/openstandards/sponsor/4/website" target="_blank"><img src="https://opencollective.com/openstandards/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/openstandards/sponsor/5/website" target="_blank"><img src="https://opencollective.com/openstandards/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/openstandards/sponsor/6/website" target="_blank"><img src="https://opencollective.com/openstandards/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/openstandards/sponsor/7/website" target="_blank"><img src="https://opencollective.com/openstandards/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/openstandards/sponsor/8/website" target="_blank"><img src="https://opencollective.com/openstandards/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/openstandards/sponsor/9/website" target="_blank"><img src="https://opencollective.com/openstandards/sponsor/9/avatar.svg"></a>


