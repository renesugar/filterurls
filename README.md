# About
**filterurls** reads a list of backup format URLs and filters out sites and URLs.

# Usage
```
Usage: python3 -B ./filterurls.py [FLAGS]
    --path:       Base path of the project to be scanned (Default: .)
    --root:       Root path of the project to be scanned (Default: /)
    --prefix:     Replace root path with this prefix (Default: /)
    --extensions: File extensions that are read (Default: .txt)
    --exclude:    Paths of folders to exclude (Default=[])
    --sites:      Path to file containing sites to exclude.
    --backup:     Bookmark backup format (title, add_date, last_modified, url)
```

# Example

```
python3 -B filterurls.py --path ./input --sites ./sites.txt --output ./urls.txt --backup
```