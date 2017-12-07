Ref: [AGWA/git-crypt: Transparent file encryption in git - GitHub](https://github.com/AGWA/git-crypt)

before getting started encryption configure, please read [Generating a new GPG key - User Documentation](https://help.github.com/articles/generating-a-new-gpg-key/)

1. Set encryption configure to .gitattributes what you want to unreadable that the others.
2. Initialize git-crypt in git repository by `git crypt init`
3. Add encryption-key with `git crypt add-gpg-user example@example.com`
4. And just commit to git as usualy
