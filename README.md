# memo
That I can't use my laptop at work 

## git nes
foundation elements: Blobs, trees and commits.
### blob
add files with git add, save the content of file in .git/object
name of the blob: hash of the content, using first 2 chars to create a subfolder in .git/objects/xx
name of the file: remaining chars of the hash

### trees 
root tree: stores the structure of files and folders of the repo, ref to every blob/sub-folder, built recursively for each folders (strcture added).
hashing trees: it is also hashed, then stored in the same way in .git/objects

### commits 
content in commits: tree, author, committer, parent commit, feat(comment), saved to .git/ojects 

## git bricks

### branches
named reference to a commit, each branch would go it .git/regs/heads when initiated
can be viewed as a file that tracking commits




