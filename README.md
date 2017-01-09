# Meta
[![badge]](https://standards.github.io/goto/approval#meta)
[<img src="https://standards.github.io/resources/images/gh-standards-logo-small.png" align="right"/>](https://standards.github.io/goto/home)

[Github Standard](https://standards.github.io/goto/home) to describe how to write a Github Standard.

> Please refer to the [Standard life cycle appendix](http://standards.github.io/goto/standard-life-cycle) to understand how you can submit a new standard, propose changes to existing ones or request validation for applied standards on your projects.

## Goals
The development world inside GitHub is vast and full of wonders, with lots people with different ways to conceive a piece of software. Open Source projects can present a huge challenge on how things should be done across scattered teams where common-knowledge distribution is a huge challenge on its own too.

Every developer comes from different background and can think of a solution in a number of different ways, but in order to be successfull there are certain ground rules that should be put in place.

Being able to generate a piece of software that followed prestablished conventions we can all agree on basically helps us:

* Measure quality in some way
* Assist a developer in understanding what the piece of software provides in order to facilitate usage
* Provide an understandable and universally accepted way to collaborate on any type of project
* Promote a healthy way to extend any software when collaboration guidelines are followed
* Bring up to speed any new developer fairly quicker reading applied standards

In order to achieve such a level of expectation, let there be standards to help us. And in order to create a standard, its own standard should be complied.

## Definition
The following sections should be added to a `README.md` file in a project in order to shape a complete standard:

* Have a meaninful and short title which should include a link to the Standards home page as well as the small logo and a reference to the [Standard life cycle appendix] with the following Markdown code:
  ```markdown
  # standard title
  <!-- Place the Parent Standard badge here when corresponds -->
  [<img src="https://standards.github.io/resources/images/gh-standards-logo-small.png" align="right"/>](https://standards.github.io/goto/home)

  [Github Standard](https://standards.github.io/goto/home) to describe ...

  > Please refer to the [Standard life cycle appendix](http://standards.github.io/goto/standard-life-cycle) to understand 
  how you can submit a new standard, propose changes to existing ones or request validation for applied 
  standards on your projects.
  ```

* **Goals:** This section should cover why the standard should exist. Always try to include the "A project compliant with this standard..." and examples of the resultant workflow of a compliant project.


* **Definition:** Which are the specific requirements that should be applied in order to be fully compliant. You can also point out optional requirements with a clear reference of why it is optional. At least there should be one compulsory rquirement, otherwise the standard would become a guideline. Refer to the [Guidelines vs. Standards appendix] for more information about this disctintion.


* **Resources:** Any reference to documentation used to create the standard as well as any appendixes. This is optional as there may not be any resource available to add.


* **Maintainers:** At least two GitHub users, with their correspondant GitHub usernames responsable for maintaining the standard. Also they could officiate as validators if no "Validators" section is included. Refer to the [Standard life cycle appendix] to know more about validators job.


* **Validators:** It can be ommited if the GitHub users added as "Mainteiners" are the ones responsable of fulfilling validators tasks. Otherwise, same requirements, at least two GitHub users with their GitHub username.

Any of these sections or additional subsections can be added as headers, subheaders or lists as long the required information is included.

## Resources

* [Guidelines vs. Standards appendix]: Information about the disctintion between a Guideline and a Standard
* [Standard life cycle appendix]: Information about a standard' life cycle

## Maintainers

1. [@leog](https://github.com/leog)
2. [@tunnckoCore](https://github.com/tunnckoCore)

[Guidelines vs. Standards appendix]: http://standards.github.io/goto/guidelines-vs-standards
[Standard life cycle appendix]: http://standards.github.io/goto/standard-life-cycle
[badge]: https://img.shields.io/badge/Standards-meta%40v1.0.0-green.svg
