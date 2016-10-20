# uTemplate Template Repository
Welcome to the Template Repository for uTemplate!  Depending on what you're here to do, there's two sections to get you started: Downloading Templates and Submitting Templates.  First up, Downloading Templates.

## Downloading Templates
uTemplate has a built-in download function.  It'll not only show you what's available and allow you to download it, it'll also handle importing them into the correct directories.

It's generally easier to let the downloader do the heavy lifting for you, but in case you want to do things manually, you can either download or fork-and-pull this repository.  Note: when placing template files in your project manually, make sure to place them in the user-specified Template directory.  (You can check and change this in in the uTemplate Preferences)

## Submitting Templates
Anyone can submit new templates to this repository.  It's easy, and your submitted templates will show up immediately in the uTemplate downloader.

To start, you'll need to fork this repository.  After you've got your own repository set up you can add your own template and submit a pull request for this repository.  Creating a template is easy -- you can read all about it in [uTemplate's documentation](http://unfinitygames.com/products/utemplate/documentation/template-creation-basics), or take a look at the [Default Templates](https://github.com/UnfinityGames/uTemplate/tree/master/Default%20Templates) here to get an idea of how they work.

When submitting templates, there are a few things to keep in mind:
* If your template is for a product available on the Asset Store, it should be placed in the Asset Store Templates directory.
* Likewise, if your template isn't for a specific product, or isn't available on the Asset Store, it should go in the Community Templates directory.
* Submitted templates should be in their own directory, especially if it's part of an Asset Store package.  For example, if you're submitting a Template for an Asset Store package, and the package is called "Awesome Template", your directory tree for the Template file should look like `"Asset Store Templates/Awesome Template/AwesomeTemplate.cs.txt"`.  Basically, each template should be contained in their own folder, to keep things neat and tidy.  The only exception would be:
* Fixing/extending already-existing templates.  If a pre-existing template needs an update it's best to submit a pull request with changes to the pre-existing file.  The reason for this is that users that have already downloaded this template will be able to update their templates, without having to search for a newer version. 

## License
This repository is designed for use in conjunction with uTemplate.  As such, this repository is considered an extension of uTemplate, and is covered under the same license (i.e. the [Unity Asset Store EULA](https://unity3d.com/legal/as_terms)).
