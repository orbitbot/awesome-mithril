# Contributing

Thank you for your suggestions! We do have some relatively strict rules to keep the list itself awesome, so please keep that in mind when you contribute your suggestion.

## Before you contribute your suggestion

Please note that this project is released with a
[Contributor Code of Conduct](code-of-conduct.md). By participating in this
project you agree to abide by its terms.

Any contributions should be Mithril-related, but they might not fit into the existing categories. If you feel that a category is missing or that the structure of the links would be better served with some changes, please mention it in your pull request when adding links or open a separate issue.

Be sure to [check existing pull requests](https://github.com/orbitbot/awesome-mithril/pulls) before filing a new one with your suggestion. Yours could be a duplicate, and reviewing duplicates just wastes everyone's times, including yours. However, if you do find a duplicate and you feel it could be done better, do feel free to contribute your suggestions to it there. (If that duplicate is abandoned when changes were requested to it, *then* you can feel free to file a new pull request for it.)

## When you contribute your suggestion

Contributing your suggestion is usually as easy as [editing `README.md`](https://help.github.com/en/articles/editing-files-in-another-users-repository) and [filing a pull request](https://help.github.com/articles/using-pull-requests/). For more complicated changes, it might be easier for you to [fork the repository first](https://help.github.com/en/articles/fork-a-repo) and then [editing what you need to in your local fork](https://help.github.com/en/articles/editing-files-in-your-repository).

Make one suggestion per pull request. If you have multiple suggestions, file a new pull request for each suggestion. It's easier to search for duplicates that way, and it's easier to say yes to one suggestion, no to another.

And finally, when you do go to file a pull request, please make sure to include a useful title with it, so we know at a glance what the suggestion is all about.

## Link format

Use the following link format. If it doesn't follow this format, it'll likely be rejected.

> ```md
> - [Link name](URL) - Short description.
> ```

As an exception, the "Snippets" section follows the following format, where the link name is itself the snippet description, with the period *inside* the hyperlink:

> ```md
> - [Short description.](URL)
> ```

References to things, *especially* in link names, should use the name and capitalization the item uses to describe itself. For instance:

- The framework this is about is "Mithril", not "Mithril.js" or "MithrilJS". [There may be existing vestiges of this inconsistency in the official docs, but that's being corrected.](https://github.com/MithrilJS/mithril.js/pull/2316)
  - As an exception, Mithril's unofficial hashtag is `#MithrilJS`. You'll see variations like `#mithril` and `#mithriljs`, but this list prefers `#MithrilJS`.
- [Mithril's internal test runner](https://github.com/MithrilJS/mithril.js/tree/next/ospec) is "ospec", not "Ospec", "ospec.js".
- [Arthur Clemens' Material Design library](https://github.com/ArthurClemens/polythene) is "Polythene", not "mithril-polythene", "polythene", or "PolytheneJS".
- [The popular V8-based server-side JavaScript runtime](https://nodejs.org/) is "Node.js", not "Node", "NodeJS", or "node".
- [The popular package manager bundled with Node](https://npmjs.com/) is "npm", not "NPM", "Npm", or "npmjs".

> Prefer:
> ```md
> - [Polythene](https://github.com/ArthurClemens/polythene) - Material Design for Mithril and React.
> ```
>
> Avoid:
> ```md
> - [Polythene](https://github.com/ArthurClemens/polythene) - Material design for mithril.js and react.
> ```
>
> Avoid:
> ```md
> - [Polythene.js](https://github.com/ArthurClemens/polythene) - Material Design for Mithril and React.
> ```

If it's a snippet, it goes in "Snippets". If you find yourself trying to type something like `- [CodePen snippet by @me](https://codepen.io/user/pen/...) - Cool dropdown.`, it belongs in "Snippets" and should be instead written as `- [Cool dropdown.](https://codepen.io/user/pen/...)`

Each link description and snippet description should start with an uppercase letter and end with a period, and it should use proper capitalization and grammar. If you aren't sure how to write it, you can still file a pull request anyways and just tell us where you're not certain, so we can help you correct it.

As an exception, if the first word references a trademark and they prefer a lowercase first letter (like eBay or npm), prefer that over this.

> Prefer:
> ```md
> - [Polythene](https://github.com/ArthurClemens/polythene) - Material Design for Mithril and React.
> ```
>
> Avoid:
> ```md
> - [Polythene](https://github.com/ArthurClemens/polythene) - A Material Design library for Mithril and React
> ```

Link additions should be added to the bottom of the relevant category. This makes merging suggestions a lot easier on our part.

> Prefer:
> ```diff
>  ### Libraries, Components & Plugins
>  
>  - [Polythene](https://github.com/ArthurClemens/polythene) - Material Design for Mithril and React.
> +- [mopt](https://github.com/MithrilJS/mopt) - Optimize `m()` calls to javascript objects.
> ```
>
> Avoid:
> ```diff
>  ### Libraries, Components & Plugins
>  
> +- [mopt](https://github.com/MithrilJS/mopt) - Optimize `m()` calls to javascript objects.
>  - [Polythene](https://github.com/ArthurClemens/polythene) - Material Design for Mithril and React.
> ```

Link additions should be self-contained, complete, and accurate. This ensures people know at a glance what it is.

> Prefer:
> ```md
> - [Polythene](https://github.com/ArthurClemens/polythene) - Material Design for Mithril and React.
> ```
>
> Avoid:
> ```md
> - [Polythene](https://github.com/ArthurClemens/polythene) - Material Design for Mithril.
> ```
>
> Avoid:
> ```md
> - [Polythene](https://github.com/ArthurClemens/polythene) - Material Design.
> ```
>
> (Context: Polythene supports both Mithril and React natively.)

Leave out extra whitespace. It doesn't really add anything, and it'll just create unnecessary diffs in the future.

> Prefer:
> ```md
> - [Polythene](https://github.com/ArthurClemens/polythene) - Material Design for Mithril and React.
> ```
>
> Avoid:
> ```md
> - [Polythene](https://github.com/ArthurClemens/polythene)  -  Material Design for Mithril and React.
> ```
>
> Avoid:
> ```md
> ### Some section
>
>
> - [Polythene](https://github.com/ArthurClemens/polythene) - Material Design for Mithril and React.
> ```

## Other suggestions

We do encourage suggestions beyond just adding links to new projects. Suggestions to add new categories or improve the existing categorization are certainly welcome, and suggestions to improve existing links are also encouraged.

If you feel an existing link could be improved, feel free to contribute that - it works the same way it would if you were creating a new link.

If you feel a category is missing or that the way categories or links are structured could be otherwise improved, please file an issue first or reference it in the relevant pull request (if it pertains to that link) so we can discuss it. If you file a pull request in light of one of these discussions, please be sure to:

1. Keep the format for sections consistent with existing ones.
2. Update the table of contents appropriately, so it continues to direct people to the right places.

## Updating your pull request

It's often difficult to keep your suggestion up to the standards above, even after you filed your pull request. We may request certain changes to your pull request for various reasons, including meeting these standards. You don't need to create a whole new pull request for this - you can just edit the existing one and it'll make our lives a lot easier. If you're not sure how to do that, [this guide can help you on various ways to update your pull request](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md) so we can merge it with the changes included.
