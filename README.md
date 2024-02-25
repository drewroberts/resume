# Drew Roberts Resume

This repository hosts the HTML & CSS files for formatting my resume. I utilize [PagedJS.org](https://pagedjs.org/documentation/2-getting-started-with-paged.js/) to use @page tags with the browser's print function. For styling, I utilize [TailwindCSS](https://tailwindcss.com/docs/installation/play-cdn) to quickly edit the format of the document with Utility classes.

## Print

The document is a US Letter size and will be printed in 72 PPI which is the standard web interface. This PPI can be modified, but this particular document doesn't need high resolution. Can simply use the print function on the browser and print to PDF or a printer. Here are the conversions for the size:

- 8.5in x 11in
- 216mm x 279mm
- 612px x 792px

## Layout

Below is a diagram of the margin boxes created with PagedJS:

![Diagram of Margin Boxes](https://github.com/drewroberts/resume/img/margin-boxes.png)

This repository uses the left margin with a width of 250px and black background on every page using the running() function. The other margins are 28px.
