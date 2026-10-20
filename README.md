# Bavi Tools — VCC listing

VRChat Creator Companion (VCC) listing for Bavi's VRChat tools.

**Add to VCC:** open https://rappyr.github.io/Bavi-VPM/ and press *Add to VCC*, or in VCC: *Settings > Packages >
Add Repository* and paste:

```
https://rappyr.github.io/Bavi-VPM/index.json
```

## Packages

| Package | Repository |
|---|---|
| Bavi Motion Patcher (`com.bavi.motion-patcher`) | https://github.com/Rappyr/Bavi-MotionPatcher |

## Maintaining

* The listing is built from the GitHub releases of the repositories in [`source.json`](source.json) by VRChat's
  [package-list-action](https://github.com/vrchat-community/package-list-action) and published to GitHub Pages
  (from VRChat's [template-package-listing](https://github.com/vrchat-community/template-package-listing)).
* It rebuilds when `source.json` changes on `main`. After releasing a package, run **Build Repo Listing** from the
  Actions tab (or `gh workflow run build-listing.yml -R Rappyr/Bavi-VPM`).
* A new tool: add its repository to `githubRepos`.
