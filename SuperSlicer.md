# SuperSlicer

[SuperSlicer](https://www.superslicer.org)

[SuperSlicer GitHub](https://github.com/supermerill/SuperSlicer)

## Commands

I had to run this one just to stop from getting this error

```
codesign --force --deep --sign - /Applications/SuperSlicer.app
```
```
xattr -cr /Applications/SuperSlicer.app
```
```
xattr -d com.apple.quarantine /Applications/SuperSlicer.app   
```
