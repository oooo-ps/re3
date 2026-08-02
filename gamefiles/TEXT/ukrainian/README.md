# Ukrainian localization set for reVC / GTA Vice City

## Usage

Install [gxter](https://github.com/oooo-ps/gxter/tree/vc-uk-andrulko) (includes [ASCII dictionary](https://github.com/oooo-ps/gxter/blob/vc-uk-andrulko/character_tables/vc_uk_andrulko.toml) for [@Andrulko's Ukrainian localization](https://kuli.com.ua/grand-theft-auto-vice-city#translations))

### Decompile from GXT

``` bash
gxter-cli -d ukrainian.gxt -c gxter/character_tables/vc_uk_andrulko.toml -o ukrainian.toml
```

### Compile to GXT

``` bash
gxter-cli ukrainian.toml -c gxter/character_tables/vc_uk_andrulko.toml -o ukrainian.gxt
```