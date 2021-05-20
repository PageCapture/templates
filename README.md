# HTML to PDF templates

This repository contains free-to-use HTML templates for you to generate PDF documents without needing to design and build your own.

The following templates are currently available:

* [Invoice Template](#invoice-template)
* [Report Template](#report-template)
* [Ticket Template](#ticket-template)

## Invoice Template

It is a very common use case to send your customers PDFs of their invoices, this template is a simple, responsive HTML
template that you can customise for your specific needs.

[Get the code](/template/invoice.html)

You can use [PageCapture](https://pagecapture.io) to convert this HTML template to a PDF with this simple curl command.
Replace `APIKEY` with your api key from your [free PageCapture account](https://app.pagecapture.io).

```
curl --header "Content-Type: application/json" \
    --header "Api-Key: APIKEY" \
    --data '{"source":"https://app.pagecapture.io/template/invoice"}' \
    https://api.pagecapture.io/pdf \
    -o invoice.pdf
```

## Report Template

Producing easy to beautiful and consumable PDF reports directly can be very difficult. Leverage your existing HTML and
CSS skills to build your report and then convert it to PDF.

[Get the code](/template/report.html)

You can use [PageCapture](https://pagecapture.io) to convert this HTML template to a PDF with this simple curl command.
Replace `APIKEY` with your api key from your [free PageCapture account](https://app.pagecapture.io).

```
curl --header "Content-Type: application/json" \
    --header "Api-Key: APIKEY" \
    --data '{"source":"https://app.pagecapture.io/template/report"}' \
    https://api.pagecapture.io/pdf \
    -o invoice.pdf
```

## Ticket Template

Have an event coming up that you need to print tickets for? You can generate HTML pages containing your tickets,
generate a PDF, and then print or email the PDF to your customers.

[Get the code](/template/ticket.html)

You can use [PageCapture](https://pagecapture.io) to convert this HTML template to a PDF with this simple curl command.
Replace `APIKEY` with your api key from your [free PageCapture account](https://app.pagecapture.io).

```
curl --header "Content-Type: application/json" \
    --header "Api-Key: APIKEY" \
    --data '{"source":"https://app.pagecapture.io/template/ticket"}' \
    https://api.pagecapture.io/pdf \
    -o invoice.pdf
```