# Gradle publish to github
This was a PoC for figuring out how to publish thing to the github package repository. While it is really simple to publish something, 
reading is a completely different story. Github requires reading users to be authenticated, already making using the repository nedlessly hard, also there is 
no central repository. So every package read this way has to be listed separately as a repository.

## Conclusion
At this point github package is unusable for anything but small privately used packages. Using it in transitive dependencies will be an absolute nightmare
