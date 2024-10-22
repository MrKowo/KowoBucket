# Kowo Scoop Bucket

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/MrKowo/KowoBucket/actions/workflows/ci.yml/badge.svg)](https://github.com/MrKowo/KowoBucket/actions/workflows/ci.yml) [![Excavator](https://github.com/MrKowo/KowoBucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/MrKowo/KowoBucket/actions/workflows/excavator.yml)

Scoop Bucket containing apps I use which aren't included in the official ones.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add KowoBucket https://github.com/MrKowo/KowoBucket
scoop install KowoBucket/<manifestname>
```


## _work in progress_

## How do I use this template?

1. ~Generate your own copy of this repository with the "Use this template"
   button.~
2. ~Allow all GitHub Actions:~
   - ~Navigate to `Settings` - `Actions` - `General` - `Actions permissions`.~
   - ~Select `Allow all actions and reusable workflows`.~
   - ~Then `Save`.~
3. ~Allow writing to the repository from within GitHub Actions:~
   - ~Navigate to `Settings` - `Actions` - `General` - `Workflow permissions`.~
   - ~Select `Read and write permissions`.~
   - ~Then `Save`.~
4. Document the bucket in `README.md`.
5. ~Replace the placeholder repository string in `bin/auto-pr.ps1`.~
6. ~Create new manifests by copying `bucket/app-name.json.template` to
   `bucket/<app-name>.json`.~
7. ~Commit and push changes.~
8. If you'd like your bucket to be indexed on `https://scoop.sh`, add the
   topic `scoop-bucket` to your repository.
