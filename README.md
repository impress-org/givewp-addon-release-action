This action clears a file within the Sucuri cache.

### Usage
```yaml
steps:
  - uses: actions/clear-sucuri-cache-action@v1
    with:
      api_key: ${{ secrets.SUCURI_API_KEY }}
      api_secret: ${{ secrets.SUCURI_API_SECRET }}
      file: /path/to/file.zip
```
