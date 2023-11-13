
🚧🚧🚧 ... IN WRITING ... 🚧🚧🚧

# Naming in software design

The naming of libraries, packages (assemblies), classes, methods, and even non-public _vars_ **must** be a №1 challenge and involve the whole team<sup>:family:</sup> in discussions. This expense will pay off with *lingua franca* throughout the team and project, and ...
<details>
  <summary>... derived benefits</summary>
  
+ common comprehension of a domain, collaboration, and indeed bound team
+ genuine design and self-descriptive code
+ inspiration for behavior/domain-driven design
+ escape from heaps of reqs and specs - hard to follow but easy to misunderstand, forget (but mostly neglected)
+ reduced efforts to get into a project for newcomers
+ comfy navigation within the source code (both with IDE's explorer and CTRL+F)
 
</details>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<sup>:family:</sup><sub> The team here there aren't developers only but customers, testers, along with end users</sub>

## Rules of thumb

The higher the level of naming, the more attention.

## Verbal sins

+ Grandiloquence in any extent

Even top developers under time pressure and brakes on perfectionism will name logic classes as *services*, *helpers*, *utils*, *handlers* but would 
be barely proud of that.

General words will sound vague if not bombastic unless they belong to the domain. Compare `[Fact]` against modest `[TestCase]`. 
PUBLIC UTILITY

### Guidelines for methods

`Get` must be taboo within method names - either this must be property or a better description of the returned: `Read`, `Calculate` u.a.

🚧 .. TO BE CONTINUED ... 🚧