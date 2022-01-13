# first-attempt-assign1
assignment-one-sos
orymar@Toris-MacBook-Air documents % pwd
/Users/orymar/documents
orymar@Toris-MacBook-Air documents % ls
GitHub		sait-wbdv
orymar@Toris-MacBook-Air documents % cd sait-wbdv
orymar@Toris-MacBook-Air sait-wbdv % ls
in-class			workspace.code-workspace
orymar@Toris-MacBook-Air sait-wbdv % cd in-class
orymar@Toris-MacBook-Air in-class % ls
01-11-22	code-journal
orymar@Toris-MacBook-Air in-class % cd code-journal
orymar@Toris-MacBook-Air code-journal % git clone https://github.com/oryxetmar/code-journal.git
Cloning into 'code-journal'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.
orymar@Toris-MacBook-Air code-journal % cd code-journal
orymar@Toris-MacBook-Air code-journal % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
orymar@Toris-MacBook-Air code-journal % add index.html
zsh: command not found: add
orymar@Toris-MacBook-Air code-journal % add <script src="https://gist.github.com/acidtone/6871979b4f4b04375edb6312dcdba5b7.js"></script>
zsh: parse error near `<'
orymar@Toris-MacBook-Air code-journal % cd code-journal
cd: no such file or directory: code-journal
orymar@Toris-MacBook-Air code-journal % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
orymar@Toris-MacBook-Air code-journal % mv index.html
usage: mv [-f | -i | -n] [-v] source target
       mv [-f | -i | -n] [-v] source ... directory
orymar@Toris-MacBook-Air code-journal % ls
LICENSE		README.md
orymar@Toris-MacBook-Air code-journal % git add index.html
fatal: pathspec 'index.html' did not match any files
orymar@Toris-MacBook-Air code-journal % git add https://gist.github.com/6871979b4f4b04375edb6312dcdba5b7.git
fatal: pathspec 'https://gist.github.com/6871979b4f4b04375edb6312dcdba5b7.git' did not match any files
orymar@Toris-MacBook-Air code-journal % git clone https://gist.github.com/6871979b4f4b04375edb6312dcdba5b7.git
Cloning into '6871979b4f4b04375edb6312dcdba5b7'...
remote: Enumerating objects: 69, done.
remote: Total 69 (delta 0), reused 0 (delta 0), pack-reused 69
Receiving objects: 100% (69/69), 7.47 KiB | 3.73 MiB/s, done.
Resolving deltas: 100% (16/16), done.
orymar@Toris-MacBook-Air code-journal % ls
6871979b4f4b04375edb6312dcdba5b7	README.md
LICENSE
orymar@Toris-MacBook-Air code-journal % ls
LICENSE		README.md	index.html
orymar@Toris-MacBook-Air code-journal % index.html
zsh: command not found: index.html
orymar@Toris-MacBook-Air code-journal % mv command index.html
mv: rename command to index.html/command: No such file or directory
orymar@Toris-MacBook-Air code-journal % git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store
	index.html/

nothing added to commit but untracked files present (use "git add" to track)
orymar@Toris-MacBook-Air code-journal % git add index.html
warning: adding embedded git repository: index.html
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint: 
hint: 	git submodule add <url> index.html
hint: 
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint: 
hint: 	git rm --cached index.html
hint: 
hint: See "git help submodule" for more information.
orymar@Toris-MacBook-Air code-journal % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store

orymar@Toris-MacBook-Air code-journal % git add <script src="https://gist.github.com/acidtone/6871979b4f4b04375edb6312dcdba5b7.js"></script>
zsh: parse error near `<'
orymar@Toris-MacBook-Air code-journal % 
