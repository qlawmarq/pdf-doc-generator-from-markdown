# cv-rejume-generator-from-markdown

[![Github Actions Badge](https://github.com/cymagix/cv-rejume-generator-from-markdown/workflows/Node/badge.svg)](https://github.com/cymagix/cv-rejume-generator-from-markdown/actions)

This template allow you to generate your own CV or rejume as a PDF from Markdown with GitHub Actions automatically easily.

Once you update [Markdown of your CV](./Curriculum_vitae.md), GitHub Actions automatically generate [PDF of your CV](./Curriculum_vitae.pdf).

Check the files and see how it works!
- [Markdown of CV template (original file)](./Curriculum_vitae.md)
- [PDF of CV template (generated file)](./Curriculum_vitae.pdf)

## Usage

### With GitHub Actions

GitHub Actions allow you to automatically generate PDFs by simply updating markdown, if you're using GitHub.

All you need to do is just create a new repository from the following link:  
https://github.com/cymagix/cv-rejume-generator-from-markdown/generate

Then, edit [Markdown of your CV](./Curriculum_vitae.md) on your repository, and wait GitHub Actions generate your PDF.

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
