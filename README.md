PDF GENERATOR API
======================
This is a simple Express server that allows downloading PDF files.

Usage
-----

`git clone https://github.com/Iyaaan/node-pdf-generator.git`

`npm install`
`npm start`

Then open [http://localhost:3000/pdf](http://localhost:3000/pdf) in your browser.


API
---

### GET /pdf?url=:file

Downloads a PDF file.

**Path Parameters:**

*   `url` - The name of the PDF file to download

**Example Request:**

Copy code

`GET /pdf?url=:mihaaru.com`

This will download the `mihaaru.com.pdf` file.