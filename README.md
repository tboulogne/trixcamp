# TrixCamp
Simple, distraction free writing app based on [Basecamp's trix-editor](https://github.com/basecamp/trix).

<img src="https://s3.amazonaws.com/michaeljcalkins/screenshot.png" height="500">

## Getting Started

1. Download your version below
2. Know the keyboard shortcuts:
  - `cmd+s` to save
  - `cmd+n` to create a new document
  - `cmd+o` to open a document

## Downloads

[Mac Download](http://bit.ly/1KhZbgq)

[Windows Download](http://bit.ly/20w3p6e)

[Linux Download](http://bit.ly/1KOiDBp)

## Developer's Guide

**Working with the code:**

1. Install all components: `npm install`
2. Run electron: `electron .`
3. Start editing!

**Packaging for distribution:**

Mac: `electron-packager ./ TrixCamp --platform=darwin --arch=x64 --version=0.36.7 --overwrite`

Windows: `electron-packager ./ TrixCamp --platform=win32 --arch=x64 --version=0.36.7 --overwrite`

Linux: `electron-packager ./ TrixCamp --platform=linux --arch=x64 --version=0.36.7 --overwrite`

**.trix files**

TrixCamp takes the title and contents of the trix editor and builds a JSON object that looks like:

```
{
  "title": "Man In The Arena",
  "contents": "It is not the critic who counts; not the man who points out how the strong man..."
}
```

It then writes this to a file of the user's choosing.  Right now I add `.trix` to the end of all the files for future developments.

## Why

This was part of an experiment I did in planning and delivering applications quickly and I feel this was a highly successful and useful proejct.

More on that here: http://michaeljcalkins.com/2016/02/10/planning-so-you-can-deliver/

For updates follow: https://twitter.com/michaeljcalkins
