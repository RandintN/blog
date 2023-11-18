+++
author = "Robson Cassiano"
title = "What is a REST API?"
date = "2019-01-30"
description = "Understanding REST APIs"
tags = ["api", "rest", "json"]
+++

## What is a REST API?

A REST API (Representational State Transfer) is an application programming interface (API) that follows a set of architectural constraints. These constraints define how resources are represented, how requests are made, and how responses are returned.

REST APIs are commonly used to connect different web applications. For example, an e-commerce application may use a REST API to connect to a payment service to process transactions.

{{< youtube F9n1N8ThpF0 >}}

### Resources and URIs

The central concept of a REST API is the resource. A resource is an object or entity that can be manipulated through the API. For example, a resource could be a product, a user, or a transaction.

Each resource is identified by a URI (Uniform Resource Identifier). A URI is an address that identifies a resource on the web. For example, the URI /products/1 could identify a specific product.

### HTTP Methods

REST APIs use HTTP methods to perform operations on resources. The most common HTTP methods are:

**GET:** Retrieve information about a resource.
**POST:** Create a new resource.
**PUT:** Update an existing resource.
**DELETE:** Delete an existing resource.
**HEAD:** Useful for retrieving only the header of the request and saving data.

### Representation of Resources

Responses from a REST API are typically represented in JSON or XML. JSON is a human-readable text format that is easy to serialize and deserialize. XML is a more structured text format that is more suitable for describing complex data.

**Most Web APIs today respond in JSON**

JSON is the most commonly used resource representation format in Web APIs. This is because JSON is easy to understand and work with, both for humans and machines.

JSON is also a lightweight format, making it ideal for mobile applications and devices with limited resources.

Example JSON representing bank customer data:
```json
{
  "id": 1,
  "name": "John Silva",
  "cpf": "123.456.789-00",
  "date_of_birth": "1980-01-01",
  "address": {
    "zip_code": "12345-678",
    "street": "Flower Street",
    "number": 123,
    "complement": "Apt 101",
    "neighborhood": "Downtown",
    "city": "São Paulo",
    "state": "SP"
  },
  "accounts": [
    {
      "number": 1234567890,
      "type": "checking",
      "balance": 1000.00
    },
    {
      "number": 9876543210,
      "type": "savings",
      "balance": 500.00
    }
  ]
}
```

### Conclusion
REST APIs are a powerful tool that can be used to connect different web applications. They are easy to use and implement, and widely used on the web.