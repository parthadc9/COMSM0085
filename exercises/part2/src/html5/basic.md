# Basic HTML5

For your first exercise, create a page called `index.html` and add the HTML5 template code to it.

The name `index.html` is a convention: most web servers, if you give an URL that looks like a "folder" e.g. `example.com/pages` (or `example.com/pages/` with slash on the end) will serve the file `index.html` from within that folder, if there is one.

## Create a page

Create content in your page to make it look like the following, then open it in your browser. All body text, but not the bullet list, is contained in paragraph tags.

<div style="background:#fff; border: 1px solid #1d1b1e; box-shadow: 0px 0px 10px #333; width: 100%; height: 490px; border-radius: 5px;">
<div style="height:40px; background-color: #1d1b1e; display:flex; justify-content: start; align-items: center; padding: 0 1em; border-radius: 5px 5px 0 0;">
    <div style="display: flex; font-size: 1rem;">
        <div style="background: #c43e3e; border-radius: 100%; width: 1em; height: 1em; margin: 0 0.5em;"></div>
        <div style="background: #c1a347; border-radius: 100%; width: 1em; height: 1em; margin: 0 0.5em;"></div>
        <div style="background: #4b3cb5; border-radius: 100%; width: 1em; height: 1em; margin: 0 0.5em;"></div>
    </div>
    <div style="font-family: monospace; font-size: 0.8em; background: #eeeeee; color: #1d1b1e; padding: 0.2em 0.5em; border-radius: 5px; margin-left: 1em; margin-right: 5em; flex-grow: 1;">http://localhost:8000</div>
</div>
<iframe style="border: none; width: 100%; height: 450px" src="../resources/examplepage.html" title="example page">
</iframe>
</div>

## Validate your page

There are various libraries and services that check if your page is valid HTML5.

At [validator.w3.org](https://validator.w3.org/) you can enter an URL, upload a file, or paste the contents of a file and validate it. Check that the page you have just written is valid HTML5.

Your browser's developer tools can also check the page you are viewing. For Chrome/Edge, to to the _Console_ tab and, if the button at the top does not read _No Issues_ but shows a number with a blue (or even yellow or red) icon, then click it to open the _Issues_ tab and see what the browser is complaining about.

You can check the sample solution [here](../resources/examplepage.html) but you might have a different, equally valid solution.
