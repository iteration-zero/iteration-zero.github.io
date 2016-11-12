---
layout: default
---

## C# Coding Standards

### Using Statements

- Using statements should be declared outside of the namespace for a type.
- Using statements should be divided in to a maximum of 3 sections with 1 line of whitespace in 
between. The sections in order, are **System**, **Third Party**, and **Project**.
- Using statements should be listed in alphabetical order in each section.

Example file

```C#
using System;
using System.Linq;

using Microsoft.EnterpriseLibrary.Data;

using IterationZero.Sample.Models;
using IterationZero.Sample.Models.Repositories;

namespace IterationZero.Sample.Repository.SqlClient {
    // Class declaration...
}
```