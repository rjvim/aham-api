---
title: Aham API

language_tabs: # must be one of https://git.io/vQNgJ
  - shell

search: true
---

# Introduction

Welcome to the Aham API.

# Authentication

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here"
  -H "Accept :  application/x.aham.v2+json"

  #Request Payload : 

  [
    [
      day: 'monday',
      available: true,
      timings: [
        {

        },
      ]
    ]
  ] 
```

