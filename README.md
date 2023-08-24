# Factory Planner - Locale

This repository centralizes the localisation efforts for Factory Planner, a mod for [Factorio](https://www.factorio.com). For further details on the mod itself, please refer to its [mod page](https://mods.factorio.com/mod/factoryplanner) and [Github project](https://github.com/ClaudeMetz/FactoryPlanner). If you want to contribute, take a look at the heading below. If you have any technical questions, feel free to join the [Discord](https://discord.gg/ABqNEQc), or open an [issue](https://github.com/ClaudeMetz/FactoryPlannerLocale/issues/new).

I realize that doing this through Github makes it somewhat unaccessible for non-technical users, which is a shame. It is however the most time-efficient and well-structured way for me to organize this. I feel like it is a good middle ground between my effort and the value to the end-user.

## Contribute

If you want to contribute to the localisation of Factory Planner, thank you! I'll try and lay out the basics of how you can do that. It does require some understanding of [git and Github](https://guides.github.com/introduction/git-handbook/), which I won't get into here.

One way you can contribute without actually submitting changes yourself is by creating an [issue](https://github.com/ClaudeMetz/FactoryPlannerLocale/issues/new). If you notice any errors, missing translations, or similar, you can create an issue alerting others to the problem. That way, it might be fixed by someone that has the skills necessary to do so.

The process to actually submit translations yourself is a bit more involved. You need to create/update a localisation file and submit it through a [pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests). The localisation files have a particular format that needs to be followed, which is explained in detail on Factorio's [wiki](https://wiki.factorio.com/Tutorial:Localisation). Read this article carefully, as it explains the file format and the particularities you'll encounter when going over the locale file.

To start translating, you'll need to take the [English locale file](https://github.com/ClaudeMetz/FactoryPlanner/blob/master/modfiles/locale/en/config.cfg) as a basis for your translations (if you're not updating an already existing language). This will be most up-to-date locale, as it's the one I am working on myself. Then, you'll have to replace all the English strings with ones in your desired language, while not breaking the format that is described in the wiki article mentioned above. The English locale will change quite frequently as the mod ifself gets updated and expanded, so it would be great if you could update your localisation periodically to incorporate those changes.

When you're done translating, you have to submit a pull request to this repository. I'll review it and, if there are no problems with it, merge it into the project. The changes will then be included with the next release of the main mod, which might take a week or two in some cases. So please be patient while waiting for your contributions to be released.

Again, if you have any technical questions, feel free to join the [Discord](https://discord.gg/ABqNEQc), where I'll try to help you with those.

## License

This project is 'licensed' under the Unlicense, meaning it is being released to the [public domain](https://en.wikipedia.org/wiki/Public_domain). This causes you to forfeit any rights to the contributions you make. This is in contrast to the rest of the mod, which is licensed under [MIT](https://en.wikipedia.org/wiki/Public_domain).
