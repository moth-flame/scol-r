Full documentation is [available on confluence](https://mothandflame.atlassian.net/wiki/spaces/ENGINEERIN/pages/1658257411/How+to+create+and+test+SCORM+packages).


To build a new zip file locally:
```
touch scorm.zip && rm scorm.zip && find . -type f \( -name "*.js" -o -name "*.html" -o -name "*.xml" \) ! -path "./node_modules/*" -print | zip scorm.zip -@
```
