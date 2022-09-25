# Pen&Paper

The better place to digitally store all things Pen&Paper!

## Introduction

After having to go through several different (and sometimes completely unsorted) collections of Pen&Paper related files for years, I decied to create this template repository.
The solution was obvious, share another standard so that we don't have to have a dozen of standards (though seriously, I'm hoping that having this one clearly documented should help at least my group).

Ok, but what is it really? - A template repository? - Another Standard?

It's just a folder structure with some "template folders" to easily create the needed folders for a new campaign, characters or sources and some placeholder (marked with `[PH]`) files for good measure.
So let's explore that in the next chapter.

## Structure

The folder structure is depicted in the following file tree.

```txt
Pen&Paper
└── -RPG_Systems_here-
    ├── Campaigns
    │   └── -Campaigns_here-
    │       └── Characters
    │           └── -Characters_here-
    │               ├── [PH]artwork.png
    │               ├── [PH]CharacterSheet.pdf
    │               ├── [PH]inventory.txt
    │               └── [PH]token.png
    ├── Content
    │   ├── 3d Models
    │   ├── Character Sheets
    │   ├── DM Tools
    │   └── Maps
    ├── Rules
    │   ├── Homebrew
    │   │   └── -Homebrew_Source_here-
    │   │       ├── [PH]book_1.0.0.pdf
    │   │       ├── [PH]book_1.1.0.pdf
    │   │       └── [PH]book_2.0.0.pdf
    │   └── Official
    │       └── -Official_Source_here-
    │           ├── [PH]book_1.0.0.pdf
    │           ├── [PH]book_1.1.0.pdf
    │           └── [PH]book_2.0.0.pdf
    └── _unsorted
```

To understand this structure properly ?two concepts need to be explained:

1. Template Folders
> A Template Folder can be identified by the pre- and appended `-` (colons). A Template Folder represents something that might be useful for a Pen&Paper and typically exists more than once, a campaign for example. If you want to create the structure for a new campaign you can simply copy the Template Folder and rename it to the name of the new campaign.
1. Placeholder Files
> A Placeholder File is typically part of a Template Folder. After having copied a Template Folder, for example the Template Folder for Player Characters, these Placeholder Files are meant to be replaced by files containing the data. When creating a campaign for example you can also decide to overwrite the Placeholder File for the CharacterSheet so that when players start to create their characters they all use the same CharacterSheet. A placeholder file might also indicate to use [semantic versioning](https://semver.org/) for a specific file.

This should cover the most common files you need to store for you Pen&Paper.
So let's get to explaining how to use this structure efficiently and make sure the upkeep for it to be sorted stays minimal.

## Rules

I'm not here to stay Rules are Rules, but make sure your group can agree on them.

1. Make sure everyone reads or gets this document explained.
2. Only create files where they are supposed to stay.
3. If you got a feeling something might get cluttered, speak with the others. For example you might need to create subfolders for regions in the Maps folder.
4. Only use the _unsorted folder if there currently is no optimal place to store the file you want to store.
5. If the _unsorted folder gets cluttered, speak with you group, it's likely you need to create a new folder to structurize the data.
6. (Optional) Think of a way to synchronize this folder with all your players so you won't need to constantly manage different versions/duplicates.

## Contributing

That's it, you read through it all ^^

Now if you think that you could do something better, please do!
Feel free to open up at least a feature/optimization request or in case you might've spotted something out of order a bug report.
And if you think that won't do feel free to fork you own version of this. Who knows, if you create a pull request it might even be merged.
