Backup procedure for photo directory
====================================
## Summary
Adobe Lightroom to copy photos off memory cards to `D:` data drive and import second copy to second drive.

`Robocopy` to network mounted disk

```
robocopy d:/pictures ??? /copyall /mt:25 /r:0 /w:0 /v /tee /log:robocopy.log
```