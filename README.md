# [ECS Document](https://github.com/ecs-support/document)

- [Github](https://github.com/GitbookIO/gitbook)
- [Document](https://docs.gitbook.com/)
- [GitBook CLI](https://github.com/GitbookIO/gitbook-cli)
- [GitBook Example](https://github.com/GitbookIO/gitbook/blob/master/docs/examples.md)
- [Markdown Guide](https://www.markdownguide.org/getting-started/)


## Note



## Setup and Installation of GitBook

Getting GitBook installed and ready-to-go should only take a few minutes.

### legacy.gitbook.com

[legacy.gitbook.com](https://legacy.gitbook.com/)  is an easy to use solution to write, publish and host books. It is the easiest solution for publishing your content and collaborating on it.

It integrates well with the  [GitBook Editor](https://legacy.gitbook.com/editor).

### Local Installation

##### Requirements

Installing GitBook is easy and straightforward. Your system just needs to meet these two requirements:

-   NodeJS (v4.0.0 and above is recommended)
-   Windows, Linux, Unix, or Mac OS X

##### Install with NPM

The best way to install GitBook is via  **NPM**. At the terminal prompt, simply run the following command to install GitBook:

```
$ npm install gitbook-cli -g

```

`gitbook-cli`  is an utility to install and use multiple versions of GitBook on the same system. It will automatically install the required version of GitBook to build a book.

##### [](https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md#create-a-book)Create a book

GitBook can setup a boilerplate book:

```
$ gitbook init

```

If you wish to create the book into a new directory, you can do so by running  `gitbook init ./directory`

Preview and serve your book using:

```
$ gitbook serve

```

Or build the static website using:

```
$ gitbook build

```

##### [](https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md#install-pre-releases)Install pre-releases

`gitbook-cli`  makes it easy to download and install other versions of GitBook to test with your book:

```
$ gitbook fetch beta

```

Use  `gitbook ls-remote`  to list remote versions available for install.

##### [](https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md#debugging)Debugging

You can use the options  `--log=debug`  and  `--debug`  to get better error messages (with stack trace). For example:

```
$ gitbook build ./ --log=debug --debug
```



### create a new repository on the command line

```git
echo "# document" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ecs-support/document.git
git push -u origin main
```

### push an existing repository from the command line

```git
git remote add origin https://github.com/ecs-support/document.git
git branch -M main
git push -u origin main
```