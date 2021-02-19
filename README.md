# Boop
serve-time javascript markdown to html compiler
inspired by the [gitlab.com/uoou/blop](https://gitlab.com/uoou/blop) bash markdown to static website compiler

save generation cycles on the dev end (keep git nice and happy)\
load boop.js in your index.html ... $$$$ profit $$$$\
Sorry users, you do have enough ram though

## plan
load boop.js in your index.html ... $$$$ profit $$$$

## Notes
- I don't know WTF I am doing .. this could just be a gist
- take a squize at ziglang.orgs served files
- githubs html structure

## Pseudocode
document.onload => {

    output = read * markdown

    give each markdown block propper styling tags

    use a preexisting markdown interpreter

    order html on page in order of number supplied by markdown metadata

    subst markdown parts for html tags

    print generated tags into index.html buffer to output

}
