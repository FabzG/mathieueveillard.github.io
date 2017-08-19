# mathieueveillard.github.io
Articles to be published on [blog.mathieueveillard.com](http://blog.mathieueveillard.com). Subjects include software development, running and photography.


### CMS
[Jekyll](https://github.com/jekyll/jekyll) (minima theme customized) and [Disqus](https://disqus.com/) for comments.


### Branching
* One branch per article.
* Branches should be named after the unique `Id` of the article (cf. below).
* Branches should be merged on master once done, allowing publication. `git rebase master` before merge.
* Good practice is to not delete branches, allowing to keep track of article versions.
* Every commit modifying the blog itself (container), not the articles (content) should be made on `master`.


### Titles
[Front matter](https://jekyllrb.com/docs/frontmatter/)'s titles should comply to a `[Field] Title` pattern, e.g. `[Running] Récit d'un marathon`.


### Articles to be published
Field | Title | Id | (Link) | (Link)
------|-------|----|--------|-------
Software | L'agilité ou l'éloge de la confiance | 2 | [GitHub](https://github.com/mathieueveillard/mathieueveillard.github.io/blob/2/_posts/2017-08-06-L-agilite-ou-l-eloge-de-la-confiance.md) |
Software | La veille technologique | | |
Software | D'amateur à professionnel du code | | |
Software | L'informatique expliquée aux professionnels du recrutement | | |
Software | Test Driven Development | | |
Running | Récit d'un Marathon | 1 | [GitHub](https://github.com/mathieueveillard/mathieueveillard.github.io/blob/1/_posts/2017-08-06-Recit-d-un-marathon.md) | [Blog](http://blog.mathieueveillard.com/running/2017/08/06/Recit-d-un-marathon.html)
Running | Courir : un apprentissage | | |
Running | Retour d'expérience après un an de blessures | | |
Photography | Ecrire en lumière | | |
Photography | Les bases de l'exposition | | |
Photography | Simplifier et s'impliquer | | |
Photography | L'objectivité en photographie | | |
Photography | Le noir et blanc | | |
Photography | Composition | | |
Photography | Parler en images | | |
Photography | La profondeur de champ | | |
Photography | S'équiper | | |
Photography | La couleur : nature, captation et restitution | | |
Photography | La balance des blancs | | |
Photography | Retoucher ses photographies | | |
Photography | Imprimer ses photographies | | |
Photography | Le format RAW | | |
Photography | La photographie au flash | | |
Photography | L'art du portrait | | |


### Proofing
`bundle exec jekyll serve`


### License
Creative Commons Attribution Share Alike 4.0.
