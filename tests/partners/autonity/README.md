### This is an example partner

To submit your own project, add a project folder to the `partners/` directory.

#### In your project folder you need to add three files: `thumbnail.png` `banner.png` & `info.json`.

### The thumbnail.png file must be no more then 125x125px
### The banner.png file must be no more then 300x533px


The `info.json` file looks like this:

``` typescript
export interface Partner {
    name: string; //40 characters max
    shortDescription: string; // 75 character max description
    longDescription: string; // 250 character max description
    tags: string[]; //keywords that best describe your project, max 5 each one no more then 20 characters
    url: string; // must be a https url
}
```
