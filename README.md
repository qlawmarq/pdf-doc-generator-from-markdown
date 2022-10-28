# pdf-doc-generator-from-markdown

[![Github Actions Badge](https://github.com/cymagix/pdf-doc-generator-from-markdown/workflows/Node/badge.svg)](https://github.com/cymagix/pdf-doc-generator-from-markdown/actions)

This template makes it easy to generate documents such as resumes and privacy policies as PDFs from Markdown using GitHub Actions.

Once you update Markdown file, GitHub Actions automatically generate the PDF version of the file.

Check the files and see how it works!
- [Markdown of CV template (original file)](./Curriculum_vitae.md)
- [PDF of CV template (generated file)](./Curriculum_vitae.pdf)

## Usage

### With GitHub Actions

GitHub Actions allow you to automatically generate PDFs by simply updating markdown, if you're using GitHub.

All you need to do is just create a new repository from the following link:  
https://github.com/cymagix/pdf-doc-generator-from-markdown/generate

Then, edit [Markdown](./Curriculum_vitae.md) on this repository, and wait GitHub Actions generate your PDF.

If all is well, a new PDF should be generated.

Also, please check [GitHub Actions docs](https://docs.github.com/en/actions) to see how it works.

### Local machine

You can also run this generator on you local machine.

First of all, please make sure Node.js is installed in your PC.

After that, excute following command:

```bash
npm i
npm run generate
```

Now, you can see some of PDF files are generated.

## Update PDF design/style/layout

Markdown files are converted once to html and then to pdf. And that means you can apply CSS styles to your PDFs.

You can update the PDF design by updating [`md.css`](./md.css).

Also, you can update [`config.json`](./config.json) to update the PDF design.

Please refer to [md-to-pdf](https://www.npmjs.com/package/md-to-pdf) for other options.

## Elements

- [md-to-pdf](https://www.npmjs.com/package/md-to-pdf)
- [GitHub Actions](https://docs.github.com/en/actions)
