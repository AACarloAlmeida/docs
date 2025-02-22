---
title: API previews
intro: You can use API previews to try out new features and provide feedback before these features become official.
redirect_from:
  - /v3/previews
versions:
  ghes: <3.4
topics:
  - API
---


API previews let you try out new endpoints and changes to existing endpoints before they become part of the official {% data variables.product.prodname_dotcom %} API.

During the preview period, we may change some features based on developer feedback. If we do make changes, we'll announce them on the [developer blog](https://developer.github.com/changes/) without advance notice.

To access an API preview, you'll need to provide a custom [media type](/rest/overview/media-types) in the `Accept` header for your requests. Feature documentation for each preview specifies which custom media type to provide.

{% ifversion ghes < 3.4 %}
## Content attachments

You can now provide more information in {% data variables.product.prodname_dotcom %} for URLs that link to registered domains by using the API to manage {% data variables.product.prodname_unfurls %}. For more information, see "[Using content attachments](/apps/using-content-attachments/)."

**Custom media types:** `corsair-preview`
**Announced:** [2018-12-10](https://developer.github.com/changes/2018-12-10-content-attachments-api/)

{% endif %}


