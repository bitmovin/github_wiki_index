Creates an index with links from a github wiki which is structured in folders. An example could be found in the wiki of this page where the index will be created in the _Sidebar.md.

![index example](https://raw.githubusercontent.com/bitmovin/github_wiki_index/master/index.png "index example")

## How does it work?

- Clone your wiki git repo (e.g., git clone https://github.com/bitmovin/github_wiki_index.wiki.git)
- Move mk_index.py into the folder of the wiki
- Execute mk_index.py with _python mk_index.py_
- Now you should see a _Sidebar.md with the index generated from your folder and file structure
