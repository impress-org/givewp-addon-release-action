This action takes a plugin slug, zip file, and readme.txt file and deploys it securely
to GiveWP.com. This should only be used on releases and after testing. Use with care.

### Usage
```yaml
steps:
  - uses: actions/givewp-addon-release@v1
    with:
      plugin-slug: give-recurring
      zip-file: /path/to/give-recurring.zip
      readme-file: /path/to/readme.txt
```