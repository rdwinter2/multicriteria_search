Backup procedure for photo directory
====================================
## Summary
Adobe Lightroom to copy photos off memory cards to `D:` data drive and import second copy to second drive.

`Robocopy` to network mounted disk

```
robocopy d:/pictures ??? /copyall /r:0 /w:0
```