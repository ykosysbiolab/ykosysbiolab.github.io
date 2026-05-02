# Systems Biology Lab Website

This is a static GitHub Pages website for the Systems Biology Lab at HUFS.

## Recommended GitHub repository

Create this repository under the `ykosysbiolab` GitHub organization:

```text
ykosysbiolab.github.io
```

Then upload all files in this folder to the repository root.

## GitHub Pages settings

Go to:

```text
Settings → Pages
```

Use:

```text
Source: Deploy from a branch
Branch: main
Folder: /root
```

The site will first appear at:

```text
https://ykosysbiolab.github.io
```

## Custom domain

This package already contains a `CNAME` file:

```text
sysbio.hufs.ac.kr
```

Ask the HUFS domain/DNS administrator to set:

```text
Type: CNAME
Host/Name: sysbio
Target/Value: ykosysbiolab.github.io
```

After DNS is updated, set the custom domain in GitHub Pages settings:

```text
sysbio.hufs.ac.kr
```

Then enable HTTPS.
