# Public Project Structure

This repository contains a sanitized showcase version of AllweK Arena. It is not the production source code.

The files under `showcase/` are intentionally limited to public-safe placeholders and examples that communicate the project shape without exposing backend logic, credentials, private routes, database details, payment/email configuration, deployment scripts, uploaded user content, or proprietary implementation.

## Sanitized Layout

```text
showcase/
  pom.xml
  src/
    main/
      java/
        org/tl/allwek/
          AllweKApplication.java
          config/
          controllers/
          models/
          repositories/
          services/
      resources/
        application.example.properties
        templates/
          index.html
        static/
          css/
            index.css
          js/
            index.js
```

## What Is Omitted

- Production backend source code
- Real configuration values
- API credentials, tokens, keys, passwords, or secrets
- Database connection details
- Payment, email, and deployment internals
- Uploaded user/media content
- Private admin logic and proprietary business rules
