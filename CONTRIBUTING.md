Thank you very much for contributing!

*Please make sure you keep the alphabetic order.*

The syntax is the following:
```markdown
  * [AppName](Link to Homepage) - Short description ([F-Droid](Link to the app on F-Droid), [Source Code](Link to the source code))
```
If the app doesn't have a homepage, use
```markdown
  * Appname - Short description ([F-Droid](Link to the app on F-Droid), [Source Code](Link to the source code))
```
If the app is not on F-Droid, provide a link to the page where you can get the .apk file (no direct link), it **must** be from the developer.  
Please use "non-free APK" if the .apk includes non-free parts.
The syntax is:
```markdown
  * Appname - Short description ([APK](Link to the download page of the .apk), [Source Code](Link to the source code))
```
If the app uses or connects to non-free servers, includes proprietary blobs, tracks users or has other antifeatures, please make sure you want to include this app. If there's an alternative with similar features and no antifeatures, include it instead.  
If you are sure there is no better alternative, mark those apps like this:
```markdown
 * Appname - Short description ([F-Droid](Link to the app on F-Droid), [Source Code](Link to the source code))  
 ![Warning description](https://img.shields.io/badge/antifeature-antifeature--description-red.svg?style=flat-square) A few words about the antifeature.
```
We are using shields.io, check their website for the image URL syntax if you stumble upon problems.

If you want to add another category, use the following syntax:
```markdown
  - [Category name](#category-name)
```
In the list, insert the category with:
```markdown
## Category name
```
Make sure #category-name is identical to the actual category name (Space gets replaced with a `-`).
