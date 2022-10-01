# homer-CBD-theme
Calm Blue Disaster is a minimal theme for Homer dashboard implemented in bluish colors

# Demo
https://user-images.githubusercontent.com/56602996/193428748-b8a4b57b-d3ae-4ca9-bc6c-ddd3f86d000a.mp4

# Applying
1. Create a `custom.css` file in the `assets` directory
```css
@charset "UTF-8";

body .tag {
  background-color: #5a95f5;
}

#bighead > div > nav > div > div.navbar-menu > div.navbar-end > div > input[type=text] {
  background-color: #5a95f5;
  color: #eafeff;
}

#bighead > div > nav > div > div.navbar-menu > div.navbar-end > div > label::before {
  color: #eafeff;
}
```

2. Modify your Homer config to include the following
```yaml
stylesheet:
  - "assets/custom.css"
```

3. Replace the default light theme definition with these values
```yaml
  light:
    highlight-primary: "#eafeff"
    highlight-secondary: "#c6f5fe"
    highlight-hover: "rgba(254, 133, 153, .5)"
    background: "#c6f5fe"
    card-background: "#eafeff"
    text: "#773c62"
    text-header: "#773c62"
    text-title: "#773c62"
    text-subtitle: "#5a95f5"
    card-shadow: rgba(0, 0, 0, .3)
    link: "#fe4466"
    link-hover: "#fe8599"
    tag: "#5a95f5"
```
