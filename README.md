# HtmlToPDF
Convert HTML to PDF in AWS lambda with .net core

The lambda function listens to S3 event on a bucket. I have configured it to the bucket where I store the invoice htmls.
When an html invoice is uploaded , the function uses Chrome driver through Puppeteer to covert it to PDF and upload the result to pdf bucket.
