# AutoFocus Algorithm for Liquid lenses
This code is written for finding a infocus image in image dataset

## Datasets

[Said Pertuz, Real image sequences](https://drive.google.com/file/d/1nFqboGIXWorr_3K9OflV8Z60guX7KO6G/view)

## Usage


```
python Focus_match.py --f Image/logitech/logi03/ --r 500 200 100 100
```

--f: Folder path which have image dataset.

--r: Regieon of Interest where focus measure is actually calculated. if you don't pass this argument, focus measure will be calculated in entire image area.  (optional)

## Links
[液体レンズ件（Auto focusing）報告書](https://www.notion.so/Auto-focusing-c843477a07fb4edbb5a90478d9318215)
