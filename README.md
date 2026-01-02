# DevHabit

A developer habit tracking system, built with a pragmatic RESTful API.

# Resources

02 - Building REST APIs

HTTP Semantics - RFC 9110 - Methods
https://datatracker.ietf.org/doc/html/rfc9110#name-methods

HTTP Semantics - RFC 9110 - Status Codes
https://datatracker.ietf.org/doc/html/rfc9110#name-status-codes

Microsoft REST API Guidelines
https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md

Google Cloud - API Design Guide
https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md

Zalando RESTful API and Event Guidelines
https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md

03 - HATEOAS and Change Management

Siren: a hypermedia specification for representing entities
https://github.com/kevinswiber/siren

Hydra: Hypermedia-Driven Web APIs
https://www.markus-lanthaler.com/hydra/

HAL - Hypertext Application Language
https://stateless.group/hal_specification.html

JSON-LD: JSON for Linking Data
https://json-ld.org/

JSON:API - A specification for building APIs in JSON
https://jsonapi.org/

OData standard with best practices for building RESTful APIs
https://www.odata.org/documentation/

04 - Authentication and Authorization

Casbin
https://github.com/casbin/casbin

GitHub REST API Documentation
https://docs.github.com/en/rest

Encrypting Data, Microsoft
https://learn.microsoft.com/en-us/dotnet/standard/security/encrypting-data

Overview of encryption, digital signatures, and hash algorithms in .NET, Microsoft
https://learn.microsoft.com/en-us/dotnet/standard/security/cryptographic-services

Key Rotation, Google Cloud
https://cloud.google.com/kms/docs/key-rotation

Re-encrypting Data, Google Cloud
https://cloud.google.com/kms/docs/key-rotation

The Importance of Key Rotation for Data Security
https://www.piiano.com/blog/key-rotation

06 - Advanced REST API Concerns

dotnet tool install --global Microsoft.OpenApi.Kiota
kiota generate -l CSharp -d <OPEN_API_SPEC_PATH> -c DevHabitClient -o ./CsharpClient
kiota generate -l typescript -d <OPEN_API_SPEC_PATH> -c DevHabitClient -o ./TypeScriptClient

Response caching
https://learn.microsoft.com/en-us/aspnet/core/performance/caching/response

Output caching
https://learn.microsoft.com/en-us/aspnet/core/performance/caching/output

Introduction to resilient app development
https://learn.microsoft.com/en-us/dotnet/core/resilience

Build resilient HTTP apps: Key development patterns
https://learn.microsoft.com/en-us/dotnet/core/resilience

Building Resilient Cloud Applications With .NET
https://www.milanjovanovic.tech/blog/building-resilient-cloud-applications-with-dotnet

Building Webhooks in .NET series
https://youtube.com/playlist?list=PLYpjLpq5ZDGsnBmwJCdFv5PhQbUZruKy3

Here's a sample import file. Update the habit_id to point to a real entity in your database and store it as a .csv file.

habit_id,date,notes
h_0194ff8e-39f7-7ac3-9cc1-f72afc27b578,2024-04-10,Focused execution
h_0194ff8e-39f7-7ac3-9cc1-f72afc27b578,2024-04-11,Making it work
h_0194ff8e-39f7-7ac3-9cc1-f72afc27b578,2024-04-12,Need more consistency
h_0194ff8e-39f7-7ac3-9cc1-f72afc27b578,2024-04-13,Better than yesterday
h_0194ff8e-39f7-7ac3-9cc1-f72afc27b578,2024-04-14,Strong effort
h_0194ff8e-39f7-7ac3-9cc1-f72afc27b578,2024-04-15,Tax day success
h_0194ff8e-39f7-7ac3-9cc1-f72afc27b578,2024-04-16,Getting stronger
h_0194ff8e-39f7-7ac3-9cc1-f72afc27b578,2024-04-17,Maintained focus
h_0194ff8e-39f7-7ac3-9cc1-f72afc27b578,2024-04-18,Steady progress
h_0194ff8e-39f7-7ac3-9cc1-f72afc27b578,2024-04-19,Almost missed
h_0194ff8e-39f7-7ac3-9cc1-f72afc27b578,2024-04-20,Good recovery
h_0194ff8e-39f7-7ac3-9cc1-f72afc27b578,2024-04-21,Need improvement

09 - Deployment and Monitoring

npm install -g @azure/static-web-apps-cli
swa init
swa build
swa deploy --env production --deployment-toke <YOUR_DEPLOYMENT_TOKEN>

Production Grade Observability with Azure Monitor Application Insights
https://youtu.be/qAlpzwNqK0s

Introduction to Application Insights - OpenTelemetry observability
https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview