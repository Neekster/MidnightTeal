# Dark Teal Theme

## Screenshots

### Lovelace Dashboard
![image](https://user-images.githubusercontent.com/58367045/147864065-3d2f80d5-0826-4bf4-b908-04355d25a651.png)
![image](https://user-images.githubusercontent.com/58367045/147864406-5c14c3ca-801e-43f9-aa30-655afce7727e.png)

### History
![image](https://user-images.githubusercontent.com/58367045/147864421-3028d86d-688a-4f1d-a682-de3d0c55753f.png)

### Settings
![image](https://user-images.githubusercontent.com/58367045/147864075-0d3852e6-abdc-44e8-8d91-260d96c5c1c2.png)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Go to the Community Store.
2. Search for `Template`.
3. Navigate to `Template` theme.
4. Press `Install`.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/Neekster/DarkTeal/blob/master/themes/Darkteal.yaml
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/Neekster/DarkTeal/blob/master/themes/Darkteal.yaml
```
