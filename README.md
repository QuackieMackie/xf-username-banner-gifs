# XenForo Username & Banner GIFs

A collection of animated username and banner GIFs for use in XenForo forums.

## Structure

> assets/ -
The `assets` directory contains the GIF files.

> less/ -
The `less` directory contains pre-written styling snippets for applying the GIFs.

## Usage

Copy the relevant LESS snippet into your XenForo template, or group `Username CSS` and update the file path.

### Example

#### Banner
```less
.userBanner.userBanner--groupName {
    background-image: url(path/to/gifName.gif);
    background-position: center;
    background-size: 100% 100%;
}
```

#### Username
Copy the contents of the `.userBanner.userBanner--groupName`.

## Credits
- [GifCities](https://gifcities.org/) - search engine used for archived GIFs, part of the [Internet Archive](https://archive.org/)