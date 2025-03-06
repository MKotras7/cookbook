[http://cookbook.matthewkotras.xyz](http://cookbook.matthewkotras.xyz)

# cookbook
My personal list of recipes

## Running locally

Ensure hugo is installed: https://gohugo.io/installation/linux/

Build using the `hugo` command in the root directory.

Then run with:

```
python3 -m http.server 8080 --directory public
```

## Useful tips

Within the recipes directory, run the command to concatenate every file into clipboard, useful for AI
```
for file in *; do echo "$file"; cat "$file"; echo ""; done | xclip -selection clipboard
```