# TestProject
Testing git-lfs usage on a UE first-person shooter template project

I'm following the instructions here:
https://wiki.unrealengine.com/Git_source_control_(Tutorial)

Not using a .gitignore file...

And keeping all the big files (they seem to all have the `.uasset` or `.umap` extension under git-lfs, as per:
https://git-lfs.github.com/

```
git init
git lfs init
git lfs track "*.uasset"
git lfs track "*.umap"
git add Content/
git commit -m "initial commit"
git push origin master
```
