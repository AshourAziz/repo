# repo
A collaborative Maven repo hosted by GitHub

## Adding files
* Get a jar, by compiling it or whatever.
* Install maven if you haven't already.
* Find the package, name and version number by looking at the MANIFEST inside the jar if available
* `mvn deploy:deploy-file -DgroupId=PACKAGE -DartifactId=NAME -Dversion=VERSION -Dfile=FILENAME.jar -Durl=file:///C:/Users/AlHarrington/GitHub/repo` for windows, or
* `mvn deploy:deploy-file -DgroupId=PACKAGE -DartifactId=NAME -Dversion=VERSION -Dfile=FILENAME.jar -Durl=file:///home/alharrington/repo` for other
* Fork the repo using the button above
* Add your fork as a new remote. `git remote add mine https://github.com/USERNAME/repo`
* Commit and push your changes. `git add .; git commit -a -m "Adding NAME by PERSON"; git push mine gh-pages`
* Create a pull request, and I'll check and pull the new artifacts.

If you have any questions, create an issue.
