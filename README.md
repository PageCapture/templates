# HTML to PDF templates

This repository contains free-to-use HTML templates for you to generate PDF documents without needing to design and build your own.

The following templates are currently available:

* [Invoice Template](#InvoiceTemplate)
* [Report Template](#ReportTemplate)
* [Ticket Template](#TicketTemplate)

<a name="InvoiceTemplate"></a>
## Invoice Template

It is a very common use case to send your customers PDFs of their invoices, this template is a simple, responsive HTML
template that you can customise for your specific needs.

[Get the code](/template/invoice.html)

You can use [PageCapture](https://pagecapture.io) to convert this HTML template to a PDF with this simple curl command.
Replace `APIKEY` with your api key from your [free PageCapture account](https://app.pagecapture.io).

```
curl --header "Content-Type: application/json" \
    --header "Api-Key: APIKEY" \
    --data '{"source":"http://www.google.com"}' \
    https://app.pagecapture.io/template/invoice \
    -o invoice.pdf
```