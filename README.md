# is-government-shutdown
Is the US government shutdown?

Poking a bit of fun at the fact that the US government is STILL shutdown.

# Super simple
It's just a static HTML page that has a bit of javascript in to get the result. It's also got a 503 easter egg.

# Hosting
All I did to host this was put it in an S3 bucket, then had CloudFront pull from the bucket. Used ACM for certificate. Registered the domain with Route53 and boom. We're live.
