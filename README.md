# Github-Foundations
## Git Terminology
- Hash: A number produced by a hash function that represents the contents of a file or another object as a fixed number of digits. Git traditionally uses SHA-1 hashes that are 160 bits long, though modern versions of Git also support SHA-256 (256 bits). One advantage to using hashes is that Git can tell whether a file has changed by hashing its contents and comparing the result to the previous hash. If the file time-and-date stamp is changed, but the file hash isn’t changed, Git knows the file contents aren’t changed.

- Object: A Git repo contains four types of objects, each uniquely identified by a hash. A blob object contains an ordinary file. A tree object represents a directory; it contains names, hashes, and permissions. A commit object represents a specific version of the working tree. An annotated tag object stores metadata, such as a name, message, and optional signature, and usually points to a commit, though it can point to other Git objects as well. Git also supports lightweight tags, which are references rather than objects.

## What are Gists?
Gists are a feature of GitHub that allows users to share code snippets, notes, or other small pieces of information in a lightweight and convenient way. They are essentially mini Git repositories, which means you can fork, clone, and version-control them just like a full repository. Gists are particularly useful for sharing quick solutions, configuration files, or examples without the need to create a full repository.

## What are wikis?
Every repository on GitHub.com comes equipped with a section for hosting documentation, called a wiki. You can use your repository's wiki to share long-form content about your project, such as how to use it, how you designed it, or its core principles. While a README file quickly tells what your project can do, you can use a wiki to provide additional documentation.

It’s worth a reminder that if your repository is private, only people who have at least read access to your repository will have access to your wiki.

## What are GitHub Pages?
Now let’s take a look at GitHub Pages. You can use GitHub Pages to publicize and host a website about yourself, your organization, or your project directly from a repository on GitHub.com.

GitHub Pages is a static site-hosting service that takes HTML, CSS, and JavaScript files straight from a repository on GitHub. Optionally, you can run the files through a build process and publish a website. You can specify a source branch and folder (e.g., /docs) for your Pages site, and GitHub will host the content publicl
