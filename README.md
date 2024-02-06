Ci Specification
====================

Ci (pronounce: `chee`). The spesification to store the files.

One of the target of this spesification is Flat File CMS.

## Summary

Store the files with these directory:

```
[/<owner>]/<container>/<year>
```

## Introduction

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be
interpreted as described in RFC 2119.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
culpa qui officia deserunt mollit anim id est laborum.

## The Directories

### Level 0 - The Owner

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
culpa qui officia deserunt mollit anim id est laborum.

### Level 1 - The Container

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
culpa qui officia deserunt mollit anim id est laborum.

### Level 2 - The Year

Partition with the year of created files.

## The Files

RECOMENDED Prefix with created date of file.

## The Path

For internal reference in user pov.

```
/<container>/<year>/<files.extension>
```

## Example

Before

```
DCIM/IMG_4291.MP4
Downloads/WhatsApp Image 2024-02-01 at 21.12.59.jpeg
Downloads/vlc-3.0.20-win64.exe
```

After using Ci Specification.

```
gallery/2022/20240501_160104_IMG_4291.MP4
gallery/2024/20240201_211259_WhatsApp Image.jpeg
application-windows/2023/vlc-3.0.20-win64.exe
```

## About the name

`Ci` means water springs. It used most of the starts name of village or district
in West of Java Island, Indonesia.
