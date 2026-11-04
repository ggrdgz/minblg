# minblg
A very minimal blog theme for [Hugo](https://gohugo.io/).

## Configuration
```yaml
menus:
  main:
  - name: Home
    pageRef: /
    weight: 10
  - name: Tags
    pageRef: /tags
    weight: 20
  - name: Feed
    url: /index.xml
    weight: 30
  - name: GitHub
    url: "https://github.com/<your_github_account>"
    weight: 40
params:
  menuColor: blue | green | purple # default is blue
  footerText: Lorem ipsum # default is "&copy; CURRENT_YEAR title"
```
