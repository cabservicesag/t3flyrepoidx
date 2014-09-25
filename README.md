t3flyrepindex
=============

*Cause live is to short to build packages*

TYPO3 Extension GIT fly index (Only distributed systems will survive)

https://github.com/cabservicesag/flyrepo

Update:
1.) get github data
php ../flyrepo/cli/getRepoFromGithubUser.php TYPO3-extensions  

2.) create repository files
php ../flyrepo/cli/createRepoFilesFromGithubJson.php repolist-TYPO3-extensions.json typo3conf/ext
