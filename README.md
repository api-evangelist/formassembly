# FormAssembly

FormAssembly is an enterprise form and data collection platform with a REST API for managing forms, collecting submissions, handling Salesforce integrations, and building compliant data collection workflows. The platform serves over 5,500 organizations and offers deployment options including cloud (FormAssembly.com), self-hosted Enterprise, and FedRAMP-authorized Government Cloud.

## API

The FormAssembly REST API (`/api_v1/`) supports OAuth2 authentication and provides endpoints for:

- **Forms** — create, view, edit, delete, and list forms; admin index for Enterprise
- **Responses** — export submissions in CSV, JSON, XML, or ZIP format with date range and pagination filtering
- **Connectors** — manage integration connectors including Salesforce mappings
- **Themes** — manage CSS themes applied to forms
- **Form Elements** — manage individual form field definitions

Base URLs vary by edition:

| Edition | Base URL |
|---------|----------|
| Developer Sandbox | `https://developer.formassembly.com/api_v1/` |
| FormAssembly.com | `https://app.formassembly.com/api_v1/` |
| Enterprise | `https://{instance_name}.tfaforms.net/api_v1/` |

## Authentication

OAuth2 protocol. Register at the FormAssembly Developer Hub to obtain a `CLIENT_ID` and `CLIENT_SECRET`. Access tokens are valid for 10 years; refresh tokens enable renewal.

## Plans

- **Atlas Explorer** — individuals, 1 user, 3 workflows, unlimited forms/responses
- **Atlas Team** — small businesses, 8 users, unlimited workflows, custom HTML/CSS/JS
- **Atlas Enterprise** — large organizations, HIPAA compliance with BAA, advanced security
- **Gov Cloud** — U.S. government agencies, FedRAMP High authorization

## Resources

- Website: https://www.formassembly.com/
- API Documentation: https://help.formassembly.com/help/working-with-the-formassembly-api
- Developer Hub: https://developer.formassembly.com/
- GitHub: https://github.com/formassembly
- Status: https://status.formassembly.com/
- Pricing: https://www.formassembly.com/pricing/
- Blog: https://www.formassembly.com/blog/
- LinkedIn: https://www.linkedin.com/company/formassembly
- X: https://twitter.com/FormAssembly
