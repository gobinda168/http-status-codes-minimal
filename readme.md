# HTTP Status Codes Minimal

Light weight package to managing HTTP status codes and reason phrases in TypeScript and Javascript applications.

## ✨ Features

- **Comprehensive yet Compact:** Get access to a complete range of HTTP status codes and reason phrases without the bloat.
- **TypeScript Ready:** Crafted with TypeScript for TypeScript, ensuring you benefit from type safety and autocompletion without sacrificing performance.
- **Feather-Light Footprint:** At just 30KB, it's designed to be incredibly efficient, making it a no-brainer addition to your project.
- **User-Friendly:** Simplified API with functions like `getReasonPhrase` and `getStatusCode` to effortlessly convert between status codes and reason phrases.

## 📦 Installation

```bash
npm install http-status-codes-minimal
```

## Usage

```bash
import {
  StatusCodes,
  ReasonPhrases,
  getReasonPhrase,
  getStatusCode,
} from "http-status-codes-minimal";

console.log(StatusCodes.ACCEPTED);
console.log(ReasonPhrases.ACCEPTED);
console.log(getStatusCode("ACCEPTED"));
console.log(getReasonPhrase(202));
```

## HTTP Status Codes and Reason Phrases

| Code | Constant                          | Reason Phrase                          |
|------|-----------------------------------|----------------------------------------|
| 100  | CONTINUE                          | Continue                               |
| 101  | SWITCHING_PROTOCOLS               | Switching Protocols                    |
| 102  | PROCESSING                        | Processing                             |
| 103  | EARLY_HINTS                       | Early Hints                            |
| 200  | OK                                | OK                                     |
| 201  | CREATED                           | Created                                |
| 202  | ACCEPTED                          | Accepted                               |
| 203  | NON_AUTHORITATIVE_INFORMATION     | Non-Authoritative Information          |
| 204  | NO_CONTENT                        | No Content                             |
| 205  | RESET_CONTENT                     | Reset Content                          |
| 206  | PARTIAL_CONTENT                   | Partial Content                        |
| 207  | MULTI_STATUS                      | Multi-Status                           |
| 300  | MULTIPLE_CHOICES                  | Multiple Choices                       |
| 301  | MOVED_PERMANENTLY                 | Moved Permanently                      |
| 302  | FOUND                             | Found                                  |
| 303  | SEE_OTHER                         | See Other                              |
| 304  | NOT_MODIFIED                      | Not Modified                           |
| 305  | USE_PROXY                         | Use Proxy                              |
| 307  | TEMPORARY_REDIRECT                | Temporary Redirect                     |
| 308  | PERMANENT_REDIRECT                | Permanent Redirect                     |
| 400  | BAD_REQUEST                       | Bad Request                            |
| 401  | UNAUTHORIZED                      | Unauthorized                           |
| 402  | PAYMENT_REQUIRED                  | Payment Required                       |
| 403  | FORBIDDEN                         | Forbidden                              |
| 404  | NOT_FOUND                         | Not Found                              |
| 405  | METHOD_NOT_ALLOWED                | Method Not Allowed                     |
| 406  | NOT_ACCEPTABLE                    | Not Acceptable                         |
| 407  | PROXY_AUTHENTICATION_REQUIRED     | Proxy Authentication Required          |
| 408  | REQUEST_TIMEOUT                   | Request Timeout                        |
| 409  | CONFLICT                          | Conflict                               |
| 410  | GONE                              | Gone                                   |
| 411  | LENGTH_REQUIRED                   | Length Required                        |
| 412  | PRECONDITION_FAILED               | Precondition Failed                    |
| 413  | PAYLOAD_TOO_LARGE                 | Payload Too Large                      |
| 414  | URI_TOO_LONG                      | URI Too Long                           |
| 415  | UNSUPPORTED_MEDIA_TYPE            | Unsupported Media Type                 |
| 416  | RANGE_NOT_SATISFIABLE             | Range Not Satisfiable                  |
| 417  | EXPECTATION_FAILED                | Expectation Failed                     |
| 418  | IM_A_TEAPOT                       | I'm a Teapot                           |
| 419  | INSUFFICIENT_SPACE_ON_RESOURCE    | Insufficient Space on Resource         |
| 420  | METHOD_FAILURE                    | Method Failure                         |
| 421  | MISDIRECTED_REQUEST               | Misdirected Request                    |
| 422  | UNPROCESSABLE_ENTITY              | Unprocessable Entity                   |
| 423  | LOCKED                            | Locked                                 |
| 424  | FAILED_DEPENDENCY                 | Failed Dependency                      |
| 426  | UPGRADE_REQUIRED                  | Upgrade Required                       |
| 428  | PRECONDITION_REQUIRED             | Precondition Required                  |
| 429  | TOO_MANY_REQUESTS                 | Too Many Requests                      |
| 431  | REQUEST_HEADER_FIELDS_TOO_LARGE   | Request Header Fields Too Large        |
| 451  | UNAVAILABLE_FOR_LEGAL_REASONS     | Unavailable For Legal Reasons          |
| 500  | INTERNAL_SERVER_ERROR             | Internal Server Error                  |
| 501  | NOT_IMPLEMENTED                   | Not Implemented                        |
| 502  | BAD_GATEWAY                       | Bad Gateway                            |
| 503  | SERVICE_UNAVAILABLE               | Service Unavailable                    |
| 504  | GATEWAY_TIMEOUT                   | Gateway Timeout                        |
| 505  | HTTP_VERSION_NOT_SUPPORTED        | HTTP Version Not Supported             |
| 507  | INSUFFICIENT_STORAGE              | Insufficient Storage                   |
| 511  | NETWORK_AUTHENTICATION_REQUIRED   | Network Authentication Required        |
